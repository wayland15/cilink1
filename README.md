<!DOCTYPE HTML>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, user-scalable=no">
  <title>Cilink</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <center><input readonly type="text" id="number" value="0"/></center>
  <center>
<input type="image" src="images\money.png" onclick="incrementValue()" width="55%" height="55%" />
</center>
<center>
<p>⚡: 2000/2000</p>
</center>
<center>
  <div class="redbox">
  <div class="container">
    <a href="boost.html" type="a">Boost</a>
    <a href="tasks.html" type="a">Tasks</a>
    <a href="#" type="a">Refes</a>
  </div>
</div>
</center>
<script>
  function incrementValue()
{
    var value = parseInt(document.getElementById('number').value, 10);
    value = isNaN(value) ? 0 : value;
    value++;
    value++;
    value++;
    document.getElementById('number').value = value;
}
</script>
</body>
</html>
