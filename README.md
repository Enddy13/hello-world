# hello-world
teste
readme-edits
<!DOCTYPE html>
<html lang='en'>
<head>
<title>My App Title</title>
<meta charset='utf-8'>
<meta name='viewport' content='width=device-width, initial-scale=1.0, user-scalable=no' />
<meta name="theme-color" content="#808080" />
<meta name="navigation-bar-button-color" content="#808080" />
<meta name="navigation-bar-button-border-color" content="#ffffff" />
<meta name="navigation-bar-button-hasshadow" content="true" />
<style>
body {
	font-family: Verdana, sans-serif;
	font-size: 0.8em;
	margin: 20px;
	background-color:gray

}

input[type=button]{
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
	padding:5px 25px ;
	color:white
}

input[type=text],textarea {
	-webkit-appearance: none;
	-moz-appearance: none;
	appearance: none;
}

input,select{
	border-radius:5px;
	box-shadow:0px 0px 3px 1px white;

	border:none;
	border-radius:5px;
	font-style:bold;
	font-size:25px;
	padding:5px;

}
input[type=text],input[type=date]{
	width:100%;
}

article{
	background-color:gray; 
	border-radius:5px;
	box-shadow:0px 0px 20px 1px white;
	padding:20px;
	max-width:480px;
	margin:auto;
	margin:auto;
	margin-top:40px; 
	color:white;
	font-size:25px 
}

</style>
</head>
<body>
<header>


</header>
<nav>

</nav>
<section>

<article> 
	<p>Write your Name </p> 
	<input type='text' id='nametxt'/> 
	<p>Write your Last Name</p> 
	<input type='text' id='lastnametxt' /> 
	<p>Age</p> 
	<select id='ageselect'> </select>
	<p id='personinfo'> </p> 
	<input type='button' id='showinfobtn' onclick='showInfo()' value='Show Info' /> 
<script> 
	var getName = document.getElementById('nametxt'); 
	var getLastName = document.getElementById('lastnametxt'); 
	for (var i = 0; i < 80; i++) { 
	var ageOption = document.createElement('option'); 
	ageOption.text = i; 
	this.ageselect.add(ageOption); 
}; 
	this.ageselect.selectedIndex = 7;
function showInfo() { 
	this.personinfo.innerText = 'Hello ' + getName.value + ' ' + getLastName.value + ' you are ' + this.ageselect.selectedIndex + ' years old'; } 
	</script> 
</article>

</section>

<footer>

</footer>
</body>
</html>
