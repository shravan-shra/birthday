
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">

	<title></title>
	<link rel="stylesheet" type="text/css" href="style2.css">
</head>
<body>
<h1> HAppy birthday </h1>
</body>

<script>

	//createElement

	/*var btn = document.createElement("BUTTON");
	btn.innerHTMLL="Click";
	document.body.appendChild(btn);*/



function createHeart(){
	const h =  document.createElement("div");
	h.classList.add("sai");
	h.style.left=Math.random()*100+"vw";
	h.style.animationDuration=Math.random()*2+6+"s";

	h.innerText="🎈🎈🎈 🎈🎈 🎈🎈🎈"; 

	document.body.appendChild(h);



}
	setInterval(createHeart , 200);

</script>
</html>
