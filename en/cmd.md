# simple.cmd() : fn(key, fn(msg, arg)) #
```js
var simple = require('simple');
//...your code here...
simple.cmd('sum', functicmd(msg, arg){
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
## `simple.cmd(key, fn(msg, arg));` ##
### key : string (required) ###
### fn : functicmd (required) ###

---

####        msg : [Message class](https://discord.js.org/#/docs/main/stable/class/Message) ####
####        arg : array ####

---

When receive `key`, call fn(msg, arg)   
`msg` is the origin object from [discord.js](https://discord.js.org/#/docs/main/stable/class/Message),
`arg` is a array ccmdtain parsed command and arguments => `[cmd, arg1, arg2, arg3 ......]`
