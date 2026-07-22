#Exemplo sobre estrutura básica do HTML5 + CSS

```
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magazine Luiza</title>
    <style>
        body {
            border: 0;
            border: none;
            margin: 0;
        }
        a {
            color: white;
            text-decoration: none;
        }
        a:hover {
            border-radius: 10px;
            border: 2px solid white;
            padding: 5px;
        }
        .container {
                background: purple;
                display: flex;
                align-items: center;
                justify-content: center; /* Isso também ajuda a centralizar horizontalmente */                
                }
        .container2 {
                background: white;
                display: flex;
                align-items: center;
                justify-content: center; /* Isso também ajuda a centralizar horizontalmente */                
                }             
        .container3 {                    
                position: relative;    
                float: left;
                background-color: #0075e2;                                 
                align-items: center;
                display: flex;
                height: 50px;
                width: 100%;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                font-size: 13px;
                }   
        .box {
            color: white;
            margin: 20px;
            }                                                         
         .box1 {            
            margin: 0px;
            padding-right: 100px;
            padding-left: 10px;
            padding-top: 10px;
            }       
         .fonte {
                background-color: #0075e2;;
                font-size: 20px;
                color: white;
                height: 40px;                 
                display: flex;
                justify-content: left;
                align-items: center;
                padding-left: 10px;
         }                   
    </style>
</head>
<body>    
    <div class="container3">        
        <div class="box1"><img src="img/logo-magalu.png" width=150"></div>                                         
        <div class="box"><a href="">Ofertas do dia</a></div>
        <div class="box"><a href="">Celulares</a></div>
        <div class="box"><a href="">Eletrodomésticos</a></div>
        <div class="box"><a href="">TV e Vídeo</a></div>
        <div class="box"><a href="">Informática</a></div>
        <span style="background: white; color: #0075e2;">Compre pelo tel. 0800 70 70 70</span>              
    </div>
    <div style="background: purple;">
        <img src="img/banner.png">
    </div>
    <div class="fonte">                
        Novidades que encontramos
    </div>    
    <div class="container2">                
        <img src="img/produto1.jpg">
        <img src="img/produto2.jpg">
        <img src="img/produto3.jpg">
        <img src="img/produto4.jpg">        
    </div>
    <div style="background: #0075e2;">
        <span style="color: purple;">Mazine Luiza</span>  
        <span style="color: white; font-weight: bold;">&copy; Todos os direitos reservados</span> 
    </div>
</body>
</html>
```
