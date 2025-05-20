<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Loja de Perfumes Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 30px;
        }
        h1 {
            color: #333;
        }
        .produtos {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .produto {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            width: 200px;
            padding: 15px;
            text-align: center;
        }
        .produto img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .nome {
            font-weight: bold;
            margin: 10px 0 5px 0;
        }
        .preco {
            color: #e91e63;
            margin-bottom: 10px;
        }
        button {
            background-color: #e91e63;
            color: #fff;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 14px;
        }
        button:hover {
            background-color: #d81b60;
        }
    </style>
</head>
<body>
    <header>
        <h1>Loja de Perfumes Online</h1>
        <p>Encontre seu perfume favorito e compre com facilidade!</p>
    </header>
    <section class="produtos">
        <div class="produto">
            <img src="https://images.unsplash.com/photo-1573164574396-cb89fa8f0b4f" alt="Perfume A" />
            <div class="nome">Perfume Floral</div>
            <div class="preco">R$ 120,00</div>
            <button>Comprar</button>
        </div>
        <div class="produto">
            <img src="https://images.unsplash.com/photo-1606788075761-4f4b7b7b7b7b" alt="Perfume B" />
            <div class="nome">Perfume Amadeirado</div>
            <div class="preco">R$ 150,00</div>
            <button>Comprar</button>
        </div>
        <div class="produto">
            <img src="https://images.unsplash.com/photo-1549924231-f129b911e442" alt="Perfume C" />
            <div class="nome">Perfume Frutal</div>
            <div class="preco">R$ 130,00</div>
            <button>Comprar</button>
        </div>
    </section>
</body>
</
