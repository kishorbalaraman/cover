# Ex.06 Book Front Cover Page Design
## Date:07.10.2025

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
```
book.html
<html>
    <head>
        <link rel="stylesheet" href="style.css">
        <title>KISHOR B (25017562)</title>
    </head>
    <body>
        <div class="name"><h1>kishor.B(25017562)</h1></div>
        
        <div class="cover">
            <div class="main">
                <div class="title">
                    <h1>SEC Insight</h1>
                    <hr>
                </div>
                
                <div class="content">
                    <p>FUNDAMENTALS OF
                        DATASCIENCE</p>
                </div>
                <br>
                <div class="subtitle">
                    <h3>
                     A Deep Dive into Python
                    </h3>
                    <h4>Statistics & Machine Learning</h4>
                </div>
                <div class="image">
                    <img src="kishor.png" alt="mypic">
                </div>
                <div class="edition">
                    <h2>Grand Edition</h2>
                    <hr>
                </div>
                <div class="author">
                    <h2>B.kishor</h2>
                </div>
                <div class="sub-bottom"><h2>MARIAS</h2></div>
            </div>
       </div>
    </body>
</html>

style.css
style.css
body{
    background-color: #666;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-style: oblique;
    color:antiquewhite;
}
.cover{
    background-image:url(frontpage.png);  
    background-clip: border-box;
    background-position-x: right;
    background-size: cover;  
    height: 725px;
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
    
}
.subtitle{
    position: relative;
    left: 10px;
    font-size:18px;
    
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
    font-weight: bolder;
}
.author{
    position: relative;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    top: 50px;
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
    right:55px;
}

```

## OUTPUT:
![alt text](<surya/bookapp/static/Screenshot 2025-10-07 182211.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
