# Ex.06 Book Front Cover Page Design
## Date: 1.05.2025

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
  <title>Book Cover</title>
  <style>
    body {
  margin: 0;
  padding: 0;
  background: #3a526c;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  font-family: 'Georgia', serif;
}

.book-cover {
  width: 400px;
  height: 600px;
  background: url('https://i.pinimg.com/736x/cd/1c/0c/cd1c0c109e2c9c084b7a25be5eab1885.jpg') center/cover;
  border: 5px solid #333;
  border-radius: 12px;
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
  color: #fff;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 30px 20px;
  text-align: center;
}

.book-title {
  font-size: 2em;
  font-weight: bold;
  margin-top: -150px;
  z-index: 1;
}

.subtitle {
  font-size: 1.3em;
  font-style: italic;
  margin-top: 200px;
}

.sight,
.qut {
  font-size: 1em;
  font-style: italic;
  margin: 10px 0;
}

.sight {
  position: relative;
  right: 150px;
}

.author {
  font-size: 1em;
  align-self: flex-end;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.passport-photo {
  position: absolute;
  bottom: 120px;
  left: 560px;
  width: 80px;
  height: 100px;
  object-fit: cover;
  border: 2px solid white;
  border-radius: 6px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
}

  </style>
</head>
<body>

  <div class="book-cover">
    <div class="sight">In Sight of Sec</div>
    <div class="cover-img"></div>
    <div class="book-title">The Great Journey</div>
    <div class="subtitle">Its how you Finished</div>
    <div class="qut">Nothing is possible if you think its impossible</div>
    <img class="passport-photo" src="C:\Users\admin\Documents\Personal Details\Naghul PP.jpg" alt="Passport Photo">

    <div class="author">By Naghul Varshan N</div>
  </div>

</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/c8fae7d7-9cea-4d9b-aa2c-a1ee84445a84)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
