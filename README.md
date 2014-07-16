# browser 

---
[![Build Status](https://travis-ci.org/dreamstu/browser.svg?branch=master)](https://travis-ci.org/dreamstu/browser)
[![spm version](http://spmjs.io/badge/browser)](http://spmjs.io/package/browser)

一套方便灵活的高可用的前端组合框架. 提供browser信息的基础组件

---

## Install

```
$ spm install browser --save
```

## Usage

```js
var browser = require('browser');
// use browser
```

---
## 属性概要

### adobeAir

`释义`
用户使用的是否是adobe 的air内嵌浏览器。

### chrome

`释义`
用户使用的浏览器的版本号，如果是0表示不是此浏览器 用户使用的浏览器的版本号，如果是0表示不是此浏览器。

### firefox

`释义`
用户使用的浏览器的版本号，如果是0表示不是此浏览器 用户使用的浏览器的版本号，如果是0表示不是此浏览器。


### ie

`释义`
用户使用的浏览器的版本号，如果是0表示不是此浏览器 用户使用的浏览器的版本号，如果是0表示不是此浏览器。


### mobileSafari

`释义`
用户使用的浏览器的版本号，如果是0表示不是此浏览器 用户使用的浏览器的版本号，如果是0表示不是此浏览器。


### name

`释义`
用户使用的浏览器的名称，如：chrome 用户使用的浏览器的名称，如：chrome。


### opera

`释义`
用户使用的浏览器的版本号，如果是0表示不是此浏览器 用户使用的浏览器的版本号，如果是0表示不是此浏览器。


### safari

`释义`
用户使用的浏览器的版本号，如果是0表示不是此浏览器 用户使用的浏览器的版本号，如果是0表示不是此浏览器。


### version

`释义`
浏览器的版本。


### engine

`释义`
浏览器引擎对象。

engine.name
`释义`
浏览器的引擎名字

engine.version
`释义`
浏览器的引擎版本

engine.gecko
`释义`
gecko 引擎的版本，0表示非此引擎。

engine.presto
`释义`
presto 引擎的版本，0表示非此引擎

engine.trident
`释义`
trident 引擎的版本，0表示非此引擎

engine.webkit
`释义`
webkit 引擎的版本，0表示非此引擎


### features

`释义`
浏览器特征信息对象。

>features.air

>features.query

>features.xpath

### plugins

`释义`
浏览器插件信息对象。


### platform

`释义`
浏览器platform信息对象。

###platform.name

`释义`
操作系统的名称

###platform.win
`释义`
操作系统的版本号，如果是0表示不是此操作系统 操作系统的版本号，如果是0表示不是此操作系统

###platform.android
`释义`
操作系统的版本号，如果是0表示不是此操作系统 Mozilla/5.0 (Linux; U; Android 2.0; en-us; Droid Build/ESD20) AppleWebKit/530.17 (KHTML, like Gecko) Version/4.0 Mobile Safari/530.17 操作系统的版本号，如果是0表示不是此操作系统

###platform.iPad
`释义`
操作系统的版本号，如果是0表示不是此操作系统 Mozilla/5.0 (iPad; U; CPU OS 3_2 like Mac OS X; en-us) AppleWebKit/531.21.10 (KHTML, like Gecko) version/4.0.4 Mobile/7B367 Safari/531.21.10 操作系统的版本号，如果是0表示不是此操作系统

###platform.iPhone
`释义`
操作系统的版本号，如果是0表示不是此操作系统 Mozilla/5.0 (iPhone; U; CPU iPhone OS 3_0_1 like Mac OS X; zh-cn) AppleWebKit/528.18 (KHTML, like Gecko) Version/4.0 Mobile/7A400 Safari/528.16 操作系统的版本号，如果是0表示不是此操作系统

###platform.iPod
`释义`
操作系统的版本号，如果是0表示不是此操作系统 iPod touch Mozilla/5.0 (iPod; U; CPU iPhone OS 3_0 like Mac OS X; zh-cn) AppleWebKit/528.18 (KHTML, like Gecko) Version/4.0 Mobile/7A341 Safari/528.16 操作系统的版本号，如果是0表示不是此操作系统

###platform.linux
`释义`
操作系统的版本号，如果是0表示不是此操作系统 操作系统的版本号，如果是0表示不是此操作系统

###platform.mac
`释义`
操作系统的版本号，如果是0表示不是此操作系统 操作系统的版本号，如果是0表示不是此操作系统

###platform.getPlatform()




---

## 方法详解

### getPlugins()

`释义`
获取浏览器的插件信息。

### getUserAgent()

`释义`
获取浏览器的userAgent信息。
