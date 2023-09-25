## Syllabus
| Topic          | state |
| -------------- | ----- |
|1. Basic          | ✅    |
|2. Object         |       |
|3. Dom            |       |
|4. Event          |       |
|5. Asynchunous    |       |
|6. OOP            |       |
|7. Error handling |       |
|8. Advance Js     |       |



## 1. BASIC
---

### what 
-  lightweight interpreted  , high level , multi-paradigm , single-threded , dynamically-typed , programming language.

### why 
- use to Make web page dynamic ,  render with html.

### ecmascript
- It is ensure that difrent documnets on js are actually talking about the same language
- js = ecmascript
- we use ES5 + ES6

### setup
- 2 way 
  1. write code in `.html` file
```html
...
<body>
 <script>
 //javascript code
 </script>
</body>...

example.html
```
   2. write code in `.js` file and link with html
```html
<body>

 <script src= "./index.js">
 </script>
</body>...

example.html
```

### variable
- container to hold data
- dynamictyped language so no need to maintion type
- 3 way to declare a variable
   1. using var      , eg- var a = "hello"
   2. using let       , eg- let b = 123
   3. using const   , eg- const = "world"

| Properties      | var | let | const |
| --------------- | --- | --- | ----- |
| global scoped   | ✔   | ✔   | ✔     |
| function scoped |  ✔    | ✔   | ✔     |
| block scoped    | ✖   | ✔   | ✔     |
| redeclared      | ✔   | ✔   | ✖     |
| reassign        | ✔   | ✖   | ✖     |
| add in          | ES1   | ES6 (2015)   | ES6 (2015)      |
| hoisting        | allowed    |  not allowed   |   not allowed    |

**def** hoisting : auto declarear on the top

### data type
1. **Primitive data type**
   - Number  => var num = 34.6
   - String      => var str = "i am ahsan"
   - Boolean   => var bool = true
   - Undefined => var yu = undefinde
   - Null           => var mi = Null
   
 **NOTE** : but also object wrapper for primitive type that have many inbuilt methods,  also can call method via primitive type.
         eg - let str = new String ();
         
2. **Non-pemitive data type**
   - Object => var obj = {name:"ahsan", roll : 12};
   - Array => var arr = [1,"hello", 2.5];
   - regexp => var num = 5 => var reg = \` the value of num= ${num}  \`

### operators 
1. Arithmetic operators => + , - , * , / , **, % , ++ , -- 
2. Assignment operators => = , += , *= , /= , %= , \*\*=
3. Comparision operators => == , != , === , !== , > , < , <= , >=
4. Logical operators => && , || , !
5. Bitwise operators => & , | , ^ , ~, << , >> , >>>
6. Special operators => ?: , , , delete , in , instanceof , new , typeof , void , yield

### conditional statement
1. if statement
2. if-else statement 
3. if-else ladder
4. switch statement

### loops
1. while loop
2. do-while loop
3. for loop
4. for in loop
5. for of loop

### function
- block of code perfoming a specific task.
  1. **Regular function**
    ```js
    function sum (a,b)
    {
    return (a+b);
    }
    
  console.log(sum (2,5));
```
    2. **Arrow function**
```js
    const sum = (a,b)=> 
    {
    return (a+b);
     }
   console.log(sum(2,5));
```
-  **Anonymous function** : function without name
- **Nested function** : function under the function
- **Callback function** : function pass as an  a argument to another fucntion

## 1. OBJECT
---
- **Nearly in js everything is an object except primitive type. **
- **But primitive also have object version (obejct wrapper).**

### object
- entity having state and behaviour  (property & method).
- js is a object-based language, js is template based not class based , here we don't create class to get the object but , we direct create objects.

### create object
- 3 way
    1. By object literal
```js
let obj = {
           name:"ahsan", 
		   age:20 , 
		   print: function (){ console.log("name = "+name)}
		   
		   }
  ```

    2. wedu eeededed

[web devlopment](WEB_DEVLOPMENT)