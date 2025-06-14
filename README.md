# Ex.06 Book Front Cover Page Design
## Date:20.05.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <title>ART OF PATIENCE </title>
    <link rel="stylesheet" href="{% static 'css/index.css' %}">
    <style>
        body {
            color: rgb(10, 0, 0);
            font-family: Helvetica, sans-serif;
            background-color: #333;
        }

        .book {
            width: 726px;
            height: 891px;
            margin: auto;
            position: relative;
            background-image: url("pp.jpg");
            background-repeat: no-repeat;
            background-size: cover;
            background-position: bottom 0px center;
        }

        h1 {
            font-size: 70px;
            margin: 60px;
            margin-bottom: 0px;
        }

        h3 {
            margin: 0px 0px 90px 60px;
            position: absolute;
            bottom: 0px;
            font-size: xx-large;
            font-weight: 10px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            color: rgb(0, 0, 0);
        }

        h4 {
            font-size: 20px;
            margin: 60px;
            margin-top: 10px;
            width: 430px;
        }

        #top {
            border-bottom: 2px solid white;
            padding: 100px 0px 5px 30px;
        }

        footer {
            position: absolute;
            bottom: 10px;
            border-top: 2px solid black;
            padding-top: 0px;
            width: 726px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }

        .photo {
            position: relative;
            top: 170px;
            left: 550px;
            width: 120px;
            height: 120px;
            background-size: cover;
        }

        #HASH {
            display: flex;
            justify-content: space-between;
        }

        #HASH span {
            margin: 10px 0px 20px 60px;
            font-size: xx-large;
            font-weight: bold;
        }

        #end {
            padding-right: 60px;
        }
    </style>
</head>
<body>
    <section class="book">
        <br><br>
        <span id="top">MENTAL GROWTH</span>
        <h1>ART OF PATIENCE</h1>
        <h4>"NURTURING CALMNESS AND PEACEFULNESS.</h4>
        <h3>SECOND Edition</h3>
        <footer>
            <div id="HASH" class="blue-msg">
                <span>DANISH SAMUEL M</span>
                <span id="end"><u>2025- SEC</u></span>
            </div>
        </footer>
        <div class="photo">
            <img src="image 34.jpeg" width="150" height="170" alt="">
        </div>
    </section>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-20 232601-1.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
