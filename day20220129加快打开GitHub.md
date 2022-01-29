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

晚上又找了几个教程，其中一个说hosts中的内容可以自动更新，我便又试了试。

下边是代码：

# GitHub520 Host Start
185.199.108.154               github.githubassets.com
140.82.113.22                 central.github.com
185.199.108.133               desktop.githubusercontent.com
185.199.108.153               assets-cdn.github.com
185.199.108.133               camo.githubusercontent.com
185.199.108.133               github.map.fastly.net
199.232.69.194                github.global.ssl.fastly.net
140.82.113.3                  gist.github.com
185.199.108.153               github.io
140.82.114.4                  github.com
140.82.112.6                  api.github.com
185.199.108.133               raw.githubusercontent.com
185.199.108.133               user-images.githubusercontent.com
185.199.108.133               favicons.githubusercontent.com
185.199.108.133               avatars5.githubusercontent.com
185.199.108.133               avatars4.githubusercontent.com
185.199.108.133               avatars3.githubusercontent.com
185.199.108.133               avatars2.githubusercontent.com
185.199.108.133               avatars1.githubusercontent.com
185.199.108.133               avatars0.githubusercontent.com
185.199.108.133               avatars.githubusercontent.com
140.82.113.9                  codeload.github.com
52.217.88.28                  github-cloud.s3.amazonaws.com
52.216.238.99                 github-com.s3.amazonaws.com
52.216.26.252                 github-production-release-asset-2e65be.s3.amazonaws.com
52.217.101.68                 github-production-user-asset-6210df.s3.amazonaws.com
52.217.48.84                  github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.108.153               githubstatus.com
64.71.168.201                 github.community
185.199.108.133               media.githubusercontent.com


# Update time: 2021-03-16T12:24:16+08:00
# Star me GitHub url: https://github.com/521xueweihan/GitHub520
# GitHub520 Host End

看着还挺全面，功效嘛，有待验证！
