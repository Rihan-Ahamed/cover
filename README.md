# Ex.06 Book Front Cover Page Design
## Date:5/05/2025

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #afc9e3; /* White background */
        }
        .book-cover {
            width: 500px;
            height: 700px;
            background: url('bookcover.jpg') center/cover no-repeat;
            border: 10px solid #edb785; /* Border color inspired by the image */
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            text-align: center;
            padding: 40px 20px;
            position: relative;
        }
        .title {
            font-size: 3rem;
            font-weight: bold;
            color: #fff;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin: 20px 0;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .subtitle {
            font-size: 1.2rem;
            color: #eae2e2;
            font-style: italic;
            margin: 10px 0 20px 0;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.7);
        }
        .author {
            font-size: 1.5rem;
            font-weight: bold;
            color: #eee8e8;
            margin-top: 30px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .quote {
            font-size: 1rem;
            color: #f0f0f0;
            margin: 20px 0;
            font-style: italic;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.7);
        }
        .decorative-line {
            height: 4px;
            width: 90%;
            margin: 20px auto;
            background: linear-gradient(90deg, #c7a585, #fff);
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="title">ON THE SHORTNESS OF LIFE</div>
        <div class="decorative-line"></div>
        <div class="subtitle">"LIFE IS LONG"</div>
        <div class="quote">IF YOU KNOW TO USE IT</div>
        <div class="author">By RIHAN AHAMED.S</div>
    </div>
</body>
</html>

~~~

## OUTPUT:
![alt text](<ex6/bookapp/static/Screenshot 2025-05-05 141050.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
