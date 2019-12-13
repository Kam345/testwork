<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <script>
    function dis(val)
    {
    document.getElementById("edu").value+=val
     }
    function solve()
    {
    let x = document.getElementById("edu").value
    let y = eval(x)
    document.getElementById("edu").value = y
    }
    function clr()
    {
    document.getElementById("edu").value = ""
    }
    </script>
<body>
<table border="6">
<h3>Kam=_+</h3>
<tr>
<td><input type="button" value="c" onclick="clr()"/></td>
<td colspan="6"><input type="text" id="edu"/></td>
</tr>
<tr>
<td><input type="button" value="+" onclick="dis('+')"/></td>
<td><input type="button" value="1" onclick="dis('1')"/></td>
<td><input type="button" value="2" onclick="dis('2')"/></td>
<td><input type="button" value="3" onclick="dis('3')"/></td>
</tr>
<tr>
<td><input type="button" value="-" onclick="dis('-')"/></td>
<td><input type="button" value="4" onclick="dis('4')"/></td>
<td><input type="button" value="5" onclick="dis('5')"/></td>
<td><input type="button" value="6" onclick="dis('6')"/></td>
</tr>
<tr>
<td><input type="button" value="*" onclick="dis('*')"/></td>
<td><input type="button" value="7" onclick="dis('7')"/></td>
<td><input type="button" value="8" onclick="dis('8')"/></td>
<td><input type="button" value="9" onclick="dis('9')"/></td>
</tr>
<tr>
<td><input type="button" value="/" onclick="dis('/')"/></td>
<td><input type="button" value="." onclick="dis('.')"/></td>
<td><input type="button" value="0" onclick="dis('0')"/></td>
<td><input type="button" value="=" onclick="solve()"/></td>
</tr>
</table>
</body>
<style>
.title{
border-radius: 10px;
margin-bottom: 10px;
text-align:center;
width: 210px;
color:#black;
border: solid black 1px;
}
input[type="button"]
{
border-radius: 10px;
background-color:blue;
color:white;
border-color:#black;
width:95%;
}
input[type="text"]
{
border-radius: 100px;
text-align: right;
background-color:red;
border-color: black ;
width:95%
}
</style>
  </body>
</html>
