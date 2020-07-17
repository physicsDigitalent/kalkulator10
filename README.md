# kalkulator10
<!DOCTYPE>
<html>
	<head>
		<meta charset="utf-8">
		<title> Web Calculator </title>
		<link rel="stylesheet" type="text/css" href="stylesheet.css">

	</head>
	<body>
		<div class="calculator">
			<div class="row">
				<div class = "calculator-message col-lg-6" ><marquee>Web Calculator| iskasipahune</marquee></div>
				<div id="dateTime" class = "calculator-date col-lg-6"></div>
			</div>
			<input type="text" class="calculator-screen"  value="0" disabled>
			<div class="calculator-keys">
				<div class="row">
					<button class="all-clear">AC</button>
					<button class="negative">+/-</button>
					<button class="operator" value="/">&divide;</button>
				</div>
				<div class="row">
					<button class="number" value="7">7</button>
					<button class="number" value="8">8</button>
					<button class="number" value="9">9</button>
					<button class="operator" value="*">&times;</button>
				</div>
				<div class="row">
					<button class="number" value="4">4</button>
					<button class="number" value="5">5</button>
					<button class="number" value="6">6</button>
					<button class="operator" value="-">-</button>
				</div>
				<div class="row">
					<button class="number" value="1">1</button>
					<button class="number" value="2">2</button>
					<button class="number" value="3">3</button>
					<button class="operator" value="+">+</button>
				</div>
				<div class="row">
					<button class="number zero-btn" value="0">0</button>
					<button class="decimal" value=".">.</button>
					<button class="equal-sign">=</button>
				</div>
			</div>
		</div>
		<script type="text/javascript" src="script.js"></script>
        <script type="text/javascript">window.onload = dateTime('dateTime');</script>
	</body>
</html>
