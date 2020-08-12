<html lang="zh">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<meta http-equiv="X-UA-Compatible" content="ie=edge">
		<link rel="stylesheet" type="text/css" href="css/about.css" />
		<title>欢乐联盟</title>
		<link rel="icon" href="img/logo-public.png" type="image/x-icon">
		<style type="text/css">
			body {
				margin: 0;
				padding: 0;
				background-color: darkslategray;
			}

			.name {
				width: 100vw;
				height: 100vh;
				background-color: darkslategray;
			}

			.head {
				width: 100%;
				height: 10%;
				background-color: darkcyan;
			}

			.top1 {
				float: left;
				width: 15%;
				height: 100%;
				background-image: url(img/1.png);

			}

			h4 {
				font-size: 20px;
				font-weight: 400;
				text-align: center;
				color: yellow;

			}

			.top2 {
				float: left;
				width: 85%;
				height: 100%;
				background-color: #060d19;
			}

			ul li {
				list-style-type: none;
				font-size: 30px;
				font-weight: bold;
				color: yellow;
				margin-left: 150px;
				display: inline;
				line-height: 40px;
				float: left;
				letter-spacing: 20px;
			}

			a {
				text-decoration: none;
				color: yellow;
			}
			
			.hbody{
				float: top;
				width: 100%;
				height: 80%;
				background-color: #00aa7f;
				font-size: 30px;
				font-weight: 600;
				color: #FFFFFF;
				text-align: center;
			}
			.footing{
				width: 100%;
				height: 10%;
				background-color: #060d19;
				color: #FFFF00;
				text-align: center;
			}
			img{
				width: 200px;
				height: 200px;
			}
		</style>
	</head>
	<body>
		<div class="name">
			<div class="head">
				<div class="top1">
					<h4><a href="index.html">League of Legends</a></h4>
				</div>
				<div class="top2">
					<ul>
						<li><a href="xiaomo.html">小莫</a></li>
						<li><a href="naihe.html">奈何</a></li>
						<li><a href="mao.html">猫</a></li>
						<li><a href="longfan.html">小帆</a></li>
					</ul>
				</div>
			</div>
			<div class="hbody">
				欢迎来到召唤师联盟
				<div class="slidershow middle">
				
					<div class="slides">
						<input type="radio" name="r" id="r1" checked />
						<input type="radio" name="r" id="r2" />
						<input type="radio" name="r" id="r3" />
						<input type="radio" name="r" id="r4" />
						<input type="radio" name="r" id="r5" />
						<div class="slide s1">
							<img src="img/1.png" alt="">
						</div>
						<div class="slide">
							<img src="img/mao.jpg" alt="">
						</div>
						<div class="slide">
							<img src="img/naihe.jpg" alt="">
						</div>
						<div class="slide">
							<img src="img/xiaomo.jpg" alt="">
						</div>
						<div class="slide">
							<img src="img/mao.jpg" alt="">
						</div>
				
						<div class="navigation">
							<label for="r1" class="bar"></label>
							<label for="r2" class="bar"></label>
							<label for="r3" class="bar"></label>
							<label for="r4" class="bar"></label>
							<label for="r5" class="bar"></label>
						</div>
					</div>
				</div>
			</div>
			<div class="footing">
				copyright: &nbsp; 欢乐联盟
			</div>
		</div>
		<audio src="audio/Free Loop.mp3" autoplay loop>
			当前浏览器不支持audio
		</audio>
	</body>
</html>
