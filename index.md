<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no"/>
<meta charset="UTF-8"/>
<style>
body, canvas {
    background-color: #000;
}
.Rotate90{
     transform: scale(1, -1) rotate(90deg);
}
.Rotate180{
     transform: scale(1, -1); 
}
.Rotate270{
     transform: scale(1, -1) rotate(270deg);
}
</style>
</head>
<body>
　　<iframe src="https://raw.githubusercontent.com/anars/blank-audio/master/500-milliseconds-of-silence.mp3" allow="autoplay" id="audio" style="display:none"></iframe>
　　<audio src="d1.mp3" autoplay loop></audio>
<img src="Colorful_World.gif" style="transform: scale(-1, 1); position:absolute; top:0px;   left:250px" />
<img src="Colorful_World.gif" style="position:absolute; top:250px; left:500px" class="Rotate90" />
<img src="Colorful_World.gif" style="position:absolute; top:500px; left:250px" class="Rotate180" />
<img src="Colorful_World.gif" style="position:absolute; top:250px; left:0px"   class="Rotate270" />
</body>
</html>
