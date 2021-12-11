<!DOCTYPE html>
<html lang="en">
<head>
<title>Colour Palette</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="sample website.css">
  <style>
    * {
    box-sizing: border-box;
  }
  
  /* Style the body */
  body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
  }
  
  /* Header/logo Title */
  .header {
    padding: 80px;
    text-align: center;
    background: #1abc9c;
    color: white;
  }
  
  /* Increase the font size of the heading */
  .header h1 {
    font-size: 40px;
  }
  
  /* Sticky navbar - toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed). The sticky value is not supported in IE or Edge 15 and earlier versions. However, for these versions the navbar will inherit default position */
  .navbar {
    overflow: hidden;
    background-color: #333;
    position: sticky;
    position: -webkit-sticky;
    top: 0;
  }
  
  /* Style the navigation bar links */
  .navbar a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
  }
  
  
  /* Right-aligned link */
  .navbar a.right {
    float: right;
  }
  
  /* Change color on hover */
  .navbar a:hover {
    background-color: #ddd;
    color: black;
  }
  
  /* Active/current link */
  .navbar a.active {
    background-color: #666;
    color: white;
  }
  
  /* Column container */
  .row {  
    display: -ms-flexbox; /* IE10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE10 */
    flex-wrap: wrap;
  }
  
  /* Create two unequal columns that sits next to each other */
  /* Sidebar/left column */
  .side {
    -ms-flex: 30%; /* IE10 */
    flex: 30%;
    background-color: #f1f1f1;
    padding: 20px;
  }
  
  /* Main column */
  .main {   
    -ms-flex: 70%; /* IE10 */
    flex: 70%;
    background-color: white;
    padding: 20px;
  }
  
  /* Fake image, just for this example */
  .fakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 20px;
  }
  
  /* Footer */
  .footer {
    padding: 20px;
    text-align: center;
    background: #ddd;
  }
  
  /* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
  @media screen and (max-width: 700px) {
    .row {   
      flex-direction: column;
    }
  }
  
  /* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
  @media screen and (max-width: 400px) {
    .navbar a {
      float: none;
      width: 100%;
    }
  }
  <div class="parallax"></div>
    </style>
</head>
<body>

<div class="header">
  <h1>Colour Palette</h1>
  <p>“Every child is an artist. The problem is how to remain an artist once we grow up.” <br> – Pablo Picasso </p>
</div>

<div class="navbar">
  <a href="file:///C:/Users/Reception-1/Desktop/Anubhav%20School/sample%20website.html" class="active">Home</a>
  <a href="file:///C:/Users/Reception-1/Desktop/Anubhav%20School/Computer/forms1.html" target="blank_">Forms for online or offline classes. </a>
  <a href="file:///C:/Users/Reception-1/Desktop/Anubhav%20School/sample%20website%20part.html">Our videos of craft.</a>
  <a href="file:///C:/Users/Reception-1/Desktop/Anubhav%20School/summary.html" class="right">Drawing summary</a>
</div>

<div class="row">
  <div class="side">
    <h2>About Us</h2>
    <img src="data:image/jpeg;base64,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" alt="">
    <p>We all have suffered from lockdown caused due to pendamic corona virus so I advise you that if you live in Haridwar than only take offline classes. <center><br> Plz Be Aware And<br> Be Precautinal.</center></p>
    <h3>More Text</h3>
    <p>Lorem ipsum dolor sit ame.</p>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div><br>
    <div class="fakeimg" style="height:60px;">Image</div>
  </div>
  <div class="main">
    <h2>Deepkala Creativity</h2>
    <h5>Art, like morality, consists of drawing the line somewhere.</h5>
    <img src="data:image/png;base64,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">
    <p>We take classes online and offline we have form for it on the upper black strip written as "Forms for online or offline drawing classes."</p>
    <p>21st century education carries with it a mix of new challenges and promising tools. Our Arts and Crafts classes offers a flexible program, innovative techniques and fresh methodologies. But at the core of our mission, lies our commitment to providing an engaging, respectful and rewarding learning environment.
    <br><br>Explore our engaging and diverse course schedule, and get in touch with our team to schedule a free trial class.</p>
    <br>
</div>
</body>
</html>
