# Ex.06 Book Front Cover Page Design
## Date:28/04/2025

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
bookcover.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(6, 6, 6);
      border: 2px solid #000000;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(102, 100, 100, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #fffdfd;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
      color: #fffdfd;
    }

    .image {
      flex: 1;
      background: url('https://upload.wikimedia.org/wikipedia/commons/6/65/Simple_flowers_black_line_art.png') center/contain no-repeat;
      margin: 30px 0;
    }

    .author {
      font-size: 20px;
      text-align: center;
      color: #ffffff;
      margin-top: -50px;
    }

    .line {
      height: 2px;
      background: #ffffff;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">THE REAL LEGEND SR STORY</div>
      <div class="line"></div>
      <div class="subtitle">Rules Breaker</div>
    </div>
    <div class="image">
        <img src="Screenshot 2025-04-28 112531.png" length="10%" width="100%">
    </div>
    <div class="author">KRISH SR</div>
  </div>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot (18).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
