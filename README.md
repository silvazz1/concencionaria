# concessionária  


concessionaria-ecommerce/
│
├── public/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│
├── server/
│   ├── server.js
│
├── package.json
└── README.md
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Concessionária E-commerce</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Concessionária E-commerce</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Produtos</a></li>
                <li><a href="#">Ofertas</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="banner">
            <img src="banner.jpg" alt="Promoção de Veículos">
        </section>

        <section id="produtos">
            <h2>Produtos em Destaque</h2>
            <div class="produtos-lista">
                <!-- Produtos serão listados aqui -->
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 Concessionária E-commerce</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
