<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supermercado Bom Preço</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        header {
            background-color: #2e8b57;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #3cb371;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .produto {
            background-color: white;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }

        .produto img {
            width: 100%;
            max-height: 150px;
            object-fit: contain;
        }

        .produto h3 {
            margin: 10px 0;
        }

        .produto p {
            color: green;
            font-weight: bold;
        }

        footer {
            background-color: #2e8b57;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Supermercado Bom Preço</h1>
        <p>Qualidade e economia para sua família</p>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Produtos</a>
        <a href="#">Ofertas</a>
        <a href="#">Contato</a>
    </nav>

    <div class="container">
        <div class="produto">
            <img src="https://i.imgur.com/u7y762i.jpg" alt="Arroz">
            <h3>Arroz 5kg</h3>
            <p>R$ 25,90</p>
        </div>
        <div class="produto">
            <img src="https://i.imgur.com/qE4Jv0F.jpg" alt="Feijão">
            <h3>Feijão Preto 1kg</h3>
            <p>R$ 7,50</p>
        </div>
        <div class="produto">
            <img src="https://i.imgur.com/lM3xNfF.jpg" alt="Leite">
            <h3>Leite Integral 1L</h3>
            <p>R$ 4,20</p>
        </div>
        <div class="produto">
            <img src="https://i.imgur.com/1n5y5E0.jpg" alt="Óleo">
            <h3>Óleo de Soja 900ml</h3>
            <p>R$ 5,80</p>
        </div>
        <div class="produto">
            <img src="https://i.imgur.com/kS9wM9g.jpg" alt="Macarrão">
            <h3>Macarrão Espaguete</h3>
            <p>R$ 3,99</p>
        </div>
        <div class="produto">
            <img src="https://i.imgur.com/5BvjYn2.jpg" alt="Café">
            <h3>Café 500g</h3>
            <p>R$ 12,50</p>
        </div>
        <div class="produto">
            <img src="https://i.imgur.com/C3u2XgJ.jpg" alt="Açúcar">
            <h3>Açúcar 1kg</h3>
            <p>R$ 3,20</p>
        </div>
        <div class="produto">
            <img src="https://i.imgur.com/6jNf4z9.jpg" alt="Farinha de Trigo">
            <h3>Farinha de Trigo 1kg</h3>
            <p>R$ 4,10</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Supermercado Bom Preço - Todos os direitos reservados.</p>
    </footer>

</body>
</html>
