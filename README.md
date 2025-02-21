# Ex.06 Book Front Cover Page Design
## Date:30-11-2023

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
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 970px;
            height: 570px;
            color:rgb(128, 0, 11);
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(./book.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(226, 101, 43);

        }

        
        .hrstyle{
            width:170px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(205, 50, 135);
            top:270px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 25px;
        
        }
        .id {
            width:950px;
            position: relative;
            top:270px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:240px;
            left:860px;
        }
        .ed{
            color: red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:18px;
        }
        .mypic{
            position: relative;
            top: 200px;
            left: 750px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:grey">
            </div>
            <div class="booktitle">
                <h1>Web Development: Fundamentals of Robotics</h1></div>
            <div class="subtitle">
                Future of Robotics                
            </div>
            <div class="mypic">
                <img src="Myphoto.jpg"  width="200" height="180" alt=" ">
            </div>
            <div class="id">
                <hr style="color: black;">
            </div>
            <div class="author">
               <p><b>Yuva Sree M</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>

```


##OUTPUT:
![Alt text](<Screenshot (30).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
