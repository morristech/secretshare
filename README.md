secretshare
===========

度盘秘享(secretshare)，使用二维码分享文件，妈妈再也不用担心我被<del>查水表</del>了


你有一个苹果我有一个苹果，我们把自己的苹果给对方，于是我们都有了两个苹果。
但是问题来了，用百度网盘分享文件被菊爆了怎么办？为什么送快递的又来敲我的门？
现在[度盘秘享]帮你解决这个问题，妈妈再也不用担心文件被xx了。

Bob使用[度盘秘享]将Bob百度网盘中的文件xxx.mp4提取生成成二维码，Bob将二维码分享给Alice，Alice再用[度盘秘享]扫描二维码，xxx.mp4就已经在Alice的百度网盘中了。就是这么简单，再也不用担心菊爆，再也不用担心收快递了。

## 截图

![main][1]


## 实现了哪些功能

 1. 模拟百度登陆
 2. 百度网盘REST浏览
 3. 二维码生成
 4. 二维码解析
 5. 百度网盘接口解析调用
 
## 使用到的开源项目

 1. android support v4 & v7
 2. commons-io
 3. gson
 4. jsoup
 5. okhttp
 6. zxing-core

[1]: /img/2-file-explore.png