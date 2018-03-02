# jquery-date [![npm](https://img.shields.io/npm/v/jquery-date.svg)](https://www.npmjs.com/package/jquery-date) 
> the mobile jquery date plugin 

说明
-----------------------------------
- 此插件依赖jquery，且是为移动端而写，也支持pc端的使用，但因为操作不便和样式问题，所以不建议。
- 支持年月、年月日、年月日时分、年月日时分秒，详细格式见demo.html/jquery-date.js。
- 时间限制limitTime参数目前只做了年月日限制。

下一版本计划，这里除了bug修复将不再做任何更新
-----------------------------------
- 不依赖jquery，实现无依赖。
- 使用new重写，配置将不挂在dom上。

使用方式
-----------------------------------
### commonJS
```js
var $ = require('jquery');
require('jquery-date');
$.date('#date');
```
### require.js
```js
require(['jquery-date'],function(){
    $.date('#date');
})
```
### browser
```js
$.date('#date');
```
demo
-----------------------------------
请点击 [demo page](https://weijhfly.github.io/date-demo.html "demo")