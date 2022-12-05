# JavaScript Arrays || WEBDEV Course by Nakul Goel, Day 7

This is the seventh lecture of the WEBDEV Course by Nakul Goel, today we will be learning what are arrays in JavaScript.

The detailed video lecture is below:-

%[https://www.youtube.com/watch?v=_V4Pe0MnHYo&t=1103s]

# Before moving ahead

Important channels to Follow and subscribe to:-

Youtube:- youtube.com/channel/UCS_0LK2cA_y4Lfl6tUfdQgw

GitHub:- github.com/01NakulGoel


# Let's start


## What are arrays?

Before understanding what is an array let's analyze one thing about JavaScript from the previous topics.

If I want to store one type of data such as an Employee Name then I can use a variable but if I want to store the name of 50 employees will I make 50 different variables?

Is it feasible?

**No**

## so what's the solution?

### Array.

The array is a continuous/ordered collection of data that helps us to store multiple values. 

for example:- 

- list of comments on Facebook.

- songs in a playlist.

Syntax of array

```
let arr = [];
```

if you want to assign like planets in the solar system then you can assign them as follows:-

```
let planets = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune']
```

# **Properties of array**

1) **Indexes**:- Each element in the array has an index to distinguish one from another.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669656512730/uREGluOhC.png align="left")

2) To access the value we can use this syntax:-

```
let planets = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune']
planets[0]    // Mercury
planets[1]     // Venus
planets[2]     // Earth

and so on

```
3) Length of the array which means how many elements are present in the array.

```
let planets = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune'];

planets.length  //8
```

4) To add an element in an array.

To add an element in an array you can use push.

```
let planets = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune'];

planets.push('Pluto')

console.log(planets)

// ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune', 'Pluto']
```

5) Modify elements in an array

```
let planets = ['Mercury', 'Venus', 'Earth', 'Mars', 'Jupiter', 'Saturn', 'Uranus', 'Neptune'];
planets[0]='Venus'
planets[1]='Mercury'

console.log(planets)  // do check in replit
```

To do questions

- **print the last three planets.**

- **find the sum of the array elements.**

- **find the sum of even elements of an array.**










# Assignment

Q1

**Description**

Print all the data in the array line wise

**Sample Input**

[1,4,5,2,6,4,1,2,3,5]

**Sample Output**

1 4 5 2 6 4 1 2 3 5

## **TestCase Code**

```
//Subscribe Nakul Goel Youtube:- This course is absolutely free

// Don't change the name of the function

function print(arr) {
  // write your code here
}

//Don't Modify this code in any case
let arr = [
  [1, 2, 3, 4, 5, 6],
  [8, 5, 2, 41, 4, 52, 3, 6, 5, 4],
  [4, 7, 1, 2, 6, 5, 2, 3, 4],
  [7, 4, 5, 2, 1, 2, 3, 6],
  [4, 1, 2, 5, 2],
];
let ans = [
  "1 2 3 4 5 6 ",
  "8 5 2 41 4 52 3 6 5 4 ",
  "4 7 1 2 6 5 2 3 4 ",
  "7 4 5 2 1 2 3 6 ",
  "4 1 2 5 2 ",
];
for (let i = 0; i < arr.length; i++) {
  let final =
    print(arr[i]) == ans[i]
      ? `Test case ${i + 1} Passed`
      : `Test case ${i + 1} Failed`;
  console.log(final);
}


```

Q2 

**Description**

`Print the odd elements of the array

**Sample Input**

[1,4,5,2,6,4,1,2,3,5]

**Sample Output**

'1 5 6 1 3 '

## **TestCase Code**

```
//Subscribe Nakul Goel youtube:- this course is absolutely free

// Don't change the name of the function

function print(arr) {
  // write your code here
}

//Don't Modify this code in any case
let arr = [
  [1, 2, 3, 4, 5, 6],
  [8, 5, 2, 41, 4, 52, 3, 6, 5, 4],
  [4, 7, 1, 2, 6, 5, 2, 3, 4],
  [7, 4, 5, 2, 1, 2, 3, 6],
  [4, 1, 2, 5, 2],
];
let ans = [
  "1 3 5 ",
  "5 41 3 5 ",
  "7 1 5 3 ",
  "7 5 1 3 ",
  "1 5 ",
];
for (let i = 0; i < arr.length; i++) {
  let final =
    print(arr[i]) == ans[i]
      ? `Test case ${i + 1} Passed`
      : `Test case ${i + 1} Failed`;
  console.log(final);
}

```

