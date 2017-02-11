<!DOCTYPE html>
<html>
<head>
<style>
#n {
	position: absolute;
	top:100px;
	left: 50px;
}
#y {
	position: absolute;
	top:100px;
	left: 100px;
}
</style>
	<title> Will you be my valentine</title>
</head>
<body>
  <h1> Will you be my valentine ?</h1>
  <button type="button" id="y"> Yes</button>
  <button type="button" id="n" onmouseover="myFunction()">No</button>
  <script>
	function myFunction(){
		document.getElementById("n").style.left = (Math.random() * 500) + "px";
		document.getElementById("n").style.top = (Math.random() * 500) + "px";
		myFunction();
	}
</script>
</body>
</html>
