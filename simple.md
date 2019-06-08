**simple**  
```js
var simple = require('simple');
simple.echo('ping', 'pong');

simple.login('./your/token/');
```
---
**[login](./simple/login)** => login with `token`   
**[echo](./simple/echo)** => when receive `req`, response with `res`  
**[on](./simple/on)** => event register  
**[set](./simple/set)** => set the config  
**[client](./simple/client)** => origin client object [client on djs](https://discord.js.org/#/docs/main/stable/class/Client)