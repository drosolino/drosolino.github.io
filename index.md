<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="css/accordion.css" rel="stylesheet" type="text/css">
        <link href="css/slideshow.css" rel="stylesheet" type="text/css">
    </head>
    <body>
        <div class="slideshow-container">
            <div class="mySlides fade">
              <div class="numbertext">1 / 3</div>
              <img src="images/image1.jpg" style="width:100%">
              <div class="text">Caption Text</div>
            </div>
    
            <div class="mySlides fade">
              <div class="numbertext">2 / 3</div>
              <img src="images/image2.jpg" style="width:100%">
              <div class="text">Caption Two</div>
            </div>
    
            <div class="mySlides fade">
              <div class="numbertext">3 / 3</div>
              <img src="images/image3.jpg" style="width:100%">
              <div class="text">Caption Three</div>
            </div>
    
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
    
        </div>
          <br>
    
          <div style="text-align:center">
            <span class="dot" onclick="currentSlide(1)"></span> 
            <span class="dot" onclick="currentSlide(2)"></span> 
            <span class="dot" onclick="currentSlide(3)"></span> 
          </div>


        <h2>Accordion</h2>

        <button class="accordion">Section 1</button>
        <div class="panel">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>

        <button class="accordion">Section 2</button>
        <div class="panel">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>

        <button class="accordion">Section 3</button>
        <div class="panel">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>


        <script type="text/javascript" src="js/accordion.js"></script>
        <script type="text/javascript" src="js/slideshow.js"></script>
    </body>
</html>
