# JavaScript Functions || Lecture-12th

# What is JavaScript Function?

In JavaScript, a function is a block of code that performs a specific task and can be reused multiple times. Functions can take input through parameters and return a value to the caller. Functions are a fundamental part of the language and are used for various purposes, such as performing calculations, manipulating data, and interacting with other code.

**Defining a function**: To define a function in JavaScript, you can use the `function` keyword followed by the function name and a list of parameters enclosed in parentheses. The function body is contained within curly braces. For example:

```javascript
function greet(name) {
  console.log("Hello, " + name + "!");
}
```

**Calling a function**: To call a function in JavaScript, you simply need to use its name followed by a list of arguments in parentheses. For example:

```javascript
greet("John");
```

**Parameters and arguments**: When defining a function, you can specify a list of parameters that the function expects to receive when it is called. These parameters act as placeholders for the actual values (called "arguments") that will be passed to the function when it is called. For example:

```javascript
function add(x, y) {
  return x + y;
}
```

In this example, the `add` function has two parameters, `x` and `y`, and it returns the sum of these values. When the function is called, the values passed to it are called arguments. For example:

```javascript
console.log(add(3, 4));  // Output: 7
console.log(add(5, 10)); // Output: 15
```

**Returning a value**: A function can return a value to the caller using the `return` statement. For example:

```javascript
function add(x, y) {
  return x + y;
}
```

## **Exercise**

1. Write a function that accepts a single argument and returns the argument multiplied by 2.
    
2. Write a function that takes in an array and returns the sum of all the elements in the array.
    
3. Write a function that accepts a string and returns a copy of the string with all vowels removed.
    
4. Write a function that takes in an object and returns a new object with all the values of the original object multiplied by 2.
    
5. Write a function that returns the current date and time.
    
6. Write a function that accepts a number and returns a string of that number spelled out in English.
    
7. Write a function that takes in an array of numbers and returns the average of all the numbers.
    
8. Write a function that accepts a string and returns the string reversed.
    
9. Write a function that takes in an array of strings and returns an array of the strings sorted alphabetically. (Optional)
    
10. Write a function that takes in an array of objects and returns an array of the objects sorted by a given property. (Optional)