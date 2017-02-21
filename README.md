# javascript-tips

###Use the literal syntax rather than creating them with constructor form

```javascript
//Don't do this
var a = new String("abc");
typeof a //'object'

//Do this
a = "abc"
typeof a //'string'

var faultyArray = new Array(1);
a // 'undefined'
a.length //1 Whoa! The constructor takes the argument as length rather than an array element
```
###Use the concise form for defining object literal methods

```javascript
//Object methods
const foo = {
  atom(){},
  molecule(){},
  compound(){}
 }
 ```
###JSON.stringify(..) will omit undefined, function and symbol values

```javascript
JSON.stringify(function(){}); //undefined
```

###Use Strict to avoid errors and accidental deeclaration of variables in global scope
```javascript
(function(){
  'use strict';
  })();
 ```
 ###Function declarations are hosted to the top of the function in which they occur
 ```javascript
 
 ```
 
