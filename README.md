# cordova-plugin-wkwebview-cookie-sync


### Preface
> This plugin was forked from https://github.com/raccoondev85/cordova-plugin-wkwebview-inject-cookie


### About
> This plugin returns the cookies from wkwebview for a specific url so the cookies can be used (e.g. to get the cookies from cordova-plugin-inappbrowser and pass it to cordova-plugin-advanced-http). The plugin also allows to set cookies to wkwebview.


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
> It doen't work with the UIWebView on iOS (It's deprecated by Apple).