
<html>
<head>
<meta http-equiv="Content-Type"
content="text/html; charset=windows-1251">
<title>Стили</title>
<style> p {background-color: #fff;
        margin: 20px auto;
        font-family: Arial;
        font-size: 2em; 
        text-transform: uppercase;
        color: rgba(0,168,255,0.5);
        text-shadow: 8px 8px 0 rgba(255,0,180,0.5);}
</style>
<script>
function er(){
document.getElementById("out1").value="ИА - мямля";
document.getElementById("out2").value="fantastic";
document.getElementById("o3").value="light on";
document.getElementById("inf1").innerHTML ="<p>"+"ИА - мямля"+"</p>";
document.getElementById("inf2").innerHTML ="<p>"+"fantastic"+"</p>";
document.getElementById("inf3").innerHTML ="<p>"+"light on"+"</p>";
}
</script>
</head>
<body>
<button onclick="er()">1.15</button>
<br>
<br>
А)<input type="text" value="а" id="out1">
<br>
<br>
Б)<input type="text" value="б" id="out2">
<br>
<br>
В)<input type="text" value="в" id="o3">
<br>
<br>
<input type="text" value="г" id="o4">
<div id="inf1"></div>
<div id="inf2"></div>
<div id="inf3"></div>
</body>
</html>
