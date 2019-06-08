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

---

####        msg : [Message class](https://discord.js.org/#/docs/main/stable/class/Message) ####
####        arg : array ####

---

當收到命令 `key` 時，呼叫 `fn(msg, arg)`  
`msg` 是 [discord.js](https://discord.js.org/#/docs/main/stable/class/Message) 的 `message` 物件  
`arg` 是包含已解析的命令的陣列，他長的像這樣 `[cmd, arg1, arg2, arg3 ......]`
