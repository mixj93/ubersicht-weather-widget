# Übersicht天气插件

优雅而强大的[Übersicht](http://tracesof.net/uebersicht/)天气插件.

[Read in English](https://github.com/mixj93/uebersicht-weather-widget/blob/master/README.md)

## 截图

![截图](./screenshot.jpg)

## 安装

### 安装Übersicht

直接从[Übersicht官网](http://tracesof.net/uebersicht/)下载安装。

### 下载插件

下载[最新版本](https://github.com/mixj93/uebersicht-weather-widget/releases/latest)的插件压缩包，解压缩下载的文件并把 `weather.jsx` 放到Übersicht的插件文件夹中。

### 配置插件

你可以在源文件中编辑配置。要使用该插件，至少需要配置一个Dark Sky的开发者密钥，可以在[这里](https://darksky.net/dev/account)申请。[Dark Sky](https://darksky.net/)是提供非常好用的天气服务，免费账号每天可以允许最多1000个的请求。

```js
// Dark Sky 密钥 https://darksky.net/dev/account
const KEY = 'your_dark_sky_key'
// 语言: en表示英语, zh表示中文
const LANG = 'zh'
// 天气数据的单位
// auto: automatically select units based on geographic location
// ca: same as si, except that windSpeed is in kilometers per hour
// uk2: same as si, except that nearestStormDistance and visibility are in miles and windSpeed is in miles per hour
// us: Imperial units (the default)
// si: SI units
const UNITS = 'auto'
// 主题: 浅色主题（light），深色主题（dark）
const theme = 'dark'
// 背景透明度 0 ~ 1
const backgroundTransparency = 0.75
// 插件位置
const POSITION = {
  x: 'right', // x可以为左（left）或右（right）
  y: 'top', // y可以为上（top）或下（bottom）
  marginX: 20,
  marginY: 20
}
```

### 启用定位服务

天气插件需要启用定位服务。按照以下步骤来启用定位服务：

- 打开*系统偏好设置*
- 点击*安全性与隐私*
- 点击*隐私*
- 选择*定位服务*
- 添加Übersicht应用

阅读更多关于[定位服务](https://support.apple.com/zh-cn/guide/mac-help/mh35873/mac)的信息。

## 贡献代码

想要改进这个插件？[提交issue](https://github.com/mixj93/uebersicht-weather-widget/issues/new)或者fork本仓库并提交PR :stuck_out_tongue_winking_eye:.

## 协议

[MIT](./LICENSE)
