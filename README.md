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


---

## 方法详解

### getPlugins()

`释义`
获取浏览器的插件信息。

### getUserAgent()

`释义`
获取浏览器的userAgent信息。
