# Ex09 Event Registration Web Application
## Date:19-12-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Sheet 1
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="logo" src="img/logo-1.png" />
      <img class="image" src="img/image-1.png" />
      <div class="text-wrapper">WORLD BLOOD DONOR DAY</div>
      <div class="div">-JUNE 14TH</div>
    </div>
  </body>
</html>

Global css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

Style css
.android-medium {
  background-color: #ff0202a8;
  width: 100%;
  min-width: 747px;
  min-height: 896px;
  position: relative;
}

.android-medium .logo {
  position: absolute;
  top: 28px;
  left: 23px;
  width: 702px;
  height: 106px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-medium .image {
  position: absolute;
  top: 185px;
  left: 256px;
  width: 236px;
  height: 371px;
  aspect-ratio: 0.63;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 586px;
  left: 91px;
  width: 565px;
  font-family: "Josefin Sans-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 665px;
  left: 519px;
  width: 206px;
  font-family: "Josefin Sans-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


sheet 2
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium"><img class="image" src="img/image-2.png" /></div>
  </body>
</html>

globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css
.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  display: flex;
}

.android-medium .image {
  width: 700px;
  height: 840px;
  aspect-ratio: 1;
  object-fit: cover;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 144138.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
