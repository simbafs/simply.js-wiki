# simple.on() : fn(event, fn) #
```js
var simple = require('simple');
//...your code here...
simple.on('ready', () => {
    console.log('I\'m ready');
});
simple.login(token);
```
---
## simple.login(event, fn); ##
### event : string (required) ###
### fn : function (require) ###
註冊一個事件  
可用的事件：
|   事件     |      敘述      |
|  :---:    |      :---:     |
|   ready   |當機氣人上線時觸發 |
