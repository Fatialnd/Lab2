<!DOCTYPE html>
<html>

<head>
    <title>FUNDAMENTALS OF WEB PROGRAMMING</title>
    <script>
        function checkAll() {
         var ans= 'not true';
         var p1=document.getElementById('c1');
         var p2=document.getElementById('c2');
          var p3=document.getElementById('c3');
         var p4=document.getElementById('c4');
         var p5=document.getElementById('c5');
         if(p1.checked && p2.checked && !p3.checked && p4.checked && !p5.checked) ans='true'
         var win =window.open("","","width = 100, height = 100");
         win.document.open();
         var str ="<h1>" + ans + "!!! </h1> <hr>";
         win.document.write(str);
         win.document.close();
    
     }
   </script>
</head>

<body>
    <p> Note the correct statements:
    </p>
   <form>
        <input type ="checkbox" id="c1" name="c1"> what is html? -The HyperText Markup Language, or HTML is the standard markup language for documents designed to be displayed in a web browser<br /> 
        <input type ="checkbox" id="c2" name="c3"> What Can Node.js Do? -Node.js can generate dynamic page content<br /> 
         <input type ="checkbox" id="c3" name="c3"> what is api? -API  is a device used to measure time.<br />
         <input type ="checkbox" id="c4" name="c4"> what is data analysis? -A website may collect a lot of data about users: what they search for, what 
they buy, what they recommend, how long they stay on each page.<br /> 
         <input type ="checkbox" id="c5" name="c5">What Can PHP Do? - Php are free coins use to buy online<br /> 
       <input type ="button" value="check" onClick="checkAll ();">
    </form>
    </body>
</html>
