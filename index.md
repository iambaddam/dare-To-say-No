<html>
<head>
<style>
#n {
	position: absolute;
	top:100px;
	left: 50px;
	background-color: red;
	color: black;
}
#y {
	position: absolute;
	top:100px;
	left: 100px;
	background-color: green;
	color: black;
}
</style>
	<title> Will you be my valentine</title>
</head>
<body>
  <h1> Will you be my valentine ?</h1>
  <button type="button" id="y" onclick="myYesFuntion()"> Yes</button>
  <button type="button" id="n" onmouseover="myFunction()">No</button>
  <script>
	function myFunction(){
		document.getElementById("n").style.left = (Math.random() * 500) + "px";
		document.getElementById("n").style.top = (Math.random() * 500) + "px";
		//myFunction();
	}
</script>
<script>
       function myYesFunction() {
	    document.write ("Your waiting list number is 56");
	}
</script>
</body>
</html>
