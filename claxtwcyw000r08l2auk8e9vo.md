# JavaScript Loops (for Loop and while Loop) increment operator, WEBDEV Course by Nakul Goel, Day 6

This is the Sixth lecture of the WEBDEV Course by Nakul Goel, today we will be learning:-

- **Increment and decrement operator:-**

  1. **post-increment and pre-increment.**

  2. **post-decrement and pre-decrement.**

- **What the hell is a loop?**

- **What is For Loop?**

- **What is while Loop?**



The detailed video lecture is below:-

%[]


# Before moving ahead

Important channels to Follow and subscribe to:-

Youtube:- youtube.com/channel/UCS_0LK2cA_y4Lfl6tUfdQgw

GitHub:- github.com/01NakulGoel

# Lets Start

let's start by understanding very small things what are increment and decrement means?

## Increment increasing a value by (+1) 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669449886012/OXkg1J-Ft.png align="left")

### Post-increment (adding ++ after the operand)
  
- In this case, the value will be returned before the increment.

- Try consoling the below code


```
let a=0;
console.log(a++)  //0
console.log(a)       // 1
```


### Pre-increment (adding ++ before the operand)

- In this case, the value will be returned after the increment.

- Try consoling the below code

```
let a=0;
console.log(++a)   // 1
console.log(a)       // 1
```

## Decrement decreasing a value by (-1) 


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669450946896/pyAP0l3Gv.png align="left")

### Post-Decrement (adding -- after the operand)
  
- In this case, the value will be returned before the decrement.

- Try consoling the below code


```
let a=0;
console.log(a--)  //0
console.log(a)       // -1
```


### Pre-Decrement (adding -- before the operand)

- In this case, the value will be returned after the decrement.

- Try consoling the below code

```
let a=0;
console.log(--a)   // -1
console.log(a)       // -1
```

# What are loops?

loops are basically the magic of programming language which makes the code shorter and this is the most important part of programming.

It is basically an instruction to repeat the same instruction or execute the same set of code again and again.

for example:
if we want to say 'Hello' ten times, one way is to write the command 10 times but if we want to print 'Hello' 1000 times or 10000 times or more that's where loops are helpful.

Let's study two types of loops today:-

### 1. While Loop

**Syntax**

```
variable initialisation
while ( condition )  {

code


variable incrementation
}
```

for example:-

1. let's print 'hello' ten times using loops.

```
let i = 0;

while( i < 10 ){

console.log( 'hello' )

i++}


```

let's **dry-run** the code:-

the dry run is basically a technique to see how the code is working in loop, lets understand it.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669457426190/BDnT6k_Z8.png align="left")


### 2. For Loop

**Syntax**

```
for(variable initialisation; condition ;  increment/decrement){
code
}
```

1. let's print 'hello' ten times using loops again.


```
for(  let i = 0  ;  i < 10  ;  i++  ){

console.log( 'Hello' )

}


```

# Assignment:-

will be uploaded at 10 PM
 


