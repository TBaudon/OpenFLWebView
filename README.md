OpenFLWebView
=============

Display a web page in your openfl game.

##Use

add OpenFLWebView in your haxelib.
Then :

  ```haxe
  var mWebView = new WebView("http://wwww.myWebSite.net", 800,800);
  mWebView.x = 200;
  mWebView.y = 100;
  addChild(mWebView);
  //later----
  mWebView.loadUrl("newUrl");
  ```
Please note that event if it looks like it's a displayObject, it won't respect the display hierarchy as it's basicaly a WebView on top of the game mainView. So it will always appear on top of your game, what ever you do.
  
##RoadMap
* Move the webview
* Remove the webView
* iOS
