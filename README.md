<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    


<body>
    
    <header class="header">
        <a href="#" class="logo">Cars.</a>

        <nav class="nav-bar">
            <a class="active" href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Review</a>
            <a href="#">Featured</a>
            <a href="#">Contact</a>
        </nav>

        <div class="social-media">
            <a href="#"><i class='bx bxl-twitter'></i></a>
            <a href="#"><i class='bx bxl-facebook'></i></a>
            <a href="#"><i class='bx bxl-instagram' ></i></a>
        </div>
    </header>

<section class="home">
    <div class="home-content">
        <h1>Car Dealing Experience.</h1>
        <h3>Redefined!</h3>
        <p>This is a car servicing point</p>
        <a href="#" class="btn">Explore Cars</a>
    </div>

    <div class="home-img">
        <div class="rhombus">
        <img src="css/car.png " alt=" ">
    </div>
</section>
</body>
</html>







.......css......








*{
    margin:0;
    padding:0;
    box-sizing: border-box;
    font-family: 'poppins', sans-serif;
}

body{
    background-color: #eaeaea;
}

.header{
    position:fixed;
    top:0;
    left:0;
    width: 100%;
    padding: 30px 8%;
    background: transparent;
    display:flex;
    justify-content:center;
    align-items: center;
    z-index: 100;
}

.logo{
    font-size: 25px;
    color: #222;
    text-decoration: none;
    font-weight:600;
    
}

.nav-bar a {
    font-size:18px;
    color: #222;
    text-decoration:none;
    font-weight: 500;
    margin: 0 20px;
    transition: .3s;
}

.nav-bar a:hover,
.nav-bar a.active
{
    color:#1743e3;
}

.social-media{
    width: 150px;
    height: 40px;
   
}

.social-media a {
display: inline-flex;
justify-content: center;
align-items: center;
width: 40px;
height: 40px;
background: transparent;
border: 2px solid transparent;
text-decoration: none;
transform: rotate(45deg);
transition: .5s;
}
.social-media a:hover{
    border-color: red;
}

.social-media a i {
    font-size: 24px;
    color: red;
    transform: rotate(-45deg)
}  
  
.home{
    position:relative;
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: space-between;
    align-items:center;
    padding: 50px 8% 0;
 
}

.home-content{
    max-width: 630px;
}

.home-content h1{
    font-size: 50px; 
    line-height: 1.2;
}

.home-content h3{
    font-size:40px;
    color:#1743e3;
}
.home-content p{
    font-size: 16px;
    margin: 15px 0 30px;;
}

.btn {
    display: inline-block;
    padding: 10px 28px;
    background:#1743e3;
    border-radius: 6px;
    box-shadow:0 0 10px rgba(0,0,0,.1);
    font-size: 16px;
    color: #eaeaea;
    letter-spacing: 1px;
    text-decoration: none;
    font-weight: 600;
    transition: .5s;
}

.btn:hover {
    background: transparent;
    color: #1743e3;
}
    
.home-img{
    position: relative;
    right: -7%;
    width: 450px;
    height: 450px;
    transform: rotate(45deg);
}

.home-img .rhombus {
    position: absolute;
    width: 100%;
    height: 100%;
    background: #eaeaea;
    border: 25px solid #1743e3;
} 

.home-img .rhombus img {
    position: absolute;
    top: 110px;
    left: -250px;
    max-width: 750px;
    transform: rotate(-45deg); 
}

.home .rhombus2 {
    position:absolute;
    top: -250px;
    right: -25px;
    width: 700px;
    height: 700px;
    background: #1743e3;
    transform:rotate(45deg);
}

