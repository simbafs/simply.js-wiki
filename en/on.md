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
registe a event
available events：
|   events   |   description  |
|    :---:   |      :---:     |
|   ready    |    trigger     |
