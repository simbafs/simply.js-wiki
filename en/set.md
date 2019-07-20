# simple.set() : fn(option, val) #
```js
var simple = require('simple');

simple.set('prefix', '/');
simple.set('splitChar', ' ');
//your command will like => /sum 1 2 3 4 5
```
```js
var simple = require('simple');

simple.set('prefix', 'e/');
simple.set('splitChar', ':');
//your command will like => e/sum:1:2:3:4:5

```
---
## `simple.set(key, val);` ##
### key : string (required) ###
### val : string (required) ###

Set `option key` to `val`

---
## Available Options ##

|   key      |   val      |
|   :----:   |   :----    |
| prefix | string     |
| splitChar  | atring     |
| activity   | string     |
