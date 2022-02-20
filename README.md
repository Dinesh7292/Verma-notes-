
<!DOCTYPE html>
<html>
<head>
<title>Symbol easy to search</title>
<style type="text/css">
input{
height:50px;
width:350px;

}
button{
width:250px;

}
</style>
</head>
<body bgcolor="silver" >
<header>

<h2 style="color:red" ><strong><u><b>Easy for search </b></u></strong></h2>


</header>
<hr>
<main>
<input type="text" style="color:brown;background:pink" id="formula" placeholder="Enter only element's symbol...."   >
<br><br>
<button onclick="check()" style="background-color:gold" >
<center><h2 style="color:blue" ><b><strong>Search</strong></b></h2></center>
</button><br><br>
<input type="" style="color:white;background:brown"  readonly="readonly" id="result" placeholder="Show Elements name.."  style="width:140px"  ><br>
<input type="" style="color:red;background-color:yellow" readonly="readonly" id="no" placeholder="Show atomic number.." style="width:90px"  ><br>
<input type="" style="color:brown;background-color:orange"  readonly="readonly" id="mass" placeholder="Show atomic mass.."  style="width:110px"  ><br>
</main>
<hr>
<footer>
<!--<h3 style="color:green" ><b><strong>&#10148; <u>How we use.</strong></u></b></h3>-->
<br>
<ul style="color:blue" >
<b>
 <li> Developer name <u style="color:red" onclick="button()" ><b><strong>DINESH VERMA.</strong></b> </u></li>
 <li type="button" onclick="hello()" >New Updated version: 19.22.008.22</li>
 </b>
 
<hr>
</ul>
<ul style="color:brown" >
<b>
Name:Dinesh kumar verma.<br>
Class: Ninth<br>
School: Dayanand public school<br>
<h2><p style="color:green" >&#x27A1;<strong>Click hear:-<a href="https://www.instagram.com/dineshverma5399/?hl=en" > Dinesh verma</a></strong></p></h2>
</b>
</ul>
<div id="Show" >

</div>
<button onclick="work()" style="width:370px;height:35px;background-color:green" >
<b style="color:red" ><strong>Enter your name</strong></b>
</button>
</footer>
</body>
<script type="text/javascript">
function check(){
 var a =document.getElementById("formula").value;

if (a == "H"){

document.getElementById("result").value = "Element:- Hydrogen.";
document.getElementById("no").value = "Atomic no:-1";
document.getElementById("mass").value = "Atomic mass:-1u";
}
else if (a == "He"){

document.getElementById("result").value = "Element:- Helium.";
document.getElementById("no").value = "Atomic no:-2";
document.getElementById("mass").value = "Atomic mass:-4u";
}
else if (a == "Li"){

document.getElementById("result").value = "Element:- Lithium.";
document.getElementById("no").value = "Atomic no:-3";
document.getElementById("mass").value = "Atomic mass:-7u";
}
else if (a == "Be"){

document.getElementById("result").value = "Element:- Beryllium.";
document.getElementById("no").value = "Atomic no:-4";
document.getElementById("mass").value = "Atomic mass:-9u";
}
else if (a == "B"){

document.getElementById("result").value = "Element:- Boron.";
document.getElementById("no").value = "Atomic no:-5";
document.getElementById("mass").value = "Atomic mass:-11u";
}
else if (a == "C"){

document.getElementById("result").value = "Element:- Carbon.";
document.getElementById("no").value = "Atomic no:-6";
document.getElementById("mass").value = "Atomic mass:-12u";
}
else if (a == "N"){

document.getElementById("result").value = "Element:- Nitrogen.";
document.getElementById("no").value = "Atomic no:-7";
document.getElementById("mass").value = "Atomic mass:-14u";
}
else if (a == "O"){

document.getElementById("result").value = "Element:- Oxygen.";
document.getElementById("no").value = "Atomic no:-8";
document.getElementById("mass").value = "Atomic mass:-16u";
}
else if (a == "F"){

document.getElementById("result").value = "Element:- Fluarine.";
document.getElementById("no").value = "Atomic no:-9";
document.getElementById("mass").value = "Atomic mass:-19u";
}
else if (a == "Ne"){

document.getElementById("result").value = "Element:- Neon.";
document.getElementById("no").value = "Atomic no:-10";
document.getElementById("mass").value = "Atomic mass:-20u";
}
else if (a == "Na"){

document.getElementById("result").value = "Element:- Sodium.";
document.getElementById("no").value = "Atomic no:-11";
document.getElementById("mass").value = "Atomic mass:-23u";
}
else if (a == "Mg"){

document.getElementById("result").value = "Element:- Magnesium.";
document.getElementById("no").value = "Atomic no:-12";
document.getElementById("mass").value = "Atomic mass:-24u";
}
else if (a == "Al"){

document.getElementById("result").value = "Element:- Aluminium.";
document.getElementById("no").value = "Atomic no:-13";
document.getElementById("mass").value = "Atomic mass:-27u";
}
else if (a == "Si"){

document.getElementById("result").value = "Element:- Silicon.";
document.getElementById("no").value = "Atomic no:-14";
document.getElementById("mass").value = "Atomic mass:-28u";
}
else if (a == "P"){

document.getElementById("result").value = "Element:- Phospharus.";
document.getElementById("no").value = "Atomic no:-15";
document.getElementById("mass").value = "Atomic mass:-31u";
}
else if (a == "S"){

document.getElementById("result").value = "Element:- Sulphur.";
document.getElementById("no").value = "Atomic no:-16";
document.getElementById("mass").value = "Atomic mass:-32u";
}
else if (a == "Cl"){

document.getElementById("result").value = "Element:- Chlorine.";
document.getElementById("no").value = "Atomic no:-17";
document.getElementById("mass").value = "Atomic mass:-35.5u";
}
else if (a == "Ar"){

document.getElementById("result").value = "Element:- Argon.";
document.getElementById("no").value = "Atomic no:-18";
document.getElementById("mass").value = "Atomic mass:-40u";
}
else if (a == "K"){

document.getElementById("result").value = "Element:- Pottassium.";
document.getElementById("no").value = "Atomic no:-19";
document.getElementById("mass").value = "Atomic mass:-39u";
}
else if (a == "Ca"){

document.getElementById("result").value = "Element:- Calcium.";
document.getElementById("no").value = "Atomic no:-20";
document.getElementById("mass").value = "Atomic mass:-40u";
}
else if (a == "Sc"){

document.getElementById("result").value = "Element:- Scandium.";
document.getElementById("no").value = "Atomic no:-21";
document.getElementById("mass").value = "Atomic mass:-45u";
}
else if (a == "Ti"){

document.getElementById("result").value = "Element:- Titanium.";
document.getElementById("no").value = "Atomic no:-22";
document.getElementById("mass").value = "Atomic mass:-48u";
}
else if (a == "V"){

document.getElementById("result").value = "Element:- Vanadium.";
document.getElementById("no").value = "Atomic no:-23";
document.getElementById("mass").value = "Atomic mass:-51u";
}
else if (a == "Cr"){

document.getElementById("result").value = "Element:- Chromium.";
document.getElementById("no").value = "Atomic no:-24";
document.getElementById("mass").value = "Atomic mass:-52u";
}
else if (a == "Mn"){

document.getElementById("result").value = "Element:- Managanese.";
document.getElementById("no").value = "Atomic no:-25";
document.getElementById("mass").value = "Atomic mass:-55u";
}
else if (a == "Fe"){

document.getElementById("result").value = "Element:- Iron.";
document.getElementById("no").value = "Atomic no:-26";
document.getElementById("mass").value = "Atomic mass:-55.8u";
}
else if (a == "Co"){

document.getElementById("result").value = "Element:- Cobalt.";
document.getElementById("no").value = "Atomic no:-27";
document.getElementById("mass").value = "Atomic mass:-59u";
}
else if (a == "Ni"){

document.getElementById("result").value = "Element:- Nickkel.";
document.getElementById("no").value = "Atomic no:-28";
document.getElementById("mass").value = "Atomic mass:-58.70u";
}
else if (a == "Cu"){

document.getElementById("result").value = "Element:- Copper.";
document.getElementById("no").value = "Atomic no:-29";
document.getElementById("mass").value = "Atomic mass:-63.5u";
}
else if (a == "Zn"){

document.getElementById("result").value = "Element:- Zinc.";
document.getElementById("no").value = "Atomic no:-30";
document.getElementById("mass").value = "Atomic mass:65u";
}
else if (a == "Ga"){

document.getElementById("result").value = "Element:- Galliium.";
document.getElementById("no").value = "Atomic no:-31";
document.getElementById("mass").value = "Atomic mass:-69.7u";
}
else if(a == "Dinesh"){

alert("Dinesh is owner of this page!");
document.getElementById("result").value = "Name:- Dinesh kumar verma";
document.getElementById("no").value = "Contact no:- 7292820582";
document.getElementById("mass").value = "village:- Saradhu";

}
else if( a == ""){
alert("No any symbol enter!");
}

else {
 document.getElementById("result").value = "Data not found........";
 alert(" This symbol is wrong!.. Enter elements symbol please!")
 alert("Try again, don't enter wrong symbol.");
 document.getElementById("no").value = " Faild...";
 document.getElementById("mass").value = " faild...";
}



}
function button(){

document.getElementById("Show").innerHTML = "This page is made by Dinesh kumar verma."+" You use update version file.";
"Contact details:-72928205××";
alert("contact details:- 72928205××");
}
function hello(){
alert("previous version 17.22.001 and 19.22.008.12");


}
function work(){
var x = "Enter your good name!";

var z =prompt(x," ");
alert("Hello "+z+" welcome to my page!");


}
</script>
</html>
