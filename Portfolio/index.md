<!DOCTYPE html>
<html>
<head>
	<title> Colin McDonnell | Portfolio | University of Southern California</title>

	<link rel = 'stylesheet' href = 'main.css'>
	<style>
		#header h1{
			font-size: 40px;
			font-family:'Overpass', sans-serif;
			text-align: left;
			margin-left:20px;
			color:#03045E;

		}
		#header p{
			color: #646E78;
			font-size: 20px;
			margin-left:25px;
			margin-bottom: -20px;
			font-family:'Overpass', sans-serif;
		}
		#header img{
			width: 140px;
			height:140px;
			border-radius: 50%;
			float:right;
			margin: 30px;
		}

		#header h1:hover{
			color: #03045E;
		}
		.box:hover .centered{
			visibility: visible;
		}
		.box:hover{
			transform: scale(1.2);
		}
		.box:hover img{
			opacity: 50%;
		}
		a:visited{
			color:#03045E;
		}
		.box{
			width: 380px;
			height: 380px;
			margin:25px;
			border-radius: 5%;
			border:solid .5px #03045E;
			background-color: white;
			float: left;
			overflow:hidden;
			transition: .3s;
			position: relative;
			text-align: center;
			font-family:'Overpass', sans-serif;
			color:#03045E;
			text-decoration: none;
		}

		.centered{
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			visibility: hidden;
			font-size:40px;

		}
		img{
			width:380px;
			height:380px;
			object-fit: cover;

		}
		#r1c2{
			width: 350px;
			height:390px;
		}


	</style>
</head>

<body>
<div id = "wrapper">
	<div id = "header">
		<img id = 'profpic' src = 'img/profpic.jpeg' alt = 'Colin Profile Picture'>
		<h1> Colin McDonnell</h1>
		<p> Hi! I'm Colin and I'm currently a product designer for MechanicAI. I am a Junior at the University of Southern California studying Data Science and Cognitive Science, heavily focused on entrepreneurial efforts!</p>
		<div id = "navbar">
		<div id = "nav">
			<a href = 'about.html'> About</a>
			<a id = 'active-nav' href = 'portfolio.html'> Work</a>
		</div>
		</div>

	</div>

	<div class = 'clearfloat'></div>

	<div id = "container">

		<div class = "row" id = "row1">
			<div class = "box" id = 'row1col1'>
				<a href = 'mechanicai.html'>
				<img id = 'r1c1' src = 'img/carr.jpeg' alt = 'Mechanic AI Logo'>
				<div class = 'centered'> MechanicAI</div>
			</a>
			</div>
			<div class = "box" id = 'row1col2'>
			<a href = 'hotel.html'>
				<img id = 'r1c2' src = 'img/hotel.png' alt = 'LavaLab Logo'>
				<div class = 'centered'> Hotel Project</div>
			</a>
			</div>
		</div>

		<div class = "row" id = "row2">
			<div class = "box" id = 'row2col1'>
				<img id = 'r2c2' src = 'img/autobound.png' alt = 'Autobound Logo'>
				<div class = 'centered'> Autobound</div>
			</div>
			<div class = "box" id = 'row2col2'>
				<img id = 'r2c2' src = 'img/sparksc.png' alt = 'Spark SC Logo'>
				<div class = 'centered'> Spark SC</div>
			</div>
		</div>


	</div>

</div>

<script>


</script>

</body>
</html>