<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport"
content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
<title>Wreck Chasing</title>

<style>
*{box-sizing:border-box;touch-action:none}
html,body{
margin:0;
width:100%;
height:100%;
overflow:hidden;
background:#050505;
font-family:Arial,sans-serif;
color:white
}

canvas{
display:block;
width:100%;
height:100%;
background:#171717
}

#hud{
position:fixed;
top:0;
left:0;
right:0;
padding:10px;
display:flex;
justify-content:space-between;
pointer-events:none;
font-weight:bold;
text-shadow:2px 2px 3px #000;
z-index:5
}

.panel{
background:rgba(0,0,0,.7);
border:1px solid #ffd400;
border-radius:8px;
padding:7px 10px
}

#dispatch{
position:fixed;
top:65px;
left:50%;
transform:translateX(-50%);
background:#111;
border:2px solid #ffd400;
border-radius:10px;
padding:10px 18px;
text-align:center;
font-weight:bold;
z-index:6;
min-width:260px
}

#controls{
position:fixed;
bottom:18px;
left:0;
right:0;
display:flex;
justify-content:space-between;
padding:0 18px;
z-index:10
}

.group{
display:grid;
grid-template-columns:70px 70px;
gap:10px
}

button{
width:70px;
height:70px;
border-radius:18px;
border:2px solid #ffd400;
background:rgba(0,0,0,.72);
color:#ffd400;
font-size:28px;
font-weight:bold
}

button:active{
background:#ffd400;
color:#000
}

#action{
position:fixed;
bottom:105px;
left:50%;
transform:translateX(-50%);
width:120px;
height:48px;
font-size:15px
}

#startScreen{
position:fixed;
inset:0;
background:#080808;
display:flex;
align-items:center;
justify-content:center;
z-index:30;
text-align:center
}

#startBox{
width
