# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the Github repository and create a Django admin interface.
### Step 2:
Write HTML and CSS Code for designing book cover page and execute them.

## Code:
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Shadows Into Light', cursive;
            background-image: url("/static/images/iot image.jpg");
            background-size: cover;
        }
            

        .insight{
            color:yellowgreen;

        }

        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(222, 222, 222);
            top:190px;
            
            font-family: 'Shadows Into Light', cursive;
            font-size: medium;
        }
        .booktitle{
            
            font-family: 'Smokum', cursive;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:orange;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
            font-family: 'Shadows Into Light', cursive;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        
        </style>
        <title>Book Cover Page</title>
    </head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Smokum&display=swap" rel="stylesheet">
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(251, 243, 244);">
            </div>
            <div class="booktitle">
                <h1>COOLEST CAREERS IN IOT </h1></div>
            <div class="subtitle">
                1.IOT Developer
            </div>
            <div class="subtitle">
                2.IOT Architect
            </div>
            <div class="subtitle">
                3.IOT Embedded System Designer
            </div>
            <div class="subtitle">
                4.IOT Solution Engineer
            </div>
            <div class="subtitle">
                5.IOT Consultant
            </div>
            <div class="mypic">
                <img src="/static/images/azeem munnar.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(182, 160, 164);">
            </div>
            <div class="author">
               <p><b>MOHAMED AZEEM N</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>First Edition</b>
            </div>
        </div>
    </body>
</html>

## Output:

![Screenshot (69)](https://github.com/mohamedazeem33/cover-page-design/assets/121040764/e64d1004-d203-4645-89e6-d6dcbd1a08f9)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
