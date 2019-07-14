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
When receive `req`, response `res`
a simple way to create a small chat bot and help information
---
#### help information ####
```js
var simple = require('simple');

simple.echo('help', 'use `ping` to check bot status, `help` to get help');
simple.login(token);
```
