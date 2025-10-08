# Ex.06 Book Front Cover Page Design
# Date:5/10/25
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
book.html

<html>
    <head>
        <link rel="stylesheet" href="cover.css">
        <title>Fundamental of web application development</title> 
    </head>
    <body>
        <div class="name"><h1>SUDHARSAN U(25010861)</h1></div>
        
        <div class="cover">
            <div class="main">
                <div class="title">
                    <p>SEC Insight</p>
                    <hr>
                </div>
                
                <div class="content">
                    <p>FUNDAMENTAL OF<br> WEB APPLICATION <br> DEVELOPMENT</p>
                </div>
                
                <br>
                <div class="subtitle">
                    <h3>
                     "DEEP DIVE IN HTML, CSS, JS BASIC"
                    </h3>
                   
                </div>
                <div class="image">
                    <img src="the art web.jpg" alt="mypic">
                </div>
                <div class="edition">
                    <h2>LATEST edition</h2>
                    <hr>
                </div>
                <div class="author">
                    <h2><b>SUDHARSAN U</b></h2>
                </div>
                <div class="sub-bottom"><h2>SEC</h2></div>
            </div>
       </div>
    </body>
</html>

cover.css

body{
    
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-style: oblique;
    color:rgb(244, 37, 6);

.cover{
    background: linear-gradient(to bottom right,#f7bd41,#17b0e8) ;  
    background-clip: border-box;
    background-position-x: right;
    background-size: cover;  
    height: 720px;
    width: 500px;
    position: relative;
    left: 500px;
}
.main{
    margin: auto;
    border: solid 8px rgb(49, 44, 59);
}
.title{
    font-size: 12px;
    color: antiquewhite;
    font-weight: 800;
    position: relative;
    top: 20px;
    left: 10px;
    width: 140px;
}
.content{
    font-size: 40px;
    text-align: center;
    position: relative;
    top: 40px;
    font-weight: bold;
    color: white;
    
}
.subtitle{
    position: relative;
    left: 10px;
    font-size:18px;
    color: rgb(3, 19, 25);

}
    
}
.image{
    width: 150px; 
    height:150px;      
    position: relative;
    top: 70px;
    left:300px;
    border: 2px solid white;
    background: white;
    overflow: hidden;   
}
.image img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.edition{
    position: relative;
    top: 50px;
    left: 1px;
}
.author{
    position: relative;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    top: 45px;
    left:20px;
    font-size: 18px;
}
.sub-bottom{
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    bottom:5px;
    left:380px;
    font-size: 15px;
}
.name{
    text-align: center;
    position: relative;
    right:30px;
    color: red;
}

```
# OUTPUT:
![alt text](<Screenshot 2025-10-08 183926.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
