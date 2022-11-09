# HTML

## Step-1

In the first step we are initialize the structure of our website.

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>workshop-website</title>
</head>
<body>
    
</body>
</html>

```
## Step-2

Inside the `body` element write the following code.

- `<div>` tag is used as a container for HTML elements
- `<img>` attribute is used for inserting images in our web page.
- `src` attribute specifies the URL of the image.
- `span` is an inline container used to mark up a part of a text, or a part of a document.

``` html
    <!--Top container-->
    <div class="top-container">
        <img class="top-cloud" src="images/cloud.png" alt="cloud">
        <h1>I'm Octocat</h1>
        <h2>a <span class="pro">pro</span>gramer</h2>
        <img class="bottom-cloud" src="images/cloud.png" alt="cloud">
        <img src="images/mountain.png" alt="mountain">
    </div>
 
```

## Step-3

After writing the above HTML syntax coppy the below code and paste it below. We are adding some content to our web page.

``` html
<!--Middel container-->
    <div class="middle-container">
        <div class="profile">
          <img src="images/OIP - Edited.png" alt="octacat" width="200px" height="200px">
          <h2>Hello.</h2>
          <p class="intro">Lorem ipsum dolor sit amet, vitae volutpat, dui conubia, dolor urna. Non auctor, montes nulla distinctio.</p>
        </div>
        <hr>
        <div class="skills">
          <h2>My Skills.</h2>
          <div class="skill-row">
            <img class="code-img" src="images/computer.png" alt=""> <!-- width="100px" height="100px">   -->
            <h3>Lorem & Ipsum</h3>
            <p>Lorem ipsum dolor sit amet, quis in duis, iaculis id felis. Consectetuer vestibulum, nunc urna lectus, erat ligula. Hendrerit nam, lectus ante, ut lorem eros.</p>
          </div>
          <div class="skill-row">
            <img class="chilli" src="images/chillies.png" alt="">
            <h3>Lorem Ipsum Dolor</h3>
            <p>Lorem ipsum dolor sit amet, mauris sed consectetuer. Etiam et eu, bibendum interdum, lacus quis mauris. Curabitur wisi, quisque vel eu, rutrum nam.</p>
          </div>
        </div>
        <hr>
        <div class="contact-me">
          <h2>Get In Touch</h2>
          <h3>Lorem ipsum dolor sit amet, non elit.</h3>
          <p class="contact-message">Lorem ipsum dolor sit amet, in quis, aenean amet. Phasellus sodales, tellus donec dui, ornare erat.</p>
          <a class="btn" href="mailto:name@email.com">CONTACT ME</a>
        </div>
      </div>
      
 ```
 
 ## Step-4
 
At the bottom add the colloing HTML syntax.
 
 ``` html
       <!--bottom container-->
      <div class="bottom-container">
        <a class="footer-link" href="https://www.linkedin.com/">LinkedIn</a>
        <a class="footer-link" href="https://twitter.com/">Twitter</a>
        <a class="footer-link" href="https://www.appbrewery.co/">Website</a>
        <p class="coppyright">© Name Surname.</p>
      </div> 
```

## Step-5

Add the following HTML syntax in the `<head>`

- In this we are attaching CSS file to modify our website.
- We are adding font link.( We add font link so that if the the system dosent have pre installed font style, the browser will automatically download the font style).

``` html
    <link rel="stylesheet" href="CSS/styles.css">
    <link rel="icon" href="favicon.ico?v=2">        <!--the broweser maight cast previous version so it maight not work in that case we use this -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather&family=Montserrat&family=Nunito:wght@200;300&family=Sacramento&display=swap" rel="stylesheet">
    
```
