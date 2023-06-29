# alura-plus
<!DOCTYPE html>
<html>
    <head>
        <title>AluraPlus</title>
        <meta <harset="UTF-8">
        <meta name="viewport" content="width-device-width, initial-scale=1">    
        <link rel="stylesheet" href="styles.css">
    </head>      
<body>
    <section class="container principal">
      <div>
    <h1>"Com a Combo+, você pode aproveitar o Alura+ e o Alura Língua por um preço único".</h1>
    <img src="img/Combo.png" alt="O Combo+ é a junção do Alura+ e Alura Língua">
        <a href="www.alura.com.br"></a> class="container__botao" Assine por 12x de R$ 120,00*</a>
    <a href="www.alura.com.br" class="container__botao botao_secundario">Assinar somente o Alura+ </a>
    <p class="container__aviso">*O preco pode variar caso a assinatura seja feito em outros planos</p>
    </div>
  </section>
</body>   
</html>

css.
:root { --branco-principal: #FFFFFF; 
    --cinza-secundario: #C0C0C0;
    --botao-azul: #167BF7;
    --cor-de-fundo: #00030C;
}

body { background-color: var(--cor-de-fundo); 
color: var(--branco-principal);
}
* {
    margin: 0;
    padding: 0;
  }
  
.principal { background-image: url("img/Background.png"); 
background-repeat: no-repeat;
background-size: contain;
}
.container {
    height: 100vh;
    display: grid;
    grid-template-columns: 50% 50%;
}

.container__botao { background-color: var(--botao-azul); 
    border-radius: 5px;
    padding: 1em;
    color: var(--branco-principal);
    display: block;
}

.botao_secundario {
    background-color: transparent;
    border: 2px solid var(--branco-principal)
    
 }









