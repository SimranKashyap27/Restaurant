# Restaurant
It is Restaurant website in which we can order food. I have used html, CSS and Bootstrap.

<!DOCTYPE HTML>
<html lang="en">
<head>
        <title>Bon Voyage- Restaurant</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta charset="UTF-8">
<link href="https://fonts.googleapis.com/css?family=Bitter|Dancing+Script|Fira+Sans|Open+Sans|Gloria+Hallelujah|M+PLUS+1p|Lato|Josefin+Slab|Istok+Web|Indie+Flower|Montserrat|Raleway|Amatic+SC|Caveat|Dancing+Script|Indie+Flower|Kalam|Shadows+Into+Light|Nothing+You+Could+Do&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
 
</head>

<style>


/* ---------------------------------
1. PRIMARY STYLES
--------------------------------- */

html { font-size: 100%; overflow-x: hidden; width: 100%; margin: 0px; padding: 0px;}

body { font-size: 14px; font-family: 'Open Sans', sans-serif; width: 100%; height: 100%; margin: 0; font-weight: 400;
         word-wrap: break-word; overflow-x: hidden; color: #333; }



h1, h2, h3, .font-beyond { font-family:'Beyond The Mountains','Nothing You Could Do', sans-serif; }

p { line-height: 1.7; font-size: 1.5em; font-weight: 400; color: #555; }

h1 { font-size: 7.5em; line-height: 1.4; }

h2 { font-size: 4em; line-height: 1.4; }

h3 { font-size: 3em; }

h4 {   font-size: 1.8em; }

h5 { font-size: 1.3em; }

h6 {  font-size: .95em; letter-spacing: 1px; }

a, button { display: inline-block; text-decoration: none; color: inherit; line-height: 1.3; -webkit-transition: all .10s ease-in-out; transition: all .10s ease-in-out;}

a:focus, a:active, a:hover,
button:focus, button:active, button:hover,
a b.light-color:hover { text-decoration: none; color: #EF0031;}

b {  font-weight: 700; }

img { width: 100%;}

li { list-style: none; display: inline-block; line-height: 1.6; font-size: 1.1em; }

span { display: inline-block; }

button { outline: 0; border: 0; background: none; cursor: pointer; }

.icon { font-size: 1.1em;display: inline-block;line-height: inherit; }


/* ---------------------------------
3. HEADER
--------------------------------- */

header {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        text-align: center;
        z-index: 1;
        padding: 25px 0;
        font-weight: 600;
        color: #fff;
     
}

header .logo {
        float: left;
        height: 70px;
}

header .logo img {
        height: 100%;
        width: auto;
}

header ul.main-menu > li > a {
        height: 100%;
        line-height: 70px;
        padding: 0px 15px;
}



section {
        padding: 100px 0 70px;
}

.heading {
        position: relative;
        text-align: center;
        margin-bottom: 70px;
}

.heading-img {
        height: auto;
        width: 40px;
        margin-bottom: 20px;
}


/*ICONS*/

.icon-gradient{ 
display: block; 
height: 80px; 
width: 80px;  
margin-left:90px;
 }



/* ALIGNMENT */

.float-left {float: left !important;}

.float-right { float: right !important;}

.center-text { text-align: center!important; }

.left-text { text-align: left !important; }

.right-text { text-align: right !important;}







/* MENU-BORDER */

.brdr-b-primary{ border-bottom: 2px solid #EF0031; }
.food-menu{ 

}
.food-menu.active{
 opacity: 0; 
display: block!important; 
animation: full-opacity-anim .3s forwards ;
}


/*SELECTION*/

ul.selecton{ text-align: center;  font-size: 1.2em;  }

ul.selecton li > a{ padding: 15px 30px;   }

ul.selecton li:hover a,
ul.selecton li a.active{ 
border-radius: 3px 3px 0 0;
 background: #EF0031; 
color: #FFFFFF;  }


@keyframes full-opacity-anim{
        100%{ opacity: 1; }
}




.color-light{ color: #cccccc; }

.semi-black{ color: #666666; }



.section1{
background-image:linear-gradient(rgb(0,0,0,0.5),rgb(0,0,0,0.5)),url(bg-14.jpg);
height:800px;
position:relative;
margin-top:0 ;
}
.div1{
margin-top:17%;
color:white;
}
.section3{
color:white;
position:relative;
background-image:linear-gradient(rgb(0,0,0,0.7),rgb(0,0,0,0.9)),url(bg-15.jpg);
repeat:no-repeat; 
background-size: cover; 
position: relative; 
z-index: 1;
}
.btn1{
border: 1px solid #DC143C;
padding:15px 30px 15px 30px;
color:#DC143C;
background-color:transparent;
color:#fff;
}
.btn1:hover{
color:#fff;
background-color:#DC143C;
}
.a1{
color:#DC143C;
}
.a1:hover{
color:#fff;
}
.menu_pic_left{
height:90px;
width:90px;
float:left;
margin:20px;
}
.menu_pic_right{
height:90px;
width:90px;
float:right;
}
.link{
text-decoration:none;
font-size:16px;
font-family: mountainsre;
color:white;
text-align:right;
margin:20px 15px 15px 20px;
}

.mb-10{
margin:10px;
}
.pr-70{
padding-right:70px;}

.mb-10 {
        margin-bottom: 10px !important;
}
.color-primary {
        color: #EF0031;
}
.mb-30{
margin-bottom:30px;
}
.mt-5{
margin-top:5px;
}
.mt-5{
margin-top:5px;
}
.mt-20{
margin-top:20px;
}
.pb-50{
padding-bottom:50px;}
.pt-70{
padding-top:70px;
}
.font-9 { font-size: .9em; }
.mt-50 {
margin-top:50px;
}

.heading1{
margin-top:30px;
margin-bottom;
}

.footer_area {
  background: #000;
  height:20vh;
  margin-bottom:0;
  padding-top:50px;
  margin-top:10%;
 }


.ab_widget p {
  font-size: 14px;
  line-height: 24px;
  font-family: "Roboto", sans-serif;
  color: #777777;
  margin-bottom: 30px; }
  .ab_widget p a {
    color: #fa333f; }
  .ab_widget p + p {
    margin-bottom: 0px; }

.social_widget{
  
  font-family: "Roboto", sans-serif;
  color: #777777;
  margin: 0 0 0 16%;
   }

.social_widget .list li {
  padding-right:30px;
 display: inline-block;

  }

  .social_widget .list li a {
    color: #cccccc;
    font-size: 25px;
    transition: all 300ms linear 0s; 
 }
  
  .social_widget .list li:hover a {
    color: #fa333f; }


.center-text { text-align: center!important; }

.title1{
float:left;
margin:3px 0 0 20px;

}
</style>


<body>

<header>
 <ul class="main-menu" id="main-menu">
                        <h3 class="title1">Bon Voyage</h3>
                        <li><a href="index.html">HOME</a></li>
                        <li><a href="destination.html">DESTINATION</a></li>
                        <li><a href="hotel.html">HOTEL</a></li>
                        <li><a href="restaurant.html">RESTAURANT</a></li>
                        <li><a href="#menu">MENU</a></li>
                        <li><a href="#services">SERVICES</a></li>
                        <li><a href="#contact">CONTACT</a></li>
                </ul>
       
</header>


<section class="section1">   
        <div class="container">
                
                        <div class="center-text div1">

                                <h5><b>BEST IN TOWN</b></h5>
                                <h1 class="heading1">Restaurant</h1>
                                
                        </div>
                
        </div><!-- container -->
</section>


<section class="story-area left-text center-sm-text pos-relative section2">
        <div class="container">
                <div class="heading">
                        <img class="heading-img" src="heading_logo.png" alt="">
                        <h2>Our Story</h2>
                </div>

                <div class="row">
                        <div class="col-md-12">
                                <p class="mb-30">Eating is an agricultural act and The Perennial is part of a larger movement to make delicious food part of the climate solution.
 At the restaurant, we are creating a market for climate beneficial ingredients and our non-profits are working to make restaurants part of the climate solution. We are committed to uniting fresh, locally grown produce with farm-raised and wild-caught seafood to make the freshest dishes you’ll find anywhere. 
Our signature raw bar offers a variety of Rhode Island oysters, crisp cherrystones, littleneck clams, and jumbo shrimp. </p>
                        </div><!-- col-md-6 -->

                       
                </div><!-- row -->
        </div><!-- container -->
</section>


<section class="section3" id="best-seller">
      
       
        <div class="container">
                <div class="heading">
                        <img class="heading-img" src="heading_logo.png" alt="">
                        <h2>Best Sellers</h2>
                </div>

                <div class="row">
                      

                        <div class="col-lg-3 col-md-4  col-sm-6">
                                <div class="center-text mb-30">
                                        <div class="pos-relative"><img src="dishes_5.jpg" alt=""></div>
                                        <h5 class="mt-20">Pizza Margherita</h5>
                                        <h4 class="mt-5"><b>$11.90</b></h4>
                                        <h6 class="mt-20"><button class="btn1"><a href="#menu" class="a1"><b>Order Now</b></a></button></h6>
                                </div><!--text-center-->
                        </div><!-- col-md-3 -->

                        <div class="col-lg-3 col-md-4  col-sm-6 ">
                                <div class="center-text mb-30">
                                        <div class="pos-relative"><img src="dishes_1.jpg" alt=""></div>
                                        <h5 class="mt-20">Pizza Margherita</h5>
                                        <h4 class="mt-5"><b>$11.90</b></h4>
                                         <h6 class="mt-20"><button class="btn1"><a href="#menu" class="a1"><b>Order Now</b></a></button></h6>
                                </div><!--text-center-->
                        </div><!-- col-md-3 -->

                        

                        <div class="col-lg-3 col-md-4  col-sm-6 ">
                                <div class="center-text mb-30">
                                        <div class="pos-relative"><img src="dishes_2.jpg" alt=""></div>
                                        <h5 class="mt-20">Pizza Margherita</h5>
                                        <h4 class="mt-5"><b>$11.90</b></h4>
                                        <h6 class="mt-20"><button class="btn1"><a href="#menu" class="a1"><b>Order Now</b></a></button></h6>
                                </div><!--text-center-->
                        </div><!-- col-md-3 -->

                        

                        <div class="col-lg-3 col-md-4  col-sm-6 ">
                                <div class="center-text mb-30">
                                        <div class="pos-relative"><img src="dishes_4.jpg" alt=""></div>
                                        <h5 class="mt-20">Pizza Margherita</h5>
                                        <h4 class="mt-5"><b>$11.90</b></h4>
                                        <h6 class="mt-20"><button class="btn1"><a href="#menu" class="a1"><b>Order Now</b></a></button></h6>
                                </div><!--text-center-->
                        </div><!-- col-md-3 -->
                </div><!-- row -->

                <h6 class="center-text "><button class="btn1"><a href="#menu" class="a1"><b>SEE TODAYS MENU</b></button></a></h6>
        </div><!-- container -->
</section>
<section class="counter-section section center-text" id="services">
        <div class="container">
                <div class="row">
                        <div class="col-sm-6 col-md-3">
                                <div class="mb-30 ">
                                        <i class="icon-gradient"><img src="icon-1.png"></i>
                                        <h2><b><span class="counter-value">574</span></b>
                                        </h2>
                                        <h5 class="semi-black"><b>Pizza per day</b></h5>
                                </div><!-- margin-b-30 -->
                        </div><!-- col-md-3-->

                        <div class="col-sm-6 col-md-3">
                                <div class="mb-30">
                                        <i class="icon-gradient"><img src="icon-2.png"></i>
                                        <h2><b><span class="counter-value">127</span></b>
                                        </h2>
                                        <h5 class="semi-black"><b>Sea Food Dshes</b></h5>
                                </div><!-- margin-b-30 -->
                        </div><!-- col-md-3-->

                        <div class="col-sm-6 col-md-3">
                                <div class="mb-30">
                                        <i class="icon-gradient"><img src="icon-3.png"></i>
                                        <h2><b><span class="counter-value">51</span></b></h2>
                                        <h5 class="semi-black"><b>Pasta Chefs</b></h5>
                                </div><!-- margin-b-30 -->
                        </div><!-- col-md-3-->

                        <div class="col-sm-6 col-md-3">
                                <div class="mb-30">
                                        <i class="icon-gradient"><img src="icon-4.png"></i>
                                        <h2><b><span class="counter-value" >72</span></b>
                                        </h2>
                                        <h5 class="semi-black"><b>Salads per day</b></h5>
                                </div><!-- margin-b-30 -->
                        </div><!-- col-md-3-->

                </div><!-- row-->
        </div><!-- container-->
</section><!-- counter-section-->


<section>
        <div class="container" id="menu">
                <div class="heading">
                        <img class="heading-img" src="heading_logo.png" alt="">
                        <h2>Our Menu</h2>
                </div>

                

               <div class="row">
                        <div class="col-sm-12">
                                <ul class="selecton brdr-b-primary mb-70">
                                        <li><a class="active" href="#menu" ><b>MENU</b></a></li>
                                </ul>
                        </div><!--col-sm-12-->
                </div><!--row-->

                <div class="row">
                        <div class="col-md-6 food-menu">
                                <div class="mb-30 ">
                                        <div><img class="menu_pic_left" src="menu-1.jpg" alt="Menu Image"></div><!--s-left-->
                                        <div >
                                                <h5 class="mb-10"><b><br>Pizza Margherita</b><b class="color-primary float-right">$10.00</b></h5>
                                                <p class="pr-70">Pizza Margherita is a typical Neapolitan pizza, made with San Marzano tomatoes.</p>
                                        </div><!--s-right-->
                                </div><!-- sided-90x -->
                        </div><!-- food-menu -->

                        <div class="col-md-6 food-menu">
                                <div class="mb-30 ">
                                        <div><img class="menu_pic_left" src="menu-2.jpg" alt="Menu Image"></div><!--s-left-->
                                        <div>
                                                <h5 class="mb-10"><b><br>Panzenella</b><b class="color-primary float-right">$20.00</b></h5>
                                                <p class="pr-70">It is an Italian food which is a Tuscan chopped salad of soaked stale bread, onions and tomatoes.</p>
                                        </div><!--s-right-->
                                </div><!-- sided-90x -->
                        </div><!-- food-menu -->

                        <div class="col-md-6 food-menu">
                                <div class="mb-30 ">
                                        <div><img class="menu_pic_left" src="menu-3.jpg" alt="Menu Image"></div><!--s-left-->
                                        <div>
                                                <h5 class="mb-10"><b><br>Prosciutto cutto Pizza</b><b class="color-primary float-right">$12.00</b></h5>
                                                <p class="pr-70">Prosciutto cotto is a favorite Italian preservation of ham that is delightful on a homemade pizza.</p>
                                        </div><!--s-right-->
                                </div><!-- sided-90x -->
                        </div><!-- food-menu -->

                        <div class="col-md-6 food-menu">
                                <div class="mb-30">
                                        <div><img class="menu_pic_left" src="menu-4.jpg" alt="Menu Image"></div><!--s-left-->
                                        <div>
                                                <h5 class="mb-10"><b><br>chicago Pizza</b><b class="color-primary float-right">$6.00</b></h5>
                                                <p class="pr-70">Pizza features a thick crust with an inch-deep smothering of tomato sauce, cheese and toppings.</p>
                                        </div><!--s-right-->
                                </div><!-- sided-90x -->
                        </div><!-- food-menu -->
                        <div class="col-md-6 food-menu deserts">
                                <div class="mb-30">
                                        <div><img class="menu_pic_left" src="menu-5.jpg" alt="Menu Image"></div><!--s-left-->
                                        <div >
                                                <h5 class="mb-10"><b><br>Ossobuco</b><b class="color-primary float-right">$15.00</b></h5>
                                                <p class="pr-70">A specialty of Lombard cuisine of cross-cut veal shanks braised with vegetables, white wine and broth.</p>
                                        </div><!--s-right-->
                                </div><!-- sided-90x -->
                        </div><!-- food-menu -->
						
                        <div class="col-md-6 food-menu">
                                <div class="mb-30 ">
                                        <div><img class="menu_pic_left" src="menu-6.jpg" alt="Menu Image"></div><!--s-left-->
                                        <div>
                                                <h5 class="mb-10"><b><br>Sicilican Pizza</b><b class="color-primary float-right">$20.00</b></h5>
                                                <p class="pr-70">Sicilian pizza is pizza prepared in a manner that originated in Sicily, Italy.</p>
                                        </div><!--s-right-->
                                </div><!-- sided-90x -->
                        </div><!-- food-menu -->

                        <div class="col-md-6 food-menu">
                                <div class="mb-30">
                                        <div><img class="menu_pic_left" src="menu-7.jpg"  alt="Menu Image"></div>
                                        <div>
                                                <h5 class="mb-10"><b><b>Detroit Pizza</b><b class="color-primary float-right">$12.00</b></h5>
                                                <p class="pr-70">Detroit-style pizza is a style of pizza developed in Detroit, Michigan.</p>
                                        </div><!--s-right-->
                                </div><!-- sided-90x -->
                        </div><!-- food-menu -->

                        <div class="col-md-6 food-menu">
                                <div class="mb-30 ">
                                        <div><img class="menu_pic_left" src="menu-8.jpg" alt="Menu Image"></div>
                                        <div>
                                                <h5 class="mb-10"><b><br>Bistecca alla Fiorentina</b><b class="color-primary float-right">$6.00</b></h5>
                                                <p class="pr-70">An Italian steak made of veal that, makes it one of the most popular dishes of Tuscan cuisine.</p>
                                        </div><!--s-right-->
                                </div>
                        </div><!-- food-menu -->
                </div><!-- row -->

                
        </div><!-- container -->
</section>

<!-- Footer -->
 <footer class="footer_area text-center" id="contact">
        	<div class="container">
        		<div class="row footer_inner">
        			<div class="col-lg-8 col-xs-10 social_widget">
        			
        					<ul class="list">
        						<li><a href="https://www.facebook.com/"><i class="fa fa-facebook"></i></a></li>
        						<li><a href="https://twitter.com/" target="_blank"><i class="fa fa-twitter"></i></a></li>
        						<li><a href="https://www.instagram.com/" target="_blank"><i class="fa fa-instagram"></i></a></li>
        						<li><a href="https://github.com/" target="_blank"><i class="fa fa-github"></i></a></li>

        					</ul>
        			</div>
        		</div>
        	</div>
 <div class="row pt-5 mt-5 text-center">
         <div class="col-md-12 f_widget ab_widget">
           <div class="border-top pt-5 ">
            <p>
  Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | This website is made with <i class="fa fa-heart-o" aria-hidden="true"></i> by <a href="#" target="_blank" >Voyage</a>
           </p>
           </div>
        </div>
     </div>
  </footer>

</body>
</html>
