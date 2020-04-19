<!DOCTYPE html>
<html>
  <head> <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">

    </head>
  <style>
    .background{ background-image: url(https://ih1.redbubble.net/image.937470579.1980/flat,750x,075,f-pad,750x1000,f8f8f8.jpg); 
    background-size: 200px 200px;
    }
    .button1{color:red;}
    .button{ height: 50px;
             width: 50px;
             margin: 2px;
             color: red;
             
    }
    .title {
      font-family: 'Montserrat', sans-serif;
    }
    </style>
<div class="background">
 <h2 class="title"> Vibe calc </h2>
  <form name="calculator">
 
  <input type="textfield" name="ans" value=""> <br>   
  <td><input type ="button" class= "button" value="7" onClick="document.calculator.ans.value+='7'"> </td>
  <td><input type ="button" class= "button" value="8" onClick="document.calculator.ans.value+='8'"> </td>
  <td><input type ="button" class= "button" value="9" onClick="document.calculator.ans.value+='9'"> </td>
  <td><input type ="button" class= "button" value="*" onClick="document.calculator.ans.value+='*'"> </td> <br>
  <td><input type ="button" class= "button" value="4" onClick="document.calculator.ans.value+='4'"> </td>
  <td><input type ="button" class= "button" value="5" onClick="document.calculator.ans.value+='5'"> </td>
  <td><input type ="button" class= "button" value="6" onClick="document.calculator.ans.value+='6'"> </td>
  <td><input type ="button" class= "button" value="-" onClick="document.calculator.ans.value+='-'"> </td><br>
  <td><input type ="button" class= "button" value="3" onClick="document.calculator.ans.value+='3'"> </td>
  <td><input type ="button" class= "button" value="2" onClick="document.calculator.ans.value+='2'"> </td>
  <td><input type ="button" class= "button" value="1" onClick="document.calculator.ans.value+='1'"> </td> 
  <td><input type ="button" class= "button" value="+" onClick="document.calculator.ans.value+='+'"> </td><br>
  <td><input type="button" class="button" value="0" onClick="document.calculator.ans.value+='0'">
  <td><input type="button" class="button" value="/" onClick="document.calculator.ans.value+='/'"
  <td><input type="button" class="button" value="." onclick="document.calculator.ans.value=+'.'"
  <!-- i dont get why its not working -->
  <td><input type ="button" class= "button" value="=" onClick="document.calculator.ans.value=eval(document.calculator.ans.value)"> </td>
  <td><input type="reset" class="button1" value"reset" </td><br>
  </form>
  </div>
  </html>
