<!DOCTYPE html>
<!--Code by Divinector (www.divinectorweb.com)-->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>kashware</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">    
</head>
<body>
    <header>
    <div class="wrapper">
        <div class="logo">
            <img src="https://i.postimg.cc/mg4rWBmv/logo.png" alt="">
        </div>
<ul class="nav-area">
<li><a href="#">KARD</a></li>
<li><a href="#">KARDLESS</a></li>
<li><a href="#">SECURITY</a></li>
<li><a href="#">REWARDS</a></li>
<li><a href="#">GET THE APP</a></li>
</ul>
</div>
<div class="welcome-text">
        <h1>
 Kashware <span> is an exclusive ecosystem that units you money</span></h1>
<a href="#">Contact US</a>
    </div>
</header>
</body>
</html>

css

* {
 margin: 0;
 padding: 0;
}
body {
 font-family: 'Poppins', sans-serif;
}
.wrapper {
 width: 1170px;
 margin: auto;
}
header {
 background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url(https://i.postimg.cc/YjcJg24M/aa.jpg);
 height: 100vh;
 -webkit-background-size: cover;
 background-size: cover;
 background-position: center center;
 position: relative;
}
.nav-area {
 float: right;
 list-style: none;
 margin-top: 30px;
}
.nav-area li {
 display: inline-block;
}
.nav-area li a {
 color: #fff;
 text-decoration: none;
 padding: 5px 20px;
 font-family: poppins;
 font-size: 16px;
 text-transform: uppercase;
}
.nav-area li a:hover {
 background: #fff;
 color: #333;
}
.logo {
 float: left;
}
.logo img {
 width: 100%;
 padding: 15px 0;
}
.welcome-text {
 position: absolute;
 width: 600px;
 height: 300px;
 margin: 20% 30%;
 text-align: center;
}
.welcome-text h1 {
 text-align: center;
 color: #fff;
 text-transform: uppercase;
 font-size: 60px;
}
.welcome-text h1 span {
 color: #00fecb;
}
.welcome-text a {
 border: 1px solid #fff;
 padding: 10px 25px;
 text-decoration: none;
 text-transform: uppercase;
 font-size: 14px;
 margin-top: 20px;
 display: inline-block;
 color: #fff;
}
.welcome-text a:hover {
 background: #fff;
 color: #333;
}
/*resposive*/
@media (max-width:600px) {
 .wrapper {
  width: 100%;
 }
 .logo {
  float: none;
  width: 50%;
  text-align: center;
  margin: auto;
 }
 img {
  width: ;
 }
 .nav-area {
  float: none;
  margin-top: 0;
 }
 .nav-area li a {
  padding: 5px;
  font-size: 11px;
 }
 .nav-area {
  text-align: center;
 }
 .welcome-text {
  width: 100%;
  height: auto;
  margin: 30% 0;
 }
 .welcome-text h1 {
  font-size: 30px;
 }
}
