<html>
<head>
    <style>
        body{
        background: #000000;
        color: rgb(174, 137, 235)

        </style>
    <style>
        h1{
            font-family: Courier New, monospace;
            text-align: center;
        }

        h3{
            font-family: Courier New, monospace;
        }
        </style>
        <script>
          
            function preco(){                           
              let vlr1 = parseFloat(document.getElementById("inp2").value);
              let vlr2 = parseFloat(document.getElementById("inp3").value);
              let vlr3 = (document.getElementById("inp").value);
              let tot = vlr1 * vlr2;
              alert("Se você comprar " + vlr2 + " unidades de "+ vlr3 + " você irá gastar " +  tot + " reais");
            }
            
        </script>
</head>
<body>
<center><h1>Formulario produto</h1></center>
<h3>Produto</h3>
<input type= "text" id= "inp"></input><br> 
<h3>Preço</h3>
<input type= "number" id= "inp2"></input><br> 
<h3>Quantidade</h3>
<input type= "number" id= "inp3"></input><br> 
<center> <button type="button" id="buto" onclick="preco()"> Ok </button> </center>
</body>
</html>
