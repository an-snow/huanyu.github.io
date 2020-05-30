# huanyu.github.io
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<title></title>
		<style>
		.city {
		float: left;
		margin: 3px;
		padding: 10px;
		width: 300px;
		height: 300px;
		border: 1px solid black;
		} 
		</style>
	</head>
	<body>
		<h1>Universal---寰宇航空俱乐部</h1>
		<p>寰宇，一个交流飞行的飞友聚集地</p>
		<div class="city">
		<h2>成员组成</h2>
		<p>寰宇共有核心成员十余人，共同管理秩序，分设宣传部，影视制作部，开发部门等，并常年与雪桑工作室保持合作关系.There are more than 10 core members in Huanyu, who jointly manage the order, set up publicity department, film and television production department, development department, etc., and maintain cooperation with snow mulberry studio all the year round</p>
		</div>
		<div class="city">
			<h3>寰宇主旨</h3>
			<ul>
				<li>尽力解决小白的每一个问题</li>
				<li>为飞友们营造一个平等交流，活跃的氛围</li>
				<li>本群严格执行人人平等的规则，如有人违反：搞黄色过度之类的，禁言处理。</li>
			</ul>
		</div>
		<table border="1">
		</table>
	<div style="position:absolute;width: 100%;height: 100%;z-index: -1;left: auto;top: auto;">
		<img src="1.png"height="100%"width="100%"style="left: auto;top: auto;">
		<p id="demo">点击这个按钮，获得您的坐标：</p>
		<button onclick="getLocation()">试一下</button>
		<script>
		var x=document.getElementById("demo");
		function getLocation()
		  {
		  if (navigator.geolocation)
		    {
		    navigator.geolocation.getCurrentPosition(showPosition);
		    }
		  else{x.innerHTML="Geolocation is not supported by this browser.";}
		  }
		function showPosition(position)
		  {
		  x.innerHTML="Latitude: " + position.coords.latitude + 
		  "<br />Longitude: " + position.coords.longitude;	
		  }
		</script>
	</body>
</html>
