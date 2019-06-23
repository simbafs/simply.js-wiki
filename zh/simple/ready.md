# simple.ready() : fn() #
```js
var simple = require('simple');
simple.ready(() => {
    console.log('i\'m ready!');
});
```
---
## simple.ready(fn); ##
### fn() : function (required) ###
當機器人準備好時（登入之後），呼叫後面的 callback 函數
