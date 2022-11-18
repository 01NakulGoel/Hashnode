# Ultimate HTML guide with Notes plus HTML exercises

Hello, welcome to my new blog where I will be teaching you HTML i.e. Hyper Text Markup Language which is the most loved markup language in the world. 


## - **what all things are covered in this blog?**

- Full HTML tutorial
- Video to explain each part(if you want a detailed explanation of the blog you can go to my youtube channel)
- Worksheet to polish your understanding

Basic Prerequisite

- Eager to learn
- Will do all the exercise


# What is HTML?

HTML stands for Hypertext Markup Language and is the most basic building block of web development.

## Why do we use HTML?
there are tons of other markup languages available in the market such as RSS, KML, SGML, etc but we still use HTML because of the following reasons
1. Lightweight
2. Easy to learn
3. Easy to understand by browser
4. User-friendly
1. SEO friendly

## History of HTML

- HTML was created by Sir Tim Berners-Lee in late 1991.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668662744732/Bu2AS18Z1.png align="left")

- Before he created HTML, he used to send research documents via email.- 

- To make it easier for scientists at different universities to gain access to each other's
documents, and he created HTML.

- The second version of HTML was released in 1995
-  The third version of HTML was released in 1997
-  The fourth version of HTML was released in 1999
-  The fifth version of HTML was released in 2014







## HTML is a programming language or not?
one of the favorite questions asked in interviews is this one whether HTML is a programming language or not, and the answer is **NO**.

because HTML does not have logic

### how do you explain HTML does not have logic 
if you write 2 + 2 in HTML you will get it as 2 + 2

and if you write 2 + 2 in the programming language you will get 4.


Before moving ahead with the HTML I want you guys to install VS code which is visual Studio code on your computer.
## What is VS code?
Visual Studio is a code editor in which you will write your code and is developed by Microsoft.

how to download VS code?

- Step 1 Search VS code on google
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664220928/V6vu68mSe.png align="left")

- Step 2 Click on the download button

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664267607/0tDYjsRn_.png align="left")

- Step 3 Install the vs code

After installation, it will look like this

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664385624/4lal-RLwR.png align="left")

if you still have doubts do comment I will surely help.


## How to make your first HTML file?

Step1 Open VS code

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664642042/NLVrdlSo4.png align="left")

Step 2 Click on a new file

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664695329/QRB24dWct.png align="left")

Step 3 write the name of the file as name.html       // you can use any name but the extension will be .html
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664737327/kz8wTfI45.png align="left")

Step 4 Click enter and the new file will be created


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664843249/kB9eq7M2t.png align="left")

Step 5 Congratulations your first index file is created


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668664937602/fpMjSWgMB.png align="left")



Now let's learn HTML

### What are HTML elements?
An HTML element is defined by a start tag, some content, and an end tag.

```
- Syntax for start tag is <starttag>
- Content - it means the content
- Syntax for end tag is </startag>
```

we will learn more in the coming part



## Basic page structure of HTML?

the basic structure of an HTML page is this means all HTML files should have this format


```
<html>
<head>

</head>
<body>

</body>
</html>
``` 


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668667236088/NM8vlRnEB.png align="left")


this is a little advance and this format you need to copy whenever you are writing HTML



```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```


## HTML Page Structure
You are one step away from building your first website in HTML. You need to add `<html>`, `<head>`,
 and `<body>` tags to successfully build your website. Let's see what each tag means:

- The `<!DOCTYPE html>` declaration defines the version of the HTML document, in this case, it is 5
- The `<html>` element is the root element of an HTML page.
- The `<head>` element contains `meta information`, `stylesheets(CSS stylesheets)`, `title`, `favicon` etc.
- The `<body>` element defines the document's body and is a container for all the visible
contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668669513094/okbaykSnm.png align="left")


## What are elements, tags, and attributes?


- HTML elements consist of an opening tag, content, and closing tag.
- Tags are basically opening tag and closing tag. 
- Attributes are written in opening tags such as id, class, style, etc.

you can understand the difference easily by looking at the diagram below

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668672571849/A8PRrU_Rz.png align="left")






## - Block and Inline element



the tags in HTML is divided in two parts:
### --Block elements

they take 100% width of the page means they stretch out to the full width of the page 

- some of the important block elements are:-

`<address> <article> <aside> <blockquote> <canvas> <div> <fieldset> <footer> <form> <h1>-<h6><header> <hr> <li> <main> <nav> <ol> <p> <section> <table> <tfoot> <ul> <video>`

### --Inline elements

they take the minimum width required to display the content

- some of the important inline elements are:-

`<a> <b> <button> <code> <i> <img> <input> <label> <map> <object> <script> <select> <small> <span> <strong> <sub> <sup><textarea> <time>`


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668679412283/RveDh8Tan.png align="left")

- ### Important HTML tags
- Headings 
   there are basically six headings in HTML that are:-

1. h1 to h6

this is heading tag ranges from h1 to h6

Syntax


```
<h1> This is Heading 1 </h1>
<h2>This is Heading 2 </h2>
<h3>This is Heading 3 </h3>
<h4>This is Heading 4 </h4>
<h5>This is Heading 5 </h5>
<h6>This is Heading 6 </h6>
``` 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668673240064/y7IdyJZws.png align="left")


- paragraph

this is a paragraph tag.

Syntax

```
<p> This is paragraph </p>
``` 


- span

this is an inline tag used to write. it works the same as a paragraph tag but it is inline.

Syntax
```
  <span>This is span tag</span>
```

- div

it is the most widely used tag which is a block tag generally used to make inline element as block element.

Syntax
```
  <div>This is div tag</div>
```

- anchor 
href stands for hyperlink and in this, you need to write the link.

Syntax

```
<a href=""></a>
```


- image

```
<img src="" alt="">
```

### - HTML forms

     ** 1. form tag**

syntax

```
  <form action=""></form>
``` 


   **   2. Input tag**

The <input> tag specifies an input field where the user can enter data.
it is a way to take input from the users.
different input tags are:-

- input type text

```
<input type="text" name="" id="">

```

- input type date


```
<input type="date" name="" id="">

``` 
 
- input type checkbox

```
<input type="checkbox" name="" id="">
```

- input type number

```
<input type="number" name="" id="">

```
- input type  radio

```
<input type="radio" name="" id="">
```

other input types are:- 
`<input type="submit">
<input type="checkbox">
<input type="date">
<input type="email">
<input type="file">
<input type="hidden">
<input type="image">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="reset">
<input type="submit">
<input type="tel">
<input type="text">
<input type="url">`



      3. label tag- it is used to label the form inputs
```
   <label for=""></label>
```

```
<form>
  <div>
    <h4>Input Elements</h4>
    <div>
      <label>Text</label>
      <input name="text" type="text" placeholder="enter text here" />
    </div>
    <div>
      <label>Email</label>
      <input name="email" type="email" />
    </div>
    <div>
      <label>Number</label>
      <input name="number" type="number" max="10" min="1"/>
    </div>
    <div>
      <label>Date</label>
      <input name="date" type="date" />
    </div>
  </div>
  <div>
    <h4>Select Elements</h4>
    <div>
      <label>Radio</label>
      <input name="radio" type="radio" value="yes" /> yes
      <input name="radio" type="radio" value="no" />Whatever
    </div>
    <div>
      <label>Checkbox</label>
      <input name="checkbox" type="checkbox" value="yes" /> yes
      <input name="checkbox" type="checkbox" value="no" />no
    </div>
    <div>
      <label>Select</label>
      <select name="select[]">
        <option value="selection_1">selection 1</option>
        <option value="selection_2">selection 2</option>
        <option value="selection_3">selection 3</option>
      </select>
    </div>
  </div>
  <div>
    <h4>Long Input Element</h4>
    <textarea name="textarea" col="5" rows="6">If you really need to input super long text.</textarea>
  </div>
  <div>
      <h4>Action Element</h4>
    <input type="submit" value='save'>
  </div>
</form>```


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668690524340/EbWQLCIWf.png align="left")

- list

  1. `<ul>`- unordered list

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668685669002/HADl_CJpw.png align="left")

  2. `<ol>` -ordered list

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668685594892/-u09yzgNQ.png align="left")

  3. `<li>` - list (it is the tag used to store the list items)





- Table

  1. `<table>`   
  2. `<thead>`
  3. `<tbody>`
  4. `<th>`
  5. `<tr>`



## Semantic markups

instead of using div we will use more specified tags which has a meaning

```
<header></header>
<nav></nav>
<main></main>
<section></section>
<article></article>
<summary></summary>
<aside></aside>
<footer></footer>

```

## HTML entity

HTML entities are the reserved characters that are used in the HTML document.

some characters like greater than less than even some of the currency symbols you cannot write directly Html entity helps you in this.


- Used to display reserved characters, that normally would be invalid

- Also used in place of difficult-to-type characters

- The browser interprets them and renders the correct character instead.

- Start with an ampersand and end with a semicolon

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668677539489/YAIIEQFnv.png align="left")



## Some important global attributes of HTML


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668682911247/8TVIkkt0u.png align="left")

both class and id is a way to group or name the HTML element


- class
> - many tags can have the same class,  it's not unique.
- id
> - it is always unique

this is enough for your understanding and congratulation you have learned HTML. 

## 5 basic exercises/worksheets



- 
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668688442507/9U7IX0mUU.png align="left")
image address
`https://cdn.britannica.com/05/236505-050-17B6E34A/Elon-Musk-2022.jpg?w=400&h=300&c=crop`

- 
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668688749138/oX6k-he6f.png align="left")
-
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668689889770/5nr0y_44i.png align="left")

## Other Important essential tags:


- <!DOCTYPE>` This tag is used to specify the version of HTML
- `<html>` represents the root of an HTML document
- `<a>` It is termed as anchor tag and it creates a hyperlink or link.
- `<b>` It is used to make a text bold.
- `<body>` It is used to define the body section of an HTML document.
- `<br>` It is used to apply single line break.
- `<button>` It is used to represent a clickable button
- `<div>` It defines a division or section within HTML document.
- `<form>` It is used to define an HTML form.
- `<h1> to <h6>` It defines headings for an HTML document from level 1 to level 6.
- `<head>` It defines the head section of an HTML document.
- `<hr>` It is used to apply thematic break between paragraph-level elements.
- `<img>` It is used to insert an image within an HTML document.
- `<input>` It defines an input field within an HTML form.
- `<label>` It defines a text label for the input field of form.
- `<li>` It is used to represent items in list.
- `<link>` It represents a relationship between current document and an external resource.
- `<meta>` It defines metadata of an HTML document.
- `<option>` It is used to define options or items in a drop-down list.
- `<p>` It represents a paragraph in an HTML document.
- `<script>` It is used to declare the JavaScript within HTML document.
- `<select>` It represents a control which provides a menu of options.
- `<small>` It is used to make text font one size smaller than document?s base font size.
- `<span>` It is used for styling and grouping inline.
- `<style>` It is used to contain style information for an HTML document.
- `<table>` It is used to present data in tabular form or to create a table within HTML document.
- `<tbody>` It represents the body content of an HTML table and used along with <thead> and <tfoot>.
- `<td>` It is used to define cells of an HTML table which contains table data
- `<textarea>` It is used to define multiple line input such as comment feedback and review etc.
- `<tfoot>` It defines the footer content of an HTML table.
- `<th>` It defines the head cell of an HTML table.
- `<thead>` It defines the header of an HTML table. It is used along with <tbody> and <tfoot> tags.
- `<title>` It defines the title or name of an HTML document.
- `<tr>` It defines the row cells in an HTML table
- `<u>` It is used to render enclosed text with an underline.
- `<ul>` It defines unordered list of items.

if you think this has taught something to you so kindly drop a comment below so that I can recreate such blogs.

```some of the data is referred from https://www.w3schools.com/```



