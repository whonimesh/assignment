<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #4CAF50;
  color: white;
}
</style>
</head>
<body>

<div class="topnav">
  <a class="active" href="#Menu">Menu</a>
  <a href="#Specials">Specials</a>
  <a href="#Maps">Maps</a>
</div>

<div style="padding-left:16px">
  <h1>Menu</h1>
  <ol>
  <li>Burger</li>
  <li>Baked Potato</li>
  <li>Chicken Salad</li>
  <li>Curry</li>
  <li>Fish pie</li>
  <li>Chicken</li>
  <li>Samosas</li>
  <li>Aloo Govi</li>
  <li>Naan</li>
  <li>Matar Paneer</li>
  <li>Tandoori Chicken</li>
  </ol>
  <br>
  <h1>Special</h1>
  <h2>Chana aloo Curry</h2>
  <p>A sultry blend of ginger, tomato, curry, and garlic marinate potatoes, chickpeas, and onions. These veggies and spices blend together to create the magical, Chana Aloo Curry. Though more traditional recipes may be spiced with chilli or cayenne pepper, Chef Marie’s special twist includes fresh jalapenos.</p>
  <h1>Maps</h1>
  <div id="googleMap" style="width:100%;height:400px;"></div>

<script>
function myMap() {
var mapProp= {
  center:new google.maps.LatLng(51.508742,-0.120850),
  zoom:5,
};
var map = new google.maps.Map(document.getElementById("googleMap"),mapProp);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_KEY&callback=myMap"></script>
</div>

</body>
</html>
