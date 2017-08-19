
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,minimum-scale=1.0,user-scalable=0">
<title>2048</title>

<link rel="stylesheet" href="css/reset.min.css">
<link rel="stylesheet" href="css/style.css">

</head>

<body>

<header>
	<div class="container">
		<h1><span>2</span><span>0</span><span>4</span><span>8</span></h1>
		<p class="inspired">by the原2048的灵感。</p>
	</div>
</header>

<div class="container">
	<div class="directions">
		<p><strong>如何玩：</strong> 使用鼠标方向键键移动数字方块。相邻的两个方块数字相同，它们可合并成一个！</p>
	</div>
	<div class="scores">
		<div class="score-container best-score">
			最佳: 
			<div class="score">
				<div id="bestScore">0</div>
			</div>
		</div>
		<div class="score-container">
			分数: 
			<div class="score">
				<div id="score">0</div>
				<div class="add" id="add"></div>
			</div>
		</div>
	</div>
	<div class="game">
		<div id="tile-container" class="tile-container"></div>
		<div class="end" id="end">游戏结束<div class="monkey">🙈</div><button class="btn not-recommended__item js-restart-btn" id="try-again">再试一次</button></div>
	</div>

	<div class="not-recommended">
		<button class="btn not-recommended__item js-restart-btn" id="restart">重新启动游戏</button>
		<span class="not-recommended__annotation"></span>
	</div>

</div>

<script src="js/index.js"></script>
<div style="text-align:center;">
<p><a href="http://www.mycodes.net/" target="_blank">源码之家</a></p>
</div>
<script src="http://www.mycodes.net/js/tongji.js"></script>
<center><script src="http://www.mycodes.net/js/youxia.js" type="text/javascript"></script></center>
</body>
</html>
