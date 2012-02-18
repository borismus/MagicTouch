#MagicTouch.js *by Boris Smus*

Standards-compatible touch event implementation to make it easier to develop
web applications for for multitouch devices.

##Installation

1. Install [npTuioClient NPAPI plugin:](https://github.com/fajran/npTuioClient)
  * Copy npTuioClient.plugin to ~/Library/Internet Plug-Ins/

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

4. Use `touch event` [APIs](http://dvcs.w3.org/hg/webevents/raw-file/tip/touchevents.html)

##Browser Compatibility

Tested on Chrome 10
