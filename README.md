# Final-Project

## Changes
  - Removed elements of html template that were unnecessary/off topic
  - Removed non-aplicable js and css files
  - Revoved unwanted css styles
  - Identified and renamed variables, id's, and class names
  - Created Store section replacing a company description section from the template
  - Removed Contact Us section
  - Created Order Form Section
  - Designed iput fields to meet order form requiremnts
  - Desinged order form CSS
  - Updated images
  - Corrected image/banner sizes
  - Changed CSS colors to a three color design present in the entire page
  - Handdrew Logo
  - Painted over banner image to match new css colors
  - Created new headers
  - Replaced placeholder text
  - Corrected Nav Bars and Read Me buttons locations
  - Added href links from the item prices to the order form
  - Created simple verification pop-up (HTML,CSS,JS)
  - Populated text fields in item descriotions and mission statement
  - Adjusted CSS styles in accordance to new images and colors
  

## Original Template Code
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- basic -->
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <!-- mobile metas -->
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="viewport" content="initial-scale=1, maximum-scale=1">
  <!-- site metas -->
  <title>bluene</title>
  <meta name="keywords" content="">
  <meta name="description" content="">
  <meta name="author" content="">
  <!-- bootstrap css -->
  <link rel="stylesheet" href="css/bootstrap.min.css">
  <!-- style css -->
  <link rel="stylesheet" href="css/style.css">
  <!-- Responsive-->
  <link rel="stylesheet" href="css/responsive.css">
  <!-- fevicon -->
  <link rel="icon" href="images/fevicon.png" type="image/gif" />
  <!-- Scrollbar Custom CSS -->
  <link rel="stylesheet" href="css/jquery.mCustomScrollbar.min.css">
  <!-- Tweaks for older IEs-->
  <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fancybox/2.1.5/jquery.fancybox.min.css" media="screen">
  <!--[if lt IE 9]>
  <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
  <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script><![endif]-->
</head>
<!-- body -->
<body class="main-layout">
<!-- loader  -->
<div class="loader_bg">
  <div class="loader"><img src="images/loading.gif" alt="#" /></div>
</div>
<!-- end loader -->
<!-- header -->
<header>
  <!-- header inner -->
  <div class="header">
    <div class="container-fluid">
      <div class="row">
        <div class="col-xl-3 col-lg-3 col-md-3 col-sm-3 col logo_section">
          <div class="full">
            <div class="center-desk">
              <div class="logo">
                <a href="index.html"><img src="images/logo.png" alt="#" /></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-9 col-lg-9 col-md-9 col-sm-9">
          <nav class="navigation navbar navbar-expand-md navbar-dark ">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExample04" aria-controls="navbarsExample04" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarsExample04">
              <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                  <a class="nav-link" href="#services">Services </a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#work"> Our  Work</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
      </div>
    </div>
  </div>
</header>
<!-- end header inner -->
<!-- end header -->
<!-- banner -->
<section class="banner_main">
  <div class="container-fluid">
    <div class="row d_flex">
      <div class="col-md-7">
        <div class="text-bg">
          <div class="padding_lert">
            <i><img src="images/btn.png" alt="#"/></i>
            <h1>A Digital Creative Agency  <br>Landing Page</h1>
            <a href="Javascript:void(0)">Read More</a>
          </div>
        </div>
      </div>
      <div class="col-md-5 bah">
        <div class="bann_img">
          <figure><img src="images/bann_img.png" alt="#"/></figure>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- end banner -->
<!-- service -->
<div id="services" class="service">
  <div class="container-fluid">
    <div class="row d_flex">
      <div class="col-md-5">
        <div class="service_img">
          <figure><img src="images/pc.png" alt="#"/></figure>
        </div>
      </div>
      <div class="col-md-7">
        <div class="titlepage">
          <h2>Full service digital capbilities From end to end workflow</h2>
          <span>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five</span>

        </div>
      </div>
    </div>
  </div>
</div>
<!-- end service -->
<!-- solutions -->
<div class="solutions">
  <div class="container">
    <div class="row d_flex">
      <div class="col-md-7">
        <div class="titlepage">
          <h2>Solutions for every <br>Specific need</h2>
          <span>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five</span>
          <a class="read_more" href="Javascript:void(0)">Read More</a>
        </div>
      </div>
      <div class="col-md-5">
        <div class="solutions_img">
          <figure><img src="images/solusan.png" alt="#"/></figure>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- end solutions -->
<!-- work -->
<div id="work" class="work">
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="titlepage">
          <h2>See More Our Work</h2>
          <span>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a istribution of letters, content here', making it look like readable English. Many desktop publishing packages </span>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6">
        <div class="our_work">
          <figure><img src="images/work1.jpg" alt="#"/></figure>
        </div>
      </div>
      <div class="col-md-6">
        <div class="our_work">
          <figure><img src="images/work2.jpg" alt="#"/></figure>
        </div>
      </div>
      <div class="col-md-6">
        <div class="our_work">
          <figure><img src="images/work3.jpg" alt="#"/></figure>
        </div>
      </div>
      <div class="col-md-6">
        <div class="our_work">
          <figure><img src="images/work4.jpg" alt="#"/></figure>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- end work -->
<!--  footer -->
<footer>
  <div class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-5">
          <div class="multipurpose">
            <h3>Let’s  <br>Talk <br> Business</h3>
          </div>
        </div>
        <div class="col-md-7 sm_none">
          <div class="contac_detel">
            <ul>
              <li><img src="images/call.png" alt="#"/>+91 1234567890</li>
              <li><a href="Javascript:void(0)"> <img src="images/gmail.png" alt="#"/>demo@gmail.com</a></li>
            </ul>
          </div>
        </div>
        <div class="col-md-12">
          <div class="multipurpose">
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
          </div>
        </div>
        <div class="col-md-7 sm_show">
          <div class="contac_detel">
            <ul>
              <li><img src="images/call.png" alt="#"/>+91 1234567890</li>
              <li><a href="Javascript:void(0)"> <img src="images/gmail.png" alt="#"/>demo@gmail.com</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="copyright">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <p>Copyright 2020 All Right Reserved By<a href="https://html.design/"> Free Html Templates</a></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</footer>
<!-- end footer -->
<!-- Javascript files-->
<script src="js/jquery.min.js"></script>
<script src="js/bootstrap.bundle.min.js"></script>
<script src="js/jquery-3.0.0.min.js"></script>
<script src="js/jquery.mCustomScrollbar.concat.min.js"></script>
<script src="js/custom.js"></script>
</body>
</html>

## Original CSS Template
/*--------------------------------------------------------------------- File Name: style.css ---------------------------------------------------------------------*/


/*--------------------------------------------------------------------- import Fonts ---------------------------------------------------------------------*/

@import url('https://fonts.googleapis.com/css?family=Rajdhani:300,400,500,600,700');
@import url('https://fonts.googleapis.com/css?family=Lato:300,400,700,900&display=swap');

/*****---------------------------------------- 1) font-family: 'Rajdhani', sans-serif;
 2) font-family: 'Poppins', sans-serif;
 ----------------------------------------*****/


/*--------------------------------------------------------------------- import Files ---------------------------------------------------------------------*/

@import url(animate.min.css);
@import url(normalize.css);
@import url(icomoon.css);
@import url(font-awesome.min.css);
@import url(meanmenu.css);
@import url(owl.carousel.min.css);
@import url(swiper.min.css);
@import url(slick.css);
@import url(jquery.fancybox.min.css);
@import url(jquery-ui.css);
@import url(nice-select.css);

/*--------------------------------------------------------------------- skeleton ---------------------------------------------------------------------*/

* {
     box-sizing: border-box !important;
}

html {
     scroll-behavior: smooth;
}

body {
     color: #666666;
     font-size: 14px;
     font-family: 'Lato', sans-serif;
     line-height: 1.80857;
     font-weight: normal;
}

a {
     color: #1f1f1f;
     text-decoration: none !important;
     outline: none !important;
     -webkit-transition: all .3s ease-in-out;
     -moz-transition: all .3s ease-in-out;
     -ms-transition: all .3s ease-in-out;
     -o-transition: all .3s ease-in-out;
     transition: all .3s ease-in-out;
}

h1,
h2,
h3,
h4,
h5,
h6 {
     letter-spacing: 0;
     font-weight: normal;
     position: relative;
     padding: 0 0 10px 0;
     font-weight: normal;
     line-height: normal;
     color: #111111;
     margin: 0
}

h1 {
     font-size: 24px;
     text-shadow: 2px 3px black;
}

h2 {
     font-size: 22px;
}

h3 {
     font-size: 18px;
}

h4 {
     font-size: 16px
}

h5 {
     font-size: 14px
}

h6 {
     font-size: 13px
}

*,
*::after,
*::before {
     -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
     box-sizing: border-box;
}

h1 a,
h2 a,
h3 a,
h4 a,
h5 a,
h6 a {
     color: #212121;
     text-decoration: none!important;
     opacity: 1
}

button:focus {
     outline: none;
}

ul,
li,
ol {
     margin: 0px;
     padding: 0px;
     list-style: none;
}

p {
     margin: 0px;
     font-weight: 500;
     font-size: 15px;
     line-height: 24px;
}

a {
     color: #222222;
     text-decoration: none;
     outline: none !important;
}

a{
     text-decoration: none !important;
     outline: none !important;
     -webkit-transition: all .3s ease-in-out;
     -moz-transition: all .3s ease-in-out;
     -ms-transition: all .3s ease-in-out;
     -o-transition: all .3s ease-in-out;
     transition: all .3s ease-in-out;
}

img {
     max-width: 100%;
     height: auto;
}

 :focus {
     outline: 0;
}

.lead {
     font-size: 18px;
     line-height: 30px;
     color: #767676;
     margin: 0;
     padding: 0;
}

.form-control:focus {
     border-color: #ffffff !important;
     box-shadow: 0 0 0 .2rem rgba(255, 255, 255, .25);
}

.navbar-form input {
     border: none !important;
}

.badge {
     font-weight: 500;
}

blockquote {
     margin: 20px 0 20px;
     padding: 30px;
}

button {
     border: 0;
     margin: 0;
     padding: 0;
     cursor: pointer;
}

.full {
     float: left;
     width: 100%;
}

.full {
     width: 100%;
     float: left;
     margin: 0;
     padding: 0;
}


/**-- heading section --**/


/*---------------------------- preloader area ----------------------------*/

.loader_bg {
     position: fixed;
     z-index: 9999999;
     background: #fff;
     width: 100%;
     height: 100%;
}

.loader {
     height: 100%;
     width: 100%;
     position: absolute;
     left: 0;
     top: 0;
     display: flex;
     justify-content: center;
     align-items: center;
}

.loader img {
     width: 280px;
}

/*-- header area --*/


.header {
     width: 100%;
     background: transparent;
     padding: 30px 30px;
     position: absolute;
     z-index: 99;
     height: 90px;
}


/*-- navigation--*/

.navigation.navbar {
     float: right;
     padding: 0px;
     padding-top: 3px !important;
}

.navigation.navbar-dark .navbar-nav .nav-link {
     padding: 0 25px;
     color: #fff;
     font-size: 16px;
     line-height: 20px;
     text-transform: uppercase;
}

.navigation.navbar-dark .navbar-nav .nav-link:focus,
.navigation.navbar-dark .navbar-nav .nav-link:hover {
     color: #D91E36;
}

.navigation.navbar-dark .navbar-nav .active>.nav-link,
.navigation.navbar-dark .navbar-nav .nav-link.active,
.navigation.navbar-dark .navbar-nav .nav-link.show,
.navigation.navbar-dark .navbar-nav .show>.nav-link {
     color: #D91E36;
}

/** banner section **/

.banner_main {
     background: url(../images/banner.jpg);
     display: flex;
     align-content: center;
     align-items: center;
     background-size: 100% 100%;
     padding-top: 13%;
     padding-bottom: 150px;
}

.text-bg {
     max-width: 669px;
     float: right;
     text-align: left;
     width: 100%;
}

.bann_img {
     padding-right: 40px;
}

.bann_img figure {
     margin: 0;
}

.bann_img figure img {
     width: 100%;
}

.text-bg h1 {
     color: #fff;
     font-size: 78px;
     line-height: 96px;
     padding-bottom: 59px;
     font-weight: 800;
     padding-top: 40px;
}

.text-bg i img {
     cursor: pointer;
}

.text-bg a {
     font-size: 17px;
     background-color: #fff;
     color: #D91E36;
     font-weight: 600;
     padding: 22px 0px;
     width: 100%;
     max-width: 320px;
     text-align: center;
     display: inline-block;
     transition: ease-in all 0.5s;
     text-transform: uppercase;
}

.text-bg a:hover {
     background-color: #D91E36;
     color: #fff;
     transition: ease-in all 0.5s;
}

.titlepage {
     text-align: center;
     padding-bottom: 60px;
}

.titlepage h2 {
     font-size: 45px;
     color: #060002;
     line-height: 55px;
     font-weight: 800;
     padding: 0;
}

.titlepage span {
     font-size: 17px;
     line-height: 30px;
     color: #060002;
     padding-top: 25px;
     display: block;
}

.d_flex {
     display: flex;
     align-items: center;
     flex-wrap: wrap;
}

.read_more {
     font-size: 16px;
     background-color: #020001;
     color: #fff;
     padding: 6px 0px;
     height: 44px;
     width: 100%;
     max-width: 144px;
     text-align: center;
     transition: ease-in all 0.5s;
     display: inline-block;
}

.read_more:hover {
     background: #D91E36 !important;
     color: #fff !important;
     transition: ease-in all 0.5s;
}

.container {
     max-width: 1170px;
}


/** banner section **/


/** service section **/

.service {
     background: #fff;
     padding-top: 90px;
}

.service .titlepage {
     text-align: left;
     padding-bottom: 0;
     max-width: 631px;
     float: left;
     padding-left: 20px;
}

.service .titlepage span {
     color: #514f50;
}

.service .titlepage .read_more {
     margin-top: 34px;
}

.service_img {
     padding-left: 30px;
}

.service_img figure {
     margin: 0px;
}

.service_img figure img {
     width: 100%;
}


/** end service section **/


/** solutions section **/

.solutions {
     background: #004B8D;
     padding: 90px 0;
     margin-top: 90px;
}

.solutions .titlepage {
     text-align: left;
     padding-bottom: 0;
}

.solutions .titlepage h2 {
     color: #fff;
}

.solutions .titlepage span {
     color: #fff;
}

.solutions .titlepage .read_more {
     background: #fff;
     color: #004B8D;
     margin-top: 54px;
}

.solutions_img {
     margin-right: -40px;
}

.solutions_img figure {
     margin: 0px;
}

.solutions_img figure img {
     width: 100%;
}


/** end solutions section **/


/** work section **/

.work {
     background: #fff;
     padding-top: 90px;
}

.our_work {
     margin-bottom: 30px;
}

.our_work figure {
     margin: 0px;
}

.our_work figure img {
     width: 100%;
}


/** end work section **/


/** footer **/

.orderform {
     margin-top: 60px;
     background: #004B8D;
     padding-top: 90px;
     text-align: center;
}

.multipurpose {
     text-align: left;
}

.multipurpose h3 {
     color: #b3b3b3;
     font-size: 80px;
     line-height: 90px;
     padding-bottom: 0;
     font-weight: bold;
}


.multipurpose p {
     color: #fff;
     font-size: 17px;
     line-height: 30px;
     padding-top: 40px;
     font-weight: 400;
}

.sm_show {
     display: none;
}

.contac_detel {
     background: #fff;
     padding: 31px 0;
}

.contac_detel ul li img {
     margin-right: 60px;
}

.contac_detel ul li {
     padding-bottom: 25px;
     font-size: 45px;
     color: #D91E36;
     line-height: 30px;
}

.contac_detel ul li:last-child {
     padding-bottom: 0;
}

.contac_detel ul li a {
     color: #D91E36;
}

.contac_detel ul li a:hover {
     color: #000;
}


/** end footer **/
/**verify **/
.overlay {
     position: fixed;
     top: 0;
     left: 0;
     right: 0;
     bottom: 0;
     background-color: rgba(0,0,0,0.5);
     display: flex;
     justify-content: center;
     align-items: center;
     z-index: 1;
}

.popup {
     background-color: #F2F2F2;
     padding: 20px;
     border-radius: 10px;
     text-align: center;
}

button {
     margin: 10px;
     padding: 10px 20px;
     border-radius: 5px;
     border: none;
     color: #F2F2F2;
     background-color: #004B8D;
     cursor: pointer;
}
/** end verification **/
/** form style **/
select{
     padding: 16px 20px;
     border: none;
     border-radius: 4px;
     background-color: #F2F2F2;
}
input[type=text] {
     padding: 12px 20px;
     margin: 8px 0;
     box-sizing: border-box;
}
input[type=text]:focus {
border: 3px solid #555;
}
/** end form style **/
