# postboy
您的定时打卡小助手<br>
目前支持application/json和application/x-www-form-urlencoded的定时post工具<br>

最新地址：http://180.76.111.151/<br>
<h2>一.应用场景</h2><br>
    针对一些打卡、签到类的场景，开发了这款postboy，可以定时帮助我们发送此类请求，得到微信通知。<br>
    在日常生活中，我们总会遇到需要每天打卡或签到领取奖励的场景。在这个巴拉巴拉的时代，每天手动真的好累累，所以我就抽空地用自己的服务器部署了下这个postboy小工具。方便自己打卡签到的同时，也为了好玩分享给大家使用。<br>
<h2>二.教程</h2><br>
请参考：
https://www.yuque.com/docs/share/c51e0279-192b-492b-8b6b-e97385b79c38<br>
大体流程：1.使用fiddler等工具抓包 2.如果需要微信通知，关注虾推啥公众号获取token  3.打开postboy网站，选择需要的打卡时间，提交抓取的数据<br>
<h2>三.其他</h2><br>
代码结构：前后端使用的是pythonweb flask，发送post请求用的是java(因为以前写过就懒得改了)，定时任务使用的是我租用的VPS中的crontab。（不会泄露用户data，请安心使用）<br>
消息通知工具使用到了这位大佬的虾推啥：http://www.xtuis.cn/<br>
