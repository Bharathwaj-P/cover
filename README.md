# Ex.06 Book Front Cover Page Design
## Date:06-10-2025

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
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="link.css">
        <title>COVER</title>
        
    </head>
    <body align="center">
        <div class="name"><h1 align="certer">Bharathwaj (25018022)</h1></div>
        <div class="Bharath">
            <div class="page1">
                <h1>SEC INSIGHT</h1>
                <hr>
            </div>
            <div class="page2">
                <p>FUNDAMENTAL OF WEB DEVELOPEMENT</p>
            </div>
            <br>
            <div class="page3">
                <h2>JAVASCRIPTS AND HTML WITH CSS</h2> 
                <h3>INTRODUCTION SQLLITE</h3>
            </div>
            <div class="picture">
                <img src="WhatsApp Image 2025-10-06 at 20.50.59_63ebea0b.jpg">
            </div>
            <div class="page4">
                <h2>GRAND EDITION</h2>
                <hr>
                <h2 align="center">P.Bharathwaj</h2>
            </div>
            
        </div>
    </body>
</html>

link.css

.name{
    text-align:center;
    position: relative;
    right:50px;
}




body{
    background-color:rgb(43, 122, 226) ;
    font-family:blueCarbria,Chchin,Georgia,Time,'Time New Roman',serif;
    font-style:oblique;
    color:rgb(1, 14, 1);
}
.Bharath{
    background-image:url(Screenshot2025-10-06-205813.png);
    background-clip:border-box;
    background-position-x:right ;
    background-size:cover;
    height: 800px;
    width:600px;
    position:relative;
    left: 400px;
}
.page1{
    margin:auto;
    border:solid 10px rgb(155, 173, 127);

}
.page2{
    font-size:50px;
    text-align:center;
    position:relative;
    top:50px;

}
.page3{
    position:relative;
    left:15px;
    font-size: 20px;

}

.picture{
    width: 150px; 
    height:150px;      
    position: relative;
    top: 70px;
    left:300px;
    border: 2px solid rgb(255, 34, 0);
    background: rgb(104, 17, 17);
    overflow: hidden;
}

.picture img{
    width:100%;
    height:100%;
    object-fit:cover;
}
.page4{
    position:relative;
    top:50px;
    left:5px;
    font-weight: bold;
}
.page5{
    position:fixed;
    font-family: Georgia, 'Times New Roman', Times, serif;
    top:50px;
    left:20px;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-10-06 212356.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
