
Firefox

(locate firefox, rpm -ql firefox)

显示程序菜单 alt

下载地址
https://www.mozilla.org/en-US/firefox/all/

(自带flash)
https://github.com/7900ms/00nottheater_deserted/blob/master/Installation_Manual/flash.txt

```
tab
Tab Mix Plus (使用内建的页面恢复机制)
(不用 Tab Mix Plus 因为没有按钮，用于“所有新标签在后台打开”)
(仅当 Tab Utilities 用不了时，比如在Firefox上，才可能出现 “用到 Tab Mix Plus” 的时机)

去广告
uBlock Origin

html 保存
UnMHT

flash拦截
http://www.adobe.com/software/flash/about/
FlashDisable 插件

鼠标摇杆手势
Mouse Gestures Suite

网页代理
FoxyProxy Standard

搜索直连
Google search link fix

中文网址
about:config ====> network.standard-url.escape-utf8 (默认t)改为 f (不改也可以用 ttps:// 式的复制粘贴得到中文网址)

三方插件
about:config 页面，xpinstall.signatures.required 设置为 false



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
```
=

https://github.com/7900ms/0nottheater_deserted_/tree/master/Usage_Manual/Firefox (centOS+xfce)

https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/Firefox (mac)

https://github.com/7900ms/00nottheater_deserted/tree/master/Usage_Manual/PaleMoon


