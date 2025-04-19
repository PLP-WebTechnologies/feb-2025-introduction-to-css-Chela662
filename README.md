<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1 id="main-heading">Welcome to My Stylish Page</h1>
  
  <p class="description">This paragraph has custom font, color, and spacing.</p>
  
  <img src="2.jpg">  class="styled-image">

  <div class="box">This is a styled box with margin, padding, and border.</div>
</body>
</html>
#.css
/* ID Selector */
#main-heading {
    color: darkblue;
    font-family: 'Georgia', serif;
    margin-bottom: 20px;
  }
  
  /* Class Selector */
  .description {
    font-family: 'Arial', sans-serif;
    color: #333;
    padding: 10px;
    line-height: 1.6;
  }
  
  /* Element Selector */
  img {
    width: 300px;
    border: 3px solid #555;
    margin: 20px 0;
    padding: 5px;
    display: block;
  }
  
  /* Another Class Selector */
  .box {
    background-color: #f0f0f0;
    padding: 15px;
    border: 2px dashed #999;
    margin-top: 30px;
    font-family: 'Courier New', monospace;
  }
  
