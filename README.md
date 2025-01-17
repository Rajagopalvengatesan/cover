# Ex.06 Book Front Cover Page Design
## Date:01-12-2023

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
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <style type="text/css">
            .frontpage{
                width: 650px;
                height: 1000px;
                color: black;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(book5.png);
                background-size: cover; 
            }

            .insight{
                font-size: large;
                color: white;

            }

            .hrstyle {
                width: 90px;

            }

            .author {
                display: inline;
                position: relative;
                color: yellow;
                top: 525px;
                font-family: Georgia;
                font-size: medium; 
            }
                .booktitle{
                font-family: 'Courier New', Courier, monospace;
                font-size: xx-large;
                text-align: center;
                position: relative;
                top:200px; 
                }

                .booksubtitle{
                font-family: 'Courier New', Courier, monospace;
                font-size: x-large;
                text-align: center;
                position: relative;
                top: 160px; 
                }

                .id{
                    width: 550px;
                    position: relative;
                    top: 525px;
                }

                .pub{
                    font-size: medium;
                    position: relative;
                    top: 500px;
                    left: 500px;

                }

                .ed {
                    color: green;
                    font-size: medium;
                    font-family: Verdana;
                    position: relative;
                    top: 400px;

                    }

                .subtitle{
                    font-family: Tahoma;
                    font-size: medium;
                    position: relative;
                    top: 150px;

                    }

                .mypic {
                    position: relative;
                    top: 460px;
                    left: 500px;
                    width: 100px;
                    height: 100px;
                    background-size: cover;

                    }

        </style>
        <title>
            BOOK COVER PAGE
        </title>
    </head>
    <body>
        <div class="frontpage">
            <div class=""insight">
            SEC INSIGHT 
            </div>
            <div class="hrstyle">
            <hr style="color: yellow">

            </div>
            <div class="booktitle">
            <h1>
               HTML Mastery: 
            </h1>
            </div>
            <div class="booksubtitle">
                <h2>
                    Building Modern and Responsive Web Experiences
                </h2>
            </div>
            <div class="subtitle">
           Unleashing the full potential of HTML5 for Seamless and Accessible Design
            </div>
            <div class="mypic">
            <img src="A 71066-.jpg" width="130" height="145" alt="">
            </div>
        <div class="id">
            <hr style="color: orange;">

        </div>
        <div class="author">
            <p><b>RAJAGOPAL V</b></p>
        </div>
        <div class="pub">
           <h3> <b>SEC</b></h3>
        </div>
        <div class="ed">
            <b>Third Edition</b>
            </div>

       
        </div>
    </body>
</html>

```

## OUTPUT:
![Alt text](<Screenshot (44).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
