# 如何屏蔽应用开屏广告

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
#### 示例
- 定位`https://open3.vistastory.com/v3/api/index/loading_ad2`并屏蔽。
<p float="left">
  <img src="https://github.com/misitechan/-QuantumultX-/blob/37edc88d567796d0300982963099b5fb20107f53/images/640.png" width="200" />
  <img src="https://github.com/misitechan/-QuantumultX-/blob/37edc88d567796d0300982963099b5fb20107f53/images/641.png" width="200" />
</p>


### 捷径断网去广告
在app打开瞬间关闭无线网络和蜂窝数据，等待一秒后再次打开，以跳过开屏广告。

### 捷径轻启动
使用快捷指令和URL Scheme无广告打开应用。

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