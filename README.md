# TouchWX

使用TouchWX开发小程序，需要学习@[小程序文档](https://developers.weixin.qq.com/miniprogram/dev/)。
`TouchWX是基于小程序组件机制开发的，所以说支持小程序全部语法。`

### 下载demo

1.下载TouchWX
```
npm install
```
2.终端命令
```
tui dev 或 tui build
```
3.启动项目
```
打开微信开发工具，选择小程序。
1.项目目录选择dist文件路径。
2.填写AppID。
3.填写项目名称。
4.完成。小程序项目首页。
```

### 创建一个新的小程序
#####安装详细流程请参考官方文档。

开发工具
```
Visual Studio Code 下载地址：https://code.visualstudio.com。
```
调试工具（微信开发工具）
```
微信开发工具 下载地址：https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html
```
插件安装
```
VS中安装Touch WX和Vetur E。
Vetur E是我们基于vue语法插件Vetur扩展，具有微信小程序API语法提示功能
```
touchui-wx-cli
```
npm install -g touchui-wx-cli
```

touchui-wx-component
```
npm install touchui-wx-components@1.0.89
```
#####项目目录结构

![WechatIMG77.jpeg](https://upload-images.jianshu.io/upload_images/2928955-b0fa57e3a3531d08.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 使用

#####终端或者VS终端输入命令。

启动服务
```
tui dev
```
打包dist
```
tui build
```

#####微信开发工具启动项目
![WechatIMG76.jpeg](https://upload-images.jianshu.io/upload_images/2928955-899322dbdf71e2dc.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


```
1.项目目录是打包好的dist目录。
2.AppID有就填写，无就选体验。
3.输入项目名称。
```

### 使用区别


