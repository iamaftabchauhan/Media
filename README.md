# Media
welcome to our website.
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>

    /* larege laptop */
@media only screen and (max-width: 1920px)and (min-width: 1600px)  {
  body {
    background-color:green;
    
  }
  p{
      color: gold;
  }
  h2{
      color: hotpink;
  }
}
/* For Laptop */
@media only screen and (max-width: 1440px)and (min-width: 1366px)  {
  body {
    background-color:green;
    
  }
  .main{
     
      width: 100%;
      height: 200px;

  }
  .logo{
    width: 33.3%;
      height: 200px; 
      background-color: lightcoral;
      float: left;
  }
  .content{
    width: 33.3%;
      height: 200px; 
      background-color: hotpink;
      float: left;
  }
  .right{
    width: 33.3%;
      height: 200px; 
      background-color: firebrick;float: left;
  }
}
/* for tab */
@media only screen and (max-width: 1024px)and (min-width: 768px)  {
  body {
    background-color:green;
    
  }
  p{
      color: gold;
  }
  h2{
      color: hotpink;
  }
}




/* mobile for landscap view  */
@media only screen and (max-width: 638px)and (min-width: 320px)  {
  body {
    background-color:khaki;
    
  }
  p{
      color: gold;
  }
  h2{
      color: hotpink;
  }
  .main{
      background-color: lawngreen;
      width: 100%;
      height: 200px;

  }
  .logo{
    width: 33.3%;
      height: 200px; 
      background-color: lightcoral;
      
  }
  .content{
    width: 33.3%;
      height: 200px; 
      background-color: green;
  }
  .right{
    width: 33.3%;
      height: 200px; 
      background-color: firebrick;
  }
}

/* mobile for potrate view  */
@media only screen and (max-width: 480px)and (min-width: 320px)  {
  body {
    background-color:khaki;
    
  }
  
  .logo{
    width: 100%;
      height: 200px; 
      background-color: lightcoral;
      
  }
  .content{
    width: 100%;
      height: 200px; 
      background-color: hotpink;
     
  }
  .right{
    width: 100%;
      height: 200px; 
      background-color: firebrick;
  }
}

</style>
</head>
<body>

<p>Resize the browser window. When the width of this document is 600 pixels or less, the background-color is "lightblue", otherwise it is "lightgreen".</p>
<h2>Lorem ipsum dolor sit amet.</h2>

<div class="main">
<div class="logo"></div>
<div class="content"></div>
<div class="right"></div>
</div>
</body>
</html>
