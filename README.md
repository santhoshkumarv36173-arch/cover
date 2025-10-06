# Ex.06 Book Front Cover Page Design
## Date:06.10.2025

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
jef.html

<html>

<head>
    <link rel="stylesheet" href="jef.css">
    <title>FWAD</title>
</head>

<body>
    <div class="main-content">
        <div class="cover">
            <div class="main">
                <div class="title">
                    <h2>SEC Insights</h2>
                    <hr>
                </div>
                <div class="content">
                    <p>Hacking Devices</p>
                </div>
                <br>
                <div class="subtitle">
                    <h3>
                        "Talk is cheap.Show me the code"
                    </h3>
                </div>
                <div class="footer">
                    <div class="image">
                        <img src="0F7A0963 copy.jpg" alt="mypic">
                    </div>
                    <div class="edition">
                        <h2>Limited Edition</h2>
                        <br>
                        <hr>
                    </div>
                    <div class="writer">
                        <h2>SANTHOSH KUMAR V</h2>
            
                    </div>
                    <div class="sub-bottom">
                        <h2>REF.NO:25016278</h2>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>

jef.css

body{
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-style: oblique;
    color:black;
    overflow-x: hidden;
}
.cover{ 
    background-clip: border-box;
    background-position-x: right;
    background-size: cover;  
    height: 720px;
    width: 500px;
    background-image: url(back.jpg);
    position: relative;
    background-color: aquamarine;
    left: 500px;
}
.main{
    margin: auto;
    border: solid 6px rgb(49, 44, 59);
    height: 710px;}
.title{
    font-size: 12px;
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
    height:200px;      
    position: relative;
    top: 70px;
    left:300px;
    border-radius: 10%;
    border: solid 4px black;
    overflow: hidden;   
}
.image img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.edition{
    position: relative;
    top: 30px;
    left: 1px;
    font-weight: bolder;
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
    bottom:25px;
    left:280px;
    font-size: 15px;
}   
.name{
    text-align: center;
    position: relative;
    right:20px;
    color: purple;
}
.footer{
    position:relative;
    top:60px;
}
.main-content{
    position:relative;
}
.writer{
    position:relative;
    bottom:20px;
}
```


## OUTPUT:
![alt text](<Screenshot 2025-10-06 183848.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
