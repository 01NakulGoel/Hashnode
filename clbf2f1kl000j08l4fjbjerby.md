# JavaScript -IX Nested loops || WebDev Course By Nakul Goel || Day-9 || Free Web Development course

This is the ninth lecture of the WEBDEV Course by Nakul Goel, today we will be learning what Nested loops are in JavaScript.

The detailed video lecture is below:-

%[] 

# Before moving ahead

Important channels to Follow and subscribe to:-

Youtube:- youtube.com/channel/UCS\_0LK2cA\_y4Lfl6tUfdQgw

GitHub:- github.com/01NakulGoel

# What are nested loops?

Nested loops in simple language are loops inside another loop.

for example

1.  Ravi, Neha, and john went to a shop to buy candies. all of them have 10 coins.
    
2.  the shopkeeper said he would give one candy for one coin and at one time he would take one coin.
    
3.  John went to the shopkeeper gave him 1 coin and got 1 candy and he again gave him one coin until his coins ended, at last, he got 10 candies.
    
4.  After that Neha and Ravi repeated the same process.
    
5.  this process of repeating the repeated thing is known as nested loops.
    
    ![Nested Loop real life example](https://cdn.hashnode.com/res/hashnode/image/upload/v1670482035971/B_ldkRRL7.png align="center")
    
6.  let's write it in the form of code
    
    ```javascript
    // if we want to store multple things of same type we will use array
    let children=['John','Neha','Ravi']
    let coins=10
    // outer loop in which each will go to shopkeeper one by one
    
    for( let i = 0 ; i < children.length ; i++ ){
    // lets print who went first
    console.log(children[i] + ' went to buy candy') ;
    
    // inner loop for spending money
    for( let j = 0 ; j < coins ; j++ ){
    // lets spend coin one by one
    console.log('   ' + children[i] + ' spent 1 coin and got 1 candy')
    }
    }
    ```
    
    you can easily understand nested loops by the following example:-
    
    ![Nested loops example](https://cdn.hashnode.com/res/hashnode/image/upload/v1670482540635/1G11Uf3nf.png align="center")
    
    ```javascript
    for(let i = 0 ; i < 4 ; i++ ) {
      console.log('Outer '+ i )
      for( let j = 0 ; j < 3; j++ ){
        console.log('    inner ' + j)
      }
    }
    ```
    
    Let's print some patterns and this will make our understanding to the next level:-
    

```javascript
/* Print
A A A A A
A A A A A
A A A A A
A A A A A */
```

for printing this pattern you need to use follow these steps:-

1.  how many times the outer loop is running?
    
2.  How many times the inner loop is running?
    
    ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670484854297/YTU8lyT6l.png align="center")
    
    ```javascript
    // let write the code
    
    for ( let i = 0 ; i < 5 ; i++ ){
    let bag = ''
    for ( let j = 0 ; j < 5 ; j++){
    bag += 'A' + ' '
    }
    console.log(bag)
    }
    ```
    

### <mark>one more example</mark>

**Description**

There are 5 fields and you need to plant 4 seeds in each field.

**Output**

![Seed planting pattern](https://cdn.hashnode.com/res/hashnode/image/upload/v1670486890375/YiTIx8-4O.png align="left")

Try it yourself before watching the code

```javascript
// let write the code

for ( let i = 0 ; i < 5 ; i++ ){
let bag = ''
for ( let j = 0 ; j < 4 ; j++){
bag += '*' + ' '
}
console.log(bag)
}
```

### <mark>let's do some questions</mark>

### Question 1

**Description**

There are 5 fields and you need to plant seeds according to the rule.

Field 1 --&gt; Seed to be planted 1

Field 2 --&gt; Seed to be planted 2

Field 3 --&gt; Seed to be planted 3

Field 4 --&gt; Seed to be planted 4

Field 5 --&gt; Seed to be planted 5

**Output**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1670487110700/DsNPKD8Bi.png align="left")

```javascript
for ( let i = 0 ; i < 5 ; i++ ){
let bag = ''
for ( let j = 0 ; j <= i ; j++){
bag += '*' + ' '
}
console.log(bag)
}
```

### Question 2

**Description**

You are going to be rich.

your mother told you she will give you money as follows:-

Day 1 --&gt; money received 1 coin

Day 2 --&gt; money received will be 1 coin + 2 coin-- total 3 coin

Day 3 --&gt; money received will be 1 coin + 2 coin + 3 coin -- total 6 coin

and so on

Input

5

Output

`Day-1 total coins = 1`

`Day-2 total coins = 3`

`Day-3 total coins = 6`

`Day-4 total coins = 10`

`Day-5 total coins = 15`

```javascript
for ( let i = 1 ; i <= 5 ; i++ ){

let totalCoin = 0
for ( let j = 1 ; j <= i ; j++){
totalCoin += j
}
let ans = 'Day-'+ i + ' total coins = ' + totalCoin
console.log(ans)
}
//
```

# Assignment

Some questions for all of you

1)

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668579076075/by0cboU2k.png align="left")

2)

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668579132268/wIcQU_j5m.png align="left")

3)

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668579181341/nWtu4s2j7.png align="left")

4)

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668579207614/eixaD53nw.png align="left")

5)

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668579238562/IvUqUPJwJ.png align="left")

> Thank you and keep learning, tomorrow we will learn GitHub.