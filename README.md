---# 1-PROJETO-DO-SEGUNDO-TRI
<<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mundo iPhone</title>

<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        background-color: #f5f5f7;
    }

    header {
        background-color: #000;
        color: white;
        text-align: center;
        padding: 20px;
    }

    nav {
        background-color: #222;
        text-align: center;
        padding: 10px;
    }

    nav a {
        color: white;
        text-decoration: none;
        margin: 15px;
    }

    .banner {
        text-align: center;
        padding: 50px;
        background: linear-gradient(to right, #000, #444);
        color: white;
    }

    .produtos {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 20px;
        padding: 30px;
    }

    .card {
        background: white;
        width: 250px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0,0,0,0.2);
        text-align: center;
        padding: 20px;
    }

    .card img {
        width: 100%;
        border-radius: 10px;
    }

    button {
        background-color: #0071e3;
        color: white;
        border: none;
        padding: 10px 20px;
        border-radius: 5px;
        cursor: pointer;
    }

    footer {
        background-color: #000;
        color: white;
        text-align: center;
        padding: 15px;
        margin-top: 20px;
    }
</style>
</head>

<body>

<header>
    <h1>Mundo iPhone</h1>
    <p>Tudo sobre os melhores iPhones</p>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Modelos</a>
    <a href="#">Preços</a>
    <a href="#">Contato</a>
</nav>

<section class="banner">
    <h2>Conheça os Novos iPhones</h2>
    <p>Design moderno, câmeras incríveis e máxima performance.</p>
</section>

<section class="produtos">
    <div class="card">
        <h3>iPhone 16</h3>
        <p>Tela avançada e ótimo desempenho.</p>
        <button>Saiba Mais</button>
    </div>

    <div class="card">
        <h3>iPhone 16 Pro</h3>
        <p>Câmera profissional e chip poderoso.</p>
        <button>Saiba Mais</button>
    </div>

    <div class="card">
        <h3>iPhone 16 Pro Max</h3>
        <p>A melhor experiência da linha iPhone.</p>
        <button>Saiba Mais</button>
    </div>
</section>

<footer>
    <p>© 2026 Mundo iPhone - Site Demonstrativo</p>
</footer>

</body>
</html>