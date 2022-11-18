[README.md](https://github.com/Pavan1205/Template-for-Travel-agency-website/files/10037064/README.md)
# Template-for-Travel-agency-website

<!DOCTYPE html>
<html>
<head>
	<title>Travel Website</title>
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="navbar">
		<div class="logo">
			<h1>Travel</h1>
		</div>
		<div class="menu">
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Services</a></li>
				<li><a href="#">Places</a></li>
				<li><a href="#">Discounts</a></li>
				<li><a href="#">Contact</a></li>
				<li><a href="#">Booking</a></li>
			</ul>
		</div>
		<div class="signup">
			<a href="#">Sign Up</a>
		</div>
	</div>
	<div class="body">
		<div class="heading">
			<h1>Travel With Us</h1>
			<br>
			<p>ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
			tempor incididunt ut labore et dolore magna aliqua. </p>
			<br>
			<br>
			<a href="#">Learn More</a>
		</div>
		<div class="tours">
			<div class="places">
				<h2>Australia</h2>
				<img src="img1.jpg" style="width: 300px; height: 250px; border-radius: 12px;">
				<br>
				<br>
				<a href="#">Book Now 15% OFF</a>
			</div>
			<div class="places">
				<h2>New York</h2>
				<img src="img2.jpg" style="width: 300px; height: 250px; border-radius: 12px;">
				<br>
				<br>
				<a href="#">Book Now 20% OFF</a>
			</div>
			<div class="places">
				<h2>Thailand</h2>
				<img src="img3.jpg" style="width: 300px; height: 250px; border-radius: 12px;">
				<br>
				<br>
				<a href="#">Book Now 25% OFF</a>
			</div>
		</div>
	</div>
	<div class="footer">
		<a href="#">Copyright</a>
		<a href="#">Terms and Conditions</a>
		<a href="#">Privacy Policy</a>
		<a href="#">Cookies</a>
		<a href="#">Complaints</a>
	</div>
</body>
</html>

style.css
*{
	padding: 0px;
	margin: 0px;
	box-sizing: border-box;
	list-style: none;
	font-family: 'Poppins', sans-serif;

}
.navbar{
	width: 100%;
	height: 80px;
	background-color: #fee;
	display: flex;
	justify-content: space-around;
	align-items: center;
	color: #000;
}
.menu ul{
	display: flex;
	align-items: center;
}
.menu ul li a{
	text-decoration: none;
	color: #000;
	padding: 5px 12px;
	letter-spacing: 2px;
	font-size: 18px;
}
.menu ul li a:hover{
	border-bottom: 4px solid #000;
	transition: 0.4s;
} 
.signup a{
	text-decoration: none;
	color: #000;
	font-size: 18px;
	font-weight: bold;
	border-radius: 12px;
	padding: 12px 30px;
	border: 2px solid #ff0000;
}
.signup a:hover{
	background-color: red;
	transition: 0.6s;
}
.body{
	width: 100%;
	height: 90vh;
	display: flex;
	justify-content: space-around;
	align-items: center;
	background-image: linear-gradient(rgba(0,0,0,0.50),rgba(0,0,0,0.50)),url(img1.jpg);
	background-position: center;
	background-size: cover;
}
.heading{
	width: 30%;
	text-align: center;
	color: #fff;
}
.heading h1{
	font-size: 40px;
}
.heading a{
	text-decoration: none;
	color: #000;
	font-size: 25px;
	font-weight: bold;
	border-radius: 45px;
	padding: 14px 50px;
	background-color: #fff;
}
.heading a:hover{
	letter-spacing: 3px;
	transition: 0.6s;
}
.tours{
	width: 70%;
	display: flex;
	justify-content: space-around;
}
.places{
	display: inline;
	text-align: center;
	border-radius: 12px;
}
.places h2{
	color: red;
	font-size: 35px;
	letter-spacing: 3px;
	border-radius: 1px;
	padding: 30px 30px;
	background-color: #000;
}
.places a{
	text-decoration: none;
	color: red;
	font-weight: bold;
	font-size: 18px;
	border-radius: 12px;
	padding: 12px 30px;
	background-color: #fff;
}
.places a:hover{
	background-color: #000;
	letter-spacing: 3px;
	transition: 0.6s;
}
.footer{
	width: 100%;
	height: 50px;
	display: flex;
	justify-content: space-around;
	align-items: center;
}
.footer a{
	text-decoration: none;
	color: green;
	font-size: 18px;
	font-weight: bold;
}
.footer a:hover{
	text-decoration: underline;
	transition: 0.4s;
}











