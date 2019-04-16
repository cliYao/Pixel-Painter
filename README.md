# Pixel Painter

* 取色器

<img src="https://github.com/cliYao/Pixel-Painter/raw/master/ScreenShots/1.gif" width="75%" height="75%">

* 放大

<img src="https://github.com/cliYao/Pixel-Painter/raw/master/ScreenShots/2.gif" width="75%" height="75%">

* 拖拽

<img src="https://github.com/cliYao/Pixel-Painter/raw/master/ScreenShots/3.gif" width="75%" height="75%">

* 多终端同步显示

<img src="https://github.com/cliYao/Pixel-Painter/raw/master/ScreenShots/4.gif" width="75%" height="75%">


* 自动保存图片，服务器重启不丢失数据

# 功能列表

* 使用canvas绘制，以节省内存提升性能
* 使用websocket进行实时传输
* 使用express构建http服务器
* 使用ws模块构建websocket后端并且express集成
* 后端使用buffer保存图片实时数据
* 后端自动保存图片状态，服务器重启也不会丢失
* 首次打开页面时，后端将图片转为png编码传给前端，以节省流量，加快打开速度
* 只有在画板上点击时，后端才会自动保存状态
* Vue
* 画板放大
* 取色器