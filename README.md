<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Loja Elegante</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Minha Loja Elegante</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Produtos</a></li>
                <li><a href="#">Sobre Nós</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section class="hero">
            <h2>Bem-vindo à nossa loja!</h2>
            <p>Confira nossos produtos exclusivos</p>
        </section>
        
        <section class="produtos-destaque">
            <h2>Produtos em Destaque</h2>
            <div class="produto">
                <img src="images/produto1.jpg" alt="Produto 1">
                <h3>Produto 1</h3>
                <p>Descrição do produto 1</p>
                <button>Comprar</button>
            </div>
            <div class="produto">
                <img src="images/produto2.jpg" alt="Produto 2">
                <h3>Produto 2</h3>
                <p>Descrição do produto 2</p>
                <button>Comprar</button>
            </div>
            <!-- Adicione mais produtos conforme necessário -->
        </section>
    </main>
    
    <footer>
        <p>© 2024 Minha Loja Elegante</p>
        <p>Contato: contato@minhalojaelegante.com</p>
    </footer>
    
    <script src="js/scripts.js"></script>
</body>
</html>
body {
    font-family: 'Georgia', serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #002147;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background-color: #004d40;
    color: #fff;
    padding: 50px 0;
    text-align: center;
}

.produtos-destaque {
    padding: 20px;
    text-align: center;
}

.produto {
    display: inline-block;
    margin: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 15px;
    width: 200px;
}

.produto img {
    max-width: 100%;
    height: auto;
    border-bottom: 1px solid #ddd;
    margin-bottom: 10px;
}

.produto h3 {
    font-size: 1.2em;
    color: #002147;
}

.produto p {
    color: #555;
}

.produto button {
    background-color: #002147;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 5px;
}

.produto button:hover {
    background-color: #004d40;
}

footer {
    background-color: #002147;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}
