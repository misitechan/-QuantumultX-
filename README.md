# 使用说明

# QuantumultX 配置仓库

## 目录

- [简介](#introduction)
- [使用说明](#usage)
  - [准备工作](#preparation)
  - [下载配置文件](#download-configuration)
  - [导入配置文件至QuantumultX](#Import)
  - [使用分流规则](#Use)
  - [复写规则使用](#Replication)
  - [注意事项](#Precautions1)
  - [其他贡献者教程](#Precautions3)
  - [自用QX配置](#Precautions2)
- [QuantumultX 分流](#2️⃣quantumultx-分流)
- [QuantumultX 复写](#3️⃣quantumultx-复写)
- [QuantumultX 脚本Task](#4️⃣quantumultx-脚本task)
- [QuantumultX 图标库](#5️⃣quantumultx-图标库)
- [Awesome Resource](#6️⃣awesome-resource)
- [更新日志](https://github.com/misitechan/-QuantumultX-/tree/main/historic%20version)
- [贡献指南](https://github.com/misitechan/Frequently-Asked-Questions/issues)
- [FAQ](https://github.com/misitechan/Frequently-Asked-Questions)
- [免责声明](#7️⃣)
- [联系我们](#Precautions5)
- [特别感谢](#8️⃣特别感谢)

---

# QuantumultX 配置仓库

## 0️⃣简介:<a name="introduction"></a>

欢迎来到QuantumultX配置仓库！这是一个专为QuantumultX用户设计的资源集合，旨在提供定制化的网络配置和脚本，优化您的网络体验和日常使用便利性。

### 特点

- **定制化配置**：提供个性化的QuantumultX配置文件，满足不同用户的需求。
- **持续更新**：定期更新配置文件，确保与QuantumultX的最新版本兼容。
- **丰富功能**：包括但不限于广告屏蔽、VIP服务解锁、智能分流等高级功能。
- **社区驱动**：鼓励社区成员贡献和分享他们的配置和脚本，共同提升用户体验。

### 使用场景

- **个人使用**：提升个人设备上的QuantumultX性能和定制化程度。
- **学习和研究**：作为学习和研究QuantumultX及其脚本功能的资源库。
- **社区贡献**：为QuantumultX社区贡献力量，分享您的创意和改进。

### 如何开始

按照我们的[使用说明](#usage)部分，您可以快速开始下载和应用这些配置到您的QuantumultX应用中。

### 参与贡献

我们非常欢迎任何形式的贡献，包括但不限于提交新的配置脚本、改进现有脚本、修复问题或完善文档。请查看我们的[贡献指南](https://github.com/misitechan/Frequently-Asked-Questions/issues)以获取更多信息。

### 联系我们

如果您有任何疑问或建议，请通过[联系我们](#Precautions5)部分提供的渠道与我们取得联系。

## 1️⃣QuantumultX 配置：<a name="usage"></a>

**最后更新时间：2024-06-08**

- 欢迎使用本仓库提供的QuantumultX配置和脚本资源。在开始使用之前，请仔细阅读以下指南以确保您能够正确并安全地使用本仓库提供的内容。

## 1. 准备工作  <a name="preparation"></a>

在开始使用之前，请确保您已经满足以下条件：

- 拥有一个GitHub账号。
- 已安装[QuantumultX](https://apps.apple.com/us/app/quantumult-x/id1443988620)应用，并能够正常使用。
- 理解基本的网络代理和分流概念。

## 2. 下载配置文件 <a name="download-configuration"></a>

本仓库提供了多种配置文件，您可以根据需要下载：

- 访问 [配置仓库主页](https://github.com/misitechan/-QuantumultX-/tree/main/Profile-gather)。
- 找到 `Profile-gather` 文件夹。
- 选择您需要的配置文件，例如 `Misitechan.conf`。
- 点击文件名，然后点击 "Raw" 按钮，文件将自动下载到您的设备。

## 3. 导入配置文件至QuantumultX <a name="Import"></a>

- 打开QuantumultX应用。
- 进入配置管理界面。
- 选择 "导入" 功能，然后上传您刚才下载的配置文件。
- 配置文件将被导入QuantumultX，您可以根据需要进行调整。

## 4. 配置证书文件

如果您之前已经生成并信任了证书，可以跳过此步骤。

#### 生成并配置证书

1. 打开 **QuantumultX**，点击右下角的 **三菱按钮**。
2. 选择 **MitM** 模块，然后选择 **生成并配置证书**。
3. 再次点击页面右下角的 **三菱按钮**，进入 **MitM** 模块，选择 **生成证书**。成功后，选择 **安装证书**。
4. 此时会跳转到 **Safari**，提示下载配置描述文件。点击 **允许**，文件将开始下载。
5. 前往 **iOS系统设置** > **通用** > **描述文件** > **已下载的描述文件**。
6. 选择下载的描述文件并 **安装**，输入密码以完成安装。
7. 进入 **iOS系统设置** > **通用** > **关于本机** > **证书信任设置**。
8. 启用 **完全信任**，选中刚刚安装的证书。

**注意事项**:

- **重要**: 点击安装证书 **必须在Safari中打开**，而不是其他浏览器，否则可能导致证书无法安装。

#### 开启模块

- 找到 **重写** 模块，将其开关设置为 **开启** 状态。
- 找到 **MitM** 模块，同样将其开关设置为 **开启** 状态。

## 5. 使用分流规则 <a name="Use"></a>

本仓库还提供了多种分流规则，用于优化您的网络体验：

- 访问 [分流规则文件夹](https://github.com/misitechan/-QuantumultX-/tree/main/list-gather)。
- 下载您需要的分流规则文件，例如 `NeteaseMusic.list`。
- 在QuantumultX中，进入分流规则管理界面。
- 导入下载的分流规则文件。

## 6. 复写规则使用 <a name="Replication"></a>

复写规则可以解锁会员服务、屏蔽广告等：

- 访问 [复写规则文件夹](https://github.com/misitechan/-QuantumultX-/tree/main/rewrite-gather)。
- 下载您需要的复写规则文件。
- 在QuantumultX中，进入复写规则管理界面。
- 导入下载的复写规则文件。

## 7. 注意事项<a name="Precautions1"></a>

- 在使用过程中，如果遇到任何问题，请先查阅本仓库的 [FAQ](https://github.com/misitechan/Frequently-Asked-Questions/blob/main/README.md) 或在 [Issues](https://github.com/misitechan/-QuantumultX-/issues) 中搜索或提问。
- 本仓库内容仅供学习和研究使用，不得用于任何商业用途。
- 使用本仓库内容时，请遵守当地法律法规。
- 要查看最新的更新和历史版本记录，请访问 [QuantumultX 历史版本存档](https://github.com/misitechan/-QuantumultX-/tree/main/historic%20version)。

## 8. 自用QX配置<a name="Precautions2"></a>

- 我们提供了一个自用的QX配置文件，您可以通过以下链接访问并下载：
  [**Misitechan.conf**](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/Profile-gather/misitechan.conf)

### 配置详情

- 上述配置文件支持QX商店最新版，并包含以下功能：
  - 图标库订阅
  - 各种VIP服务
  - 网易云音乐解锁教程
  - iOS更新屏蔽
  - 智能分流
  - 墨鱼去开屏2.0
  - 各种APP净化
  - Boxjs订阅
  - 流媒体解锁查询
  - 高德地图和知乎去广告
  - 节点信息查询

## 9. 其他贡献者教程<a name="Precautions3"></a>

### GitHub加速代理
- 为了加速GitHub的访问速度，您可以使用`ghproxy`服务。使用时，在GitHub raw链接前添加以下代理地址：
  https://gh.idayer.com/
例如，将 `https://raw.githubusercontent.com/` 替换为 `https://gh.idayer.com/`

### BoxJs教程
- 如果您需要BoxJs的安装及订阅教程，可以参考[@limboprossr](https://t.me/limboprossr) 提供的指南：
- [**BoxJS 安装及订阅**](https://limbopro.com/archives/19265.html)
- [**本配置需要配置的BoxJs订阅-iRingo**](https://github.com/VirgilClyne/iRingo/raw/main/BoxJs/iRingo.BoxJs.json) 
- [**本配置需要配置的BoxJs订阅-NobyDa**](https://raw.githubusercontent.com/NobyDa/Script/master/NobyDa_BoxJs.json)
- [**本配置需要配置的BoxJs订阅-XiaoMao**](https://raw.githubusercontent.com/xiaomaoJT/QxScript/main/rewrite/boxJS/XiaoMao.json)
- [**本配置需要配置的BoxJs订阅-Yuheng0101**](https://raw.githubusercontent.com/Yuheng0101/X/main/Tasks/boxjs.json)

### 更多去开屏广告教程
- 如果您需要更多的iOS和Android去开屏广告教程，可以参考[@dgksf2013](https://github.com/ddgksf2013) 提供的：
  [**如何有效减少Android、IOS端应用开屏广告的打扰**](https://mp.weixin.qq.com/s/DOwEQs4Z7eFpGWOVAO-2QA)

### Quantumult X 视频指南
- 另外，我们推荐[@Serdongchanyo](https://github.com/erdongchanyo) 提供的详细视频指南，它将帮助您更好地理解和使用Quantumult X：
  [**Quantumult X 小白系列教程**](https://github.com/erdongchanyo/Rules/blob/main/Quantumult%20X/README.md)

### 解锁网易云音乐教程
- 如果您需要解锁网易云音乐，可以参考[@dgksf2013](https://github.com/ddgksf2013) 提供的：
  [**利用QuantumultX解锁网易云付费及非版权音乐**](https://mp.weixin.qq.com/s/ca6U1O2FTfcqzL7TnJ04IQ)

## 10. 免责声明

- 本仓库提供的所有内容均由用户自主收集和分享，作者不对使用过程中可能出现的任何问题承担责任。
- 使用本仓库内容即表示您已阅读并同意 [免责声明](#7️⃣)。

## 11. 联系我们 <a name="Precautions5"></a>

如果您在使用过程中遇到任何问题或有任何建议，我们鼓励您通过以下渠道联系我们：

- **GitHub Issues**: [提交问题](https://github.com/misitechan/-QuantumultX-/issues/new)
- **电子邮件**: [电子邮件地址](chenjunf1147262614@gmail.com)

## 2️⃣QuantumultX 分流：

### 分流规则列表

获取以下分流规则，以优化您的网络体验和访问特定服务：

- **网易云音乐分流**
  [NeteaseMusic.list](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/list-gather/NeteaseMusic.list)
- **ChatGPT 分流**
  [OpenAi.list](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/list-gather/OpenAi.list)
- **中国大陆软件IP修改分流**
  [Anti-ip.list](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/list-gather/Anti-ip.list)
- **TikTok地区分流**
  [TikTok.list](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/list-gather/TikTok.list)
- **抖音IP分流**
  [DouYin.list](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/list-gather/DouYin.list)
- **GitHub分流**
  [GitHub.list](https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/list-gather/GitHub.list)
- **哔哩哔哩港澳台解锁分流**
  [GitHub.list](https://raw.githubusercontent.com/ddgksf2013/Filter/master/StreamingSE.list)

> 更多的分流请参考 [*@blackmatrix7*](https://github.com/blackmatrix7) 提供的 [***Quantumult X 分流***](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX)， [*@deezertidal*](https://github.com/deezertidal/QuantumultX-Rewrite) 提供的 [***Quantumult X 分流***](https://whatshub.top/rule)

## 3️⃣QuantumultX 复写：

### 注意：带 ● 的需配合boxjs使用

<table>
    <tr> <th> 类别 </th> <th> 序号 </th> <th> 功能 </th> <th> 链接 </th> <th> 作者 </th> <th> 更新日期 </th></tr >
    <tr>
		<td rowspan="20"><strong>会员解锁</strong></td>
		<td > 1 </td> <td > 哔哩哔哩广告净化</td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Bilibili.conf"><em>BilibiliVip.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>	
	<tr>
		<td > 2 </td> <td > Spotify会员 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/UnlockVip/Spotify.conf"><em>SpotifyPro.conf</em></a></td><td>app2smile
		</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 3</td> <td > 墨鱼专属VIP </td> <td ><a href="https://github.com/ddgksf2013/dev/raw/master/ForOwnUse.conf"><em>ForOwnUse.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 4 </td> <td >酷我SVIP</td> <td ><a href="https://raw.githubusercontent.com/Yuheng0101/X/main/Scripts/kuwo.js"><em>Kuwo.conf</em></a></td><td>dyqc_777</td><td>2024.6.7</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 财新周刊VIP </td> <td ><a href="https://github.com/ddgksf2013/MoYu/raw/master/CaiXinZhouKanProCrack.js"><em>CXZK.vip.js</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 6 </td> <td > Nicegram高级版<br> [也可用Swiftgram]</td> <td ><a href="https://github.com/ddgksf2013/MoYu/raw/master/NicegramProCrack.js"><em>Nicegram.pro.js</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 7 </td> <td > RevenueCat多合一 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/dbb1695cd96743eef18f3fac5c6fe227/raw/revenuecat.js"><em>revenuecat.js</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 8 </td> <td > BuyiTunes多合一 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/9e0f6c7341beea09a31aa309d9d7f502/raw/buyitunes.js"><em>buyitunes.js</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 9</td> <td > 喜马拉雅VIP</td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/privilege/ximalayaVIP.js"><em>ximalayaVIP.js</em></a></td><td>GieGie777</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 10 </td> <td > Emby解锁 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/EmbyPlugin.conf"><em>EmbyPlugin.conf</em></a></td><td>rartv</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 11 </td> <td > 微博VIP </td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/privilege/weiboVIP.js"><em>weiboVIP.js</em></a></td><td>XiaoMao</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 12 </td> <td > 网易云VIP </td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/privilege/NeteaseMusicVipCrack.js"><em>weiboVIP.js</em></a></td><td>Hausd0rff</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 13 </td> <td > WPS VIP ●</td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/privilege/WPSVIP.js"><em>WPS VIP.js</em></a></td><td>XiaoMao</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 14 </td> <td > 知音漫客VIP </td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/privilege/Zymh.js"><em>zymkVIP.js</em></a></td><td>admin</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 15 </td> <td > 懒人听书VIP </td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/privilege/lrts.js"><em>lrtsVIP.js</em></a></td><td>GieGie777</td><td>2024.5.26</td>
    </tr>
	<tr>
		<td > 16 </td> <td > 阿里云盘VIP ● </td> <td ><a href="https://raw.githubusercontent.com/xiaomaoJT/QxScript/main/rewrite/boxJS/XiaoMaoALiCloud.js"><em>xiaoMaoALiCloud.js</em></a></td><td>XiaoMao</td><td>2024.6.08</td>
    </tr>
	<tr>
		<td > 17 </td> <td > 加藤视频VIP  </td> <td ><a href="https://raw.githubusercontent.com/WeiGiegie/666/main/jtsp.js"><em>jtsp.js</em></a></td><td>WeiGiegie</td><td>2024.6.08</td>
    </tr>
	<tr>
		<td > 18 </td> <td > 迅雷VIP  </td> <td ><a href="https://whatshub.top/rewrite/thunder.conf"><em>thunder.conf</em></a></td><td>Marol62926</td><td>2024.6.08</td>
    </tr>
		<tr>
		<td > 19 </td> <td > KeepVIP  </td> <td ><a href="https://whatshub.top/rewrite/keep.conf"><em>keep.conf</em></a></td><td>89996462</td><td>2024.6.08</td>
    </tr>
   </tr>
		<tr>
		<td > 20 </td> <td > 喜马拉雅儿童VIP  </td> <td ><a href="https://raw.githubusercontent.com/WeiGiegie/666/main/xmet.js"><em>xmet.js</em></a></td><td>WeiGiegie</td><td>2024.6.08</td>
    </tr>		
	<tr>
		<td colspan="5">  </td>
    </tr>
    <tr>
		<td rowspan="28"><strong>广告屏蔽</strong></td>
		<td > 1 </td> <td > 微信小程序去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Applet.conf"><em>Applet.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
    <tr>
		<td > 2 </td> <td > 墨鱼去开屏2.0 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/StartUp.conf"><em>StartUp.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
    <tr>
		<td > 3 </td> <td > 油管广告屏蔽<br><strong><em>视频自动PIP+背景播放</strong></em> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/YoutubeAds.conf"><em>YoutubeAds.conf</em></a></td><td>divineEngine<br>Maasea</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 4 </td> <td > <s> 公众号图文去广告 </s><br><strong><em>无法去除朋友圈AD</strong></em> </td> <td ><s> <a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/WeChat.conf"><em>WeChatAdBlock.conf</em></a></s> </td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 知乎去广告 </td> <td ><a href="https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/zheye/zheye.snippet"><em>Zhihu_Plus.conf</em></a></td><td>blackmatrix7</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 6 </td> <td > 百度贴吧去广告 </td> <td ><a href="https://github.com/app2smile/rules/raw/master/module/tieba-qx.conf"><em>Tieba_Ads.conf</em></a></td><td>app2smile</td> <td>2024.5.23</td> 
    </tr>
	<tr>
		<td > 7 </td> <td > 百度网盘去广告 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/f43026707830c7818ee3ba624e383c8d/raw/baiduCloud.vip.js"><em>BdPanAdBlock.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
		<tr>
		<td > 8 </td> <td > <strong><em>喜马拉雅去广告</strong></em> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Ximalaya.conf"><em>XmlyAdBlock.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 9 </td> <td > 小红书去水印</td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/XiaoHongShu.conf"><em>XiaoHongShu.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 10 </td> <td > Keep超级净化</td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/KeepStyle.conf"><em>keepStyle.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 11 </td> <td > <strong>Pixiv去广告 </strong></td> <td ><a href="https://github.com/ddgksf2013/Scripts/raw/master/pixivAds.js"><em>PixivAds.js</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 12 </td> <td > 酷安去广告</td> <td ><a href="https://github.com/ddgksf2013/Scripts/raw/master/coolapk.js"><em>coolapk.js</em></a></td><td>ddgksf2013</td> <td>2024.5.23</td> 
    </tr>
	<tr>
		<td > 13 </td> <td > 12306去广告</td> <td ><a href="https://github.com/ddgksf2013/Scripts/raw/master/12306.js"><em>12306.js</em></a></td><td>ddgksf2013</td> <td>2024.5.23</td> 
    </tr>
	<tr>
		<td > 14 </td> <td >[未适配新版] <s> 多多视频去广告</s>  </td> <td ><s> <a href="https://raw.githubusercontent.com/ddgksf2013/Scripts/master/rrtv_json.js"><em>DuoduoVideoAds.js</em></a></s> </td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 15 </td> <td > <strong>微博(国际版)去广告 </strong></td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Weibo.conf"><em>Weibo.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 16 </td> <td > 高德地图去广告[卸载重装] </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Amap.conf"><em>Amap.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 17 </td> <td > 网易云去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Netease.conf"><em>Netease.conf</em></a></td><td>ddgksf2013</td> <td>2024.5.23</td> 
    </tr>
	<tr>
		<td > 18 </td> <td > 菜鸟裹裹去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Cainiao.conf"><em>Cainiao.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 19 </td> <td > 起点去广告[卸载重装] </td> <td ><a href="https://raw.githubusercontent.com/app2smile/rules/master/module/qidian.conf"><em>qidian.conf</em></a></td><td>app2smile</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 20 </td> <td > 随手记去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/SuiShouJi.conf"><em>SuiShouJi.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 21 </td> <td > Bing首页简化 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/BingSimplify.conf"><em>BingSimplify.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 22 </td> <td >[新版失效]<s> 优酷净化[卸载重装]</s> </td> <td ><s> <a href="https://gist.githubusercontent.com/ddgksf2013/5b431857f8b88acbc7ac2453a21e676a/raw/youku.adblock.js"><em>youku.adblock.js</em></a></s> </td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
    <tr>
		<td > 23 </td> <td > 百度地图净化[卸载重装] </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/beec132ca0c3570ffa0cf331bce8f82a/raw/baidumap.adblock.conf"><em>baidumap.conf</em></a></td><td>ddgksf2013</td>  <td>2024.5.23</td>
    </tr>
<tr>
		<td > 24 </td> <td > 皮皮虾净化及去水印 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/bb1dadbd32f67c68772caebcc70b0a33/raw/pipixia.adblock.js"><em>pipixia.adblock.js</em></a></td><td>Liquor030</td> <td>2024.5.23</td> 
    </tr>
	<tr>
		<td > 25 </td> <td > 什么值得买 </td> <td ><a href="https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/smzdm/smzdm_remove_ads.qxrewrite"><em>smzdmAds.conf</em></a></td><td>blackmatrix7</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 26 </td> <td > 微信阅读精简 </td> <td ><a href="https://raw.githubusercontent.com/Maasea/sgmodule/master/WeRead.sgmodule"><em>WeRead.sgmodule</em></a></td><td>Maasea</td><td>2024.5.23</td>  
    </tr>
	<tr>
		<td > 27 </td> <td > 去广告合集 </td> <td ><a href="https://raw.githubusercontent.com/fmz200/wool_scripts/main/QuantumultX/rewrite/chongxie.txt"><em>chongxie.txt</em></a></td><td>fmz200</td><td>2024.6.02</td>  
    </tr>
	<tr>
		<td > 28 </td> <td > 酷我广告净化 </td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/ad%20guard/kuwoadblock.conf"><em>kuwoadblock.conf</em></a></td><td>ddgksf2013</td><td>2024.6.08</td>  
    </tr>
	<tr>
		<td colspan="5">  </td>
    </tr>
	<tr>
		<td rowspan="13"><strong>应用增强</strong></td>
		<td > 1 </td> <td > <s>B站自动换区</s>[不适用新版] ●</td> <td ><s><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/BilibiliAutoRegion.conf"><em>BilibiliAutoRegion.conf</em></a></s></td><td>Nobyda</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 2 </td> <td > <strong>B站CC繁体字幕转简体</strong> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/Bilibili_CC.conf"><em>Bilibili_CC.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 3 </td> <td > 百度网盘净化+解锁倍速 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/f43026707830c7818ee3ba624e383c8d/raw/baiduCloud.vip.js"><em>BaiduCloud.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 4 </td> <td > Youtube无中文字幕机翻方案 </td> <td ><a href="https://raw.githubusercontent.com/id77/QuantumultX/master/rewrite/Youtube_CC.conf#out=Hant"><em>Youtube_CC.conf</em></a></td><td>id77</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 各种流媒体字幕翻译 </td> <td ><a href="https://raw.githubusercontent.com/Neurogram-R/Quantumult-X/main/snippet/Dualsub.snippet"><em>Dualsub.conf</em></a></td><td>Neurogram-R</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 6 </td> <td > 微信110解锁被屏蔽的URL </td> <td ><a href="https://raw.githubusercontent.com/ddgksf2013/Rewrite/master/Function/UnblockURLinWeChat.conf"><em>WeChat110.conf</em></a></td><td>zZPiglet</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 7 </td> <td > 指南针解锁经纬度 ●</td> <td ><a href="https://raw.githubusercontent.com/VirgilClyne/iRingo/main/snippet/Location.snippet"><em>Location.conf</em></a></td><td>VirgilClyne</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 8 </td> <td > Testflight共享+解锁区域限制 ●</td> <td ><a href="https://raw.githubusercontent.com/NobyDa/Script/master/TestFlight/TestFlightAccount.js"><em>TestFlightAccount.conf</em></a></td><td>NobyDa</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 9 </td> <td > UposRedirect </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/UposRedirect.conf"><em>UposRedirect.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 10 </td> <td > <strong>阿里云盘倍速</strong> </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/f4752e632fd3375ea2811985c5b635dc/raw/alicloud.js"><em>alicloud.js</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 11 </td> <td > Spotify歌词翻译 [需要API] ●</td> <td ><a href="https://raw.githubusercontent.com/app2smile/rules/master/js/spotify-lyric.js"><em>spotify-lyric.js</em></a></td><td>app2smile</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 12 </td> <td > VVebo修复用户时间线 </td> <td ><a href="https://raw.githubusercontent.com/bin64/Scripts/main/QuantumultX/vvebo.js"><em>vvebo.js</em></a></td><td>suiyuran</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td > 13 </td> <td > Siri解锁全功能 ●</td> <td ><a href="https://raw.githubusercontent.com/misitechan/-QuantumultX-/main/rewrite-gather/other/Siri.snippet"><em>Siri.js</em></a></td><td>iRingo</td>  <td>2024.5.23</td>
    </tr>
	<tr>
		<td colspan="5">  </td>
    </tr>
	<tr>
		<td rowspan="7"><strong>网页优化</strong></td>
		<td > 1 </td> <td > 自用影视网站去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/WebAdBlock.conf"><em>WebAdBlock.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 2 </td> <td > Google自动翻页 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/EndlessGoogle.conf"><em>EndlessGoogle.conf</em></a></td><td>langkhach</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 3 </td> <td > <strong><em>Safari超级搜索V2.0</em></strong><br>翻译·社区·购物·换区·视频·引擎  </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/Q-Search.conf"><em>Q-Search.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 4 </td> <td > 豆瓣电影<br><strong><em>网页优化+快捷观影</em></strong>  </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/Douban.conf"><em>Douban.conf</em></a></td><td>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 解锁NewBing搜索 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/NewBing.conf"><em>NewBing.conf</em></a></td><td>Nobyda<br>ddgksf2013</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 6 </td> <td > 百度搜索去广告 </td> <td ><a href="https://raw.githubusercontent.com/limbopro/Adblock4limbo/main/Adblock4limbo.conf"><em>Adblock4limbo.conf</em></a></td><td>limbopro</td><td>2024.5.23</td>
    </tr>
	<tr>
		<td > 7 </td> <td > 解决Google搜索人机验证 ●</td> <td ><a href="https://raw.githubusercontent.com/NobyDa/Script/master/QuantumultX/Snippet/GoogleCAPTCHA.snippet"><em>CAPTCHA.snippet</em></a></td><td>NobyDa</td><td>2024.5.23</td>
    </tr>
</table>

> 更多的重写请参考 [*@ddgksf2013*](https://github.com/ddgksf2013) 提供的 [***Quantumult X 重写配置***](https://github.com/ddgksf2013/Rewrite/tree/master)，[*@deezertidal*](https://github.com/deezertidal/QuantumultX-Rewrite) 提供的 [***Quantumult X 重写配置***](https://whatshub.top/quantumultx)

## 4️⃣QuantumultX 脚本Task：

- [x] QX每日色图脚本 [*setu.js*](https://github.com/ddgksf2013/Scripts/raw/master/setu.js)
- [x] 得宝小程序签到 [*db.js*](https://github.com/ddgksf2013/Scripts/raw/master/debao.js)
- [x] 同程旅行小程序签到 [*tclx.js*](https://github.com/ddgksf2013/Scripts/raw/master/tclx.js)
- [x] 书香门第网页签到 [*sxmd.js*](https://github.com/ddgksf2013/Scripts/raw/master/shuxiangmendi.js)
- [x] 每天60s读懂世界 [*60s.js*](https://github.com/ddgksf2013/Scripts/raw/master/60s.js)
- [x] Glados签到 [*glados.js*](https://gist.githubusercontent.com/ddgksf2013/32b3d37d78433a34370cbfb69780160d/raw/glados.js)
- [x] Emby自动保号 [*emby.js*](https://gist.githubusercontent.com/ddgksf2013/e6793129fba99bb539cd7a49f74a48fa/raw/embyAutoSign.js)

> 更多的签到脚本请参考 [*@Chavyleung*](https://github.com/chavyleung) 提供的 [***Quantumult X 签到脚本***](https://github.com/chavyleung/scripts/blob/master/QuantumultX_Remote_Task.conf)

## 5️⃣QuantumultX 图标库

| 序号 | 点击名称快捷添加图标订阅 | 作者 |
| :----: | :---- | :----: |
| 1  | [Qure图标库（彩色1）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fgithub.com%2FKoolson%2FQure%2Fraw%2Fmaster%2FOther%2FQureColor-All.json%22%0A%5D) | Koolson |
| 2  | [Qure图标库（彩色2）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FKoolson%2FQure%2Fmaster%2FOther%2FQureColor.json%22%0A%5D) | Koolson | 
| 3  | [Qure图标库（mini）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FKoolson%2FQure%2Fmaster%2FOther%2FQuremini.json%22%0A%5D) |  Koolson |
| 4  | [Orz-3图标库（mini style）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fgithub.com%2FOrz-3%2Fmini%2Fraw%2Fmaster%2Fmini.json%22%0A%5D) | Orz-3 |
| 5  | [Orz-3图标库（mini color）](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FOrz-3%2Fmini%2Fmaster%2FminiColor.json%22%0A%5D) | Orz-3 |
| 6  | [泡泡图标库 ](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2Ftugepaopao%2FImage-Storage%2Fmaster%2Fother%2FCute.json%22%0A%5D) | tugepaopao |
| 7 | [小猫咪库](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FYuanxsxs%2FQtumultX%2Fmaster%2FIcon%2FCatcat.json%22%0A%5D) | Yuanxsxs |
| 8 | [姿势图标库](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FLovedGM%2FQuantumult-X-TuBiao%2Fmain%2Fzishi-cs.json%22%0A%5D) | LovedGM | 
| 9 | [Semporia库 ](https://quantumult.app/x/open-app/ui?module=gallery&type=icon&action=add&content=%5B%0A%20%20%20%20%22https%3A%2F%2Fraw.githubusercontent.com%2FSemporia%2FHand-Painted-icon%2Fmaster%2FSemporia.json%22%0A%5D) | Semporia |

> 更多的图标订阅请参考 [*@ddgksf2013*](https://github.com/ddgksf2013) 集合的 [***Quantumult X 图标库***](https://github.com/ddgksf2013/Icon/blob/master/README.md)

## 6️⃣Awesome Resource：

* 1080P超清IPTV国内[***直播源***](https://github.com/ddgksf2013/M3U8LIST/raw/master/IPTV2022.m3u)
* 网盘资源 [*Tg.md*](https://t.me/ddgksf2023): TrollStore、Windows、Cracker.ipa、Android.apk...
* [***优秀Web网站合集***](https://github.com/misitechan/html)：影视、工具、下载、阅读、Porn...
* IOS手机端应用推荐[*Appraven.net*](https://appraven.net/collection/37743082)
* 微信屏蔽朋友圈广告[*WeChat.web*](https://mp.weixin.qq.com/s/f_miMTmLOTDnk4C0OanHyw)
* IOS、Android[TV]、Web、AppleTV观影方案[***Notion.md***](https://ddgksf2013.notion.site/IOS-Android-TV-Web-AppleTV-737275e3de2c4def86196d8c982ef86e?pvs=4)
* 一些自用优质安卓APPS [***Awesome-Android-Apps***](https://github.com/misitechan/Android)
* 收集脚本[***合集***](https://github.com/misitechan/-QuantumultX-/tree/main/Task)：各种自动签到脚本、日报、提醒...
---

## 7️⃣ [免责声明](https://github.com/misitechan/-QuantumultX-)  <a name="7️⃣"></a>

### 本仓库声明

**本仓库**（以下简称“**本库**”）提供的所有信息、文档、脚本、配置文件（以下简称“**内容**”）均由用户自主收集、整理和分享，旨在为QuantumultX等工具的用户提供参考和便利。使用本库内容时，请用户自行承担风险，并遵守以下条款：

### 1. 责任限制

- 本产品提供的所有信息、工具和资源均按“现状”提供，不包含任何形式的保证。
- 我们不对因使用本产品而可能产生的任何直接、间接、附带的损失或损害承担责任。

### 2. 版权和知识产权

- 本产品中包含的所有内容，包括但不限于文本、图像、音频、视频和代码，均为我们或其相应的版权持有者所有。
- 未经明确授权，您不得复制、修改、分发或以任何方式使用上述内容。

### 3. 用户行为

- 用户应遵守所有适用的法律法规，不得使用本产品进行任何非法活动。
- 用户不得通过本产品传播恶意软件、垃圾邮件或参与任何可能损害他人权益的行为。

### 4. 服务更改和中断

- 我们保留随时修改或中断服务的权利，无论是暂时的还是永久的，且不承担由此给用户带来的任何责任。

### 5. 第三方链接

- 本产品可能包含指向第三方网站或资源的链接，我们不控制这些第三方网站，也不对它们的内容负责。

### 6. 免责声明的变更

- 我们保留随时更新和修改免责声明的权利，用户应定期查看以获取最新信息。

### 7. 适用法律

- 本免责声明应受中华人民共和国法律管辖，并按照该国法律解释。

通过使用本库内容，即表示用户已阅读、理解并同意上述免责声明。如有任何疑问或异议，请在继续使用前停止使用本库内容。

## 8️⃣特别感谢：

以下排名不分先后

[**@ddgksf2013**](https://github.com/ddgksf2013) [*@Blackmatrix7*](https://github.com/blackmatrix7/ios_rule_script) [*@DivineEngine*](https://github.com/DivineEngine) [*@App2smile*](https://github.com/app2smile/rules)  [*@Peng-YM*](https://github.com/Peng-YM) [*@Nick-workflow*](https://github.com/Nick-workflow) [*@KOP-XIAO*](https://github.com/KOP-XIAO) [*@NobyDa*](https://github.com/NobyDa) [*@Neurogram-R*](https://github.com/Neurogram-R) [*@yjqiang*](https://github.com/yjqiang) [*@O7Y0*](https://github.com/O7Y0) [*@Choler*](https://github.com/Choler) [*@id77*](https://github.com/id77) [*@zmqcherish*](https://github.com/zmqcherish) [*@Qure*](https://github.com/Koolson/Qure) [*@Orz-3*](https://github.com/Orz-3) [*@kyle*](https://github.com/Xirou) [*@HotKids*](https://github.com/hotKids) [*@langkach*](https://github.com/langkhach270389) [*@lxk0301*](https://github.com/lxk0301) [*@zqzess*](https://github.com/zqzess/rule_for_quantumultX) [*@Anti-AD*](https://github.com/privacy-protection-tools/anti-AD) [*@VirgilClyne*](https://github.com/VirgilClyne/iRingo#iringo) [*@zZPiglet*](https://github.com/zZPiglet/Task/tree/master) [*@Chavyleung*](https://github.com/chavyleung) [*@tugepaopao*](https://github.com/tugepaopao/Image-Storage) [*@Yuanxsxs*](https://github.com/Yuanxsxs) [*@LovedGM*](https://github.com/LovedGM/Quantumult-X-TuBiao) [*@Semporia*](https://github.com/Semporia) [*@Koolson*](https://github.com/Koolson)

---

### [回到顶部](https://github.com/misitechan/-QuantumultX-)

