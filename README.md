<html>

<head>
  <title>Saylani Walfare Trust - PK</title>
  <link rel="icon" href="images.png" type="image/x-icon">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
    <style type="text/css">
        body {
    margin: 0px;
    padding: 0px;
}

.navMail {
    background-color: #dee2e6;
    padding-left: 70px;
    font-family: system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans","Liberation Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-size: 14px;
    color: #495057;
    height: 25px;
    display: flex;
    width: 1100px;
}
.navMail >p {
    margin-top: 0%;
}
.ABH {
    display: flex;
}
.lang-menu {
    width: 130px;
    height: 16px;
}
.selected-lang {
    padding-left: 22px;
    cursor: pointer;
    display: flex;
    justify-content: space-between;
    line-height: 2;
    padding-right: 9px;
}
.selected-lang::before {
    content: '';
    display: block;
    width: 32;
    height: 32px;
    background-image: url(https://flagsapi.com/US/flat/32.png);
}
.pk::before{
    background-image:url(https://flagsapi.com/PK/flat/32.png);
}
.ae::before {
    background-image: url(https://flagsapi.com/AE/flat/32.png);
}
.tr:before {
    background-image: url(https://flagsapi.com/TR/flat/32.png);
}

.lang-menu  ul {
    margin: 0;
    padding: 0;
    background-color: rgb(87, 81, 81);
    border: 1px solid #f8f8f8;
    box-shadow: 0px 1px 10px rgba(0, 0, 0, 0.2) ;
    border-radius: 5px ;
    display: none;
    position: absolute;
}
.lang-menu  ul  li {
    list-style: none;
    display: flex;
    justify-content: space-between;
}
.lang-menu  ul  li a {
    display: block;
    width: 123px;
    padding: 5px 10px;
    font-size: 17px;
    color: #fff;
}
.lang-menu  ul  li a:hover {
    background-color: #dee2e6;
}
.lang-menu  ul  li a::before {
    content: '';
    display: inline-block;
    vertical-align: middle;
    margin-right: 5px;
    width: 32;
    height: 32px;
}
a {
    text-decoration: none;
}
.lang-menu:hover ul {
    display: block;
}
.blank {
    width: 100px;
    background-color: #dee2e6;
    height: 26px;
}
.navMail > p {
    padding-top: 2px;
}


.navBar {
    margin-bottom: 30px;
    margin-top: 20px;
    height: 80px;
    width: 100%;
    display: flex;
    align-items: center;
    border: #dee2e6;
    margin-top: 0%;
    border-bottom: 1px solid #dee2e6;
    box-shadow: 0px 1px 10px rgba(0, 0, 0, 0.2);
}
.navLogo {
    margin-left: 170px;
    width: 10px;
    height: 10px;
    font-size: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.navOptions {
    display: flex;
    justify-content: right;
    width: 100vw;
    margin-right: 380px;
    }
 
.navOptions > ul {
    display: flex;
    text-align: left;
    list-style: none;
    padding: 0;
    padding-left: 130px;
    text-decoration: none;
}

.navOptions > ul > li {
    width: 100px;
    height: 40px;
    font-size: 16px;
    color: rgb(56, 54, 54);
    cursor: pointer;
    border-radius: 90px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    display: flex;
    justify-content: center;
    align-items: center;
    transition:0.4s;
}
.donate {
    margin-left: 50px;
    margin-right: 50px;
    font-size: small;
    color: white;
    border-radius: 4px;
    padding: 10px;
    background-color: #3c7ad6;
}
.sponsor {
    margin: 10px;
    font-size: small;color: white;
    border-radius: 4px;
    padding: 10px;
    border: 1px solid #3c7ad6;
    background-color: #9bcf21;
}
.front {
    width: 100%;
    height: 580px;
    display: flex;
    font-family: 'Poppins', sans-serif;
}

.welcome {
    width: 50%;
    height: 600px;
    margin-left: 85px;
    margin-top: 80px;
    color: rgba(0,0,0,.85);
    font-size: 12px;
    font-weight: 400;
    text-align: left;
    line-height: 1.23;
    margin-bottom: 0.5em;
}
.welcome p {
    font-size: 16px;
    line-height: 26px;

}
.saylani {
    color: #9bcf21;
}
.more {
    color: #3c7ad6;
}
.btn {
    width: 200px;
    height: 50px;
    border-radius: 4px;
    background-color: #f8f8f8;
}
.image {
    width: 400px; 
    height: 600px;    
    margin-top: 10px;
    margin-bottom: 0%;
    margin-right: 210px;
}
.general {
    background-color: #f2ffd4;
    margin: 93px;
    margin-top: 0px;
    margin-bottom: 50px;
    height: 185px;
    border-radius: 10px;
}
.main {
    background-color: #fff;
    margin: 70px;
    font-family: 'Poppins', sans-serif;
    margin-left: 27px;
    border-radius: 5px;
    border: 1px black solid;
    position: absolute;
    height: 50px;
    width: 250px;
    display: flex;
}
.main p {
    background-color: #313438;
    height: 35px;
    margin-top: 0%;
    padding-top: 15px;
    padding-left: 10px;
    padding-right: 10px;
    font-size: 12px;
    width: 70px;
    color: #fff;
}
.dollar {
    background-color: #313438;
    color: #fff;
    margin-top: 0%;
    margin-bottom: 0%;
    margin-left: 150px;
    padding-top: 15px;
    padding-right: 19px;
    height: 35px;
    width: 60px;
    text-align: center;
}
.blood {
    background-color: #fff;
    color: hsl(214, 7%, 21%);
    margin-left: 300px;
    margin-top: 50px;
    padding-top: 15px;
    padding-left: 20px;
    padding-right: 20px;
    height: 35px;
    font-size: 14px;
    position: absolute;
    font-family:  'Poppins', sans-serif;
    border-radius: 5px;
}
.quick {
    background-color:hwb(81 35% 23%);
    color: #fff;
    font-family: 'Poppins', sans-serif;
    text-align: center;
    position: absolute;
    border-radius: 5px;
    font-size: 14px !important;
    height: 35px;
    width: 150px;
    margin-left: 310px;
    margin-top: 115px;
    padding-top: 15px;
}
.family {
    background-color: #fff;
    color: #313438;
    margin-left: 630px;
    margin-top: 50px;
    padding-top: 15px;
    padding-left: 20px;
    padding-right: 20px;    
    height: 35px;
    font-size: 14px;
    position: absolute;
    font-family:  'Poppins', sans-serif;
    border-radius: 5px;
}
.medical {
    background-color: #fff;
    color: #313438;
    margin-left: 805px;
    margin-top: 50px;
    padding-top: 15px;
    padding-left: 20px;
    padding-right: 20px;
    height: 35px;
    font-size: 14px;
    position: absolute;
    font-family:  'Poppins', sans-serif;
    border-radius: 5px;
}
.food {
    background-color: #fff;
    color: #313438;
    margin-left: 945px;
    margin-top: 50px;
    padding-top: 15px;
    padding-left: 20px;
    padding-right: 20px;
    margin-bottom: 0%;
    padding-bottom: 0%;
    height: 35px;
    font-size: 14px;
    position: absolute;
    font-family: 'Poppins', sans-serif;
    border-radius: 5px;
}
.img {
    margin-top: 0%;
    padding-left: 75px;
    margin-right: 75px;
    margin-bottom: 50px;
}
.what {
    font-family: 'Poppins', sans-serif;
    text-align: center;
    color: rgba(0, 0, 0, 0.89);
}
.container {
    background-color: white;
    width: 90%;
    height: 220px;
    margin-right: 5%;
    padding-left: 35px;
    margin-top: 20px;
    display: flex;
}
.col1 {
    margin-top: 30px;
    margin-bottom: 90px;
    margin-left: 40px;
    background-color: #f2ffd4;
    height: 150px;
    width: 160px;    
    cursor: pointer;
    border-radius: 10px;
}
.col1::before{
    transform: scale(1);
    animation-delay: 0.3s;
}
.col1 img {
    padding-left: 30%;
    padding-right: 25%;
    padding-top: 15%;
    height: 70px;
    padding-bottom: 5%;
}
.col1 span {
    text-align: center;
    font-family: 'Poppins', sans-serif;
    font-size: large;
    padding-left: 28%;
}
.col2 {
    margin-top: 30px;
    margin-bottom: 90px;
    margin-left: 30px;
    background-color: #f2ffd4;
    height: 150px;    
    cursor: pointer;
    width: 160px;
    border-radius: 10px;
}
.col2 img {
    padding-left: 30%;
    padding-right: 25%;
    padding-top: 15%;
    height: 70px;
    padding-bottom: 5%;
}
.col2 span {
    text-align: center;
    font-family: 'Poppins', sans-serif;
    font-size: large;
    padding-left: 28%;
}
.col3 {
    margin-top: 30px;
    margin-bottom: 90px;
    margin-left: 30px;
    background-color: #f2ffd4;
    height: 150px;
    width: 180px;
    cursor: pointer;
    border-radius: 10px;
}
.col3 img {
    padding-left: 40%;
    padding-right: 25%;
    padding-top: 15%;
    height: 70px;
    padding-bottom: 5%;
}
.col3 span {
    text-align: center;
    font-family: 'Poppins', sans-serif;
    font-size: large;
    padding-left: 13%;
}
.col4 {
    margin-top: 30px;
    margin-bottom: 90px;
    margin-left: 30px;
    background-color: #f2ffd4;
    height: 150px;
    width: 160px;
    cursor: pointer;
    border-radius: 10px;
}
.col4 img {
    padding-left: 30%;
    padding-right: 25%;
    padding-top: 15%;
    height: 70px;
    padding-bottom: 5%;
}
.col4 span {
    text-align: center;
    font-family: 'Poppins', sans-serif;
    font-size: large;
    padding-left: 28%;
}
.col5 {
    margin-top: 30px;
    margin-bottom: 90px;
    margin-left: 30px;
    background-color: #f2ffd4;
    height: 150px;
    cursor: pointer;
    width: 160px;
    border-radius: 10px;
}
.col5 img {
    padding-left: 30%;
    padding-right: 25%;
    padding-top: 15%;
    height: 70px;
    padding-bottom: 5%;
}
.col5 span {
    text-align: center;
    font-family: 'Poppins', sans-serif;
    font-size: large;
    padding-left: 28%;
}
.col6 {
    margin-top: 30px;
    margin-bottom: 90px;
    margin-left: 30px;
    background-color: #f2ffd4;
    height: 150px;
    width: 160px;
    cursor: pointer;
    border-radius: 10px;
}
.col6 img {
    padding-left: 30%;
    padding-right: 25%;
    padding-top: 15%;
    height: 70px;
    padding-bottom: 5%;
}
.col6 span {
    text-align: center;
    font-family: 'Poppins', sans-serif;
    font-size: large;
    padding-left: 39%;
}
.fund {
    display: flex;
    width: 91%;
    margin-left: 5%;
    margin-right: 4%;
}
.filter {
    background-color: rgba(0,0,0,0.6) !important;
    width: 350px;
    height: 300px;
    margin-bottom: 35px;
    margin-left: 5px;
    margin-right: 18px;
    display: flex;
    border-radius: 10px;
    position: relative;
    transform: none;
}
.filter h5{
    font-family: 'Poppins', sans-serif;
    font-size: 17px;
    color: #fff;
    display: flex;
    padding-left: 15px;
    padding-top: 180px;
    justify-content: center;
    position: absolute;
}
.filter button {
    color: #fff;
    font-family: 'Poppins', sans-serif;
    font-size: 15px;
    background-color: #9bcf21;
    position: absolute;
    margin-top: 245;
    height: 45px;
    border-radius: 6px;
    width: 330px;
    margin-left: 10px;
    margin-right: 10px;
    border-style: none;
}
.courses {
    background-color: rgba(0,0,0,0.6) !important;
    width: 350px;
    height: 300px;
    margin-bottom: 35px;
    margin-left: 5px;
    margin-right: 18px;
    display: flex;
    border-radius: 10px;
    position: relative;
    transform: none;
}
.courses h5 {
    font-family: 'Poppins', sans-serif;
    font-size: 17px;
    color: #fff;
    display: flex;
    padding-left: 15px;
    padding-top: 180px;
    justify-content: center;
    position: absolute;
}
.courses button {
    color: #fff;
    font-family: 'Poppins', sans-serif;
    font-size: 15px;
    background-color: #9bcf21;
    position: absolute;
    margin-top: 245px;
    height: 45px;
    border-radius: 6px;
    width: 330px;
    margin-left: 10px;
    margin-right: 10px;
    border-style: none;
}
.zakat {
    background-color: rgba(0,0,0,0.6) !important;
    width: 350px;
    height: 300px;
    margin-bottom: 35px;
    margin-left: 5px;
    margin-right: 18px;
    display: flex;
    border-radius: 10px;
    position: relative;
    transform: none;
}
.zakat h5 {
    font-family: 'Poppins', sans-serif;
    font-size: 17px;
    color: #fff;
    display: flex;
    padding-left: 15px;
    padding-top: 180px;
    justify-content: center;
    position: absolute;
}
.zakat button {
    color: #fff;
    font-family: 'Poppins', sans-serif;
    font-size: 15px;
    background-color: #9bcf21;
    position: absolute;
    margin-top: 245px;
    height: 45px;
    border-radius: 6px;
    width: 330px;
    margin-left: 10px;
    margin-right: 10px;
    border-style: none;
}
.footer {
    background-color: #424242;
    height: 350px;
    width: 100%;
    margin-bottom: 0%;
    position: relative;
}
.wave img {
    height: 349px;
    width: 1250px;
    padding: 2px;
    position: absolute;
    opacity: .1;
}
.loog img {
    height: 80px;
    width: 300px;
    padding-left: 70px;
    padding-top: 50px;
    position: absolute;
}
.face img {
    height: 40px;
    width: 40px;
    margin-left: 100px;
    margin-top: 160px;
    position: absolute;
    border-radius: 5px;
    cursor: pointer;
}
.twit img {
    height: 40px;
    width: 40px;
    margin-left: 150px;
    margin-top: 160px;
    position: absolute;
    border-radius: 5px;
    cursor: pointer;
}
.yout img {
    height: 40px;
    width: 40px;
    margin-left: 200px;
    margin-top: 160px;
    position: absolute;
    cursor: pointer;
    border-radius: 5px;
}

.ab span{
    font-family: 'Poppins', sans-serif;
    color: #fff;
    padding-left: 470px;   
    padding-top: 40px;
    cursor: pointer;
}
.ab p {
    font-size: 14px;
}
.ab {
    display: flex;
}
.access span{
    padding-top: 0%;
    font-family: 'Poppins', sans-serif;
    padding-left: 100px;
    padding-top: 40px;
    color: #fff;
    position: absolute;
    cursor: pointer;
}
.access p {
    font-size: 14px;
}
.access {
    display: flex;
}
.tax h2 {
    line-height: 35px;
}
.tax span {
    font-family: 'Poppins', sans-serif;
    padding-top: 0%;
    padding-left: 300px;
    padding-top: 40px;
    color: #fff;
    position: absolute;
    line-height: 10%;
    cursor: pointer;
}
.tax p {
    font-size: 13px;
}
.divider {
    padding-top: 245px;
    color: #fff;
    margin-left: 0%;
    position: absolute;
    opacity: .2;
    padding-left: 95px;
}
.copy p {
    color: #fff;
    padding-top: 260px;
    position: absolute;
    padding-left: 38%;
    font-size: 14px;
    font-family: 'Poppins', sans-serif;
}
    </style>

</head>

<body>
  <div class="header">
    <div class="ABH">
      <div class="navMail">
        <p>✉ &nbsp;info@SaylaniWelfareUSA.com &nbsp;&nbsp;&nbsp;&nbsp;✆&nbsp;833-786-0999 </p>
      </div>
      <div class="lang-menu">
        <div class="selected-lang">
          English
        </div>
        <ul>
          <li>
            <a href="#" class="pk">Urdu</a>
          </li>
          <li>
            <a href="#" class="ae">Arabic</a>
          </li>
          <li>
            <a href="#" class="tr">Turkey</a>
          </li>
        </ul>
      </div>
      <div class="blank"></div>
    </div>
    <div class="navBar">
      <div class="navLogo">
        <span>
          <img src="logo.22bf709605809177256c-removebg-preview.png" width="190px" height="55px">
        </span>
      </div>
      <div class="navOptions">
        <ul>
          <li><a style="color: rgb(56, 54, 54);" class="home" href="#">Home</a></li>
          <li><a class="about">About</a></li>
          <li><a class="services">Services</a></li>
          <li><a class="media">Media</a></li>
          <li><a class="news">News</a></li>
          <li><a class="contact us">Contact us</a></li>
          <li><a class="bank">Bank Details</a></li>
          <li><a class="donate">DONATE NOW</a></li>
          <li><a class="sponsor">BE A SPONSOR</a></li>
        </ul>
      </div>
    </div>
    <div class="front">
      <div class="welcome" style="font-family: 'Poppins';font-size: 22px;">
        <h1>Welcome to the <br> <a class="saylani">Saylani</a> Welfare</h1>
        <h3>The largest NGO offering free <a class="more"> healthcare <br> and lot more.</a></h3>
        <p>Saylani Welfare is on the ground and already working with local
          communities to assess how best to support underprivileged families
          <br> in more than 63 areas of day to day lives.
        </p>
        <button class="btn">Explorer More →</button>
      </div>
      <div class="image">
        <img src="38.png" width="500px" height="500px">
      </div>
    </div>
    <div class="general">
      <div class="main">
        <p style="text-align: center;">General</p>
        <p style="font-size: large;" class="dollar">$</p>
      </div>
      <div style="text-align: center;" class="blood"><b>Blood Bank / Thalassemia Treatment</b></div>
      <div style="text-align: center;" class="family"><b>Family Kifalat</b></div>
      <div style="text-align: center;" class="medical"><b>Medical</b></div>
      <div style="text-align: center;" class="food"><b>Food</b></div>
      <div class="quick">Quick Donate</div>
    </div>

    <div class="img">
      <img src="95f11c54-b518-4d7f-8d24-b280acc914ef.jpg" alt="Saylani Walfare" height="625" width="1110">
    </div>

    <p>
    <h1 style="text-align: center;" class="what">What We Are Doing</h1>
    </p>

    <div class="container">

      <div class="col1">
        <img src="	https://res.cloudinary.com/saylani-welfare/image/upload/v1646927889/website-images/static/44.png">
        <span><b>Welfare</b></span>
      </div>
      <div class="col2">
        <img src="https://res.cloudinary.com/saylani-welfare/image/upload/v1646927857/website-images/static/41.png">
        <span><b>Medical</b></span>
      </div>
      <div class="col3">
        <img src="https://res.cloudinary.com/saylani-welfare/image/upload/v1646927849/website-images/static/39.png">
        <span><b>Online Sadqah</b></span>
      </div>
      <div class="col4">
        <img src="	https://res.cloudinary.com/saylani-welfare/image/upload/v1646927853/website-images/static/40.png">
        <span><b>RO Plant</b></span>
      </div>
      <div class="col5">
        <img src="https://res.cloudinary.com/saylani-welfare/image/upload/v1646927923/website-images/static/48.png">
        <span><b>Education</b></span>
      </div>
      <div class="col6">
        <img src="https://res.cloudinary.com/saylani-welfare/image/upload/v1646927876/website-images/static/43.png">
        <span><b>Food</b></span>
      </div>
    </div>

    <div class="fund">
      <div class="filter">
        <h5>RO Water Filter Plant</h5>
        <button>Donate</button>
          <img src="image (6).jpg"
        width="350px" height="300px" style="border-radius: 10px;">
      </div>
      <div class="courses">
        <h5>IT Entrepreneurship Courses</h5>
        <button>Donate</button>
        <img src="image (8).jpg"
          width="350px" height="300px" style="border-radius: 10px;">
      </div>
      <div class="zakat">
        <h5>Zakat</h5>
        <button>Donate</button>
        <img src="image (7).jpg"
          width="350px" height="300px" style="border-radius: 10px;">
      </div>
    </div>

<footer class="footer">

  <div class="wave">
    <div class="copy"><p>Copyright &copy; 2023 by Saylani Walfare Int Trust</p></div>
    <div class="divider">_________________________________________________________________________________________________________________________________</div>
    <img src="https://www.saylaniwelfareusa.com/static/media/upcoming_background.a669f19ea2aee3c7e10f.png" alt="">
  </div>
  <div class="loog">
    <img src="https://www.saylaniwelfareusa.com/static/media/logo_saylaniwelfareusa.22bf709605809177256c.png" alt="">
  </div>
  <div class="face">
    <img src="Facebook.png"></div>
  <div class="twit"> 
    <img src="Twitter.jpg"></div>
  <div class="yout">
    <img src="Youtube.png"></div>
  <div class="ab">
    <span><h2>About</h2> <p>Introduction</p><p>Chairman message</p></span>
  <div class="access">
    <span><h2>Explore</h2> <p>News</p><p>Media</p><p>Contact</p><p>Donation</p></span>
  <div class="tax">
    <span><h2>Contact</h2> <p>1 E Erie St STE 525-2783 Chicago,</p><p>IL 60611</p>
    <p>Email:info@SaylaniWelfareUSA.com</p><p style="color: #1890ff;">Call: 833-786-0999</p>
    <p>Tax ID: 88-3709826</p><p>Muhammed Haris</p> </span>
  </div>


</footer>
    </body>
    </html>
