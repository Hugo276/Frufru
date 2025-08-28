# Frufru
!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Trabaio</title>
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
            <img src="https://via.placeholder.com/200x150?text=Arroz" alt="Arroz">
            <h3>Arroz 5kg</h3>
            <p>R$ 25,90</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/200x150?text=Feijão" alt="Feijão">
            <h3>Feijão Preto 1kg</h3>
            <p>R$ 7,50</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/200x150?text=Leite" alt="Leite">
            <h3>Leite Integral 1L</h3>
            <p>R$ 4,20</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/200x150?text=Óleo" alt="Óleo">
            <h3>Óleo de Soja 900ml</h3>
            <p>R$ 5,80</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/200x150?text=Macarrão" alt="Macarrão">
            <h3>Macarrão Espaguete</h3>
            <p>R$ 3,99</p>
        </div>
    </div>

</body>
</html>


Substitui por png dps
