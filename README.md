<!doctype html>
<html>
<head>
<meta charset='utf-8'>
<title>Jinhua Test</title>
<link rel="stylesheet" href="main.css"/>
<script src="/socket.io/socket.io.js"></script>
<script src="js/jquery-1.11.2.min.js"></script>
<script src="js/jquery.cookie.js"></script>
<script src="js/hotjs-i18n.js"></script>
<script src="js/en.lang.js"></script>
<script src="js/zh.lang.js"></script>
<script src="main.js"></script>
</head>
<body>
	<div id='env'>
		<span class='I18N' i18n='language'>Language</span>: <select id='lang'>
		<option value='en'>English</option>
		<option value='zh'>中文</option>
		</select>
		<h3 id="roomname"></h3>
		<div id='roomdesc'></div>
		<h3 id='sharedcards'></h3>
		<h3 id='pot'></h3>
		<h3 id='countdown'></h3>
		<ul id="seats"></ul>
		<h3 id='mycards'></h3>
	</div>
	<div id='logs'>
	<ul id="messages" class="list"></ul>
	</div>
<!-- 
	<form action="">
		<input id="m" autocomplete="off" />
		<button id='send'>Send</button>
	</form>
 -->	
	<div id='cmds' class='inactive'></div>
</body>
</html>
