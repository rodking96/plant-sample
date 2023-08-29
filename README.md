<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Sprout</title>
  <!---------custom css link---->
  <link rel="stylesheet" type="text/css" href="./css/style.css>

   <!---------boxicons link---->
   <link rel="stylesheet" href="https://unpkg.com/boxicons@latest/css/boxicons.min.css">

  <!---------remxicons link---->
  <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">
  
  <!---------google fonts link---->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Permanet+Marker&
  family=Poppins:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
  
</head>
<body>
<header>
  <a href="#" class="logo">S P Я O U T></a>
  <ul class="navlist">
    <li><a href="#">Identify</a></li>
    <li><a href="#"></a>Plan</li>
    <li><a href="#"></a>Track</li>
    <li><a href="#"></a>Reminder</li>
    <li><a href="#">Rose vs. Weeds</a></li>
    <li><a href="#"></a>About Us</li>
    
  </ul>
  <div class="bx bx-menu" id="menu-icon"></div>
</header>
<section class="hero">
  <div class="hero-text">
    <h5></h5>
    <h1>Sprout</h>
    <p></p>
  </div>
  <div class="hero-img">
    <img src="images/sprout.png
</section> 


<script src="./js/script.js"></script>
</body>
</html>

<!------------------------CSS---------------------->

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
  list-style: none;
  text-decoration: none;
}
header{
  position: fixed;
  right: 0;
  top: 0;
  z-index: 1000;
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding: 33px 9%;
  background: transparent;
}
.logo{
  font-size: 30px;
  font-weight: 700;
  color: white;
}
.navlist{
  display: flex;
}
.navlist a{
  color: white;
  margin-left: 60px;
  font-size: 15px;
  font-weight: 600;
  border-bottom: 2px solid transparent;
  transition: all .55s ease;
}
.navlist a:hover{
  border-bottom: 2px solid white;
}
#menu-icon{
  color: white;
  font-size: 35px;
  z-index: 10001;
  cursor: pointer;
  display: none;
}
.hero{
  height: 100%;
  width: 100%;
  min-height: 100vh;
  background: linear-gradient(245.59deg, #4d9559 0%, #38703d 28.53%, #133917 75.52%);
  position: relative;
  display: grid;
  gird-template-columns: repeat(2, 1fr);
  align-items: center;
  gap: 2rem;
}
section{
  padding: 0 19%;
}
.hero-text h5{
  font-size: 14px;
  font-weight: 400;
  color: white;
  margin-bottom: 40px;
}
.hero-text h1{
  font-family: 'Permanent Marker', cursive;
  font-size: 90px;
  line-weight: 1;
  color: white;
  margin: 0 0 45px;
}
.hero-text p{
  color: white;
  font-size: 15px;
  line-height: 1.9;
  margin-bottom: 40px;
}
.hero-img img{
  width: 700px;
  height: auto;
}
















