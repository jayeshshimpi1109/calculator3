# Jayesh_calculator


<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>


<!-- Actuall Code start from here created by jayesh shimpi -->
<style>
body, html {
	background: #ECEDEF;
	margin: 0;
	padding: 0;
}
 
.container {
	position: fixed;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	background: #fff;
	box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.2);
	border-radius: 14px;
	padding-bottom: 20px;
	width: 320px;
  
	
}
.display {
	width: 100%;
	height: 60px;
	padding: 40px 0;
	background-color: #1a2ee6;
	border-top-left-radius: 14px;
	border-top-right-radius: 14px;
}
.buttons {
	padding: 10px 5px 0 20px;
}
.row {
	width: 280px;
	float: left;
}
input[type=button] {
	width: 35px;
	height: 35px;
	float: left;
	padding: 0;
	margin: 5px;
	box-sizing: border-box;
	background: #ecedef;
	border: none;
	font-size: 30px;
	line-height: 30px;
	border-radius: 50%;
	font-weight: 600;
	color: #5E5858;
	cursor: pointer;
	
}
input[type=text] {
	width: 200px;
	height: 60px;
	float: left;
	padding: 0;
	box-sizing: border-box;
	border: none;
	background: none;
	color: #ffffff;
	text-align: right;
	font-weight: 500;
	font-size: 40px;
	line-height: 60px;
	margin: 0 25px;
	
}
.red {
	background: #ebdedf !important;
	color: #ffffff !important;
	
}
center {
    color: #e9490a;
    font-family: Verdana;
}

</style>
<body>



  <!-- JavaScript part start from here -->
  <script>
    function calcNumbers(result){
      form.displayResult.value=form.displayResult.value+result;
      
    }

    function csFunction(clr){
      form.displayResult.value="";
    }

    function jlightblue(chk){

      var ok=chk;
      if(ok==="J"){
      document.getElementById("myDisplay").style.background = "lightblue";
      }
    }
    function agreen(chk){

    var okay=chk;
    if(okay==="A"){
         document.getElementById("myDisplay").style.background = "green";
     }
    }

    function yYello(chk){

var ok=chk;
if(ok==="Y"){
document.getElementById("myDisplay").style.background = "yellow";
}
}

    </script> 



    <!-- Html part start from here -->
    <div class="container" > 
      <center>Simple Calculator 
        <a href="#"><span class="glyphicon glyphicon-heart-empty"></span></a>
      </center>
 
          
      <form name="form">
      <div class="display" id="myDisplay">
      <input type="text" placeholder="_ _ _ _ _ _" name="displayResult"/>
      </div>



      




 


      <div class="buttons">

        <div class="row">
          <input type="button" id="j" name="J" value="J" onClick="jlightblue(J.value)">
          <input type="button" id="a" name="A" value="A" onClick="agreen(A.value)">
          <input type="button" id="y" name="Y" value="Y" onClick="yYello(Y.value)">
          <input type="button" id="e" name="E" value="E" onClick="myFun(E.value)">
          <input type="button" id="s" name="S" value="S" onClick="myFun(s.value)">
          <input type="button" id="h" name="H" value="H" onClick="myFun(H.value)">
          </div>





      <div class="row">
      <input type="button" name="b7" value="7" onClick="calcNumbers(b7.value)">
      <input type="button" name="b8" value="8" onClick="calcNumbers(b8.value)">
      <input type="button" name="b9" value="9" onClick="calcNumbers(b9.value)">
      <input type="button" name="addb" value="+" onClick="calcNumbers(addb.value)">
      
      </div>
      
      <div class="row">
      <input type="button" name="b4" value="4" onClick="calcNumbers(b4.value)">
      <input type="button" name="b5" value="5" onClick="calcNumbers(b5.value)">
      <input type="button" name="b6" value="6" onClick="calcNumbers(b6.value)">
      <input type="button" name="subb" value="-" onClick="calcNumbers(subb.value)">
      </div>
      
      <div class="row">
      <input type="button" name="b1" value="1" onClick="calcNumbers(b1.value)">
      <input type="button" name="b2" value="2" onClick="calcNumbers(b2.value)">
      <input type="button" name="b3" value="3" onClick="calcNumbers(b3.value)">
      <input type="button" name="mulb" value="*" onClick="calcNumbers(mulb.value)">
      </div>
      
      <div class="row">
      <input type="button" name="b0" value="0" onClick="calcNumbers(b0.value)">
      <input type="button" name="potb" value="." onClick="calcNumbers(potb.value)">
      <input type="button" name="divb" value="/" onClick="calcNumbers(divb.value)">
      <input type="button" class="red" value="=" onClick="displayResult.value=eval(displayResult.value)">
      </div>

      <div class="row">
                <input type="button" name="CS" value="cs" onClick="csFunction(CS.value)">
      <br>
          <center> &nbsp; &nbsp;  &nbsp; I MADE 
             <span class="glyphicon glyphicon-heart"></span><br>
          @Jayesh_shimpi</center>
      </div>
      
      </form>
    </div>
  


</body>
</html>
