<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>Menu Pizzeria</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff8f0;
      padding: 20px;
    }

    header {
      text-align: center;
      background-color: #e74c3c;
      color: white;
      padding: 20px;
      border-radius: 10px;
    }

    .menu-section {
      margin: 30px 0;
    }

    .menu-section h2 {
      border-bottom: 2px solid #e74c3c;
      color: #e74c3c;
      padding-bottom: 5px;
    }

    .item {
      display: flex;
      justify-content: space-between;
      padding: 10px;
      background: #fff;
      border-radius: 5px;
      box-shadow: 0 1px 4px rgba(0, 0, 0, 0.1);
      margin-bottom: 8px;
    }

    .item-name {
      font-weight: bold;
    }

    .item-price {
      color: #27ae60;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      color: #777;
    }
  </style>
</head>
<body>

  <header>
    <h1>Menu Pizzeria Pitagora</h1>
  </header>

  <!-- elenco Pizze -->
  <section class="menu-section">
    <h2>🍕 Pizze</h2>
    <div class="item"><span class="item-name">Margherita</span><span class="item-price">€6.00</span></div>
    <div class="item"><span class="item-name">Diavola</span><span class="item-price">€7.50</span></div>
    <div class="item"><span class="item-name">Capricciosa</span><span class="item-price">€8.00</span></div>
    <div class="item"><span class="item-name">Quattro Formaggi</span><span class="item-price">€8.50</span></div>
  </section>

  <!-- elenco Pizze Dolci -->
  <section class="menu-section">
    <h2>🍫 Pizze Dolci</h2>
    <div class="item"><span class="item-name">Nutella</span><span class="item-price">€5.00</span></div>
    <div class="item"><span class="item-name">Nutella e Fragole</span><span class="item-price">€6.00</span></div>
    <div class="item"><span class="item-name">Nutella e Banane</span><span class="item-price">€6.00</span></div>
  </section>

  <!-- elenco Dolci -->
  <section class="menu-section">
    <h2>🍰 Dolci</h2>
    <div class="item"><span class="item-name">Tiramisù</span><span class="item-price">€4.50</span></div>
    <div class="item"><span class="item-name">Panna Cotta</span><span class="item-price">€4.00</span></div>
    <div class="item"><span class="item-name">Cannolo Siciliano</span><span class="item-price">€3.50</span></div>
    <div class="item"><span class="item-name">Gelato Artigianale</span><span class="item-price">€3.00</span></div>
  </section>

  <!-- elenco Bevande -->
  <section class="menu-section">
    <h2>🥤 Bevande</h2>
    <div class="item"><span class="item-name">Acqua Naturale (0.5L)</span><span class="item-price">€1.00</span></div>
    <div class="item"><span class="item-name">Coca-Cola (0.33L)</span><span class="item-price">€2.00</span></div>
    <div class="item"><span class="item-name">Fanta (0.33L)</span><span class="item-price">€2.00</span></div>
    <div class="item"><span class="item-name">Birra (0.5L)</span><span class="item-price">€3.50</span></div>
  </section>

  <!-- elenco Liquori -->
  <section class="menu-section">
    <h2>🥃 Liquori</h2>
    <div class="item"><span class="item-name">Limoncello</span><span class="item-price">€2.50</span></div>
    <div class="item"><span class="item-name">Grappa</span><span class="item-price">€3.00</span></div>
    <div class="item"><span class="item-name">Amaro</span><span class="item-price">€2.50</span></div>
    <div class="item"><span class="item-name">Sambuca</span><span class="item-price">€3.00</span></div>
  </section>

  <footer>
    © 2025 Pizzeria Bella Napoli - Tutti i diritti riservati
  </footer>

</body>
</html>
