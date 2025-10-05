# Ex.06 Book Front Cover Page Design
## Date:06.09.2025

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
cover.html
<html>
<head>
<title>Book Cover Page</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="bookpage">
	<div class="insight">
		SEC INSIGHT
    </div>
    <div class="hrstyle">
	<hr style="color: antiquewhite;">
    </div>
    <div class="booktitle">
	<h1>FUTURE BY INTELLIGENCE</h1>
    </div>
    <div class="subtitle">
         Fom chatbox to self-driving systems,AI has advanced rapidly.The growth is driven by data,innovation and global demand across all major fields
    </div>
    <div class="mypic">
        <img src ="IAM.jpg" width="110" height="100">
    </div>
    <div class="id">
	<hr style="color:purple;">
    </div>
    <div class="author">
	<p><b>S SWARNA PRIYA</b></p>
    </div>
    <div class="ed">
	    SEC
    </div>
    <div class="pub">
	    RARE Edition
    </div>
    </div>
</body>
</html>

style.css
bookpage{
    width:600px;
    height:700px;
    color:rgb(234, 255, 0);
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family: 'Franklin Gothic Medium','Arial Narrow',Arial,sans-serif;
    background-image: url(Screenshot\ \(52\)\ -\ Copy.png);
    background-size: cover;
    
    
}

.insight{
    color: rgb(207, 79, 79);
    position:relative;
}
.hrstyle{
    width:30%;
}
.author{
    display: inline;
    position: relative;
    color: yellowgreen;
    font-family:Georgia;
    font-size: medium;
    top:30%;
    
}
.booktitle{
    font-family: 'courier New',Courier, monospace;
    font-size: larger;
    text-align: center;
    position: relative;
    top: 33px;
}

.id{
    width:500px;
    position: relative;
    top: 175px;
}
.pub{
    color:brown;
    font-size: medium;
    position: relative;
    top:5%;
}
.ed{
    color: aqua;
    font-size: medium;
    position: relative;
    left: 85%;
}
.subtitle{
    font-family: Georgia, 'Times New Roman', Times, serif;
    font-size: large;
    position: relative;
    left: 15px;
    top:40px
}
.mypic{
     position: relative;
     top: 150px;
     left: 500px;
     width: 200px;
     height: 200px;
     background-size: contain;
}
```

## OUTPUT:
![alt text](<Screenshot (55).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
