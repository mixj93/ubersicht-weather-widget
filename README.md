# Übersicht Weather Widget

Nice and powerful weather widget for [Übersicht](http://tracesof.net/uebersicht/).

## Screenshot

![Screenshot](./screenshot.jpg)

## Install

### Install Übersicht

Just downloading from [Übersicht's website](http://tracesof.net/uebersicht/).

### Download Widget

### Configure Widget

You can edit config in source file. To use this widget, you should at least get an Dark Sky Key [here](https://darksky.net/dev/account). [Dark Sky](https://darksky.net/) is a really good weather service.

```js
// Dark Sky Key https://darksky.net/dev/account
const KEY = 'your_dark_sky_key'
const LANG = 'zh' // language: en for English, zh for Chinese
// weather data units
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
