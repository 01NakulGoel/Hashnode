# Mastering React in 8 weeks - Day 2

Hello, Hashnoders or learners,

I am back with the second blog about mastering react in 8 weeks and I hope you guys are learning a lot from my blogs.

### Prerequisites

1. kindly install a code editor on your PC, I will recommend installing VS code i.e. visual studio code and I want you to practice on VScode.
    
    How to install VS code
    
    1. Go to the Visual Studio Code website ([**https://code.visualstudio.com/**](https://code.visualstudio.com/)) and click the "Download" button to download the latest version of VS Code.
        
    2. Once the download is complete, double-click the downloaded installer file to start the installation process.
        
    3. Follow the prompts to install VS Code. The installation process is straightforward and should only take a few minutes.
        
    4. Once the installation is complete, you can launch VS Code by clicking the VS Code icon on your desktop or in the start menu.
        
    5. If you want to install additional extensions or add-ons for VS Code, you can open the VS Code Extension Marketplace by clicking the "Extensions" icon in the left-side menu, or by pressing Ctrl+Shift+X (Windows) or Cmd+Shift+X (Mac). From here, you can browse and install extensions to customize and extend the functionality of VS Code.
        
    6. some important VS extensions that I will recommend are:-
        
        * **Live Server** - This extension allows you to quickly spin up a development server to test your web pages and applications. Simply right-click on an HTML file and select "Open with Live Server" to launch the server.
            
        * **Prettier** - This extension is a code formatter that helps you to automatically format your code according to a set of style rules. It can save you a lot of time and effort by automatically formatting your code as you type.
            
        * **Bracket Pair Colorizer** - This extension adds color coding to matching brackets, making it easier to see which brackets belong to which blocks of code.
            
2. Nodejs
    
    **To install Node.js, you will need to follow these steps:**
    
    1. Go to the Node.js website ([**https://nodejs.org/**](https://nodejs.org/)) and click the "Download" button to download the latest version of Node.js.
        
    2. Once the download is complete, double-click the downloaded installer file to start the installation process.
        
    3. Follow the prompts to install Node.js. The installation process is straightforward and should only take a few minutes.
        
    4. Once the installation is complete, you can verify that Node.js is installed by opening a terminal or command prompt and typing the following command:
        
    
    ```javascript
    node -v
    ```
    
    This will print the version number of Node.js that is installed on your machine.
    
    1. To install npm (the Node.js package manager), simply run the following command in your terminal or command prompt:
        
    
    ```javascript
    npm install -g npm
    ```
    
    This will install npm globally on your machine, which means that you will be able to use it from any directory.
    

# Lets Install React

1. Now make a folder and open in your vs code and go to the terminal.
    
2. To install a React app, you will need to have Node.js and npm (the Node.js package manager) installed on your machine.
    
3. Once you have Node.js and npm installed, you can use the following steps to install a new React app:
    
    * Open a terminal and navigate to the directory where you want to create your new React app.
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671799341832/b8531a84-b89f-4e8d-8284-009fe80083cb.png align="center")
        
    * Run the following command to create a new React app:
        
    
    ```javascript
    npx create-react-app my-app
    ```
    
    This will create a new directory called "my-app" with a basic React app setup.
    
    you can name it anything.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671799782196/625b22a9-f990-4872-9f0b-5b518c3bf158.png align="center")
    
    It can take time to install react according to your <mark>internet speed</mark> and your PC specs.
    
    * Navigate into the new project directory by running the following command:
        
    
    ```javascript
    cd my-app
    ```
    
    * Start the development server by running the following command:
        
    
    ```javascript
    npm start
    ```
    
    This will open a new browser window with your React app running.
    

<mark>I will recommend following my approach and do not install it globally reason being when you install it globally it is difficult to update the resource globally and moreover it can lead to version conflicts and other issues.</mark>

if you see the below window your react app has been installed perfectly,

## Congratulations

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671800011394/7b64a9da-ffd5-4b41-a31a-37a1cc72b1be.png align="center")

## Folder Structure in React

Below is the typical image of the folder structure that you will see after installing react app.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671800204077/f2fba89c-aa31-415e-90f4-685b80b1e646.png align="center")

1. **node\_modules**:- it contains all the dependencies of your project and typically it's a heavy folder so you should always mention the node\_modules folder in your .gitignore file so that it can be ignored.
    
2. **public folder**:- this folder contains the HTML file that is used to render the app, sometimes it can contain favicon, images, logo, and so on. the most important file for us is index.html therefore do not modify this file.
    
    index.html file contains the div which is the root element.
    
    do not change anything in the body tag.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671812542478/ff3c34c6-c9a0-4729-b45c-fca3213e69bc.png align="center")
    
    you will see a div with root as an id, basically root component will render all the UI of our application. we will understand how at a later stage in the article.
    
3. **src folder**:- It means source code therefore it will contain all the js files.
    
    This is the folder where you will spend most of your time.
    
4. **.gitignore**:- it's basically a text file where you can write the location of the file that should be ignored such as node\_modules.
    
    ```javascript
    # See https://help.github.com/articles/ignoring-files/ for more about ignoring files.
    
    # dependencies
    /node_modules
    /.pnp
    .pnp.js
    
    # testing
    /coverage
    
    # production
    /build
    
    # misc
    .DS_Store
    .env.local
    .env.development.local
    .env.test.local
    .env.production.local
    
    npm-debug.log*
    yarn-debug.log*
    yarn-error.log*
    ```
    
5. **package.json**:- this is a file that contains all the dependencies of node.js and scripts. it is always present in the root directory of the file.
    
6. **README.md**:- it is a file that contains information about the project.
    

### Wondering how this page is rendered? let's understand

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671800011394/7b64a9da-ffd5-4b41-a31a-37a1cc72b1be.png align="center")

1. firstly, go to index.html file and there you will see a div with id root.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671814427448/9d80a819-6045-4a63-bcbd-2f4391e75dbd.png align="center")
    
2. now let's head to the index.js file in the src folder, it will look like this
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671814492548/72ef41f2-7296-492a-ad0c-19c76f5cb530.png align="center")
    
3. see the root variable and you will find some similarities:-
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671814569458/ca715b10-81dc-4480-84ea-d149483a190e.png align="center")
    
    ```javascript
    const root=ReactDOM.createRoot(document.getElementById('root'))
    ```
    
4. you need to create a root element and then we will render it like this.
    
    ```javascript
    root.render(
      <React.StrictMode>
        <App />
      </React.StrictMode>
    );
    ```
    
5. in root.render you can see two things, first is `React.StrictMode` , and the second os `<App />`
    
    * `React.StrictMode` is a component that is used to help identify potential problems in a React app. It is designed to trigger warnings in development mode to help developers find and fix problems that may cause bugs or performance issues.
        
        i will recommend removing it if you are starting up with React as it will show many possible errors, we will turn it on when we get a little familiar with the tools.
        
    * what is `<App />` ?
        
        This is how we run a function in React, whenever you are writing a function make sure you are naming it in <mark>PascalCase</mark>, not in camelCase.
        
    * but we have not declared the app function in our index.js file as we are importing it from another file.
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671816176968/987435b5-ee72-48c7-a23c-6e97adf9afbd.png align="center")
        
    * let's go to the App.js file in the src folder.
        
        ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671816277718/3d4d4419-403e-4c78-9f55-e11f2d1b2b10.png align="center")
        
    * finally, we came to the function App which is responsible for rendering all the elements in our dom.
        
        ### **but how come we are writing HTML in a .js file?**
        
        ### **is it possible?**
        
        This is where we will learn our new concept which is **JSX(JavaScript XML)**.
        

## What is JSX?

JSX (JavaScript XML) is a syntax extension for JS which allows us to write HTML-like code in JS.

It looks like HTML but it's not proper HTML.

We can write such code with the help of a transpiler that is babel.

let's understand the hard part first and then we will move to the easy part:-

In JS if we want to create an element we use the following code

```javascript
/*
if you want to create an element like this:-
*/
<div class='container' style= 'color: red;' >
Hello, world!
</div>

//Normal Vanilla JS

let div =document.createElement('div');
div.classlist.add('container');
div.style.color='red'
div.textContent= 'Hello World!'


// React
//for reference
React.createElement(tagName, attributes in form of object, textContent or child element)

//code
let div = const element = React.createElement(
  'div',
  { className: 'container', style: { color: 'red' } },
  'Hello, world!'
);
```

This is the basic difference between creating an element in react vs creating an element with js but creating an element in react also has a drawback i.e.

<mark>what if we want to create an element like below ?</mark>

```xml
<div>  
<h1>Hello World</h1>
<p>This is a paragraph</p>
</div>
```

we can create the following code in React like this

```javascript
const element = React.createElement(
  'div',
  { className: 'container' },
  React.createElement('h1', null, 'Hello, world!'),
  React.createElement('p', null, 'This is a paragraph')
);

// or we can use an array for all the child element:-
const element = React.createElement(
  'div',
  { className: 'container' },
 [ React.createElement('h1', null, 'Hello, world!'),
  React.createElement('p', null, 'This is a paragraph')]
);
```

**<mark>Activity time</mark>**

1. go to the index.js folder
    
2. create the following element, using React.createElement(), and store it in the variable myCode.
    
    ```xml
    <div>  
    <h1 style='color:red;' >your name</h1>
    <p>I am learning React </p>
    </div>
    ```
    
3. after you do this in root.Render instead of &lt;App /&gt; write this:-
    
    ```javascript
    root.render(
      
        {myCode}
      
    );
    ```
    
4. meanwhile, remove the strict mode also and then save it, and refresh the localhost page. you will see something like this:-
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671818851953/b380d698-0251-4944-b740-b3a51911d16b.png align="center")
    
5. one more thing we understood is that if we want to run JS in root.render then we will write it under a curly bracket like this {}.
    
    we will look more into it in the blog ahead.
    

now let's understand how we can write the same code with JSX.

```xml
root.render(
<div>  
<h1 style={{color:'red'}} >Nakul Goel</h1>
<p>I am learning React </p>
</div>
);
```

does it look super easy as compared to our above code?

let's break it.

```xml
//remeber for function we have to use PascalCase

const MyCode = ()=>{    
  return(
  <div>  
  <h1 style={{color:'red'}} >Nakul Goel</h1>
  <p>I am learning React </p>
  </div>
  )
  }

root.render(
<MyCode />
);

/* to call a function in React you will always call it like <name /> instead of name() */
```

now let's understand some rules of JSX:-

* JSX elements must be properly nested. For example, you can't have a `div` element inside an `h1` element.
    
* JSX elements must be closed. For example, you must include the closing tag for a `div` element, like this: `</div>`.
    
    as we know image tag does not have a closing tag but in JSX we need to close it like this:-
    
    ```xml
     <img src="" alt=""/>
    ```
    
* JSX elements can contain only one root element. For example, this is not allowed: `<h1>Hello, world!</h1><p>This is a paragraph</p>`. Instead, you must wrap the elements in a container element, like this: `<div><h1>Hello, world!</h1><p>This is a paragraph</p></div>`.
    
* You must use camelCase for attribute names in JSX. For example, you should use `className` instead of `class`, and `onClick` instead of `onclick`.
    
* You must use curly braces to enclose JavaScript expressions in JSX. For example: `{2 + 2}`.
    
* You must use quotes around attribute values in JSX unless the value is a JavaScript expression. For example: `<h1 className="title">Hello, world!</h1>`.
    

I thought of ending the blog here but let's understand one more thing what is the use of Babel which is a transpiler for JSX?

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671826468743/1b826636-a9ca-4272-bea3-40be49a9afcf.png align="center")

in the above post, you can see the JSX is converted from JSX to React.createElement().

try it out yourself

1. go to [https://babeljs.io/](https://babeljs.io/)
    
2. Click on try it out.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671826668268/8dbc8611-0740-4982-8f3b-3f011e280af9.png align="center")
    
3. then write your JSX and see hows it's converted.
    

now lets start the quiz.

## Quiz

We will learn some parts in the next blog but still, it's worth searching for new things.

1. What is JSX?
    
    a) A syntax extension for JavaScript that allows you to write HTML-like code in your JavaScript files.
    
    b) A transpiler that converts JSX into regular JavaScript code.
    
    c) A library for building web and mobile applications.
    
    d) A virtual DOM (Document Object Model) element.
    
2. How do you create a JSX element that represents an `h1` element with the text "Hello, world!"?
    
    a) `const element = <h1>Hello, world!</h1>;`
    
    b) `const element = React.createElement('h1', null, 'Hello, world!');`
    
    c) `const element = { type: 'h1', content: 'Hello, world!' };`
    
    d) `const element = '<h1>Hello, world!</h1>';`
    
3. How do you pass an attribute to a JSX element?
    
    a) By using camelCase and enclosing the attribute value in quotes.
    
    b) By using hyphen-separated names and enclosing the attribute value in quotes.
    
    c) By using camelCase and enclosing the attribute value in curly braces.
    
    d) By using hyphen-separated names and enclosing the attribute value in curly braces.
    
4. How do you nest JSX elements?
    
    a) By enclosing them in quotes.
    
    b) By enclosing them in curly braces.
    
    c) By enclosing them in parentheses.
    
    d) By enclosing them in brackets.
    
5. How do you use a JavaScript expression in a JSX element?
    
    a) By enclosing it in quotes.
    
    b) By enclosing it in curly braces.
    
    c) By enclosing it in parentheses.
    
    d) By enclosing it in brackets.
    
6. How do you use conditional rendering in JSX?
    
    a) By using `if` statements.
    
    b) By using `switch` statements.
    
    c) By using ternary operators.
    
    d) By using `for` loops.
    
7. How do you use loops in JSX?
    
    a) By using `while` loops.
    
    b) By using `for` loops.
    
    c) By using `map` functions.
    
    d) By using `reduce` functions.
    
8. What is the purpose of the `key` the attribute in a JSX element?
    
    a) It specifies a unique identifier for the element.
    
    b) It specifies the element's class name.
    
    c) It specifies the element's style.
    
    d) It specifies the element's content.
    
9. What is the purpose of the `ReactDOM.render` function?
    
    a) It renders a JSX element to the DOM (Document Object Model).
    
    b) It transpires JSX into regular JavaScript code.
    
    c) It creates a virtual DOM element.
    
    d) It installs dependencies for a React application.
    
10. How do you use a React component in a JSX element?
    
    a) By enclosing the component name in quotes.
    
    b) By enclosing the component name in curly braces.
    
    c) By enclosing the component name in parentheses.
    
    d) By enclosing the component name in brackets.
    

For answers, you can attempt this quiz on google forms as well.

[https://forms.gle/GsK4og3cnGMXJnrT9](https://forms.gle/GsK4og3cnGMXJnrT9)

<mark>this is it for today!!</mark>

**we will meet in the next blog, keep learning.**

<mark>if any one of you wants to work with me on this course please mail me at nakulgoyal78@gmail.com</mark>

This will help me release worksheets + quizzes for all of you faster.