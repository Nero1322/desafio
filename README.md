# Desafio
Desafio UM | Lógica de Programação | Decodificador de texto
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DecodificadorAlura</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="style.css">
</head>

<body>
<header>
    <h1><img class="LogoAlura" src="imagens/LogoAlura.png" alt="LogoAlura"></h1>
</header>

<main>

        <section>
            <div>
            <textarea class="text-area" cols="25" rows="4" placeholder="Digite seu texto"></textarea>
            </div>
           
            <section>
            <div class="informação">
                <h6>Apenas letras minúsculas e sem acento.</h6>
            </div>       
        </section>     
           
        <section>
            <div class="botoes">
                <button class="btn-encriptar" onclick="btnEncriptar()">Criptografar</button>
                <button class="btn-desencriptar" onclick="btnDesencriptar()">Descriptografar</button>

                <div class="container">
                    <button class="button">Copiar</button>
                </div>
            </div>        
        </section>
                       
        <section>
                <div>
                <textarea class="mensagem" cols="18" rows="12"></textarea>
                </div>   

        </section>  
           
</main>
<footer>
    
</footer>
<script src="script.js"></script>
</body>
</html>

    


