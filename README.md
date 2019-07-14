# Welcome to the simple wiki! #    
bug report please use [issue](https://github.com/simba-fs/simple/issues)    
thank you for using my library   

---
# Install #  
with npm:   
`npm install simba-fs/simple`
---

# Document #
[wiki](./simple.md)  
[中文](./README-zh-TW.md)  

# Code #
[simple](https://github.com/simba-fs/simple)


**simple**  
```js
var simple = require('simple');
simple.echo('ping', 'pong');

simple.login('./your/token/');
```
---
**[login](./simple/login.md)** => login with `token`   
**[echo](./simple/echo.md)** => when receive `req`, response with `res`  
**[on](./simple/on.md)** => event register  
**[set](./simple/set.md)** => set the config  
**[client](#)** => origin client object [client on djs](https://discord.js.org/#/docs/main/stable/class/Client)  
**[ready](./simple/ready.md)** => ready  
