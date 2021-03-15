# cordova-plugin-wkwebview-inject-cookie


### Preface
> This plugin was forked from https://github.com/raccoondev85/cordova-plugin-wkwebview-inject-cookie


### About
> The plugin returns cookies from WKWebView for specific url so the cookies can be used (e.g. to get cookies from cordova-plugin-inappbrowser and pass them to cordova-plugin-advanced-http). The plugin also allows to set cookies to WKWebView.


### Install

> Install latest release

     cordova plugin add @zalaris/cordova-plugin-wkwebview-inject-cookie
     
> Or install from github master

     cordova plugin add https://github.com/zalaris/cordova-plugin-wkwebview-inject-cookie
     
### Uninstall

     cordova plugin rm @zalaris/cordova-plugin-wkwebview-inject-cookie

## Usage

```
wkWebView.setCookie(domain, path, name, value, expire, successCallback, errorCallback);
wkWebView.getCookies(url, successCallback, errorCallback)
```

## Limitations
> The plugin does not work with old UIWebView on iOS (It has been deprecated by Apple).