<div align="center">
    <h1>WebView 电视</h1>
<div align="center">

![GitHub Repo stars](https://img.shields.io/github/stars/hxh19950701/WebViewTvLive)
![GitHub top language](https://img.shields.io/github/languages/top/hxh19950701/WebViewTvLive)
![GitHub repo size](https://img.shields.io/github/repo-size/hxh19950701/WebViewTvLive)
![GitHub Release](https://img.shields.io/github/v/release/hxh19950701/WebViewTvLive)


</div>
    <p>使用 腾讯X5 WebView 开发的电视直播App</p>
</div>
    <p>原理：加载官方直播网页，识别网页中的video标签自动全屏。</p>

    
<img src="./images/image_1.jpg"/>
<br/>
<img src="./images/image_2.jpg"/>


## 功能

- 自动更新频道列表
- 多直播源
- 播放异常自动换源/刷新
- 应用自定义设置
- 适配手机、平板和电视
- 上下键换台反转

## 待开发的功能
- 数字键换台
- 自定义播放列表源
- 局域网远程设置
- 手势调节屏幕亮度和音量
- 适配回看功能
- 自主选择是否启用TBS内核

## 下载
- 从 Github 下载 <br>
https://github.com/hxh19950701/WebViewTvLive/releases <br>
- 微信 <br>
若您不方便访问 Github，也可关注微信公众号 “**网页电视**” 获取最新版下载链接。

## 优势

- 直接使用官网直播链接，非常稳定可靠
- 兼容 m3u8 链接

## 局限

- 比起直接加载直播源，载入频道稍长，需要等待一定时间
- 使用的是网页播放器播放，对设备性能有一定的要求
- 对低版本 Android 设备兼容性比较差，建议 Android 9 或以上的设备
- 官网直播，无法选择视频清晰度，大部分为720P
- 官网直播，帧率有限，大部分为24FPS

## FAQ

**Q: 在我的电视机/盒子上无法自动全屏？**<br/>
A: 一般是设备 WebView 的问题，待X5内核下载完成，重启 App 即可。若无法自动下载X5内核，请在设置-TBS调试界面内选择“安装线上内核”来手动安装。<br/>
<br/>
**Q: 访问央视网总提示“您当前的浏览器不支持视频播放，请升级浏览器或更换设备”？**<br/>
A: 和上面是一样的问题，安装X5内核或者升级设备的WebView即可解决。<br/>
<br/>
**Q: 在TBS调试界面“安装线上内核”老是失败？**<br/>
A: 可能刚好遇到了官方X5内核下载限流时间段，请换个时间段重试。参见[《关于官网X5内核SDK加载不稳定问题说明》](https://doc.weixin.qq.com/doc/w3_AGoAtwbdAFwlo0hmqkbTl6p19tCOV)。<br/>
<br/>
**Q: 尝试了以上所有的办法，在我的设备上依然闪退/无法自动全屏？**<br/>
A: 请去这里反馈。https://github.com/hxh19950701/WebViewTvLive/issues/34<br/>
<br/>
**Q: 我打开怎么只有CCTV-1？**<br/>
A: ~~频道列表托管在Github，出现此问题请检查您与Github之间的连接。~~<br/>
最新的版本应该不会出现这样的问题了。

## 注意
- 请尊重作者，源码仅供您学习、交流使用。<br/>
- 若您二次打包了我的应用，请自用，或者在注明原App名称的情况下适度分享。<br/>
- 不要利用此项目牟利。<br/>
- 本项目中的官方直播地址均为网友自行收集，若不小心侵犯了版权方的权益，请联系作者删除。<br/>

## 捐赠
如果 App 对您有帮助，请捐赠作者。作者会更积极的维护此项目！<br/>
<a href="DonationList.md">查看已捐赠名单</a>
<br/>
<br/>
<img src="./images/image_5.png"/>