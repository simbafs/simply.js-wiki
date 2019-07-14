# simple.echo() : fn(req, res) #
```js
var simple = require('simple');
//...your code here...
simple.echo('ping', 'pong');
simple.login(token);
```
---
## `simple.echo(req, res);` ##
### req : string (required) ###
### res : string (required) ###
當收到命令 `req` 時回覆 `res`   
---
#### 幫助訊息 ####
```js
var simple = require('simple');

simple.echo('help', 'use `ping` to check bot status, `help` to get help');
simple.login(token);
```
