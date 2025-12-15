# Ex.05 Book Cover Page Design
## Date:15-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

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
```
book.html

<html>
    <head>
        <title>Book Cover</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>

        <h1 class="title">About The Book</h1>
        <hr>
        <p>
            This book on <p2></p2>"Web Application Development" explains how to create websites and online applications that users can interact with. It usually covers the basics like HTML, CSS, JavaScript, and then moves to advanced concepts such as frontend frameworks, backend programming, databases, APIs, security, and deployment. The book guides readers through how a web app works from the user interface to the server and database, helping them learn how to build complete, functional applications for the web.
        </p>
        <div class="quote-box">
        <h3>
           "A web app development book opens the door to creating digital experiences that connect people, ideas, and technology."
        </h3>
        </div>
        <div class="pic-box">
           <img src="25009369.jpg" align="left"width="125" height="100">
           <p3>NM Muthukumaran</p3>
            <p>NM Muthukumaran is a dedicated and detail-oriented individual with a strong interest in technology and software development.</p>

    

        </div>
        <div class="end-box">
            <p4>SEC Publishers</p4>
            <p5>Printed in India</p5>
            <p6 class="price">Price:&#8377;399</p6>
            </h4>
        </div>       
    </body>

style.css

body
{
    margin-left:500px;
    margin-right:500px;
    background-image: url("Screenshot\ 2025-12-12\ 094342.png");
    background-repeat: no-repeat;
    background-size: contain;
    background-position: center;
    
}
h1
{
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;


}
p
{
    font-family:'seogoe ui', Tahoma, Geneva, Verdana, sans-serif;
    
}
p3
{
    font-style: oblique;
    color: #aa1d1d;
}
p4
{
    display: block;
}
p5
{
    display: block;
}
h4
{
    text-align: left;
}
.quote-box
{
    border: 2px solid black;
    padding: 10px;
    margin-bottom: 20px;
    background-color: lightgoldenrodyellow;
    font-family: cursive;
    font-size: 14px;
    border-left: 10px solid gray;

}
.pic-box
{

    border: 2px solid black;
    padding: 10px;
    margin-top: 40px;
    background-color: lightgoldenrodyellow;
    font-family: cursive;
    font-size: 14px;
    border-left: 10px solid gray;




}
.end-box
{
    
    border: 2px solid black;
    padding: 5px;
    margin-top: 100px;
    background-color: lightgoldenrodyellow;
    font-family: cursive;
    font-size: 14px;
    border-left: 10px solid gray;
    color:rgb(138, 43, 226);
    
    
    

}
.price
{
    display: block;
    text-align:right;
    
    
}
```

## OUTPUT:

![alt text](<Screenshot 2025-12-15 182314.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
