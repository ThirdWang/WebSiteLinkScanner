# WebSiteLinkScanner
网站内链接扫描,简单的做一些网站内的链接搜集,也可以保存图片   

## 选项说明  
<pre>-m  http://www.baidu.com/  # 就是要扫描的网站  
-s                          # 有此选项可保存图片  
-t  3                       # 请求一个链接等待时间，单位是秒，默认为0，如设置3秒，等待时间为2~4秒之间的一个随机值  
-b                          # 有此选项，在扫描结束后发出警告声提示扫描结束，提示10声，在cmder下无效  
-l  500                     # 保存url最长长度，默认为600，超过600则不保存</pre>
-z                          # 有此选项则扫描子域名