<html>
<head> </head>

<body>
   <img src=5.jpeg>

   <p>MENU</p>
   
  <section center>
  <img src=1.jpeg>
  <img src=2.jpeg>
  <img src=3.jpeg>
  <img src=4.jpeg>
  </section>
  
    <section center>
  <img src=1.jpeg>
  <img src=2.jpeg>
  <img src=3.jpeg>
  <img src=4.jpeg>
  </section>
  
    <section center>
  <img src=1.jpeg>
  <img src=2.jpeg>
  <img src=3.jpeg>
  <img src=4.jpeg>
  </section>


<style>
section {
display: flex;
width:900px;
height:1000px;
}

section img{
width:0px;
flex-grow:1;
odject-fit:cover;
opacity:.8;
transition: .3s ease;
}

section img:hover{
cursor:crosshair;
width:500px;
opacity: 1;
filter contrast(120%)
}

section{
display:flex;
align-items:center;
justify-content:center;
}

img{
width:1340px;
height:700px;
}

p{
width:300px;
height:10px;
display:flex;
align-items:center;
justify-content:center;
}

</style>

</body>

</html>
