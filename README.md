<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Metro Shoes</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    *{
    box-sizing: border-box;
}
body{
    font-family: 'Poppins', sans-serif;
}
.navbar{
    display: flex;
    padding:10px;
}
nav{
    flex :   auto      ;
    text-align: right;
    font-size: 20px;
}
nav ul{
    display: inline-block;
    list-style-type: none;
}
nav ul li{
    display: inline-block;
    margin-right: 20px; 
}
nav li:hover{
    background:#FFF3F3;
}
a{
    text-decoration: none;
    color: red;
}
p{
    color:blue;
    margin-bottom: 20px;
}
.container{
    max-width: 1300px;
    margin:auto;
    padding-left: 25px;
    padding-right: 25px;
}
.row{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-around;
}
.col-2{
    flex-basis:50%;
    min-width:300px;
}
.col-2 img{
    max-width:100%;
    padding:0px 0;  
}
.col-2 h1{
    font-size: 40px;
    line-height: 0px;
    margin: 10px 0px;   
}   
.btn{
    background:#ff523b;
    color: #fff;
    padding:8px 30px;
    border-radius: 30px;
}
.btn:hover{
    background: #563434;
}
.categories{
    margin:70px 0;
}
.col-3{
    flex-basis:30%;
    min-width: 250px;
    margin-bottom: 30px;
}
.col-3 img{
    width:100%;
    background: radial-gradient(#fff, #ffd6d6) ;
}
.small-container{
    max-width:1080px;
    margin:auto;
    padding-left: 25px;
    padding-right: 25px;
}
.col-4{
    flex-basis:25%;
    padding:10px;
    min-width:200px;
    margin-bottom: 50px;
}
.col-4 img{
    width: 100%;
}
.title{
    text-align: center;
    margin: 0 auto 80px;
    position:relative;
    line-height:10px;
    color: #555;
}
h4{
    color:#555;
    font-weight:normal;
}
.col-4 p{
    font-size:14px;
}
.rating .fa{
    color:#ff523b
}
/*-----------------------footer-------------------------*/
.footer{
    background: black; 
    color: #8a8a8a;
    font-size: 14px;
    padding:60px 0 20px;
}
.footer p{
    color: #8a8a8a;
}
.footer h3{
    color: #fff;
    margin-bottom: 10px;
}
.footer-col-1, .footer-col-2{
    min-width : 250px;
    margin-bottom:20px;
}
.footer-col-1 li, .footer-col-2 li:hover{
    color: #ffebcc;
}
.app-logo{
    margin-top: 20px;
}
.app-logo img{
    width: 140px;
}
footer hr{
    border: none;
    background: #b5b5b5;
    height:2px;
    margin: 30px 0;
}
.copyright{
    text-align: center;
}
@media only screen and (max-width:600px){
    .row{
        text-align: center;
    }
    .col-2, .col-3, .col-4{
        flex-basis: 100%;
    } 
}
@media only screen and (max-width:600px){
        nav ul{
        position:absolute;
        top:70px;
        left:0;
        background: #333;
        width:100%;
        overflow: hidden;
        }
        nav ul li{
        display:block;
        margin-right:50px;
        margin-top:10px;
        margin-bottom:10px;
        }    
</style>
</head>
<body>
    <div class="header">
    <div class="container">
        <div class="navbar">               
            <nav>
                <ul id="menuitems">
                    <li><a href="">Home</a></li>
                    <li><a href="">Product</a></li>
                    <li><a href="">About</a></li>
                    <li><a href="">Contact</a></li>
                    <li><a href="">Account   </a></li>
                </ul>
            </nav>
        </div>
        <div class="row">   
            <div class="col-2"><h1>Metro Shoes</h1> <br>
            <p>Success isn't always about greatness. It's about Consistency.<br> Conistent hard work gains success.   </p>
            <a href="" class="btn">Buy Now &#8594;</a>
            </div>
            <div class="col-2">
                <img src="shoe_2-removebg-preview.png"  >
            </div>
        </div>
    </div>
</div>
<!-----------------------------------------categories------------------------------------------------------------>
<div class="categories">
    <div class="small-container">
        <div class="row">
            <div class="col-3"><img src="unsplash6.jpg"></div>
            <div class="col-3"><img src="unsplash2.jpg"></div>
            <div class="col-3"><img src="unsplash4.jpg"></div>
        </div>
    </div>
    <!------------------------------products---------------------------------------------------------------------->
    <div class="small-container">
        <h2 class="title">Featured Products</h2>
        <div class="row">
            <div class="col-4">
                <img src="s1.jpg">
                <h4>Brown Stylish Men shoe</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star-half"></i>
              <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
            </div>
            <div class="col-4">
                <img src="s2.jpg">
                <h4>Men Navy Running Shoes</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
            </div>
            <p>$55.00</p>
            </div>
            <div class="col-4">
                <img src="s3.jpg">
                <h4>Unisex Running Shoes</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star-o"></i>
            </div>
            <p>$60.00</p>
            </div>
            <div class="col-4">
                <img src="s6.jpg">
                <h4>White Stylish Shoes</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star-half"></i>
              <i class="fa fa-star-o"></i>
            </div>
            <p>$65.00</p>
            </div>
        </div>
        <h2 class="title">Latest Products</h2>
        <div class="row">
            <div class="col-4">
                <img src="s7.jpg">
                <h4> Reebok Running Shoes</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star-half"></i>
              <i class="fa fa-star-o"></i>
            </div>
            <p>$50.00</p>
            </div>
            <div class="col-4">
                <img src="s8.jpg">
                <h4>White Stylish Shoes</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
            </div>
            <p>$55.00</p>
            </div>
            <div class="col-4">
                <img src="s9.jpg">
                <h4> Stylish Shoes</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star-o"></i>
            </div>
            <p>$60.00</p>
            </div>
            <div class="col-4">
                <img src="s10.jpg">
                <h4>Green Stylish Shoes</h4>
            <div class="rating">
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star"></i>
              <i class="fa fa-star-half"></i>
              <i class="fa fa-star-o"></i>
            </div>
            <p>$65.00</p>
            </div>
    </div>
    <div class="row">
        <div class="col-4">
            <img src="s11.jpg">
            <h4>Red Running Shoes</h4>
        <div class="rating">
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star-half"></i>
          <i class="fa fa-star-o"></i>
        </div>
        <p>$50.00</p>
        </div>
        <div class="col-4">
            <img src="s12.jpg">
            <h4>Reebok navy blue shoes</h4>
        <div class="rating">
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
        </div>
        <p>$55.00</p>
        </div>
        <div class="col-4">
            <img src="s13.jpg">
            <h4>White Stylish shoes</h4>
        <div class="rating">
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star-o"></i>
        </div>
        <p>$60.00</p>
        </div>
        <div class="col-4">
            <img src="s15.jpg">
            <h4>Yellow Reebok Shoes</h4>
        <div class="rating">
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star"></i>
          <i class="fa fa-star-half"></i>
          <i class="fa fa-star-o"></i>
        </div>
        <p>$65.00</p>
        </div>
</div>
</div>
<!-------------------------------------footer-------------------------->
<div class="footer">
    <div class="container">
        <div class="row">
            <div class="footer-col-1">
                <h3>Download our App</h3>
                <p>Download App for Android and ios mobile Phone</p>
                <div class="applogo">
                   <a href=""> <img src="rsz_s18.jpg"></a>
                </div>
            </div>
            <div class="footer-col-2">
                <h3>Useful Links</h3>
                <ul>
                    <a href="">
                    <li>Coupons</li>
                    <li>Return Policy</li>
                    <li>Blog Post</li>
                     <li>Join Affiliate</li>
                    </a>
                </ul>
    </div>
    <div class="footer-col-2">
        <h3>Follow Us On</h3>
        <ul>
            <a href="#">
            <li>Facebook</li>
            <li>Instagram</li>
            <li>Twitter</li>
             <li>YouTube</li>
            </a>
        </ul>
</div>
        </div>
        <hr>
        <p class="copyright">Copyright 2020- Metro Shoes</p>
    </div>
</div>
</div>
</body>
</html>
