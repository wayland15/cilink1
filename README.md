<!DOCTYPE HTML>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Cilink</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <center><input type="text" id="number" value="0"/></center>
  <center>
<input type="image" src="images\money.png" onclick="incrementValue()" width="60%" height="60%" />
</center>
<center>
<p>Energy: 2000/2000</p>
</center>
<center>
<a href="boost.html" type="a">Boost</a>
<a href="#" type="a">Tasks</a>
<a href="#" type="a">Refes</a>
</center>
<script>
  function incrementValue()
{
    var value = parseInt(document.getElementById('number').value, 10);
    value = isNaN(value) ? 0 : value;
    value++;
    document.getElementById('number').value = value;
}
</script>
</body>
</html>
