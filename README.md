��# barb

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, intial scale=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>barber shop </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <section id="banner">
        <div class="banner-text">
            <h1>HAIR STUDIO</h1>
            <p>Style Your Hair Is Style Your Life</p>
            <div class="banner-btn">
                <a href="#"><span></span>Find Out</a>
                <a href="#"><span></span>Read More</a>

            </div>
        </div>
    </section>
    <div id="sideNav">
        <nav>
            <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">FEATURES</a></li>
            <li><a href="#">SERVICES</a></li>
            <li><a href="#">TESTIMONIALS</a></li>
            <li><a href="#">MEET US</a></li>
        </ul>
        </nav>
    </div>
    <div id="menuBtn">
        <img src="images/menu.png"  id="menu" alt="">
    </div>

<section id="features">
    <div class="title-text">
        <p>FEATURES</p>
        <h1>Why Choose Use</h1>
    </div>
    <div class="features-box">
        <h1>Experienced staff</h1>
    </div>
    <div class="features-img">
        <img src="images/img3.jpg" alt="">
    </div>
</section>









    <script>
        var menuBtn = document.getElementById("menuBtn")
        var sideNav = document.getElementById("sideNav")
        var menu = document.getElementById("menu")
       
        menuBtn.onclick = function(){
            if(sideNav.style.right == "-250px"){
                sideNav.style.right = "0";
                menu.src = "images/menu.png";
            }
            else{
                sideNav.style.right = "-250";
                menu.src = "images/menu.png";
                menu.src = "images/menu.png";

            }
        }

    </script>

    
</body>
</html>
