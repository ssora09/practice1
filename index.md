<!DOCTYPE html> <html>
<head>
<meta charset="UTF-8">
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.5.11/p5.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.5.11/addons/p5.dom.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.5.11/addons/p5.sound.min.js"></script>
<script src="sketch.js"></script>
<style>
html, body {margin:0; padding:0; overflow:hidden;} </style>
</head> <body> </body>
</html>

function setup() { createCanvas(windowWidth, windowHeight); background(255,0,0);
}
function draw() {
if (mouseIsPressed) {
var size = random(10, 100);
ellipse(mouseX, mouseY, size, size); }
}
