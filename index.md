
<html lang = "en">
<head>
	<meta  charset="UTF=8"/>
	<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
	<meta http-equiv="X-UA-Compatible" content="ie=edge"/>
	<link rel="stylesheet" href="WEB.css"/>
	<title>XYZ</title>
</head>
<body>
	<nav>
		<div class="hamburger">
			<div class="line"></div>
			<div class="line"></div>
			<div class="line"></div>
		</div>
		
		<ul class="nav-links">
			<li><a href="#home">Home</a></li>
			<li><a href="#aboutme">About Me</a></li>
			<li><a href="#hobbies">My Hobbies</a></li>
			<li><a href="#contact">Contact Form</a></li>
			
		</ul>
		
	</nav>
	
	<div >
		<img id="home" src="img.png" alt="My Website" style="width:100%;max-width:1000px;">
	</div>
	<div class="intro" id = "home"><b>Akash Agrawal</b></div>
	<div class = "x"><p>
	Hi , I am Akash currently pursuing B.Tech in Aerospace Engineering from IIT Bombay.
	I have always been passionate about finding how machine works and also have a great interet
	in flying objects. My other interests include coding and current affairs.
	</p>
	</div>
	<div class="intro" id = "aboutme"><b>About Me</b></div>
	
	<div class = "x"><p>	
	I like to explore new things in technology, of which machine learning fascinates me the most.
	<br><br>
	I prefer to spend my time playing badmintom or playing mobile games.
	<br><br>
	</p>
	</div>
	<div class="intro" id = "hobbies"><b>My Hobbies</b></div>
	<div class = "x"><p>
	Cycling<br>
    Playing cricket, badminton, electronic games<br>
    Traveling<br>
    Swimming<br><br><br><br>
	</p></div>
	<div class="intro" ><b>Contact</b></div>
	<div class="container" >
		<h1 class="h"  style="text-align: center;margin-bottom: 45px;">Contact Form</h1>
		<form id = "contact"
		action="https://formspree.io/xvowdolz"
		method="POST"
	  >
	  <div style="text-align: center;">
		<label>
		  Your Name</label></div>
		  <div style="text-align: center;">
		  <input type="text" name="name"  placeholder="Your name....">
		
	</div>
	  <div style="text-align: center;">
		<label>
		  Your email</label></div>
		  <div style="text-align: center;">
		  <input type="text" name="_replyto" placeholder="Your email.......">
		
	</div>
		<div style="text-align: center;">
		<label>
		  Message</label></div>
		  <div style="text-align: center;">
		  <textarea name="message" placeholder="Write something......"></textarea>
		
	</div>
		<!-- your other form fields go here -->
	  <div><button type="submit">Send</button></div>	
		
	  </form>
	</div>
	<br><br><br><br>
	<script src="app.js"></script>
</body>
</html>
