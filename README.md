# Ex.06 Book Front Cover Page Design
## Date:11/05/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
### HTML
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>SAN BOOKS</title>
        <title>Book Cover</title>
        <link rel="stylesheet" href="a.css">
    </head>
    <body>
    <div class="bookcover">
        <div class="head">
            <b>SAN BOOKS</b>
        </div>
        <div class="style">
            <hr style="color:rgb(209, 165, 165)">
        </div>
        <div class="title">
            <h1>POWER OF BRAIN</h1>
        </div>
        <div class="subtitle">
            <b>Structure of Brain</b>
        </div>
        <div class="photo">
            <img src="image.webp" width="90" height="100">
        </div>
        <div class="line">
            <hr style="color:rgba(144, 203, 219, 0.555)">
        </div>
        <div class="authorname">
            <p><b>SANJAY S</b></p>
        </div>
        <div class="by">
            <h4>SAN INDUSTRY</h4>
        </div>
        <div class="about">
            <p>Brain Power will explain the science behind what really affects our brains, as well as providing practical tips and exercises to improve and maintain brain function into old age.</p>
        </div>
    </div>
    </body>
</html>    
```
### EXTERNAL CSS
```CSS
.bookcover{
    width: 400px;
    height: 600px;
    position: relative;
    top: 40px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family: ' Arial, sans-serif';
    background-image: url(brain.avif);
    background-size: cover;
}
.head{
    color:rgb(248, 245, 245);

}
.style{
    width:90px;
}
.authorname{ 
    position: relative;
    color:rgb(255, 255, 255);
    top:190px;
    left:265px;
    font-size: medium;
}
.title{
    color:rgb(255, 255, 255);
    font-family: Roquen;
    font-size: larger;
    text-align: center;
    position: relative;
    top: 30px;
}
.line {
    width:400px;
    position: relative;
    top:270px;  
}
.by{
    color:rgb(255, 255, 255);
    font-size: medium;
    font-family: Verdana;
    position:relative;
    top:180px;
}
.subtitle{
    color:rgb(255, 255, 255);
    font-family: Verdana;
    font-size: large;
    position: relative;
    left:30px;
    top:40px;
}
.photo{
    position: relative;
    top: 180px;
    left: 260px;
    width: 90px;
    height: 80px;
    background-size:contain;
}
.about{
    color:rgb(255, 255, 255);
    position: relative;
    left:7px;
    top: 200px;
}
```

## OUTPUT:
![alt text](out.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
