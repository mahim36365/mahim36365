
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,32 @@
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CrossOver Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>CrossOver Calculator</h1>
    <form action="" name="clc">
        <input type="text" name="display" style="width: 370px; height: 70px; background-color: #4c555c;color: white;"><br>
        <input class="btn" type="button" value="0" onclick="clc.display.value += '0'">
        <input class="btn" type="button" value="1" onclick="clc.display.value += '1'">
        <input class="btn" type="button" value="2" onclick="clc.display.value += '2'">
        <input class="btn" type="button" value="+" onclick="clc.display.value += '+'" style=" background-color: #cc5c11;"><br>
        <input class="btn" type="button" value="3" onclick="clc.display.value += '3'">
        <input class="btn" type="button" value="4" onclick="clc.display.value += '4'">
        <input class="btn" type="button" value="5" onclick="clc.display.value += '5'">
        <input class="btn" type="button" value="-" onclick="clc.display.value += '-'" style="background-color: #ba55d3;"><br>
        <input class="btn" type="button" value="6" onclick="clc.display.value += '6'">
        <input class="btn" type="button" value="7" onclick="clc.display.value += '7'">
        <input class="btn" type="button" value="8" onclick="clc.display.value += '8'">
        <input class="btn" type="button" value="*" onclick="clc.display.value += '*'" style="background-color: #7db1b2;"><br>
        <input class="btn" type="button" value="9" onclick="clc.display.value += '9'">
        <input class="btn" type="button" value="C" onclick="clc.display.value =''" style="background-color:#cc0000;">
        <input class="btn" type="button" value="=" onclick="clc.display.value =eval(clc.display.value)">
        <input class="btn" type="button" value="&#247;" onclick="clc.display.value += '/'" style="background-color: #1f80c9;">
    </form>
</body>
</html>
‎style.css
+35
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,35 @@
body{
    margin: 0px;
    padding: 0px;
    background-color: #011627;
    color: #fdfffc;
    text-align: center;
    background-image: url(https://cdn.pixabay.com/photo/2015/07/02/10/13/sky-828648_960_720.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
}
h1{
    font-size: 45px;
}
input{
    width: 75px;
    height: 50px;
    font-size: 45px;
    border-radius: 10px;
    margin: 10px;
    background-color: white;
    color: black;
    border-style: none;
}
.btn:hover{
    background-color:yellow;
    cursor: pointer;
}



