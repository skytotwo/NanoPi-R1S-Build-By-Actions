# 使用Github的Actions功能在线编译NanoPi-R1S固件（包含H5和H3）
之前我们要编译OpenWrt固件，就需要自己准备好虚拟机，或者租好服务器，准备好梯子，编译一次耗时4,5个小时都有，很费力劳神。实际上像这种编译的操作完全可以放在Github上来执行，最近入手了NanoPi-R1s H5，自己也用传统方式编译了几个固件，但也想着能否尝试更方便的编译。随后，便尝试编写了NanoPi-R1s的Actions的YML执行文件，自己尝试了下，编译很成功，整个过程就是“简单，顺畅”，一共耗时大概2小时，一旦启动了Actions服务，你就可以关闭网页该干嘛干嘛，随时可以打开页面查看进度
下图是编译的结果页面：
![QQ20191207164250.png](http://picture.totoro.site/images/2019/12/07/QQ20191207164250.png)
可以看到它会按照你给的步骤一步步自动执行，随后编译完成，会打包压缩，直接点击下载即可。

具体查看博客：https://totoro.site/index.php/archives/70/
![QQ20191210160737.png](http://picture.totoro.site/images/2019/12/10/QQ20191210160737.png)
