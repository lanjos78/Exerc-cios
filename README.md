# Exerícios
//Exercicio cores RGB
<!DOCTYPE html>
<html>
<head>
	<script type="application/javascript">
	function init()
	{
		var canvas = document.getElementById("canvas");
		if (canvas.getContext)
		{
			var ctx = canvas.getContext("2d");
			// Especifica uma cor em RGB
			ctx.fillStyle = "rgb(200, 0, 0 )" ;
			ctx.fillRect(300, 40, 100, 50);
		}

	}	
	</script>
</head>
<body onload="init();">
	<canvas id="canvas" width="500"> height="500"></canvas><br>

</body>
</html>
