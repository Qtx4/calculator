# calculator
<!doctype html>
<html>
<head>
<title>kartik claculator</title>
<style type="text/css">


 body{
       height:720px;
      background-image:linear-gradient(to bottom right,green,red,blue);


 


    }
      .divstyle{
                position:absolute;
                top:150px;
                left:550px;
   }
    .button{
           width:55px;
           height:50px;
          font-size:25px;
           margin:5px;
           margin-left:14px;
           cursor:pointer;
           border:2px;
           background-color:blue;
           color:white;
  }
    .textdisplay{
                       width:215px;
                       margin:5px;
                       font-size:25px;
                       padding:5px;
                       border:2px;
                 }
  .c{
       width:100px;
  }

</style
</head>
<body>
<div class="bgcoll"></div>
<div class="divstyle">
<form name="formstyle">

<input class="textdisplay"type="text"name="ans"><br>
<input class="button"type="button"name=""value="1 "onclick="formstyle.ans.value+='1'">
<input class="button"type="button"name=""value="2"onclick="formstyle.ans.value+='2'">
<input class="button"type="button"name=""value="3"onclick="formstyle.ans.value+='3'"><br>


<input class="button"type="button"name=""value="4"onclick="formstyle.ans.value+='4'">
<input class="button"type="button"name=""value="5"onclick="formstyle.ans.value+='5'">
<input class="button"type="button"name=""value="6"onclick="formstyle.ans.value+='6'"><br>



<input class="button"type="button"name=""value="7"onclick="formstyle.ans.value+='7'">
<input class="button"type="button"name=""value="8"onclick="formstyle.ans.value+='8'">
<input class="button"type="button"name=""value="9"onclick="formstyle.ans.value+='9'"><br>



<input class="button"type="button"name=""value="+"onclick="formstyle.ans.value+='+'">
<input class="button"type="button"name=""value="-"onclick="formstyle.ans.value+='-'">
<input class="button"type="button"name=""value="*"onclick="formstyle.ans.value+='*'"><br>

<input class="button"type="button"name=""value="/"onclick="formstyle.ans.value+='/'">
<input class="button"type="button"name=""value="0"onclick="formstyle.ans.value+='0'">
<input class="button"type="button"name=""value="="onclick="formstyle.ans.value=eval(formstyle.ans.value)"><br>



<input class="button"type="button"name=""value="c"onclick="formstyle.ans.value=''"id="clear all">


</from>
</div>
</body>
</html>
