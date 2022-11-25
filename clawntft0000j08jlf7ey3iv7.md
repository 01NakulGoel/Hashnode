# JavaScript  Logical Operator and Ternary Operator, WEBDEV Course by Nakul Goel, Day 5

This is the Fifth lecture of the WEBDEV Course by Nakul Goel, today we will be learning what are Logical operators and Ternary operators in JavaScript.

The detailed video lecture is below:-

%[https://youtu.be/SVza5Znih8g]


# Before moving ahead

Important channels to Follow and subscribe to:-

Youtube:- youtube.com/channel/UCS_0LK2cA_y4Lfl6tUfdQgw

GitHub:- github.com/01NakulGoel

# Lets Start

Before moving ahead there is one more very small concept of truth and falsey value, lets understand it.

# TRUTHY and FALSEY VALUE

## Falsey value

These are the values that are considered falsey in Javascript.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669384733646/mscHFzT7o.png align="left")

1) ''

2)0

3) false

4) null

5) undefined

6) NaN

## Truthy value

** The value other than falsey value are the truthy value.**

# Logical Operator
 
as the name suggests the operators which provide logic to perform an operation or not are the logical operators.


# There are basically three logical operators:-

##  1. AND Operator (&&)

In simple words, I can say this is a very sad operator, it always sees the negative in a person. 

what does that mean, it means whenever it sees any falsey value it tends to return it, and if don't find any falsey value, it will return the last truthy value.

```
let a = 0;
let b = 'Nakul';
let c = 'John';

let z = a && b && c;

console.log(z);
```

```
let a = 1;
let b = 'Nakul';
let c = 'John';

let z = a && b && c;

console.log(z);
```

```
let a = 0;
let b = null;
let c = 'John';

let z = a && b && c;

console.log(z);
```

```
let a = 'Nakul';
let b = '';
let c = 'John';

let z = a && b && c;

console.log(z);
```

```
let bankBalance=5000

let minimumBalance=0

let z= bankBalance && minimumBalance

console.log(z)
```

##  2. OR Operator (||)

In simple words, I can say this is a very happy operator, it always sees the positivity in a person. 

what does that mean, it means whenever it sees any truthy value it tends to return it, and if don't find any truthy value, it will return the last falsey value.

```
let a = true;
let b = 0;
let c = null;

let z = a || b || c;

console.log(z);
```

```
let a = false;
let b =true;
let c = null;

let z = a || b || c;

console.log(z);
```

```
let a = true;
let b = 0;
let c = 1;

let z = a || b || c;

console.log(z);
```

```
let a = '';
let b = 5;
let c = null;

let z = a || b || c;

console.log(z);
```

##  3. NOT Operator (!)

In simple word this will change a truth value to falsey and falsey to truthy.





# Ternary Operator

This is a shorthand for the if else statement. 

```
(condition)
 ? this will execute if the condition is true
: this will execute if the condition is false

```

if the condition is `if` `else if` `else` then shorthand will be:-

```
  (condition)
? this will execute if the condition is true
: (condition)
? this will execute if the condition is true
: this will execute if the condition is false


```

```
let a=20
let b=40

// if else if else

let c =  (a>b)
  ? 'Passed'
  : (a>=20)
     ? 'Not Expelled'
     : 'Expelled'

console.log(c)
```
# Assignment

**Do this assignment using the ternary operator.**

## Q1 

Declare a variable num1 and assign a value 5 if num1 is even print num1 is even else print num1 is odd.

## Q2 

John and Nisha went to the restaurant and ordered food, John ordered `Butter Chicken and butter Naan`, and Nisha ordered `Burger, French Fries, and a soft drink`.

The total bill for John was ₹1200   and the Total bill for Nisha was  ₹1800.

**Hotel Policy**

- if the bill is greater than 1700 customer will get a 50% discount.

- if the bill is greater than and equal to 1100, the customer will get a 30% discount.

- else no discount.

Print the final bill of Nisha and John in console . also, print what items they ordered.

**
if you guys are learning from this course do comment and subscribe to the youtube channel and be regular.**





