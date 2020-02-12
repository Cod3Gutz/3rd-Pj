<!DOCTYPE html>
<html>
 <head>
   <style>
 body{
   background-image: url(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fclipground.com%2Fimages%2Ffree-linkedin-background-clipart-17.jpg&f=1&nofb=1);
 }
 p{
   color:crimson;
 }
 h1{
   color:cyan;
 }
 </style>
 </head>
  <body>
   <h1>This Is An Example Of A <U>While</u> Loop</h1>

<script>
  debugger;
  var cntdwn = 1;
  while(cntdwn <=6){//this creates a condition in order to prevent infinite loop
    document.write("<p>Black Queens "+ cntdwn +" </p>");//this writes a paragrah onto the html 
    document.write("<img src='./images/blackqueens/photo" + cntdwn + ".jpeg'/>");//writes the image from the relative source onto the page 
    document.write("<br>");//linebreak

    cntdwn++;//loops the images in order by incriminating
    //cntdwn = cntdwn + 1;another way to execute this code
  }
  alert("Successful Loop");
</script>



 </body>
 <html>
