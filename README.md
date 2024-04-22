# Ex.06 Book Front Cover Page Design
## Date:22.04.24

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
<html>
    <head>
        <title>
            HTML page
        </title>
        <style>
img{
    height: 60%;
    width:25%;
    /* position: absolute;
    left:63%;
    top:64%; */
    float: right;
    /* opacity: 70%; */

}
h1{
    font-size: 400%;
}
p{font-size: 200%;

}       
.container{
    color: rgb(18, 18, 21);
    position: absolute;
    top: 10%;
    left: 30%;
    padding: 25px;
    background-image: url(bg.jpg);
    background-repeat: no-repeat;
    background-size: 100% 100%;
    color: rgb(3, 2, 2);
 
    height: 120%;
    width: 30%;
    background-color: aqua;
}

hr{
    color: rgb(18, 16, 12);
}
.center
{
    height: 20%;
    align-items: flex-end;
    display: flex;
    justify-content: space-between;
    padding: 25px;
}
.details
{
    height: 10%;
    align-items: center;
    display: flex;
    justify-content: space-between;
    padding: 25px;
}
#hr1
{
    width: 20%;
    margin-left: 0.2%;
    color: blue;
}


        </style>
    </head>
<body>
<div class="container">
    <h2> SEC INSIGHT</h2>
    <h1><br>Unlocking Solutions:<br> The Art of <br>Prompt Engineering
    </h1>
    <p>
    </p>
    <div class ="center">
        <p>        
        </p>  
        <br><br><br>  
        <img src="pic.jpg">
    </div>
    <hr>
    <div class="details">
        <p>JESU SMARTIA A</p>
        <p>SEC</p>
    </div>    
</div>    
</body>
</html>
```

## OUTPUT:

![Screenshot 2024-04-22 003434](https://github.com/jesu-smartia05/cover/assets/148514819/b33e516f-1ebc-4c02-85db-f680ef1b405d)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
