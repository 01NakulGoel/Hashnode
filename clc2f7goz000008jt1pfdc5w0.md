# Mastering React in 8 weeks - Day 3

Hi, Hashnoders or Learners

today we will study some really amazing things about React.

in this blog, we will be doing some practice questions as well so tighten your seat belt as this journey will be a roller coaster ride for all of you.

![Free photos of Roller coaster](https://cdn.pixabay.com/photo/2016/09/28/18/12/roller-coaster-1701085_960_720.jpg align="left")

# React component?

In React, a component is a piece of reusable code that represents a part of a user interface. Components can be either a function or a class.

```javascript
const MyCode = ()=>{    
  return(
  <div>  
  <h1 style={{color:'red'}} >Nakul Goel</h1>
  <p>I am learning React </p>
  </div>
  )
  }
```

basically, MyCode (<mark>always remember to use PascalCase in React component</mark>) is a React component.

to render React component we will render it like the following part:-

```javascript
root.render(
<MyCode />
)
```

we will always run react component as I have stated above.

In React Component we can basically add a variable that props (short form for the properties ) to make it dynamic.

watch the below code

```javascript
const MyCode = (props)=>{
let {style,heading,description} = props

    
  return(
  <div>  
  <h1 style={style} >{heading}</h1>
  <p> {description} </p>
  </div>
  )
  }
```

now we need to add props while calling the component

```javascript
we have added all the props when we are actually calling the component

root.render(
    <App style={{color:'red'}} description='I am learning React' heading='Nakul Goel' />
);
```

it will look like this after rendering.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671906365912/178f29d8-d13b-4fd7-ae36-80be347c117f.png align="center")

we can also use objects like the below code:-

```javascript
let props = {style:{color:'red'}, description:'I am learning React',heading:'Nakul Goel'}

//after that you can do destructing of props.

root.render(
    <App {...props} />
);
```

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671906996230/da4725ce-4de0-4130-a3d9-45ab1b7d49d5.png align="center")

Let us understand the component on a wider

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671908149352/79fe7d88-8475-4e0b-81ca-7d93025ce8c2.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671908889229/0ba4a082-87b0-48db-b3f0-56928ea44398.png align="center")

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671909172070/02eedd04-8c3f-4c9e-86ef-5bbab995eb4f.png align="center")

I hope this part is pretty much clear to all of you and if any one of you is facing any issue on the above diagram then comments will help you in that as well.

### Activity time

1. Create a list of your favorite movies with JSX like this:-
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1671912261219/ff92b50f-6c87-4efb-b2c1-75515005aaea.png align="center")
    
2. open your VS code and start writing code, if you want to learn.
    
3. be honest with yourself, at last, you are learning this for your growth.
    
4. this is the code of the above problem
    
    ```javascript
    const App = (props) => {
      let { style, heading } = props;
    
      return (
        <div>
          <h1 style={style}>{heading}</h1>
          <ul>
            <li>Black Panther (2018)</li>
            <li> Avengers: Endgame (2019)</li>
            <li> Iron Man (2008)</li>
            <li> Avatar: The Way of Water (2022)</li>
          </ul>
       </div>
      );
    };
    ```
    
    this activity was simple but this activity will teach us some new things.
    
    ### <mark>Activity 2.0</mark>
    
    Psuedo code
    
    1. Create a list of movies using an array of strings, where each string represents a movie in the list.
        
    2. Use a map function to iterate over the array and return a list element for each item.
        
    3. Use a JSX expression to enclose the list elements in a parent element, such as a div or ul element.
        
    4. try it yourself give it at least five minutes on it.
        
    5. we can do the above problem like this:-
        
        ```javascript
        const App = (props) => {
          let { style, heading } = props;
        
          const movies = [
            "Black Panther (2018)",
            "Avengers: Endgame (2019)",
            "Iron Man (2008)",
            "Avatar: The Way of Water (2022)",
          ];
        
          return (
            <div>
              <h1 style={style}>{heading}</h1>
              <ul>
                {
                movies.map(
                  (movie, i) => {
                 return <li key={i}>{movie}</li>;
                }
                )
                }
              </ul>
            </div>
          );
        };
        ```
        
    6. here in the above code, we are running js in the curly bracket, and in that bracket, we are running a map function which is returning us an array of li tags.
        
        ```javascript
        [<li key=1> Black Panther (2018)</li>,
         <li key=2> Avengers: Endgame (2019)</li>,
        <li key=3> Iron Man (2008)</li>,
        <li key=4> Avatar: The Way of Water (2022)</li>]
        ```
        
        and when we put this array in a curly bracket it joins automatically, I will tell you one thing do not focus on how React is made only focus on how we can use it effectively.
        
    7. one more new thing you must have noticed is a key attribute.
        
    8. In React, the key attribute is a special attribute that is used to uniquely identify each element in a list of elements. It is often used when rendering a list of elements dynamically, such as in a map or filter function. The key attribute helps React optimize the rendering of lists by allowing it to keep track of which elements have changed, added, or removed.
        
    9. make sure you always have key attributes, especially when using the map function.
        
        ```javascript
        const list = [
          { id: 1, name: 'Item 1' },
          { id: 2, name: 'Item 2' },
          { id: 3, name: 'Item 3' }
        ];
        
        const items = list.map(item => <li key={item.id}>{item.name}</li>);
        
        return <ul>{items}</ul>;
        ```
        
    
    In this example, the key attribute is set to the id of each item in the list. This allows React to keep track of the individual items and optimize the rendering of the list. It is important to note that the key attribute should be unique within the list of elements, and should not be used for any other purpose.
    

this is actually a pre-release and i am working on this blog right now,

i am adding additional info to the blog till then please do above activities.