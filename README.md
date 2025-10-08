# Ex.06 Book Front Cover Page Design
## Date:22.09.2025

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
book.html

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>The Horizon of Silence — by Abhishek</title>
  <link rel="stylesheet" href="book.css">

</head>
<body>
  <div class="cover">
    <div>
      <h1>The Horizon of Silence</h1>
      <h2>On Time, Being, and the Spaces Between</h2>
    </div>

    <div class="quote">
      “Beyond words and noise, philosophy is found in the pause that lingers.”
    </div>

    <div class="author">By Abhishek </div>
  </div>
</body>
</html>


book.css


    :root{
      --accent: #D49A6A;
      --deep: #0E141B;
      --soft: #C3D1D6;
      --paper: #F3EFE9;
      --serif: "Georgia", serif;
      --sans: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial;
    }

    body{
      height:100vh;
      margin:0;
      display:flex;
      align-items:center;
      justify-content:center;
      background: radial-gradient(circle at 20% 30%, #1d2738, #0e141b 80%);
      font-family:var(--sans);
      color:var(--paper);
    }

    .cover{
      width:400px;
      height:600px;
      background: linear-gradient(135deg, #111922, #0a0f15);
      border-radius:12px;
      box-shadow: 0 25px 70px rgba(0,0,0,0.8);
      position:relative;
      display:flex;
      flex-direction:column;
      justify-content:space-between;
      padding:40px 30px;
      overflow:hidden;
    }

    .cover::before{
      content:"";
      position:absolute;
      inset:0;
      background: radial-gradient(circle at 70% 40%, rgba(212,154,106,0.25), transparent 70%);
      z-index:0;
    }

    h1{
      font-family:var(--serif);
      font-size:2.4rem;
      margin:0;
      position:relative;
      z-index:1;
      color:var(--paper);
      text-shadow:0 4px 20px rgba(0,0,0,0.5);
    }

    h2{
      font-size:1rem;
      font-style:italic;
      font-weight:400;
      margin-top:10px;
      position:relative;
      z-index:1;
      color:rgba(255,255,255,0.75);
    }

    .quote{
      position:relative;
      z-index:1;
      font-family:var(--serif);
      font-size:0.95rem;
      text-align:center;
      line-height:1.4;
      margin:20px 0;
      padding:15px;
      background:rgba(255,255,255,0.05);
      border-radius:8px;
    }

    .author{
      position:relative;
      z-index:1;
      text-align:right;
      font-weight:600;
      font-size:1.1rem;
      color:var(--accent);
    }
  


```

## OUTPUT:
![alt text](<Screenshot (21).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
