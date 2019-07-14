# simple.set() : fn(option, val) #
```js
var simple = require('simple');

simple.set('promptChar', '/');
simple.set('splitChar', ' ');
//你的命令會長的像這樣 => /sum 1 2 3 4 5
```
```js
var simple = require('simple');

simple.set('promptChar', 'e/');
simple.set('splitChar', ':');
//你的命令會長的像這樣 => e/sum:1:2:3:4:5

```
---
## `simple.set(key, val);` ##
### key : string (required) ###
### val : string (required) ###

把 `key` 設定成 `val`    

---
## 可用的設定值 ##

|   key      |   val      |
|   :----:   |   :----:   |
| promptChar |   string   |
| splitChar  |   atring   |
| activity   |   string   |
