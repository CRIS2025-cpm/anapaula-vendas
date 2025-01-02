<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja Limpeza Total</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #007BFF;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    header p {
      margin: 5px 0 0;
      font-size: 18px;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #0056b3;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }
    .container {
      padding: 20px;
    }
    .product {
      border: 1px solid #ddd;
      border-radius: 8px;
      background: white;
      padding: 15px;
      margin: 15px 0;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    .product h3 {
      margin: 0 0 10px;
    }
    .product p {
      margin: 5px 0;
    }
    .product button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
    }
    .product button:hover {
      background-color: #218838;
    }
    footer {
      background-color: #007BFF;
      color: white;
      text-align: center;
      padding: 15px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Loja Limpeza Total</h1>
    <p>DONA DO SITE: ANA PAULA</p>
    <p>Produtos de Limpeza de Alta Qualidade</p>
  </header>
  <nav>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Contato</a>
  </nav>
  <div class="container" id="produtos">
    <h2>Produtos</h2>
    <div class="product">
      <h3>Pasta Clareadora - 500g</h3>
      <p>Limpa tudo! Dá brilho em alumínio, tira manchas, remove graxa em todas as superfícies. MULTIUSO.</p>
      <p><strong>Preço:</strong> R$ 8,00</p>
      <button onclick="location.href='https://wa.me/5532991078781?text=Olá,%20gostaria%20de%20comprar%20a%20Pasta%20Clareadora%20de%20500g%20por%20R$8,00'">
        Comprar pelo WhatsApp
      </button>
    </div>
    <div class="product">
      <h3>Pasta Clareadora - 250g</h3>
      <p>Limpa tudo! Dá brilho em alumínio, tira manchas, remove graxa em todas as superfícies. MULTIUSO.</p>
      <p><strong>Preço:</strong> R$ 4,00</p>
      <button onclick="location.href='https://wa.me/5532991078781?text=Olá,%20gostaria%20de%20comprar%20a%20Pasta%20Clareadora%20de%20250g%20por%20R$4,00'">
        Comprar pelo WhatsApp
      </button>
    </div>
    <div class="product">
      <h3>Desinfetante - 2L</h3>
      <p>Verifique pelo WhatsApp a disponibilidade das fragrâncias.</p>
      <p><strong>Preço:</strong> R$ 7,50</p>
      <button onclick="location.href='https://wa.me/5532991078781?text=Olá,%20gostaria%20de%20comprar%20o%20Desinfetante%20de%202L%20por%20R$7,50'">
        Comprar pelo WhatsApp
      </button>
    </div>
    <div class="product">
      <h3>Amaciante Downe - 2L</h3>
      <p>Amaciante de roupas com toque suave e agradável.</p>
      <p><strong>Preço:</strong> R$ 10,00</p>
      <button onclick="location.href='https://wa.me/5532991078781?text=Olá,%20gostaria%20de%20comprar%20o%20Amaciante%20Downe%20de%202L%20por%20R$10,00'">
        Comprar pelo WhatsApp
      </button>
    </div>
    <div class="product">
      <h3>Sabão Caseiro</h3>
      <p>Limpa tudo! Ideal para vasilhas, roupas e muito mais.</p>
      <p><strong>Preço:</strong> R$ 4,00 (por barra)</p>
      <button onclick="location.href='https://wa.me/5532991078781?text=Olá,%20gostaria%20de%20comprar%20o%20Sabão%20Caseiro%20por%20R$4,00'">
        Comprar pelo WhatsApp
      </button>
    </div>
  </div>
  <footer>
    <p>Entre em contato pelo WhatsApp: +55 32 99107-8781</p>
  </footer>
</body>
</html>
