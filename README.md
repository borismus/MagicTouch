# MagicTouch.js *by Boris Smus*

Standards-compatible touch event implementation to make it easier to develop
web applications for for multitouch devices.

## Installation

1. Install [npTuioClient NPAPI plugin:](https://github.com/fajran/npTuioClient)
  * Copy npTuioClient.plugin to ~/Library/Internet Plug-Ins/
  * Note that on Mac OS X 10.8 and up, you will require version
[1.5b1-osx](https://github.com/downloads/fajran/npTuioClient/npTuioClient-1.5b1-osx.zip)

2. Install [TongSeng](https://github.com/fajran/tongseng)
  * Run TongSeng.app and press the Start button

3. Include [MagicTouch.js](http://github.com/borismus/MagicTouch) and embed the npTuioClient plugin in your application:


```html
<head>
  <!-- your head -->
  <script src=”/path/to/magictouch.js"</script>
</head>

<body>
  <!-- your body -->
  <object id="tuio" type="application/x-tuio" style="width: 0px; height: 0px;">
    Touch input plugin failed to load!
  </object>
</body>
```

4. Use `touch event` [APIs](http://www.w3.org/TR/touch-events/)

## Browser Compatibility

Tested on Chrome 10
