# JavaScript Strings || WEBDEV Course by Nakul Goel, Day 8

This is the eighth lecture of the WEBDEV Course by Nakul Goel, today we will be learning what are strings in JavaScript.

The detailed video lecture is below:-

%[] 

# Before moving ahead

Important channels to Follow and subscribe to:-

Youtube:- youtube.com/channel/UCS\_0LK2cA\_y4Lfl6tUfdQgw

GitHub:- github.com/01NakulGoel

# Let's start

## What are Strings?

1.  The string is a sequence of characters.
    
2.  It can include all alphabets, capital (A-Z) and small (a-z), numbers(0-9), and also all special characters like ^,%,@, etc
    
3.  Each character has an index, Starting from 0 to the length of the string
    

## Why do we need strings?

1.  90% of the data stored in the database is the sequence of characters, and the sequence of characters can only be stored in the string.
    

## Properties of string

### 1) Indexes:- Each character in the string has an index to distinguish one from another.

index starts from zero same as the array.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1670221430637/9TxdaPyak.png align="left")

### 2) Access- To access each character we can use box notation:-

```plaintext
let bestCourse='webdev';

console.log(bestCourse[0]);    //w
console.log(bestCourse[1]);    //e
console.log(bestCourse[2]);   //b
console.log(bestCourse[3]);   //d
console.log(bestCourse[4]);   //e
console.log(bestCourse[5]);   //v
```

### 3) Strings are immutable

It means you cannot delete or update a particular character from the string.

```plaintext
let bestCourse='Webdev';

bestCourse[0]='N';    // this will not work

console.log(bestCourse);   // webdev
```

### 4) Length of the string

```plaintext
let bestCourse='webdev'       

console.log(bestCourse.length)  //6
```

## Real World use of the Strings

### 1) check the password

```plaintext
let pass='asdvjbh'

if(pass.length>6){
console.log('strong password')}
else{
console.log('weak password')
}
```

### 2) print all characters in the string using the loop

```plaintext
let name='john'

for(let i=0;i<name.length;i++){
console.log(name[i])
}
```

### 3) update name from Jehn to John or update 1st index to o

as we all know we cannot change, delete or update characters in a string but we can use a new variable instead.

```plaintext
let name='Jehn';
let newName=''
for(let i=0;i<name.length;i++){
if(i==1){
newName=newName + 'o'
}else{
newName=newName + name[i]
}

}
console.log(newName)
```

## Assignment

### 1\. Reverse a string

Description You are given a string, stored in a variable with the name str You have to print the reverse string

Input

'John'

Output

'nhoJ'

Test case Code

```plaintext
//Subscribe Nakul Goel youtube:- this course is absolutely free

// Don't change the name of the function

function print(str) {
  // write your code here
  return 
}

//Don't Modify this code in any case

let arr = [];
let ans = []
let testCases = 50
let maxLengthOfString = 20

for (let i = 0; i < testCases; i++) {
  arr.push(generateStr(Math.floor(Math.random() * maxLengthOfString)))

}

for (let i = 0; i < arr.length; i++) {
  ans.push(arr[i].split('').reverse().join(''))
}
console.log(ans, arr)

let totalScoreOfTestCases = 0

for (let i = 0; i < arr.length; i++) {

  if (print(arr[i]) === ans[i]) {
    console.log(`Test case ${i + 1} Passed`)
    totalScoreOfTestCases += 10
  } else {
    console.log(`Test case ${i + 1} Failed`)
  }

}

console.log(`Total Score is ${totalScoreOfTestCases} / ${arr.length * 10}`)



function generateStr(length) {
  let char = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789';
  let result = '';
  const charactersLength = char.length;
  for (let i = 0; i < length; i++) {
    result += char[(Math.floor(Math.random() * charactersLength))];
  }
  return result;
}
```

### 2) Replace

**Description**

You are given a string, stored in a variable with the name str You have to change the character 'a' with 'e'. and change the character 'h' with 'f'.

**Input**

janhfg

**Output**

jenffg

```plaintext
//Subscribe Nakul Goel youtube:- this course is absolutely free

// Don't change the name of the function

function print(str) {
  // write your code here
  return 
}

//Don't Modify this code in any case

let arr = [];
let ans = []
let testCases = 50
let maxLengthOfString = 20

for (let i = 0; i < testCases; i++) {
  arr.push(generateStr(Math.floor(Math.random() * maxLengthOfString)))

}

for (let i = 0; i < arr.length; i++) {
  let ans1=''
  for(let j=0;j<arr[i].length;j++){
    arr[i][j]=='a' ? 
      ans1+='e':
      arr[i][j]=='h'?
      ans1+='f':
      ans1+=arr[i][j]
  }
  ans.push(ans1)
}


let totalScoreOfTestCases = 0

for (let i = 0; i < arr.length; i++) {

  if (print(arr[i]) === ans[i]) {
    console.log(`Test case ${i + 1} Passed`)
    totalScoreOfTestCases += 10
  } else {
    console.log(`Test case ${i + 1} Failed`)
  }

}

console.log(`Total Score is ${totalScoreOfTestCases} / ${arr.length * 10}`)



function generateStr(length) {
  let char = 'abcdefghijklmnopqrstuvwxyz';
  let result = '';
  const charactersLength = char.length;
  for (let i = 0; i < length; i++) {
    result += char[(Math.floor(Math.random() * charactersLength))];
  }
  return result;
}
```