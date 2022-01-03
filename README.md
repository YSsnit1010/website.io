# website.io
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">
    <link rel="stylesheet" href="newstyle.css">
    <title>Fiyorina</title>
<style>
   
</style>
</head>
<body>
    <nav class="nav-main">
        <div class="logo"></div>
    
<ul>
  <li><a href="about_us.html">About Us</a></li>
  <li><a href="our_offices.html">Our Offices</a></li>
  
  <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">What We Do</a>
    <div class="dropdown-content">
      <a href="fight-against-hunger.html">Fight Against Hunger</a>
      <a href="education.html">Education</a>
      <a href="resilience.html">Resilience</a>
    </div>
    <li><a href="newstyle.html">Home</a></li>
  </li>
</ul>
    </nav>
<div class="hero-image">
    <div class="hero-text">
        <h1 id="header" style="color: white;font-size:50px;">Be The Change You Want To See In The World</h1>
        <button class="button">Donate</button>
    </div>
</div>
<div class="secondpart">
    <h2 id="header" style="color: rgb(47, 129, 236);font-size: xx-large;">Rescue The Next Generation</h2>
    <p style="color: black;font-size: large;">
        Fiyorina fights and works with effort for chidren's rights and their future.</p> 
    <p style="color: black;font-size: large;">
        The young generation is today's seed but tomorrow's flower that we the older generation must look after and nourish.</p> 
    <p style="color: black;font-size: large;">
        This is why we invite you to join our community to make these children's lives better</p>
</div>
<section class="thirdpart">
    <h3 id="header2" style="color: black;">Contact Us</h3>
    <p style="color: black;font-size: large;">
        xxx.123@gmail.com</p>
</section>


</body>
</html>
body {
    text-align: center;
    font-family: "Sofia", sans-serif;
}
.hero-image{
    background-image: url("image/doll.jpg");
    background-repeat: no-repeat;
    background-attachment:fixed;
    background-position: center;
    background-size: cover;
    height:750px;
    position:static;
    margin-top: 0;
    padding-top: 0;
}
.hero-text {
    text-align: center;
    position: relative;
    top: 50%;
    font:xx-large;
    
}
button {
    padding: 15px 25px;
    font-size: 24px;
    font-family: "Sofia", serif;
    text-align: center;
    cursor: pointer;
    outline: none;
    color: #fff;
    background-color: #0446aa;
    border: none;
    border-radius: 15px;
}

.button:hover {background-color: #3e898e}



#header {
    margin-top: 0px;
    margin-bottom: 0px;
}
#header2 {
    margin-top: 0px;
    margin-bottom: 0px;
}
.secondpart {
    background-color:rgb(236, 232, 232);
    text-align: center;
    
}
.thirdpart {
    background-color:rgb(47, 129, 236);
    text-align: center;
    margin-top: -20px;
    padding-top: -20px;
}
.nav-main {
    width: 100%;
    height: 60px;
    background-color: rgb(236, 232, 232);
    list-style-type: none;
    font-family: "Sofia", sans-serif;
    font: medium;
    margin: 0;
    padding: 0;
    overflow: hidden;
    float: right;
}


ul {
list-style-type: none;
font-family: "Sofia", sans-serif;
font: large;
margin: 0;
padding: 0;
overflow: hidden;
float: right;
}

li {
float:right;
}
.logo {
    width: 60px;
    height: 100%;
    float: left;
    background-image: url("image/logo_fiyorina\ \(2\).jpg");
    background-repeat: no-repeat;
    background-size: 75%;
    background-position: center;
    cursor: pointer;
}

li a, .dropbtn {
display: inline-block;
color: black;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
background-color: rgb(47, 129, 236);
}

li.dropdown {
display: inline-block;
}

.dropdown-content {
display: none;
position: absolute;
background-color: rgb(236, 232, 232);
min-width: 160px;
box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
z-index: 1;
}

.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
text-align: left;
}

.dropdown-content a:hover {background-color: rgb(201, 192, 192);}

.dropdown:hover .dropdown-content {
display: block;
}

