<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Rüya ❤️ Enes</title>
<style>
body{
background:#ff4d6d;
color:white;
font-family:Arial;
text-align:center;
padding-top:100px;
overflow:hidden;
}

h1{font-size:40px;}
p{font-size:20px;}

.heart{
position:absolute;
color:white;
font-size:20px;
animation:float 6s linear infinite;
}

@keyframes float{
0%{transform:translateY(0);}
100%{transform:translateY(-1000px);}
}
</style>
</head>

<body>

<h1>Rüya ❤️ Enes</h1>

<p>Kadınlar Günün Kutlu Olsun Güzelim 🌹</p>

<p>
Belki bugün geç kaldım ama şunu bilmeni istiyorum...  
Sen benim hayatımdaki en değerli kadınlardan birisin.  
Uzakta olsak bile kalbim hep senin yanında. ❤️
</p>

<script>
setInterval(function(){
let heart=document.createElement("div");
heart.className="heart";
heart.innerHTML="❤️";
heart.style.left=Math.random()*100+"vw";
heart.style.fontSize=(Math.random()*20+10)+"px";
document.body.appendChild(heart);

setTimeout(()=>{heart.remove();},6000);
},300);
</script>

</body>
</html># Veocities Design	
