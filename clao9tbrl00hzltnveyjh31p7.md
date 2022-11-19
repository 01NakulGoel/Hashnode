# Getting Started with CSS, Part-1 for beginners

Design is so simple that's why it is so complicated. The website design looks very simple but it's a little complex and this blog is here to help you to make it easier than ever before.

Hello everyone and welcome to my new blog, in this blog we will be learning about CSS which is Cascading style sheets before you move ahead I recommend you to watch the HTML tutorial on my blog page. and do all the exercises mentioned in the HTML tutorial.


# What are we going to learn in this blog?

- Introduction
- History of CSS
-How to link the CSS file
- Color value in CSS
- Font-Size
- Text-Align



# What is CSS?

CSS stands for cascading style sheet. it is a language that is used to style web pages so that they become more presentable. 
it includes color, layout, fonts, animation, and much more.

# History of CSS

The history of every language is very important that's how we come to know how that language was developed.

**HÃ¥kon Wium Lie is the inventor of CSS**

- the first version was released in 1996.
- CSS2 was released in1998.
- CSS3 was released in 2011.

# How to add CSS to your file?

There are three ways to add CSS to your file
## - CSS as an attribute
  The attribute is something that is written inside the opening tag. it is denoted by `style` in CSS.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668872111733/QL3jRjiPx.png align="left")

## - Add a `<style>` tag in the head part


```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

<style>
    h1{
        color: red;
    }
</style>

</head>
<body>
    <h1>Nakul Goel</h1>
</body>
</html>
  ```


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668872480007/m6Yit68jn.png align="left")

## - By linking style sheet in head tag(most appropriate way)

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

<link rel="stylesheet" href="style.css">

</head>
<body>
    <h1>Nakul Goel</h1>
</body>
</html>
```


in the `<head>` tag I have linked a file that is style.css and you can write CSS in that file, this is the most preferred way.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668872668542/uykhLibQp.png align="left")

# CSS properties

## 1. color (it is used to give color to the tags)
  - it is used to give color and it has three values:-
    1. Hex color
      - A hexadecimal color is a 6-digit representation of the color that starts with the # symbol and is the 
         permutation of numbers from 0 to F
    2. RGB color- it stands for red green and blue
         -RGB color consists of three values of color from 0 to 255.
           ` rgb(0-255,0-255,0-255)`

           `rgb(0,0,0), rgb(120,10,250), rgb(155,102,45)`
         
    3. By color name
         - The colors in CSS can be specified in Hexadecimal values also.


## 2. Font -size
    - It is used to change the font size of the text.
    
```
h1{
font-size:120px;
}
```
px is the unit for font, there are other units as well we will discuss them at a later stage.

## 3. Text-align:
    - This property affects the block element in the horizontal axis.
There are basically four values of text-align:-
   1. Left

   It will put all the text on the left side.

   2. right

   It will align the text to the right.

   3. Center

  It will align the text to the center.

  4. justify 

  This text will take full width.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668875860164/1Nrj7FPOk.png align="left")

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668875878509/OVMZ3gOJ8.png align="left")






 



