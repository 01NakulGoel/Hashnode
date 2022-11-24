# JavaScript Conditional Statements (if/else), WEBDEV Course by Nakul Goel, Day 4

This is the Fourth lecture of the WEBDEV Course by Nakul Goel, today we will be learning what are conditional statements in JavaScript.

The detailed video lecture is below:-

%[https://youtu.be/a5PTgn1eebI]



# Before moving ahead

Important channels to Follow and subscribe to:-

Youtube:- youtube.com/channel/UCS_0LK2cA_y4Lfl6tUfdQgw

GitHub:- github.com/01NakulGoel

# Lets Start

Today we will be learning the conditional statement in JavaScript.


# What are conditional statements?

As the name suggests conditional statements are based on some condition that is if that statement is true then that execution will take place otherwise it will move to the next condition.

**so let's understand by an example:-**

## **Example 1**

There is a student **Alex** in the class who scored 50 marks in Maths, 70 marks in Science, and 20 marks in English.

To pass a subject he needs to score at least 40 marks in each subject.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669300617703/r7FJfKY8S.png align="left")

In this question there is a condition if Alex has scored 40+ marks in a subject then he will pass otherwise it will fail so normally the answer would look like this.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669300774642/Yg1JVA5fb.png align="left")

Alex got passed in Maths and Science but failed in English, this is how we think normally but how to write it in a code format lets us understand.

```
if(condition ){
  //what needs to be done
}else{
  // what needs to be done
}
```

so how we will write the above answer in code let's see:-

```
let student='Alex'
let englishMarks=20
let mathsMarks=50
let scienceMarks=70

let passMarks=40

if(englishMarks>passMarks){
  console.log(student + ' has passed')
}else{
  console.log(student + ' has failed')
}

```

for Maths and Science marks, you need to write the code yourself and check in replit.


## **Example 2**

John and Nisha went to the restaurant and ordered food, John ordered `Butter paneer masala and butter Naan`, and Nisha ordered `Pizza and a soft drink`.

The total bill for John was ₹1000   and the Total bill for Nisha was  ₹1500.

**Hotel Policy**

- if the bill is greater than 2000 customer will get a 50% discount.

- if the bill is greater than and equal to 1500, the customer will get a 30% discount.

- else no discount.


here there are three conditions hence we will use the if  //  else if //else condition, let's understand its syntax is

```
if(condition ){
  //what needs to be done
}
else if (condition){
 // what needs to be done
}
else{
  // what needs to be done
}
```


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669304262924/xIfBUoNjK.png align="left")
 

this is the pseudo code kindly watch the code and try to write on your own if you face any issues then only see the answer.

```
let nishaBill= 1500

let johnBill= 1000


if(nishaBill>2000){
console.log('Yipee I got 50 % discount ')
  nishaBill= nishaBill - nishaBill*(50/100)
} else if( nishaBill>=1500){
  console.log('Yipee I got 30 % discount ')
  nishaBill=nishaBill - nishaBill*(30/100)
}else{
console.log('Oh No!! I got 0 % discount ')
  nishaBill=nishaBill
}
console.log(nishaBill)

```

## **Example 3**

// john went to the market and his mother told 
// if rice is available buy rice,
// if pulses are available buy pulses
// if sugar is available buy sugar





```
let sugar='Not Available'
let rice= 'Available'
let pulses ='Available'

if(sugar=='Available'){
  console.log('buy sugar')
}

if(rice =='Available'){
  console.log('buy rice')
}

if(pulses =='Available'){
  console.log('buy pulses')
}
```















# Assignment


## Q1 

Declare a variable num1 and assign a value 5 if num1 is even print num1 is even else print num1 is odd.

## Q2 

John and Nisha went to the restaurant and ordered food, John ordered `Butter Chicken and butter Naan`, and Nisha ordered `Burger, French Fries, and a soft drink`.

The total bill for John was ₹1200   and the Total bill for Nisha was  ₹1800.

**Hotel Policy**

- if the bill is greater than 1700 customer will get a 50% discount.

- if the bill is greater than and equal to 1100, the customer will get a 30% discount.

- else no discount.

print final bill of Nisha and John in console. also, print what items they ordered.

**
if you guys are learning from this course do comment and subscribe to the youtube channel and be regular.**
