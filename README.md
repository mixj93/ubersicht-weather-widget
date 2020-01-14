# Übersicht Weather Widget

Nice and powerful weather widget for [Übersicht](http://tracesof.net/uebersicht/).

[阅读中文文档](https://github.com/mixj93/uebersicht-weather-widget/blob/master/README-zh.md)


## Screenshot

![Screenshot](./screenshot.jpg)

## Install

### Install Übersicht

Just downloading from [Übersicht's website](http://tracesof.net/uebersicht/).

### Download Widget

Download the widget zip file check out [the latest release](https://github.com/mixj93/uebersicht-weather-widget/releases/latest), unzip the file and put `weather.jsx` into Übersicht widgets folder.

### Configure Widget

You can edit config in source file. To use this widget, you should at least get an Dark Sky Key [here](https://darksky.net/dev/account). [Dark Sky](https://darksky.net/) is a really good weather service and allows up to 1,000 free calls per day.

```js
// Dark Sky Key https://darksky.net/dev/account
const KEY = 'your_dark_sky_key'
// language: en for English, zh for Chinese
const LANG = 'zh'
// weather data units
// auto: automatically select units based on geographic location
// ca: same as si, except that windSpeed is in kilometers per hour
// uk2: same as si, except that nearestStormDistance and visibility are in miles and windSpeed is in miles per hour
// us: Imperial units (the default)
// si: SI units
const UNITS = 'auto'
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

- Go to *System Preferences*
- Click the *Security & Privacy*
- Click the *Privacy* tab
- Select *Location Services*
- Add Übersicht App

More information about [Location Services](https://support.apple.com/en-us/HT204690).

## Contribute

Have an idea for improving this widget? [Open an issue](https://github.com/mixj93/uebersicht-weather-widget/issues/new) or fork this repository and send a pull request :stuck_out_tongue_winking_eye:.

## License

[MIT](./LICENSE)
