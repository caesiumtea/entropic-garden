#### general
- indentation is optional/not semantic
-  `console.log(x)`   where x is a variable, prints value of x to the console


#### variables
var is global
let is only within the scope it's declared
const is a "variable" that can't be changed (throws error if you try)
- **variables and function names are case sensitive**

#### objects
```javascript
var myobj = {
"prop1": "nice",
2: "cool"
}
```
- **property names are not written like variables!!** if it's a word then it's a STRING. other types like ints can also be property names/keys. idek if "name" is what it's called, prolly not.
- objects can be declared more willy-nilly than you tend to think.. like an object is basically jsut any jumble of key-value pairs stuffed into some curly braces, in the same way in array is jsut any random shit shoved into some square braces.
- method to check if a property exists: `myobj.hasOwnProperty(p)`
##### rules for dot notation
- *however*  when  you use dot notation like `myobj.prop1` THEN it's like some kind of special case where if the key is a string, you write it without quotes after the dot. only works when there are no spaces in the string!! 
- if the key is a strong containing whitespace then you need to use bracket notation (? is that what its called) instead like `myobj["prop1"]` . 
- basically *bracket notation shold always be valid* no matter what the the key is, whereas dot notation is more of a special case???

##### `this`,  global object, etc
-  `this` refers to whatver object is being referenced on the line that's currently being evaluated
- if no context is specified then the default value is what's called the "global object" - in a web browser this is generally `window` from the DOM
- but declaring 'strict mode' (?) makes it consider the default global object `undefined` instead


#### idk
- switch is a thing. better than elif chains sometimes, espcially if several 