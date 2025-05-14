# Ex.06 Book Front Cover Page Design
## Date:09-05-2025

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
  <meta charset="UTF-8">
  <title>FUNDAMENTAL OF WEB APPLICATION</title>
  <style>
    body {
      margin: 0;
      color: whitesmoke;
      font-family: Helvetica, sans-serif;
    }

    .book {
      width: 726px;
      height: 891px;
      margin: auto;
      position: relative;
     background: url("book.jpg") no-repeat center center; 
      background-size: cover;
    }

    .header-line {
      border-bottom: 2px solid white;
      padding: 100px 0 5px 30px;
      font-size: 18px;
      font-weight: bold;
    }

    .title {
      font-size: 70px;
      margin: 20px 60px 0;
    }

    .subtitle {
      font-size: 25px;
      margin: 10px 60px;
      width: 430px;
      color: rgb(184, 227, 227);
    }

    .edition {
      position: absolute;
      bottom: 70px;
      margin-left: 70px;
      font-size: xX-large;
      font-family: Verdana, sans-serif;
      font-weight: bold;
    }

    .photo {
        position: absolute;
        bottom: 10px;   /* Distance from bottom */
        right: 30px;     /* Distance from left */
        width: 140px;
        height: 150px;
        border: 2px solid white;
         border-radius: 10px;
        overflow: hidden;
        margin-bottom: 80px;
    }


    .photo img {
      width: 100%;
      height: 100%;
      object-fit:fill;
    }

    .footer {
      position: absolute;
      bottom: 20px;
      width: 100%;
      border-top: 2px solid black;
      font-family: 'Gill Sans', Calibri, sans-serif;
    }

    .footer-content {
      display: flex;
      justify-content: space-between;
      padding: 0 70px;
    }

    .footer-content span {
      font-size:x-large;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <section class="book">
    <div class="header-line">EXPERT INSIGHT</div>
    <h1 class="title">FUNDAMENTAL OF WEB APPLICATION</h1>
    <h4 class="subtitle">Frontend Development, Backend Development and  Database Management</h4>
    <h3 class="edition">  THIRD Edition</h3>
    <h3> ----------------------------------------------------</h3>

    <footer class="footer">
      <div class="footer-content">
        <span>GOGINENI BIDHISHA </span>
        <span><u>SEC</u></span>
      </div>
    </footer>

    <div class="photo">
      <img src="MYPHOTO.png" alt="Author Photo">
    </div>
   
  </section>

</body>
</html>

```

## OUTPUT:
![Screenshot 2025-05-09 151422](https://github.com/user-attachments/assets/4e15a0c8-4d31-4ebe-b4ae-f021daed4290)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
