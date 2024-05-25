# 屏蔽APP开屏广告指南

## Android端
### 李跳跳
李跳跳是一款启动广告跳过软件，通过模拟人手指点击开屏广告右上角的“跳过广告”按钮来实现瞬间跳过广告。

#### 安装与使用
1. 下载李跳跳APP。
2. 打开手机的**无障碍权限**。
3. 导入去开屏广告规则。
4. 在李跳跳设置中找到需要屏蔽广告的APP，并打开开关。

#### 附加功能
- 自动跳过网易云、抖音的更新弹窗。
- 支持自定义规则跳过任意弹窗。


#### 下载地址
- [李跳跳APK](https://wwa.lanzoui.com/b00um9rih) 密码: 65c9 
- [李跳跳去除开屏广告规则](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/tutorial/ltt_regulation.txt)


## iOS端
### 抓包去广告
IOS 端开屏广告屏蔽 Demo，以「看天下」为例。

首先使用抓包软件对应用进行**全局抓包**，这里使用的是 Http Catcher，当前也可使用免费的 Stream 软件，当开屏广告出现 1~2 秒后，完全退出应用，返回抓包软件。

分析相关域名，并寻找开屏广告图片的 URL，进行全局搜索，定位其是由哪个请求返回的，即在响应体中找对应域名。
<p float="left">
  <img src="https://github.com/misitechan/-QuantumultX-/blob/37edc88d567796d0300982963099b5fb20107f53/images/640.png" width="350" />
  <img src="https://github.com/misitechan/-QuantumultX-/blob/37edc88d567796d0300982963099b5fb20107f53/images/641.png" width="350" />
</p>

#### 示例
- 定位`https://open3.vistastory.com/v3/api/index/loading_ad2`并屏蔽。

<p float="left">
  <img src="https://github.com/misitechan/-QuantumultX-/blob/63cd69edd55a8634503516b463f7e2a3e789992c/images/642.png" width="350" />
  <img src="https://github.com/misitechan/-QuantumultX-/blob/63cd69edd55a8634503516b463f7e2a3e789992c/images/643.png" width="350" />


### 找到开屏广告的响应请求后，我们只需屏蔽它即可，对于小编经常使用的QuantumultX 工具，其广告屏蔽方式如下：
<span style="background-color: #cccccc; padding: 2px 4px; border-radius: 3px;">
[rewrite_local]  <br>
^https?:\/\/open3\.vistastory\.com\/v\d\/api\/index\/loading_ad url reject  <br>
[mitm]  <br>
hostname=open3.vistastory.com</span>  <br>


- 广告屏蔽规则写好后，就可以测试下规则的有效性，看其能否屏蔽开屏广告（由于广告的缓存机制，在多数情况下，应用需要卸载重新安装）。


### 捷径轻启动
在iOS中，URL Scheme是一种允许应用程序通过URL调用其他应用程序的机制。通过URL Scheme，你可以从一个应用程序跳转到另一个应用程序，并且可以传递一些数据。这对于在不同应用之间进行集成和交互非常有用[文字来源于ChatGPT]。

步骤：使用快捷指令，创建打开URL命令，将AppScheme输入，并将改捷径命名为需要打开APP的软件名，建议提前找好软件图标，将捷径添加到主屏幕，更改图标，返回桌面点击启动，点击同意权限，之后便可无广告打开应用，友情提醒，此方法不会随着应用的更新而失效。

#### AppScheme资源
- [AppScheme GitHub库](https://github.com/ddgksf2013/AppScheme)

### 换区换语言
建议将苹果手机和安卓手机的地区换成非国区，语言换成英文或繁体。

## FAQ
1. **添加了去广告重写规则后还有开屏广告？**
   - 检查证书文件是否正确安装、信任。
   - 卸载重新安装APP，因为应用的广告通常设有缓存机制。

2. **卸载重新安装App后还有开屏广告？**
   - 广告模块可能为内嵌。
   - 广告请求可能不是Http。
   - 去广告规则可能不包含所使用的App。

3. **如何全面去除App的开屏广告？**
   - 使用墨鱼开屏广告2.0并配合神机广告终结者去广告分流。

4. **每次更新App后广告就出现？**
   - 不要随意更新应用，因为去广告规则更新速度可能跟不上App更新速度。

5. **抖音新版能屏蔽广告吗？**
   - 不能，新版抖音已禁止MIMT，无法去除广告。

6. **对广告深恶痛绝怎么办？**
   - 卸载有广告的App。

请根据个人需求和设备情况选择合适的方法，并确保遵循相关法律法规。