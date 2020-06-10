<!DOCTYPE html>
<html>
<body>

<h2>JavaScript  Loop</h2>

<p id="demo"></p>

<script>
var text = " Nimesh"
var i = 0;

do {
  text += "<br>Hello"  + text;
  text += "<br>Goodbye" +text;
  i++;
}
while (i < 1);  

document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>
