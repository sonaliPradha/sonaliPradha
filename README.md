<!DOCTYPE html>
<html lang="en">
<head>
   <link rel="stylesheet" href!DOCTYPE html><html lang="en"><head>   <link rel="stylesheet" href="Calc.css">
   <title>Calulator</title>
</head>
<body>
   <div class="main">
      <input type="text" id = 'res'>
      <div class="btn">
         <input type="button" value = 'C' onclick = "Clear()">
         <input type="button" value = '%' onclick = "Solve('%')">
         <input type="button" value = '←' onclick ="Back('←')">
         <input type="button" value = '/' onclick = "Solve('/')">
         <br>
         <input type="button" value = '7' onclick = "Solve('7')">
         <input type="button" value = '8' onclick = "Solve('8')">
         <input type="button" value = '9' onclick = "Solve('9')">
         <input type="button" value = 'x' onclick = "Solve('*')">
         <br>
         <input type="button" value = '4' onclick = "Solve('4')">
         <input type="button" value = '5' onclick = "Solve('5')">
         <input type="button" value = '6' onclick = "Solve('6')">
         <input type="button" value = '-' onclick = "Solve('-')">
         <br>
         <input type="button" value = '1' onclick = "Solve('1')">
         <input type="button" value = '2' onclick = "Solve('2')">
         <input type="button" value = '3' onclick = "Solve('3')">
         <input type="button" value = '+' onclick = "Solve('+')">
         <br>
         <input type="button" value = '00'onclick = "Solve('00')">
         <input type="button" value = '0' onclick = "Solve('0')">
         <input type="button" value = '.' onclick = "Solve('.')">
         <input type="button" value = '=' onclick = "Result()">
      </div>
   </div>
   <script src = 'Calc.js' ></script>
</body>
</html>
