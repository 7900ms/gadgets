
Firefox

(locate firefox, rpm -ql firefox)

显示程序菜单 alt

```
下载地址 Firefox Release 
https://www.mozilla.org/en-US/firefox/all/
下载地址 Firefox ESR (when in trouble, try using ESR)
https://www.mozilla.org/en-US/firefox/organizations/all/
```

(自带flash)
https://github.com/7900ms/00nottheater_deserted/blob/master/Installation_Manual/flash.txt

```
about:config
extensions.legacy.enabled (Firefox Release 66 之后失效)
```
```
tab (过期)
Tab Mix Plus (使用内建的页面恢复机制)
(不用 Tab Mix Plus 因为没有按钮，用于“所有新标签在后台打开”)
(仅当 Tab Utilities 用不了时，比如在Firefox上，才可能出现 “用到 Tab Mix Plus” 的时机)

tab 新解决方案(实现 新标签在当前标签右侧+自动打开链接在新标签)
Open Tabs Next to Current
https://addons.mozilla.org/en-US/firefox/addon/open-tabs-next-to-current/?src=search
Open in new tab
https://addons.mozilla.org/en-US/firefox/addon/open-in-new-tab-domain/?src=search

去广告
uBlock Origin

undo tab
Undo Closed Tabs Button

html 保存
UnMHT

flash拦截
http://www.adobe.com/software/flash/about/
FlashDisable 插件

鼠标摇杆手势 (过期)
Mouse Gestures Suite

鼠标摇杆手势 
Foxy Gestures
https://addons.mozilla.org/en-US/firefox/addon/foxy-gestures/?src=search

母语阅读
TranslateWebpageAtGoogle
https://translate.google.com/translate?hl=zh-CN&sl=en&tl=zh-CN&u=

搜索直连
~Google search link fix~
google-no-tracking-url 

中文网址
about:config ====> network.standard-url.escape-utf8 (默认t)改为 f (不改也可以用 ttps:// 式的复制粘贴得到中文网址)


```
```
首选项
  主页 about:blank
  检查更新 no
  记住网站密码 no

webrtc漏洞测试
  https://haoip.cn/
  防止：
  ublock:防止 WebRTC 泄露本地IP地址

dns
  114.114.114.110
  114.114.115.110
  DNS 清理
  sudo dscacheutil -flushcache && sudo killall -HUP mDNSResponder

内存
  about:config
  media.mediasource.webm.enabled ===> 改为 t
  启用硬件加速

SSD写入保护
  about:config
  browser.sessionstore.interval ====》 默认 15000 || 60000(六万，即60秒 1分钟)(注：15000，是15秒)
  改为 1800000 即 30分钟

  https://www.v2ex.com/t/308601

三方插件
  about:config 页面，xpinstall.signatures.required 设置为 false

homepage
  https://github.com/7900ms/noname/blob/master/homepage.txt

图集
http://imgur.com/a/sgrpQ

下载
curl -O http://xxxx.plist

网页代理
  FoxyProxy Standard
  https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt
  AutoProxy Base64

```
=

https://github.com/7900ms/0nottheater_deserted_/tree/master/Usage_Manual/Firefox (centOS+xfce)

https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/Firefox (mac)

https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/PaleMoon


