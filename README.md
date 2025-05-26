# Ex.06 Book Front Cover Page Design
## Date:

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
<html>

<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color:white;
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color:black;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
      margin: 50px auto;
      position: relative;
    }
    
    .book-cover .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 15px;
      font-weight: bold;
      color: azure;
    }

    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 10px;
      width: 80px;
    }
    .book-cover .title1 {
      position: absolute;
      top: 180px;
      left: 30px;
      font-size: 32px;
      font-weight: bold;
      color:  white;
    }
    .book-cover .title2 {
      position: absolute;
      top: 260px;
      left: 30px;
      font-size: 22px;
      font-weight: bold;
      color:  white;
    }

    .book-cover .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 18px;
      font-weight: bold;
      color:  white;
    }
    .book-cover .subtitle2 {
      position: absolute;
      top: 530px;
      left: 20px;
      font-size: 10px;
      font-weight: bold;
      color: white;
    }
    .book-cover .subtitle3 {
      position: absolute;
      top: 560px;
      left: 20px;
      font-size: 10px;
      font-weight: bold;
      color: white;
    }
    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }
    .book-cover .line3
    {
      position: absolute;
      bottom:38px;
      left: 20px;
      width: 115px;
    }


    .book-cover .author {
      position: absolute;
      bottom: 25px;
      left: 20px;
      font-size: 18px;
      color: whitesmoke;
    }

    .book-cover .number {
      position: absolute;
      bottom: 5px;
      left: 20px;
      font-size: 18px;
      color: white;
    }

    .book-cover .end {
      position: absolute;
      bottom: 5px;
      right: 50px;
      font-size: 18px;
      color: white;
    }
    .book-cover .mypic
    {
      position: relative;
      top:550px;
      left: 370px;
      width : 8px;
      height: 8px;
      background-size:fit;
    }


    .book-cover .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="c:\Users\admin\Downloads\book.html" alt="Book Cover Image" class="image">
    <div class="insight"> Think and Grow Rich</div>
    <div class="line1"><hr style="color:rgb(48, 14, 110)"></div>
    <div class="title1"> The Magic of thinking big</div>
    <div class="title2">EMBRACING INNOVATION IN A CONNECTED WORLD</div>
    <div class="subtitle1"> How an abundant future is possible for you</div>
    <div class="line2"><hr style="color:rgb(9, 64, 69)"></div>
    <div class="subtitle2">We talk on principal, but act on motivation</div>
    <div class="subtitle3">BUILDING BRIDGES TO THE FUTURE</div>
    <div class="line3"><hr style="color:rgba(255, 235, 205, 0.845)"></div>
    <div class="mypic"><img src="c:\Users\admin\Downloads\photo.jpeg"width="120" height="120" ></div>
    <div class="end">SEC</div>
    <div class="number">9645316123</div>

    <div class="author">RAMYA P</div>

  </div>
</body>

</html>

```

## OUTPUT:
![Screenshot 2025-05-26 090127](https://github.com/user-attachments/assets/05c495ed-2039-48b9-a341-49726c9643a2)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
