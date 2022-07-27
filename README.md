# postboy———您的定时打卡小助手<br>
<div align=center>
<img src="https://user-images.githubusercontent.com/64674765/181200364-99a35443-d645-4bf4-b824-7b7f9c32eda8.jpg" width="50%">
</div>
<br>
<h3>最新地址：http://180.76.111.151/</h3><br>
<h2>一.应用场景</h2><br>
    目前支持application/json和application/x-www-form-urlencoded的定时post工具<br>
    针对一些打卡、签到类的场景，开发了这款postboy，可以定时帮助我们发送此类请求，得到微信通知。<br>
    在日常生活中，我们总会遇到需要每天打卡或签到领取奖励的场景。在这个巴拉巴拉的时代，每天手动真的好累累，所以我就抽空地用自己的服务器部署了下这个postboy小工具。方便自己打卡签到的同时，也为了好玩分享给大家使用。<br>
<h2>二.教程</h2><br>
请参考：
https://www.yuque.com/docs/share/c51e0279-192b-492b-8b6b-e97385b79c38<br>
大体流程：1.使用fiddler等工具抓包 2.如果需要微信通知，关注虾推啥公众号获取token  3.打开postboy网站，选择需要的打卡时间，提交抓取的数据<br>
<h2>三.其他</h2><br>
代码还没清理自己的数据，暂不开源，后续有时间会上传一个docker镜像大家可以自行部署，如果是简单使用可以暂时用我的网站工具，有问题可以提issue或者公众号“弄倭乱来”联系。<br>
代码结构：前后端使用的是pythonweb flask，发送post请求用的是java(因为以前写过就懒得改了)，定时任务使用的是我租用的VPS中的crontab。（不会泄露用户data，请安心使用）<br>
消息通知工具使用到了这位大佬的虾推啥：http://www.xtuis.cn/<br>
欢迎关注我的公众号，方便获取更新消息、留言答疑、一起玩耍<br>
<img src="https://user-images.githubusercontent.com/64674765/181194615-2ae83f5e-4472-4507-9e37-c0ef84ae9ed5.png" width="30%">
