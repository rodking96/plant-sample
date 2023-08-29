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
<div scroll-down">
  <a href=#"><i class="ri-arrow-down-s-fill"></i></a>
</div>

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
.scroll-down{
  position: absolute; 
  bottom: 6%;
  right: 9%;
}
.scroll-down i{
  display: block;
  padding: 12px;
  font-size: 25px;
  color: white;
  background: #4d9559;
  border-radius: 30px;
  transition: all .50s ease;
}
.scroll-down i:hover{
  transform: translateY(-5px);
}
@media (max-width: 1535px){
  header{
    padding: 15px 3%;
    transition: .2s
  }
  .icons{
    padding: 0 3%;
    transition: .2s;
  }
  .scroll-down{
    right: 3%;
    transition: .2s;
  }
}
@media (max-width: 1460px){
  section{
    padding: 0 12%;
    transition: .2s;
  }
}
@media (max-width: 1340px){
  .hero-img img{
    width: 100%;
    height: auto;
  }
  .hero-text h1{
    font-size: 75px;
    margin: 0 0 30px;
  }
  .hero-text h5{
    margin-bottom: 25px;
  }
}
@media (max-width: 1195px){
  section{
    padding: 0 3%;
    transition: .2s;
  }
  .hero-text{
    padding-top: 115px;
  }
  .hero-img{
    text-align: center;
  }
  .hero-img img{
    width: 560px;
    height: auto;
  }
  .hero{
    height: 100%;
    gap: 2rem;
    grid-template-coulumns: 1fr;
  }
  .icons{
    display: none;
  }
  .scroll-down{
    display: none;
  }
}
@media (max-width: 990px){
  #menu-icon{
    display: block;
  }
  .navlist{
    position: absolute;
    top: 100%;
    right: -100%;
    width: 300px;
    height: 40vh;
    background: #4d9559;
    display: flex;
    align-items: center;
    flex-direction: column;
    padding: 50px 20px;
    transition: all .55s ease;
  }
  .navlist a{
    margin-left: 0;
    display: block;
    margin: 7px 0;
  }
  .navlist.open{
    right: 0;
  }
}
@media (max-width: 680px){
  .hero-img img{
    width: 100%;
    height: auto;
  }
}































