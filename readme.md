<!doctype html>
<html lang="ru">
	<head>
		<meta charset="Utf-8">
		<meta name="site">
		<title>Shop</title>
		<style>
			@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200;500&display=swap");
			* {
				margin: 0;
				padding: 0;
				box-sizing: border-box;
			}
			body {
				font-family: "Montserrat", sans-serif;
				font-weight: 200;
				color: var(--tg-theme-text-color);
				background: var(--tg-theme-bg-color);
			}
			#main {
				width: 100%
				padding: 20px;
				text-align: center;
			}
			h1 {
				margin-top: 50px;
				margin-bottom: 10px;
			img {
				width: 40px;
				margin: 0px;
			}
			p {
				width: 350px;
				margin: 0 auto;
				
			}
			button {
				border: 0;
				border-radius: 5px;
				margin-top: 50px;
				height: 60px;
				width: 2000px;
				font-size: 20px;
				font-weight: 500;
				cursor: pointer;
				transition: all 500ms case;
				color: var(--tg-theme-button-color);
				background: var(--tg-theme-button-text-color);
			}
			button:hover {
				background: var(--tg-theme-secondary-bg-color)
			}
		</style>
	</head>
	<body>
		<div id="main">
			<h1>Онлайн магазин</h1>
			<img src="https://cdn-icons-png.flaticon.com/512/3595/3595455.png">
			<button id="buy">Купить</button>
			<p>Hi, can you buy this object</p>
		</div>
		<script src="https://telegram.org/js/telegram-web-app.js"></script>
	</body>
</html>
