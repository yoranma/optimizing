## 网站优化项目
主要技术点：
* 1.分析网站性能，保障网站流畅运行，渲染速度在60fps以下，避免卡顿、界面元素强制更新等问题
* 2.借助辅助工具(如page speed insights等)优化页面关键路径、资源文件大小尺寸等
* 3.对外站点部署的方式有多种(github page或ngrok等)



## 测试方式
测试环境：win10 + chrome 62


### 1)科学上网：shadowsocks
* https://github.com/shadowsocks/shadowsocks-windows

### 2)发布站点 github page 或 ngrok35 
* 或者使用github配置项，搭建github page站点，即时对外发布的站点了。（推荐）
* https://ngrok.com/download
* https://ngrok.com/docs 搭建本地站点，并对外发布


### 3)谷歌插件跑分 pagespeed insight
* https://developers.google.com/speed/pagespeed/insights/
* https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fac705072.ngrok.io%2F&tab=desktop

### 4)根据优化建议优化站点

* 压缩图片的方法: TinyPng44 -- https://tinypng.com/, Base64 Image30 -- https://www.base64-image.de/
* 优化谷歌字体加载：异步
* https://www.lockedowndesign.com/load-google-fonts-asynchronously-for-page-speed/
* 最小化css
  https://cssminifier.com/
  http://www.phpied.com/cssmin-js/
* 最小化js
  http://closure-compiler.appspot.com/


### 5)参考别人经验优化
* https://discussions.youdaxue.com/t/topic/38793