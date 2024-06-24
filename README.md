-<!DOCTYPE html>
<html lang="pt-br">
<head>
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário de Pedido</title>
    <link rel="stylesheet" href="styles.css"> <!-- Estilos opcionais -->
</head>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Imagem de Fundo</title>
    <style>
        body {
            background-image: url('rolex-diamantes.webp');
            background-size: cover; /* Para cobrir toda a área do body */
            background-position: center; 50px
            /* Outras propriedades opcionais: */
            /* background-repeat: no-repeat; */
            /* background-attachment: fixed; */
        }
    </style>
</head>
<body>
    
    <h1>ROLEX</h1>
    <p>A LOJA PARA QUEM BUSCA INOVAÇAO.</p>


<body>
    <h1>Faça seu Pedido</h1>
    <form action="processar_pedido.php" method="post">
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="produto">Produto:</label>
        <select id="produto" name="produto">
            <option value="produto1">Produto 1</option>
            <option value="produto2">Produto 2</option>
            <option value="produto2">Produto 3</option>
            <option value="produto2">Produto 4</option>
            <option value="produto2">Produto 5</option>
            <option value="produto2">Produto 6</option>
            <option value="produto2">Produto 7</option>
            <option value="produto2">Produto 8</option>
            <!-- Adicione mais produtos conforme necessário -->
        </select>
        
        <label for="quantidade">Quantidade:</label>
        <input type="number" id="quantidade" name="quantidade" min="1" required>
        
        <a href="vitrine.html">entre aqui para ver opções</a>
        <button type="submit">Enviar Pedido</button>
    </form>
</body>
</html>


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Imagens</title>
    <style>
        /* Estilos para centralizar o conteúdo e dar um espaçamento entre as imagens */
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            max-width: 1000px;
            padding: 20px;
        }

        .gallery img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }

        .gallery img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }

         .gallery img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }

        .caption {
            text-align: center;
            margin-top: 10px;
            font-size: 14px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div>
            <img src="imagem1.jpg" alt="Descrição da Imagem 1">
            <p class="caption">Legenda da Imagem 1</p>
        </div>
        <div>
            <img src="imagem2.jpg" alt="Descrição da Imagem 2">
            <p class="caption">Legenda da Imagem 2</p>
        </div>
        <div>
            <img src="imagem2.jpg" alt="Descrição da Imagem 2">
            <p class="caption">Legenda da Imagem 2</p>
        </div>
        <div>
            <img src="imagem2.jpg" alt="Descrição da Imagem 2">
            <p class="caption">Legenda da Imagem 2</p>
        </div>
        <div>
            <img src="imagem2.jpg" alt="Descrição da Imagem 2">
            <p class="caption">Legenda da Imagem 2</p>
        </div>
        <div>
            <img src="imagem2.jpg" alt="Descrição da Imagem 2">
            <p class="caption">Legenda da Imagem 2</p>
        </div>
        <div>
            <img src="imagem2.jpg" alt="Descrição da Imagem 2">
            <p class="caption">Legenda da Imagem 2</p>
        </div> <div>
            <img src="images.jpeg" alt="Descrição da Imagem 2">
            <p class="caption">rolex horizon RS 23,200</p>
        </div>
        

        <!-- Adicione mais imagens conforme necessário -->
    </div>
</body>
</html>
