# Introduction to JavaScript and JS Variables, WEBDEV Course by Nakul Goel Day-1,

This is the first lecture of the WEBDEV Course by Nakul Goel,  instead of starting with HTML and CSS we will be starting with JavaScript.

The detailed video lecture is below:-

%[https://www.youtube.com/watch?v=Ue47DP_ytMo]

Before moving ahead 

## Important channels to Follow and subscribe to:-

- Youtube:- https://www.youtube.com/channel/UCS_0LK2cA_y4Lfl6tUfdQgw

- GitHub:- https://github.com/01NakulGoel

### There are the following reasons why we are starting with JavaScript:-
1. JavaScript is a programming language that is a little difficult to learn. it will take time.
2. Your logic-building ability will improve.
3. all the frontend and backend frameworks use JavaScript.


So let's get started:-

## What is JavaScript?
- JavaScript is an object-oriented programming language that is used in website development. 
- It is the most loved language on the web.
- 92% of websites use JavaScript.
 
(As a beginner this definition is more than enough, we will go to the third month)

## History of JavaScript?


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669006674622/ApuQqFP7U.png align="left")

- **1995: The Birth of JavaScript - by Brendan Eich **
  
     Mr. Brendan Eich who is the father of the most loved language in the world has written that language in 
just 10 days. the name of JavaScript was LiveScript at that time.

- **1996: JavaScript vs. Java**
  
   1. ** Are JavaScript and java the same or even related?**

   ** No **, both languages are very different from each other, javascript got its name from Java because 
Java was the most popular language at that time.



- **1997: ECMAScript Is Born As The JavaScript Standard**

The JavaScript community started growing and as it was growing rapidly it needed a managing body to manage and maintain the language standards that's how ECMA was born which is the managing authority of JavaScript. After this, JavaScript is also known as ECMAScript.


- **2009: ES5**

ES5 update was launched, which was a major update through which we got getter-setter methods, some of the new array functions, and much more. we will learn about this also when it will be required.


- **2015: Anticipated Update of the year ~ ES6/ES2015**

ES6 is the latest update of JavaScript from which we got new syntax and much other support. we will have a special lecture on ES6 once you get familiar with JavaScript basics.


## What are JavaScript variables?

we can understand a variable by it is an empty container where you can store something in it. 

for example sugar in a sugar box, then the sugar box is the variable and sugar is the value.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669007688262/olUh5Hr1x.png align="left")



### Before we move forward let's set up a coding environment for all of us to code together:-

1. Go to https://replit.com/~ and sign up using your google account.

2. click on create a button on the left-hand side at the corner.

 ![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669007960272/Yua9yzsTl.png align="left")

3. Search and click on node.js

 ![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669008007440/AW4m3Lif4.png align="left")

4. Give your file a title and click on create repl.

 ![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669008168457/Bc_FkALjh.png align="left")

5. It will look like this.

 ![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669008246909/kzOImdDRU.png align="left")

6. Now you can write code in it.


 ![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669008350079/8H8oo3me_.png align="left")



### Now let's understand variables in JavaScript:-


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669010264952/LtrM33DII.png align="left")

in the above example, we have declared a variable in JavaScript and for declaring a variable you can use three keywords:-

1. var
2. let
3. const - this value will not be changed and it's unique, we will deep dive into it at a later stage.




```
var courseName = 'WEBDEV'
const duration = '8 months'
let aim = 'Full Stack Developer'

```

### some important things to take care of while assigning the name to the string:-

- Variable names cannot contain spaces.
- Variable names must begin with a letter, an underscore (_), or a dollar sign ($).
- Variable names can only contain letters, numbers, underscores, or dollar signs.
- Variable names are case-sensitive.
- Certain words may not be used as variable names, because they have other meanings within JavaScript.

### To declare a variable you should use either snake_case or camelCase:-

1).camelCase:- 
The first letter is always small and instead of space, we will make the first letter of the second-word capital.

for example:-

**Nakul Goel** can be written as **nakulGoel**.
**Sugar Box**  can be written as **sugarBox**

2) snake_case  

It will contain all lowercase words and will be separated by an underscore(_).

**Nakul Goel** can be written as **nakul_goel**
**Sugar Box** can be written as **sugar_box**


### To get an output of the variable you can use:-
```
console.log(myNumber)

//that means the name of the variable
```

> 
> Suppose a name= Rosy Sharma
> it is constant throughout her life.
> 

like pi=3.14 the value is the same in every mathematical calculation.

we will learn types of value that we can assign to a variable that is primitive value types:-

### 1) Number

 we can assign numbers to the value of the variable.

### 2) String - a way to store alphabets

Strings are basically a collection of characters (numbers, symbols, alphabet)
anything inside the quote is the string. it cannot be changed.

three ways to store alphabets(strings)

1) '   ' single quote

2) "  " double quote

3) `` backticks



### 3) Boolean 

you can also store true and false as a value in a string.

```
var gameOver = true
```



```
to check data type = `typeOf( 'aman')`
output= string
`typeOf( 123)`
output number
```

Assignment:-

Q1 Declare a variable with your name, age, and location and assign the appropriate value and print it in the console.

Q2 Declare a variable name myNumber and declare a value 50 to it and print it and then change the value to 60, then change it to 70 and print the last value.











