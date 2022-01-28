# day20220129加快打开GitHub

昨天最后的五分钟，没有打卡GitHub，气得直捶头。

随意状态，打开网页搜了搜GitHub。

发现了一个简书文章：解决GitHub官网打不开问题

照着里边的步骤，果然，瞬开网页——知识就是力量！

## 方法如下：

将如下文件复制：

#github
140.82.112.4 github.com
199.232.69.194 github.global.ssl.fastly.net
185.199.108.153 assets-cdn.github.com
185.199.110.153 assets-cdn.github.com
185.199.111.153 assets-cdn.github.comem32\drivers\etc

粘贴至C:\Windows\System32\drivers\etc中的hosts中

打开cmd窗口，执行ipconfig /flushdns命令

解决了大的心头大患！

又是收获的一天。
