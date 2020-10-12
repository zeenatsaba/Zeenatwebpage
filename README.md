# Zeenatwebpage
<html>
	<head>
		<title>My First HTML Page</title>

		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<style>
		* {
			margin: 0;
			font-family: Tahoma;
		}
		img {
			max-width: 100%;
		}
		.wrap {
		}
		.img {
			border-radius: 50%;
			width: 100px;
		}
		.row1, .row2, .row6, .row7, .wrap1 {
			background-color: #a1a1a1;
		}
		.row3, .row4, .row5, .row8, .wrap2 {
			background-color: #ccc;
		}
                       .row1, .row7 {
			width: 80%;
			margin: 0 auto;
			display: grid;
			grid-template-columns: auto auto;
			grid-gap: 20px;
		}
		.row4, .row5 {
			width: 80%;
			margin: 0 auto;
			display: grid;
			grid-template-columns: auto auto auto;
			grid-gap: 20px;
			padding-bottom: 30px;
		}
		.bgwhite {
			background-color: #fff;
		}
		.bgblack {
			background-color: #000;
			color: #fff;
		}
		.alignright {
			text-align: right;
		}
		.aligncenter {
			text-align: center;
		}
		.row1, .pad20 {
			padding: 20px;
		}
		.row2 a {
			background-color: #000;
			color: #fff;
			padding: 10px 15px;
			text-decoration: none;
		}

@media only screen and (max-width:576px) {
			.row1, .row7, .row4, .row5 {
				grid-template-columns: auto;
			}
			.row1 div, .row7 div {
				text-align: center;
			}
			.row7 div ul {
				text-align: left;
			}
		}
		</style>
	</head>
<body>
		<div class="wrap1">
			<div class="row1">
				<div><img src="ZeenatDP.jpg" class="img"></div>
				<div class="alignright pad20">
					<h4>Zeenat Saba</h4>
					<p>Web Developer<br>
					B.Tech CSE</p>
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row2 aligncenter pad20">
				<a href="">Projects</a><a href="">About</a><a href="">Contact</a>
			</div>
		</div>
		<div class="wrap">
			<div class="row3 aligncenter pad20">
				<h2>Projects/Experience</h2>
			</div>
		</div>
<div class="wrap2">
			<div class="row4">
				<div>
					<img src="ZeenatAI.jpg">
					<p>ARTIFICIAL INTELLIGENCE</p>
					
				</div>
				<div>
					<img src="zeenattense.jpg">
					<p>UNIVERSITY OF CALIFORNIA</p>
					
				</div>
				<div>
					<img src="ZeenatT.jpg">
					<p>TCS ION</p>
					
				</div>
			</div>
		</div>
<div class="wrap2">
			<div class="row5">
				<div>
					<img src="zeenatB.jpg">
					<p>IIT BOMBAY</p>
				</div>
				<div>
					<img src="zeenatC.jpg">
					<p>ZEAL INSTITUTES</p>
					
				</div>
				<div>
					<img src="zeenatp.jpg">
					<p>CERTIFICATE OF EXCELLENCE</p>
					
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row6 aligncenter pad20">
				<h2>About Me</h2>
			</div>
		</div>
<div class="wrap1">
			<div class="row7">
				<div class="bgwhite pad20">
					<h4 class="aligncenter">Personal Details</h4>
					<ul>
						<li>Zeenat Saba</li>
						<li>DOB: 11-09-2001</li>
						<li>PHONE:_________</li>
						<li>STATUS: CSE Student </li>
						<li>Under-graduate</li>
					</ul>
				</div>
				<div class="bgblack pad20">
					<h4 class="aligncenter">Education/Skillset</h4>
					<ul>
						<li>B.Tech</li>
						<li>HTML</li>
						<li>CSS</li>
						<li>PHP</li>
						<li>Developer</li>
					</ul>
				</div>
			</div>
		</div>
		<div class="wrap">
			<div class="row8 aligncenter pad20">&copy; Copyright 2020.</div>
		</div>
	</body>
</html>
