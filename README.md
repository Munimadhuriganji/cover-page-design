# cover-page-design
## AIM:
to develop a website to display the cover page design of a book

Design Steps:
Step 1:
Clone the GitHub repository and create a Django admin interface.

Step 2:
Write HTML and CSS code for designing the book cover page and execute them.

Code:
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: red;
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: linear-gradient(black, silver), url('../images/back.jpg');
            background-size: cover;
        }

        .insight{
            color: brown;

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: white;
            display: inline;
            position: relative;
            color: red;
            top: 190px;

            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .id{
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub{
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }
        .ed{
            color: blue;
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 85px;

        }
        .subtile{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
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
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1>
            </div>
            <div class="subtitle">
                HTML and CSS Combined with Dajngo Architechture
            </div>
            <div class="mypic">
                <img src="/static/images/mine.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>madhuri</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Thirteenth Edition</b>
            </div>
        </div>
    </body>
</html>
Output:
![image](https://github.com/Munimadhuriganji/cover-page-design/assets/138849444/092ae645-360f-4944-be9c-c693c93a7c5a)


HTML Validator:


Result:
The program for designing book cover using HTML and CSS is executed succesfully.
To develop a website to display the cover page design of a book


