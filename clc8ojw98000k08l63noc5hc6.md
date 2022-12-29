# Mastering React Day-5

Hello everyone and I once again welcome you all to the 5th day of mastering react in 8 weeks series.

so how are you all doing?

This blog can be a little small in terms of writing as today I will be teaching you how to get API requests, I hope most of you guys are aware of the promises and async/await, even if you are not let's start from the beginning and for those who know let's just brush up your concepts once again.

# API request?

## What is an API request?

let's understand in layman's language first, all the websites on the internet are not hardcoded which means the data is not fixed it is actually changing as per the inputs or requests from the user.

so what actually happens?

Let's take an example of our favorite search engine i.e. google.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672202867248/01881ac5-4981-4997-91eb-8fa471d40e06.png align="center")

let's make a request to google **what is React?**

below is the response from google.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672202932959/92076279-ef81-4d0f-82c3-9e5ff1f8d479.png align="center")

let's make another request to google asking **what is JavaScript?**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672203018224/23267847-2deb-4b6c-b420-68dba7da8b73.png align="center")

can you see the similarity in both requests?

The structure is actually the same just the data changing as per the input from the user.

This means we need to store data somewhere and ask for it as per user need or requirement. this is basically an API request.

An **API request** is a request made to an application programming interface (API) in order to retrieve or modify data or trigger an action. In simpler terms, an API request is a way for one computer system (the client) to ask another computer system (the server) to do something, such as send some data or perform a specific task.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672204213690/a7601154-8091-4075-a43e-c6fb60783177.gif align="center")

let's understand this from a broader perspective:-

* A user wants to buy a product from an online store.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293300636/4c2a35d8-ffeb-4a37-badb-a716de8272c7.png align="center")
    
* The user adds the product to their shopping cart and proceeds to the checkout page.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293323644/519b8435-5155-4238-839e-9679e3715e16.png align="center")
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293336199/6fe21302-1c4f-4655-810e-d5d50f0e505e.png align="center")
    
* The user's web browser sends an API request to the online store's server, asking to create an order for the product in the user's shopping cart.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293380060/140cbeba-0153-4c5c-b2a8-1bbd3dedf203.png align="center")
    
* The server receives the API request and processes it, creating a new order for the product.
    
* The server sends a response back to the user's web browser, which includes the order details (such as the order number and the total price).
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293394563/789f58e7-ed3f-490c-ac53-ea92f4a3074d.png align="center")
    
* The web browser displays the order details to the user and prompts them to enter their payment information.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293406568/bcb86856-9dd5-4173-b0d4-b06fcba90f7f.png align="center")
    
* The user enters their payment information and submits the order.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293413624/f211035c-55b4-4fc9-9a53-1d1c4154800a.png align="center")
    
* The user's web browser sends another API request to the online store's server, asking to process the payment for the order.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293438640/58a23e46-abce-4738-a095-eb10df7648f1.png align="center")
    
* The server receives the API request and processes the payment, charging the user's credit card or debit card.
    
* The server sends a response back to the user's web browser, which includes a confirmation that the payment was successful.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293449768/aa9d12eb-eaa9-47ce-9be7-63491de5aae0.png align="center")
    
* The web browser displays a confirmation message to the user, indicating that the order was placed successfully.
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672293460596/86af5091-1ccd-4ba6-b45c-11e76a604ddc.png align="center")
    

so I hope we are cleared with what is an API request also why we need it.

### In what format do we receive or send data?

The data is sent from client to server or server to client in form of JSON (JavaScript Object Notation) which is the lightweight and fastest way to transfer data from one point to another.

Overall, JSON is a popular choice for transmitting data between systems because it is lightweight, easy to parse, easy to read by humans, and widely supported.

To convert normal data to JSON data, you can use a function or library that can convert the data to JSON format. For example, in JavaScript, you can use the `JSON.stringify` function to convert a JavaScript object or array to a JSON string:

```javascript
const data = {
  name: 'John',
  age: 30,
  city: 'New York'
};

const jsonData = JSON.stringify(data);
// jsonData is now a JSON string: '{"name":"John","age":30,"city":"New York"}'
```

To convert JSON data to normal data, you can use a function or library that can parse the JSON data and convert it to a format that is specific to a particular programming language or application.

For example, in JavaScript, you can use the `JSON.parse` function to convert a JSON string to a JavaScript object or array:

```javascript
const jsonData = '{"name":"John","age":30,"city":"New York"}';

const data = JSON.parse(jsonData);
// data is now a JavaScript object: { name: 'John', age: 30, city: 'New York' }
```

### How to make a request to receive data?

In JS to get data, we will be using fetch,

The `fetch` function in JavaScript is used to make HTTP requests to a server. `fetch` takes a URL and options object as arguments and returns a promise that resolves with the response from the server.

please watch below how to request data from API, I will teach you more about Get, Post, Put, Delete and Patch in the upcoming lectures.

### Requesting data

let's request data from some API and let's just post it.

you can request data from the API in two ways:-

The API which we will be using is JSON placeholder which is a free API.

| S.No. | API | link |
| --- | --- | --- |
| 1 | **Documentation** | [https://jsonplaceholder.typicode.com/](https://jsonplaceholder.typicode.com/) |
| 2 | **Posts** | [https://jsonplaceholder.typicode.com/posts](https://jsonplaceholder.typicode.com/posts) |
| 3 | **Comments** | [https://jsonplaceholder.typicode.com/comments](https://jsonplaceholder.typicode.com/comments) |

1. Promises
    
    1. firstly we will import React from React.
        
    2. we will use useState(), today I am telling you a new syntax that is React.useState().
        
    3. don't get confused:- useState() and React.useState() are same.
        
    4. useState() returns an array with two values:-
        
        1. The **current state** value is equal to the argument passed to the `useState` when we first declare it and it gets rendered.
            
        2. second is a function that can be used to update the state value. This function is called the "state setter function."
            
    5. now we will use a promise to fetch the data.
        
    
    ```javascript
    import React from "react";
    
    const [Post,setPost]=React.useState([]);
    fetch('https://jsonplaceholder.typicode.com/posts')
          .then(response => response.json())
          .then((data) => {console.log(data)
                           setPost(data)})
    ```
    
2. Async/await
    
    ```javascript
    import React from "react";
    
    const [Post,setPost]=React.useState([]);
    async function dataFetch(){ 
    let res= await fetch('https://jsonplaceholder.typicode.com/posts')
    let data = await res.json()    
    setPost(data)
    }
    ```
    
    ## **Activity**
    
    **Objective**
    
    1. create a `code sandbox` react template.
        
    2. create a button and when you click on button 10 post should be shown on the screen as a list.
        

# Components Hierachy

A component hierarchy refers to the structure of the React components in a web application and the relationships between them.

Its very important to understand component hierachy because it will help me in imagining how a website is made.

let take an example of hashnode and understand its component hierachy:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672289319094/7adcdffc-270f-4764-a5d3-d559084cbf92.png align="center")

Let's divide it into two parts that are the header and main , it doesn't have footer as it is not required.

In the comment section tell me the reason **why Hashnode does n't have a footer.**

below is the component tree:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672120563261/a4e60cf8-775f-4aa7-abb7-bb43203d9ab5.png align="center")

lets divide the header and main into more small components like below:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672120317071/f1bf14fd-e2ba-427c-a48e-5c556e893f51.png align="center")

component tree:-

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672120501901/8e6e2e97-f829-4a28-b7b8-acb5dd8c2113.png align="center")

## **Activity-2**

now i have an activity for all of you

1. Divide sidebar and section into further sub category.
    
2. Share the image in the comment section so that i can see
    
3. Do it otherwise you will be stuck at imagining a lot of things.
    

tomorrow we will learn useState and that's it for today , its a very easy lecture for you guys.

**Keep Learning.**

if you have any questions or doubt, drop them in the comment section.