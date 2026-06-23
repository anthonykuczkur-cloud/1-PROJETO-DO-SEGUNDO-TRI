---# 1-PROJETO-DO-SEGUNDO-TRI
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SportWear - Blusas Esportivas</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
}

header{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
}

nav{
    background:#222;
    padding:15px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}

.banner{
    background:linear-gradient(to right,#0077ff,#00c3ff);
    color:white;
    text-align:center;
    padding:80px 20px;
}

.banner h1{
    font-size:50px;
}

.produtos{
    padding:40px;
}

.produtos h2{
    text-align:center;
    margin-bottom:30px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:12px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
    overflow:hidden;
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card-info{
    padding:15px;
    text-align:center;
}

.preco{
    color:green;
    font-size:22px;
    margin:10px 0;
}

button{
    background:#0077ff;
    color:white;
    border:none;
    padding:10px 20px;
    border-radius:5px;
    cursor:pointer;
}

#carrinho{
    position:fixed;
    top:15px;
    right:15px;
    background:#fff;
    padding:10px 15px;
    border-radius:20px;
    font-weight:bold;
    box-shadow:0 0 10px rgba(0,0,0,.2);
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}
</style>
</head>

<body>

<div id="carrinho">🛒 0 itens</div>

<header>
    <h1>SportWear</h1>
    <p>As melhores blusas esportivas para seu treino</p>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Produtos</a>
    <a href="#">Promoções</a>
    <a href="#">Contato</a>
</nav>

<section class="banner">
    <h1>Nova Coleção 2026</h1>
    <p>Conforto, estilo e performance.</p>
</section>

<section class="produtos">
    <h2>Blusas em Destaque</h2>

    <div class="grid">

        <div class="card">
            <img src="https://via.placeholder.com/300x250" alt="Blusa Dry Fit">
            <div class="card-info">
                <h3>Blusa Dry Fit</h3>
                <p>Ideal para corrida e academia.</p>
                <div class="preco">R$ 79,90</div>
                <button onclick="adicionar()">Comprar</button>
            </div>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/300x250" alt="Blusa Treino">
            <div class="card-info">
                <h3>Blusa Treino Pro</h3>
                <p>Tecido leve e respirável.</p>
                <div class="preco">R$ 99,90</div>
                <button onclick="adicionar()">Comprar</button>
            </div>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/300x250" alt="Blusa Manga Longa">
            <div class="card-info">
                <h3>Blusa Manga Longa</h3>
                <p>Perfeita para dias frios.</p>
                <div class="preco">R$ 119,90</div>
                <button onclick="adicionar()">Comprar</button>
            </div>
        </div>

    </div>
</section>

<footer>
    <p>© 2026 SportWear - Todos os direitos reservados.</p>
</footer>

<script>
let itens = 0;

function adicionar(){
    itens++;
    document.getElementById("carrinho").innerHTML =
    "🛒 " + itens + " itens";
}
</script>

</body>
</html>