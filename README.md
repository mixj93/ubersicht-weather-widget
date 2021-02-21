# Übersicht Weather Widget

> Nice and powerful weather widget for [Übersicht](http://tracesof.net/uebersicht/).
>
> [阅读中文文档](https://github.com/mixj93/uebersicht-weather-widget/blob/master/README-zh.md)

## 🎉🎉🎉 Version 2.0! Upgrade from Dark Sky to Open Weather

[Because Dark Sky no longer accepting new signups](https://blog.darksky.net/). Now this widget use [Open Weather](https://openweathermap.org/), please rest assured to use.

## Screenshot

![Screenshot](./screenshot.jpg)

## Install

### Install Übersicht

Just downloading from [Übersicht's website](http://tracesof.net/uebersicht/).

### Download Widget

Download the widget zip file check out [the latest release](https://github.com/mixj93/uebersicht-weather-widget/releases/latest), unzip the file and put `Weather.jsx` into Übersicht widgets folder.

### Configure Widget

You can edit config in source file. To use this widget, you should at least get an Open Weather API Key [here](https://home.openweathermap.org/api_keys). [Open Weather](https://openweathermap.org/) is a really good weather service and allows up to 60 free calls/minute or 1,000,000 free calls/month.

```js
// Open Weather API Key https://openweathermap.org/api
const KEY = 'OPEN_WEATHER_API_KEY'
// language: en for English, zh for Chinese
const LANG = 'zh'
// standard(default), metric and imperial units are available.
const UNITS = 'metric'
// theme: light or dark
const theme = 'dark'
// background transparency. value from 0 to 1
const backgroundTransparency = 0.75
// widget position
const POSITION = {
  x: 'right', // x is left or right
  y: 'top', // y is top or bottom
  marginX: 20,
  marginY: 20
}
```

### Enable Location Services

Weather widget need to use location services. Follow these steps to enable location services:

- Go to _System Preferences_
- Click the _Security & Privacy_
- Click the _Privacy_ tab
- Select _Location Services_
- Add Übersicht App

More information about [Location Services](https://support.apple.com/en-us/HT204690).

## Contribute

Have an idea for improving this widget? [Open an issue](https://github.com/mixj93/uebersicht-weather-widget/issues/new) or fork this repository and send a pull request :stuck_out_tongue_winking_eye:.

## License

[MIT](./LICENSE)
