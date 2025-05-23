# Ex.06 Book Front Cover Page Design
## Date:15-05-2025

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
  <title>Geometric Template with Photo</title>
  <style>
    body {
      background-color: #555;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .template {
      width: 600px;
      height: 850px;
      background: white;
      position: relative;
      box-shadow: 0 0 15px rgba(0,0,0,0.2);
      overflow: hidden;
      font-family: Arial, sans-serif;
    }

    .shape1 {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 40%;
      background: #004080;
      clip-path: polygon(0 100%, 0 40%, 60% 40%, 100% 0, 100% 100%);
      z-index: 1;
    }

    .shape2 {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 50%;
      background: rgba(255, 255, 255, 0.1);
      clip-path: polygon(0 100%, 20% 50%, 100% 10%, 100% 100%);
      z-index: 2;
    }

    .shape3 {
      position: absolute;
      bottom: 0;
      width: 100%;
      height: 50%;
      background: rgba(255, 255, 255, 0.1);
      clip-path: polygon(0 100%, 30% 60%, 90% 30%, 100% 100%);
      z-index: 3;
    }

    .top-fade {
      position: absolute;
      top: 0;
      left: 0;
      width: 60%;
      height: 20%;
      background: linear-gradient(to right, rgba(0,0,0,0.05), transparent);
      clip-path: polygon(0 0, 100% 0, 50% 100%, 0 100%);
    }

    .top-text {
      position: absolute;
      top: 20px;
      left: 30px;
      font-size: 12px;
      color: #888;
      letter-spacing: 2px;
    }

    .center-text {
      position: absolute;
      top: 45%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      color: #004080;
      z-index: 4;
    }

    .center-text h1 {
      margin: 0;
      font-size: 26px;
    }

    .center-text p {
      font-size: 14px;
      letter-spacing: 4px;
    }

    .bottom-text {
      position: absolute;
      bottom: 30px;
      right: 30px;
      color: white;
      text-align: right;
      z-index: 4;
    }

    .bottom-text h4 {
      margin: 0;
      font-size: 14px;
    }

    .bottom-text p {
      margin: 5px 0 0;
      font-size: 10px;
      line-height: 1.3;
    }

    .profile-photo {
      position: absolute;
      bottom: 90px;
      right: 40px;
      width: 80px;
      height: 100px;
      object-fit: cover;
      border: 2px solid white;
      z-index: 5;
      background: white;
    }
  </style>
</head>
<body>
  <div class="template">
    <div class="shape1"></div>
    <div class="shape2"></div>
    <div class="shape3"></div>
    <div class="top-fade"></div>

    <div class="top-text">YOUR TEXT HERE</div>

    <div class="center-text">
      <h1>GEOMETRIC</h1>
      <p>TEMPLATE</p>
    </div>

    <div class="bottom-text">
      <h4>Lorem ipsum dolor sit amet</h4>
      <p>Enterprise user account capable non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </div>

    <!-- Profile photo -->
    <img src="my photo.jpg" alt="Profile" class="profile-photo">
  </div>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2025-05-20 220231.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
