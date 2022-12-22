# Mastering React in 8 weeks - Day 1

Hi, I am Nakul Goel and I will be your instructor in this 8 weeks react mastery course, where we will be covering everything about react.

This course is entirely free for all students who want to learn.

In this course, we will be going from beginner level to all the way to mastering react, so this is friendly for beginners but keep in mind this course has some prerequisites.

so please check all the prerequisites and then only start this course.

### Pre-Requisite

1.  Learn HTML and CSS.
    
2.  Learn JavaScript and be familiar with ES6 syntax.
    
3.  Basic understanding of DOM (document object model).
    
4.  Download and install a code editor.
    
    My preference will be to download and install VS Code.
    
    A quick guide to installing VS code:-
    
    1.  Go to the Visual Studio Code website ([**https://code.visualstudio.com/**](https://code.visualstudio.com/))
        
    2.  Click the "Download" button on the homepage
        
    3.  Select the version of VS Code that you want to download (e.g. Windows, macOS, Linux)
        
    4.  Follow the prompts to complete the installation
        
5.  Make an account on [https://codepen.io/](https://codepen.io/) and [https://codesandbox.io/](https://codesandbox.io/) because I will be sharing a lot of code on these platforms so be aware of these platforms.
    

Welcome Everyone, I am very happy you made it through, so congratulation.

The first 10 blogs of `react` can be tricky for most of you, so even if you are not completely understanding a part then also try to learn and complete at least 10 blogs after 10 blogs `react` will be super easy for all of you.

# What is a framework and why do we need it?

A framework is a set of tools, libraries, and conventions that are designed to help developers build applications more efficiently.

It provides a structure that developers can follow, which helps them to avoid reinventing the wheel and to focus on building the unique features of their applications.

Imagine that you are planning a vacation. A framework is like a pre-planned tour package that includes everything you need for your trip. It includes a set of hotels, flights, and activities that are carefully selected and organized for you.

Without a framework, you would have to plan every aspect of your trip yourself. You would need to research and book your own flights, hotels, and activities, which can be time-consuming and overwhelming.

On the other hand, with a framework, you can simply follow the pre-planned itinerary and enjoy your trip without having to worry about the details. The framework takes care of everything for you, so you can focus on having a good time.

**There are several benefits to using a framework:**

1.  Time savings: A framework can save developers time by providing pre-built libraries and tools that they can use in their applications. This means that they don't have to build everything from scratch, which can be time-consuming.
    
2.  Consistency: A framework can help to ensure that an application is built in a consistent manner, which can make it easier to maintain and scale.
    
3.  Best practices: A framework is often based on best practices that have been developed by experienced developers. This means that developers who use a framework can benefit from the collective knowledge and experience of the community.
    
4.  Support: A framework often has a strong community of developers who can provide support and assistance when needed.
    
5.  High Reusability and readability.
    

## Why React Why not Angular or Vue?

React, Angular, and Vue.js are all popular JavaScript libraries for building user interfaces. They each have their own strengths and are suitable for different types of projects.

Angular is one of the best frameworks developed by google but it's very complex to understand, it has a wide range of tools to develop a web application, and it includes everything to build from the user side interface to the backend. it is used to build enterprise-level complex applications and the prerequisite to learn it will include typescript as well.

1.  Full-featured framework
    
2.  Large community
    
3.  TypeScript support
    
4.  MVC architecture
    

now let's talk about Vue, it's a lightweight framework developed by Evan You and is used to develop small-size applications.

1.  Easy to learn
    
2.  Lightweight and fast
    
3.  Reactive components
    
4.  Strong ecosystem
    

why I am telling you about angular or Vue that's because you should always be familiar with the present technologies.

### **Now it's time why react.**

why are we learning `react`?

any idea?

This course is about `react` that's why we are learning `react` lol.

# What is React?

React is a popular JavaScript library for building user interfaces. It was developed by Facebook and is often used for building single-page applications and mobile applications.

some of the popular websites made using react framework are:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671665765909/7oQmMeSVE.png align="center")

Downloads of react, so you can automatically see how popular is react.

![Angular vs React vs Vue: Which is the Best Choice for 2021 - Merehead](https://merehead.com/blog/wp-content/uploads/3-181.png align="left")

if we need to develop an android or ios app then we also have `react native` which is similar to react.

![Pros and Cons of React Native and Native Apps](https://www.futuremind.com/m/articles/none/react_native_vs_native_apps_kJeZgPh.png align="left")

so there are a lot of things that we can do with `react`.

Remember react is built on top of js which means all the rules of JS are applied to react.

Here is an example that compares React and JavaScript using the metaphor of building a car:

*   React is like the body of the car. It provides the structure and appearance of the car, but it doesn't do anything on its own.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671667872551/ve_a6nwtq.png align="center")

*   JavaScript is like the engine of the car. It provides the power and functionality that makes the car move.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671668238459/d1V9dDtfQ.png align="center")
    

Let's revise some of the basic ES6 syntaxes so that we can become more powerful:-

1.  Arrow functions: Arrow functions are a shorter syntax for defining functions.
    
    *   Arrow functions are anonymous, which means that they don't have a name.
        
    *   Arrow functions do not have their own `this` value. Instead, they inherit the `this` value from the surrounding context.
        
    *   Arrow functions cannot be used as constructors (i.e., you cannot use `new` an arrow function)
        
    
    For example, you can use an arrow function like this:
    
    ```javascript
    const greet = name => `Hello, ${name}!`;
    const hello = (name,place)=>{
    `Hello, ${name} from ${place}`
    }
    ```
    
2.  Destructuring: Destructuring allows you to extract values from objects and arrays and assign them to variables. For example, you can use destructuring like this:
    

```javascript
const user = { name: 'John', age: 30 };
const { name, age } = user;
```

3.  Spread operator: The spread operator allows you to expand an array or object into separate elements or properties. For example, you can use the spread operator like this:
    
    ```javascript
    const numbers = [1, 2, 3];
    const newNumbers = [...numbers, 4, 5];
    ```
    
4.  Classes: ES6 introduces a new syntax for defining classes. For example, you can define a class like this:
    
    ```javascript
    class Animal {
      constructor(name) {
        this.name = name;
      }
      speak() {
        console.log(`${this.name} makes a sound.`);
      }
    }
    
    const dog = new Animal('Dog');
    dog.speak(); // Output: "Dog makes a sound."
    ```
    
5.  template strings: Template strings are a new way to create strings that support interpolation and multi-line strings. For example, you can use template strings like this:
    

```javascript
const name = 'John';
console.log(`Hello, ${name}!`); // Output: "Hello, John!"

const multiline = `This is a
multiline string.`;
console.log(multiline); // Output: "This is a\nmultiline string."
```

6.  Immutability and Mutability:-
    
    Immutability refers to the idea that once an object is created, its properties cannot be changed. In other words, an immutable object is an object that is read-only.
    
    in JavaScript, immutability can be achieved by using a combination of const declarations, object.freeze(), and the spread operator (...).
    
    ```javascript
    const user = { name: 'John', age: 30 };
    
    // Freeze the object to prevent further changes
    Object.freeze(user);
    
    // This will throw an error because the object is frozen
    try {
      user.name = 'Jane';
    } catch (e) {
      console.log(e);
    }
    
    // Create a new object with the updated name using the spread operator
    const updatedUser = { ...user, name: 'Jane' };
    
    console.log(user.name); // Output: "John"
    console.log(updatedUser.name); // Output: "Jane"
    ```
    
7.  Default parameters: ES6 allows you to specify default values for function parameters. For example, you can use default parameters like this:
    

```javascript
const greet = (name = 'John') => `Hello, ${name}!`;
console.log(greet()); // Output: "Hello, John!"
console.log(greet('Jane')); // Output: "Hello, Jane!"
```

8.  Modules: ES6 introduces a new syntax for organizing code into modules. For example, you can define a module like this:
    
    ```javascript
    // Define a module in a file called "math.js"
    export const add = (x, y) => x + y;
    export const subtract = (x, y) => x - y;
    
    // Import the module in another file
    import { add, subtract } from './math';
    console.log(add(1, 2)); // Output: 3
    console.log(subtract(5, 3)); // Output: 2
    ```
    
9.  Spread and rest operator: The spread operator allows you to expand an array or object into separate elements or properties, while the rest operator allows you to capture multiple arguments into an array. For example, you can use the spread and rest operator like this:
    
    ```javascript
    const numbers = [1, 2, 3];
    const newNumbers = [...numbers, 4, 5];
    console.log(newNumbers); // Output: [1, 2, 3, 4, 5]
    
    const sum = (...args) => args.reduce((acc, val) => acc + val, 0);
    console.log(sum(1, 2, 3)); // Output: 6
    ```
    
10.  Sets: Sets are a new data structure that allows you to store unique values. For example, you can use sets like this:
    

`javascript const set = new Set([1, 2, 3]); set.add(4); set.delete(2); console.log(set.has(2)); // Output: false console.log(set.size); // Output: 3`

11.  Higher Order Functions: It is a function that takes another function as an argument and returns a new function.
    
    ```javascript
    javascript const withLogging = (fn) => { return (...args) => { console.log('Calling function:', fn.name); return fn(...args); }; };
    
    const add = (a, b) => a + b;
    
    const addWithLogging = withLogging(add);
    
    console.log(addWithLogging(1, 2)); // Output: 3 (with log message)
    
    javascript //reduce HOF 
    const numbers = [1, 2, 3, 4];
    
    const sum = numbers.reduce((accumulator, currentValue) => accumulator + currentValue, 0);
    
    console.log(sum); // Output: 10
    
    //filter HOF 
    const numbers = [1, 2, 3, 4, 5];
    
    const evenNumbers = numbers.filter(number => number % 2 === 0);
    
    console.log(evenNumbers); // Output: [2, 4]
    
    // Sort HOF 
    const numbers = [4, 2, 5, 1, 3];
    
    const sortedNumbers = numbers.sort((a, b) => a - b);
    
    console.log(sortedNumbers); // Output: [1, 2, 3, 4, 5]
    
    // map 
    const numbers = [1, 2, 3, 4];
    
    const doubledNumbers = numbers.map(number => number * 2);
    
    console.log(doubledNumbers); // Output 
    ```
    
12.  Closures are functions that have access to the variables in the scope in which they were created, even if the function is called outside of that scope. Closures are a powerful feature in JavaScript and are often used to create functions with private variables or to create functions that have access to variables that are defined in outer scopes.
    
13.  Promises are a pattern in JavaScript for handling asynchronous operations. A promise represents the result of an asynchronous operation, which may be a value or an error. Promises allow you to chain asynchronous operations together and to write asynchronous code in a more synchronous-looking style.
    
14.  Async functions are a pattern in JavaScript for writing asynchronous code in a synchronous-looking style. An async function is a function that is marked with the `async` keyword and returns a promise. Async functions can be used with the `await` operator to wait for the promise to be resolved before continuing.
    
15.  The `GET`, `POST`, `PUT`, `PATCH`, and `DELETE` HTTP methods are used to request data from or make changes to a server. `GET` is used to retrieve data, `POST` is used to create data, `PUT` is used to update data, `PATCH` is used to partially update data, and `DELETE` is used to delete data. These methods are often used in combination with APIs (Application Programming Interfaces) to interact with servers and databases.
    
16.  JSON Server is a tool that allows you to create a fake REST API by creating a JSON file and running it as a server. It is often used for prototyping or for testing applications that need to interact with an API.
    
17.  An API (Application Programming Interface) is a set of rules that define how two or more systems can communicate with each other. An API often exposes a set of endpoints that can be used to perform different operations, such as retrieving data or making changes to data.
    
18.  CRUD operations are the basic operations that are performed on a database or an API. CRUD stands for Create, Read, Update, and Delete, and these operations correspond to the ability to create new data, retrieve existing data, update existing data, and delete existing data.
    

I want you guys to understand all the concepts in deep because of that I tried to help you revise all the concepts again.

Now we will learn `react`

**One important announcement**

<mark>A driver does not know how a car is made but one thing that he knows is how to drive a car.</mark>

<mark>so instead of focusing on how </mark> `react` <mark>is made do focus on how to use it effectively.</mark>

**Let's learn react**

React is a javascript frontend framework that is used to design beautiful user interfaces.

![Netflix-Originals Clone using React js for beginners | by Ritesh Singh |  Medium](https://miro.medium.com/max/1400/1*IRxZZOeetdgTl9s5ub9qkg.png align="left")

it increases the reusability of the same element again.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671706950683/7GreXU5Er.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671707398281/eW1VZyaK7.png align="center")

The above example is of the Twitter comment section where you can actually see a lot of common things, actually, everything is the same just the data changing, so all the comments in Twitter are not hardcoded all the code is dynamic.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671707859996/SjI9zxrPf.png align="center")

we can arrange a simple component of a form like this in the tree format.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671706830609/Nj0IBFBw_.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671708257594/Pv37OEns4.png align="center")

if i am searching or reloading this page then only the component inside home will change rest every component will remain still, this actually makes your application much faster.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671708499918/xjoFAINtl.png align="center")

the green box actually changed and the purple remained the same. so instead of loading the whole page, only the required components were reloaded.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671708846838/815_iV6nd.png align="center")

when there is a change instead of changing the whole virtual tree `react` compares the previous virtual tree with the current tree and calculate the minimum number of dom changes required. This step of updating the dom with a minimum number of updates is known as "reconciliation".

that's it for the introduction, we will meet in the next blog.

Keep Learning and do practice ES6.