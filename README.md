NUMEROS-PARES
=============

Este codigo nos evalúa y clasifica un numero si es entero, decimal o letra

<!doctype html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>numeros pares</title>

<script type="text/javascript">



var num = prompt("digite un numero entero");

if (isNaN(num)) {
	alert("PROBLEMAS  "  +num+   "no es un numero")
} 
else{


if (num % 1==0) {

	alert("numero ingresado es entero")
if (num % 2==0) {

	alert("numero ingresado  par")
} else{
alert("numero ingresado es impar")
};

} else{

	alert("numero ingresado es decimal")
};
 
};

	</script>	


</head>

<body>
	

	
</body>
</html>
