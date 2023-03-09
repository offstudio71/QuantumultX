懒人配置文件（Quantumult X）:分流、重写规则

## 1️⃣QuantumultX 懒人配置
* 配置更新时间：2023-03-09
* 自用QX配置 [***Cuttlefish.conf***](https://github.com/ddgksf2013/Profile/raw/master/QuantumultX.conf) 
* 上述配置支持QX商店最新版，包括图标库订阅、智能分流、去广告、各种APP净化、Boxjs订阅、流媒体解锁查询...

## 2️⃣QuantumultX 分流：
* 网易云音乐分流 [*NeteaseMusic.list*](https://github.com/ddgksf2013/Filter/raw/master/NeteaseMusic.list)
* 自用影视广告屏蔽 [*Mybreak.list*](https://github.com/ddgksf2013/Filter/raw/master/Mybreak.list)
* IP隐藏の分流[不建议使用] [*Anti-ip.list*](https://github.com/ddgksf2013/Filter/raw/master/anti-ip-attribution.list)
* Emby分流 [*Emby.list*](https://github.com/ddgksf2013/Filter/blob/master/Emby.list)

## 3️⃣QuantumultX 复写：
<table>
    <tr> <th> 类别 </th> <th> 序号 </th> <th> 功能 </th> <th> 链接 </th> <th> 作者 </th> </tr >
    <tr>
		<td rowspan="4"><strong>会员解锁</strong></td>
		<td > 1 </td> <td > 真B站去广告+解锁普通视频<br><strong><em>1080P高码率</em></strong> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Bilibili.conf"><em>BilibiliVip.conf</em></a></td><td>ddgksf2013</td>
    </tr>	
	<tr>
		<td > 2 </td> <td > Spotify会员 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/UnlockVip/Spotify.conf"><em>SpotifyPro.conf</em></a></td><td>app2smile</td>
    </tr>
	<tr>
		<td > 3 </td> <td > 酷我音乐SVIP+净化 </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/0f76e952f0c4a2579932f45a209b40c3/raw/Kuwo.conf"><em>Kuwo.conf</em></a></td><td>ddgksf2013</td>
    </tr>
  	<tr>
		<td colspan="5">  </td>
    </tr>
    <tr>
		<td rowspan="19"><strong>广告屏蔽</strong></td>
		<td > 1 </td> <td > 微信小程序去广告 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/Applet.conf"><em>Applet.conf</em></a></td><td>ddgksf2013</td>
    </tr>
    <tr>
		<td > 2 </td> <td > 油管广告屏蔽<br><strong><em>视频自动PIP+背景播放</strong></em> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/YoutubeAds.conf"><em>YoutubeAds.conf</em></a></td><td>divineEngine<br>Maasea</td>  
    </tr>
	<tr>
		<td > 3 </td> <td > 公众号图文去广告<br><strong><em>无法去除朋友圈AD</strong></em> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/AdBlock/WeChat.conf"><em>WeChatAdBlock.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 4 </td> <td > 知乎去广告 </td> <td ><a href="https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/zheye/zheye.snippet"><em>Zhihu_Plus.conf</em></a></td><td>blackmatrix7</td>  
    </tr>
	<tr>
		<td > 5 </td> <td > <strong>Pixiv去广告 </strong></td> <td ><a href="https://github.com/ddgksf2013/Scripts/raw/master/pixivAds.js"><em>PixivAds.js</em></a></td><td>ddgksf2013</td>  
    </tr>
	<tr>
		<td colspan="5">  </td>
    </tr>
	<tr>
		<td rowspan="10"><strong>应用增强</strong></td>
		<td > 1 </td> <td > B站自动换区 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/BilibiliAutoRegion.conf"><em>BilibiliAutoRegion.conf</em></a></td><td>Nobyda</td>
    </tr>
	<tr>
		<td > 2 </td> <td > <strong>B站CC繁体字幕转简体</strong> </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/Bilibili_CC.conf"><em>Bilibili_CC.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 3 </td> <td > 百度网盘倍速 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/BaiduCloud.conf"><em>BaiduCloud.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 4 </td> <td > Youtube无中文字幕机翻方案 </td> <td ><a href="https://raw.githubusercontent.com/id77/QuantumultX/master/rewrite/Youtube_CC.conf#out=Hant"><em>Youtube_CC.conf</em></a></td><td>id77</td>
    </tr>
	<tr>
		<td > 5 </td> <td > 各种流媒体字幕翻译 </td> <td ><a href="https://raw.githubusercontent.com/Neurogram-R/Quantumult-X/main/snippet/Dualsub.snippet"><em>Dualsub.conf</em></a></td><td>Neurogram-R</td>
    </tr>
	<tr>
		<td > 6 </td> <td > 微信110解锁被屏蔽的URL </td> <td ><a href="https://github.com/zZPiglet/Task/raw/master/UnblockURLinWeChat.conf"><em>WeChat110.conf</em></a></td><td>zZPiglet</td>
    </tr>
	<tr>
		<td > 7 </td> <td > Testflight共享+解锁区域限制 </td> <td ><a href="https://raw.githubusercontent.com/NobyDa/Script/master/TestFlight/TestFlightAccount.js"><em>TestFlightAccount.conf</em></a></td><td>NobyDa</td>
    </tr>
	<tr>
		<td > 8 </td> <td > UposRedirect </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Function/UposRedirect.conf"><em>UposRedirect.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 9 </td> <td > <strong>阿里云盘倍速</strong> </td> <td ><a href="https://gist.githubusercontent.com/ddgksf2013/f4752e632fd3375ea2811985c5b635dc/raw/alicloud.js"><em>alicloud.js</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td colspan="5">  </td>
    </tr>
	<tr>
		<td rowspan="4"><strong>网页优化</strong></td>
		<td > 1 </td> <td > Google自动翻页 </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/EndlessGoogle.conf"><em>EndlessGoogle.conf</em></a></td><td>langkhach</td>
    </tr>
	<tr>
		<td > 2 </td> <td > <strong><em>Safari超级搜索V2.0</em></strong><br>翻译·社区·购物·换区·视频·引擎  </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/Q-Search.conf"><em>Q-Search.conf</em></a></td><td>ddgksf2013</td>
    </tr>
	<tr>
		<td > 3 </td> <td > 豆瓣电影<br><strong><em>网页优化+快捷观影</em></strong>  </td> <td ><a href="https://github.com/ddgksf2013/Rewrite/raw/master/Html/Douban.conf"><em>Douban.conf</em></a></td><td>ddgksf2013</td>
    </tr>
</table>

## 4️⃣QuantumultX 脚本Task：
- [x] 喵喵记账每日签到 [*mmjz.js*](https://github.com/ddgksf2013/Scripts/raw/master/mmjz.js)
- [x] QX每日色图脚本 [*setu.js*](https://github.com/ddgksf2013/Scripts/raw/master/setu.js)
- [x] 得宝小程序签到 [*db.js*](https://github.com/ddgksf2013/Scripts/raw/master/debao.js)
- [x] 同程旅行小程序签到 [*tclx.js*](https://github.com/ddgksf2013/Scripts/raw/master/tclx.js)
- [x] 书香门第网页签到 [*sxmd.js*](https://github.com/ddgksf2013/Scripts/raw/master/shuxiangmendi.js)
- [x] 每天60s读懂世界 [*60s.js*](https://github.com/ddgksf2013/Scripts/raw/master/60s.js)

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
