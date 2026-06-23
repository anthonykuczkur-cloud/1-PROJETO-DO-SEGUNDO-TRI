DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PUMA Sports</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f5f5f5;
}

header{
    background:#000;
    color:#fff;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:32px;
    font-weight:bold;
    color:#fff;
}

nav a{
    color:#fff;
    text-decoration:none;
    margin-left:20px;
    transition:0.3s;
}

nav a:hover{
    color:#ffcc00;
}

.hero{
    height:90vh;
    background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
    url('https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=1200');
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:#fff;
}

.hero-content h1{
    font-size:60px;
    margin-bottom:20px;
}

.hero-content p{
    font-size:22px;
    margin-bottom:30px;
}

.btn{
    background:#ffcc00;
    color:#000;
    padding:15px 30px;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

.produtos{
    padding:80px 8%;
}

.titulo{
    text-align:center;
    margin-bottom:40px;
    font-size:40px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#fff;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 4px 10px rgba(0,0,0,.1);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card-content{
    padding:20px;
    text-align:center;
}

.preco{
    color:#00a000;
    font-size:22px;
    margin:10px 0;
}

button{
    background:#000;
    color:#fff;
    border:none;
    padding:12px 20px;
    border-radius:8px;
    cursor:pointer;
}

.sobre{
    background:#000;
    color:#fff;
    padding:80px 10%;
    text-align:center;
}

.contato{
    padding:80px 10%;
}

form{
    max-width:600px;
    margin:auto;
}

input, textarea{
    width:100%;
    padding:15px;
    margin:10px 0;