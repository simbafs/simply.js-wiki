# simple.on() : fn(key, fn(msg, arg)) #
```js
var simple = require('simple');
//...your code here...
simple.on('sum', function(msg, arg){
	if(arg.length == 1){
		msg.reply('WRONG: at least a number');
	}else{
		var sum = 0;
		for(var i = 1; i < arg.length; i++){
			sum += arg[i];
		}
		msg.reply(sum);
	}
});
simple.login(token);
```
---
## `simple.on(key, fn(msg, arg));` ##
### key : string (required) ###
### fn : function (required) ###
#### msg : [Message class](https://discord.js.org/#/docs/main/stable/class/Message) ####
#### arg : array ####
When receive `key`, call fn with `msg`, `arg`  
msg is the origin object from [discord.js](https://discord.js.org/#/docs/main/stable/class/Message),
arg is a array contain parsed command and arguments => `[cmd, arg1, arg2, arg3 ......]`
