# Übersicht 天气插件

> 优雅而强大的[Übersicht](http://tracesof.net/uebersicht/)天气插件.
>
> [Read in English](https://github.com/mixj93/uebersicht-weather-widget/blob/master/README.md)

## 🎉🎉🎉 2.0 版本！ 从 Dark Sky 更新到 Open Weather

[由于 Dark Sky 不再接受新的注册](https://blog.darksky.net/)。现在插件使用 [Open Weather](https://openweathermap.org/)，请放心食用。

## 截图

![截图](./screenshot.jpg)

## 安装

### 安装 Übersicht

直接从[Übersicht 官网](http://tracesof.net/uebersicht/)下载安装。

### 下载插件

下载[最新版本](https://github.com/mixj93/uebersicht-weather-widget/releases/latest)的插件压缩包，解压缩下载的文件并把 `weather.jsx` 放到 Übersicht 的插件文件夹中。

### 配置插件

你可以在源文件中编辑配置。要使用该插件，至少需要配置一个 Open Weather API 密钥，可以在[这里](https://home.openweathermap.org/api_keys)申请。[Dark Sky](https://openweathermap.org/)是提供非常好用的天气服务，免费账号每分钟可以允许最多 60 个的请求或每月最多 1,000,000 个的请求。

```js
// Dark Sky 密钥 https://openweathermap.org/api
const KEY = 'OPEN_WEATHER_API_KEY'
// 语言: en表示英语, zh表示中文
const LANG = 'zh'
// 天气数据的单位
// standard(default), metric and imperial units are available.
const UNITS = 'metric'
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
- 添加 Übersicht 应用

阅读更多关于[定位服务](https://support.apple.com/zh-cn/guide/mac-help/mh35873/mac)的信息。

## 贡献代码

想要改进这个插件？[提交 issue](https://github.com/mixj93/uebersicht-weather-widget/issues/new)或者 fork 本仓库并提交 PR :stuck_out_tongue_winking_eye:.

## 协议

[MIT](./LICENSE)
