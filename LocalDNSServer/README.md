#  工作原理

* 通过macOS的`/etc/resolver/`目录功能定义指定域名（根域名）使用的DNS服务器为本地服务器。在目录中创建名为local的文件
``` local
domain example.com
nameserver 127.0.0.1
```
* 通过dnsmasq提供本地DNS服务功能

