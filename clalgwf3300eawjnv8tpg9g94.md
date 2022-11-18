# Primitive Value Types in JavaScript - Advance

Hello everyone today we will be learning about the primitive data types in JavaScript.
what are primitive value types?
it basically means what are all the values we can assign to the variables.

# There are basically 7 primitive data types:-

- ### string

- ### number

- ### boolean

- ### undefined

- ### null

- ### bigInt

- ### symbol

## 1.** string **
the string is a very common value type which means anything that is surrounded by a similar quote.

there are three ways to declare strings

```
let str='Hello' //single quote

let str2="World"  //Double quote

let str3=`Hello World`   //backticks that are present above your tab key

```

Double and single quotes are self-understandable but the backticks in JavaScript are known as **Template Literals**.

Backticks are “extended functionality” quotes. They allow us to embed variables and expressions into a string by wrapping them in ${…}  for example:
```

let str='Hello' //single quote

let str2="World"  //Double quote

let str3=`${str} ${str2}`      //output will be same that is `Hello World`


```

## 2. **Number**
the second value type is the number and it also has a limitation that is
 -2<sup>53</sup>-1 <=Number<=2<sup>53</sup>-1 
and second thing is number type and floating type in JS is same.



## 3. **boolean**

it has two values `true` and `false`.
  -falsy values

     -''
     - 0
    - false
    - undefined
    - null
    - NaN
  -rest all values are truthy

```
let a= true
let b=false
```


## 4. **undefined**
undefined is something that is defined by the JS for example if there is something with no values then JS will automatically assign it a value that is undefined.

```
let a;   //if we print both of them value will be undefined
let b;
```

## 5. **null**
null is the value that is assigned by the user, it represents emptiness, nothingness or the value is unknown.
```type of null will always return object```


## 6.**BigInt**
the limitation of the number can be taken care of by the bigint which means it is used for declaring the larger number that are greater than 2^53-1 and less than -2^53-1.

```
console.log(9999999999999999);    // → 10000000000000000

```

## 7. Symbol
this is the new value type that is introduced in JavaScript which helps in making the two values with the same syntax not equal.
means it guarantees a unique value every time.

```
let s1=Symbol('hi')   // it has a unique value that is a unique hash code
let s2=Symbol('hi')   // // it has a unique value that is a unique hash code


s1==s2   //false both will have a different unique value that will look the same but is actually different.
```
