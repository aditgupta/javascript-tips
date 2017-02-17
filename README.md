# javascript-tips

Use the literal syntax rather than creating them with native constructor

```javascript
//Don't do this
var a = new String("abc");
typeof a //'object'

//Do this
a = "abc"
typeof a //'string'
```
