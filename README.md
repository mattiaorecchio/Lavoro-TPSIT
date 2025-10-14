Questo menu' e' stato progettato da 4 sviluppatori ed ognuno aveva un compito:
il primo sviluppatore e' stato assegnato al menu' pizza
il secondo sviluppaore e' stato assegnato al menu' dolci 
il terzo sviluppatore e' stato assegnato al menu bevande
il quarto sviluppatore e' stato assegnato al menu' vini e liquori
Questo menu' della pizzeria "Palato Partenopeo" e' stato progettato da:
Mattia Orecchio(project manager), 
Michele Delos(collaboratore),
Giuseppe Altamore(collaboratore),
Manuel di Bonito(collaboratore, 
Francesco Mallardo finito in ospedale dopo aver assaggiato la pizza,
Alessia D'isanto giorno di festa per viaggio a "PARIGI".





<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <title>Pizzeria Palato Partenopeo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #444444; /* grigio scuro */
      padding: 20px;
    }

    header {
      text-align: center;
      background-color: #ffffff; /* rosso bordeaux */
      color: #e0e0e0; /* grigio chiaro */
      padding: 15px;
      border-radius: 8px;
    }
    h1, h2 {
      margin: 0 0 15px;
      font-weight: normal;
    }
    h2 {
      color: #85656d; /* rosso bordeaux */
      border-bottom: 2px solid #2e0b13;
      padding-bottom: 5px;
      margin-top: 40px;
    }
    .menu-section {
      max-width: 700px;
      margin: auto;
    }

    .item-row {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      margin-bottom: 20px;
    }
    .item-row .item {
      flex: 1 1 calc(50% - 10px);
    }
    .item {
      background: white;
      border-radius: 6px;
      margin-bottom: 15px;
      padding: 15px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      cursor: pointer;
      transition: box-shadow 0.2s ease;
    }
    .item:hover {
      box-shadow: 0 0 12px rgba(0,0,0,0.2);
    }
    .item-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .item-name {
      font-weight: bold;
      font-size: 1.1em;
      color: #9b213f; /* rosso bordeaux */
    }
    .item-price {
      color: #666666; /* grigio medio */
      font-weight: bold;
    }
    .ingredients {
      display: none;
      margin-top: 8px;
      font-size: 0.95em;
      color: #666666;
    }
    .item.active .ingredients {
      display: block;
    }
    .item-image {
      width: 100%;
      max-height: 200px;
      object-fit: cover;
      border-radius: 6px 6px 0 0;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      margin-top: 50px;
      font-style: italic;
      color: #666666;
    }
  </style>
</head>
<body>
  <header>
    <img src="./immagini/logo.png" alt="Logo Pizzeria Palato Partenopeo" class="logo" />
  </header>
  

  <!-- resto della pagina invariato... -->


  <!-- ANTIPASTI -->
  <section class="menu-section">
    <h2>Antipasti</h2>
    <div class="item">
      <img src="./immagini/bruschette_miste.jpg" alt="Bruschette miste" class="item-image" />
      <div class="item-header">
        <span class="item-name">Bruschette miste</span>
        <span class="item-price">€6.00</span>
      </div>
      <div class="ingredients">Pane tostato con pomodoro, aglio, basilico e olio EVO</div>
    </div>
    <div class="item">
      <img src="./immagini/tagliere_salumi_formaggi.jpg" alt="Tagliere di salumi e formaggi" class="item-image" />
      <div class="item-header">
        <span class="item-name">Tagliere di salumi e formaggi</span>
        <span class="item-price">€12.00</span>
      </div>
      <div class="ingredients">Salame, prosciutto crudo, coppa, formaggi misti, miele e marmellata</div>
    </div>
    <div class="item">
      <img src="./immagini/frittura_calamari_gamberi.jpg" alt="Frittura di calamari e gamberi" class="item-image" />
      <div class="item-header">
        <span class="item-name">Frittura di calamari e gamberi</span>
        <span class="item-price">€10.00</span>
      </div>
      <div class="ingredients">Calamari e gamberi fritti croccanti, limone</div>
    </div>
    <div class="item">
      <img src="./immagini/mozzarella_incarrozza.jpg" alt="Mozzarella in carrozza" class="item-image" />
      <div class="item-header">
        <span class="item-name">Mozzarella in carrozza</span>
        <span class="item-price">€7.00</span>
      </div>
      <div class="ingredients">Mozzarella impanata e fritta, salsa al pomodoro</div>
    </div>
    <div class="item">
      <img src="./immagini/polpette_della_nonna.jpg" alt="Polpette della nonna" class="item-image" />
      <div class="item-header">
        <span class="item-name">Polpette della nonna</span>
        <span class="item-price">€6.50</span>
      </div>
      <div class="ingredients">Polpette di carne con salsa al pomodoro</div>
    </div>
    <div class="item">
      <img src="./immagini/caprese.jpg" alt="Caprese" class="item-image" />
      <div class="item-header">
        <span class="item-name">Caprese</span>
        <span class="item-price">€8.00</span>
      </div>
      <div class="ingredients">Mozzarella di bufala, pomodoro, basilico, olio EVO</div>
    </div>
    <div class="item">
      <img src="./immagini/crostino_ai_funghi.jpg" alt="Crostini ai funghi" class="item-image" />
      <div class="item-header">
        <span class="item-name">Crostini ai funghi</span>
        <span class="item-price">€6.50</span>
      </div>
      <div class="ingredients">Pane tostato con crema di funghi porcini</div>
    </div>
    <div class="item">
      <img src="./immagini/insalata_di_mare.jpg" alt="Insalata di mare" class="item-image" />
      <div class="item-header">
        <span class="item-name">Insalata di mare</span>
        <span class="item-price">€9.00</span>
      </div>
      <div class="ingredients">Misto di frutti di mare, olio, limone e prezzemolo</div>
    </div>
    <div class="item">
      <img src="./immagini/olive_ascolane.jpg" alt="Olive ascolane" class="item-image" />
      <div class="item-header">
        <span class="item-name">Olive ascolane</span>
        <span class="item-price">€7.00</span>
      </div>
      <div class="ingredients">Olive verdi ripiene di carne, impanate e fritte</div>
    </div>
    <div class="item">
      <img src="./immagini/carpaccio_bresaola.jpg" alt="Carpaccio di bresaola" class="item-image" />
      <div class="item-header">
        <span class="item-name">Carpaccio di bresaola</span>
        <span class="item-price">€8.50</span>
      </div>
      <div class="ingredients">Bresaola, rucola, scaglie di parmigiano, olio EVO</div>
    </div>
  </section>

  <!-- PIZZE CLASSICHE -->
<section class="menu-section">
  <h2>Pizze Classiche</h2>

  <div class="item-row">
    <div class="item">
      <img src="./immagini/margherita.jpg" alt="Margherita" class="item-image" />
      <div class="item-header">
        <span class="item-name">Margherita</span>
        <span class="item-price">€6.00</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Basilico</div>
    </div>
    <div class="item">
      <img src="./immagini/diavola.jpg" alt="Diavola" class="item-image" />
      <div class="item-header">
        <span class="item-name">Diavola</span>
        <span class="item-price">€7.00</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Salame piccante</div>
    </div>
  </div>

  <div class="item-row">
    <div class="item">
      <img src="./immagini/capricciosa.jpg" alt="Capricciosa" class="item-image" />
      <div class="item-header">
        <span class="item-name">Capricciosa</span>
        <span class="item-price">€8.00</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Prosciutto, Funghi, Carciofi</div>
    </div>
    <div class="item">
      <img src="./immagini/quattro_stagioni.jpg" alt="Quattro Stagioni" class="item-image" />
      <div class="item-header">
        <span class="item-name">Quattro Stagioni</span>
        <span class="item-price">€8.50</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Prosciutto, Funghi, Carciofi, Olive</div>
    </div>
  </div>

  <div class="item-row">
    <div class="item">
      <img src="./immagini/funghi.jpg" alt="Funghi" class="item-image" />
      <div class="item-header">
        <span class="item-name">Funghi</span>
        <span class="item-price">€7.00</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Funghi</div>
    </div>
    <div class="item">
      <img src="./immagini/marinara.jpg" alt="Marinara" class="item-image" />
      <div class="item-header">
        <span class="item-name">Marinara</span>
        <span class="item-price">€5.00</span>
      </div>
      <div class="ingredients">Pomodoro, Aglio, Origano</div>
    </div>
  </div>

  <div class="item-row">
    <div class="item">
      <img src="./immagini/napoli.jpg" alt="Napoli" class="item-image" />
      <div class="item-header">
        <span class="item-name">Napoli</span>
        <span class="item-price">€7.50</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Acciughe, Capperi</div>
    </div>
    <div class="item">
      <img src="./immagini/prosciutto_cotto.jpg" alt="Prosciutto Cotto" class="item-image" />
      <div class="item-header">
        <span class="item-name">Prosciutto Cotto</span>
        <span class="item-price">€7.00</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Prosciutto cotto</div>
    </div>
  </div>

  <div class="item-row">
    <div class="item">
      <img src="./immagini/caprese_pizza.jpg" alt="Caprese" class="item-image" />
      <div class="item-header">
        <span class="item-name">Caprese</span>
        <span class="item-price">€8.00</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella di bufala, Basilico</div>
    </div>
    <div class="item">
      <img src="./immagini/rucola.jpg" alt="Rucola" class="item-image" />
      <div class="item-header">
        <span class="item-name">Rucola</span>
        <span class="item-price">€8.50</span>
      </div>
      <div class="ingredients">Pomodoro, Mozzarella, Rucola, Scaglie di parmigiano</div> 
    </div>
  </div>
    <div class="item-row">
    <div class="item">
      <img src="./immagini/pizza_crocche.jpg" alt="Crocchettone" class="item-image" />
      <div class="item-header">
        <span class="item-name">Crocchettone</span>
        <span class="item-price">€8.00</span>
      </div>
      <div class="ingredients">Crocche freschi, Prosciutto cotto, Mozzarella</div> 
    </div>
    <div class="item">
      <img src="./immagini/wurstel_patatine.jpg" alt="Wurstel e Patatine" class="item-image" />
      <div class="item-header">
        <span class="item-name">Wurstel e Patatine</span>
        <span class="item-price">€8.50</span>
      </div>
      <div class="ingredients"> Mozzarella, Wurstel, Patatine fritte</div> 
    </div>
  </div>
</section>



  <!-- DOLCI -->
  <section class="menu-section">
    <h2>Dolci</h2>
    <div class="item">
      <img src="./immagini/tiramisu.jpg" alt="Tiramisù" class="item-image" />
      <div class="item-header">
        <span class="item-name">Tiramisù</span>
        <span class="item-price">€5.00</span>
      </div>
      <div class="ingredients">Mascarpone, caffè, savoiardi, cacao</div>
    </div>
    <div class="item">
      <img src="./immagini/panna_cotta.jpg" alt="Panna Cotta" class="item-image" />
      <div class="item-header">
        <span class="item-name">Panna Cotta</span>
        <span class="item-price">€4.50</span>
      </div>
      <div class="ingredients">Panna, zucchero, gelatina, frutti di bosco</div>
    </div>
    <div class="item">
      <img src="./immagini/cannoli_siciliani.jpg" alt="Cannoli Siciliani" class="item-image" />
      <div class="item-header">
        <span class="item-name">Cannoli Siciliani</span>
        <span class="item-price">€5.50</span>
      </div>
      <div class="ingredients">Cialda croccante, ricotta dolce, canditi</div>
    </div>
    <div class="item">
      <img src="./immagini/crostata.jpg" alt="Crostata" class="item-image" />
      <div class="item-header">
        <span class="item-name">Crostata</span>
        <span class="item-price">€4.00</span>
      </div>
      <div class="ingredients">Pasta frolla, marmellata</div>
    </div>
    <div class="item">
      <img src="./immagini/gelato.jpg" alt="Gelato" class="item-image" />
      <div class="item-header">
        <span class="item-name">Gelato</span>
        <span class="item-price">€3.50</span>
      </div>
      <div class="ingredients">Varie creme e gusti</div>
    </div>
  </section>

  <!-- BEVANDE -->
  <section class="menu-section">
    <h2>Bevande</h2>
    <div class="item">
      <div class="item-header">
        <span class="item-name">Acqua naturale 0.5L</span>
        <span class="item-price">€1.00</span>
      </div>
    </div>
    <div class="item">
      <div class="item-header">
        <span class="item-name">Acqua frizzante 0.5L</span>
        <span class="item-price">€1.50</span>
      </div>
    </div>
    <div class="item">
      <div class="item-header">
        <span class="item-name">Bibita (Coca Cola, Fanta, Sprite) 0.33L</span>
        <span class="item-price">€2.00</span>
      </div>
    </div>
    <div class="item">
      <div class="item-header">
        <span class="item-name">Birra (bottiglia 0.33L)</span>
        <span class="item-price">€3.00</span>
      </div>
    </div>
    <div class="item">
      <div class="item-header">
        <span class="item-name">Vino rosso / bianco (bicchiere 0.2L)</span>
        <span class="item-price">€4.00</span>
      </div>
    </div>
  </section>

  <!-- VINI -->
<section class="menu-section">
  <h2>Vini</h2>

  <div class="item">
    <div class="item-header">
      <span class="item-name">Vino della casa (rosso / bianco) - Bicchiere 0.2L</span>
      <span class="item-price">€4.00</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Falanghina (bottiglia 0.75L)</span>
      <span class="item-price">€15.00</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Greco di Tufo (bottiglia 0.75L)</span>
      <span class="item-price">€18.00</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Fiano di Avellino (bottiglia 0.75L)</span>
      <span class="item-price">€18.00</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Aglianico del Vulture (bottiglia 0.75L)</span>
      <span class="item-price">€20.00</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Chianti Classico DOCG (bottiglia 0.75L)</span>
      <span class="item-price">€22.00</span>
    </div>
  </div>
</section>

<!-- LIQUORI E DIGESTIVI -->
<section class="menu-section">
  <h2>Liquori e Digestivi</h2>

  <div class="item">
    <div class="item-header">
      <span class="item-name">Limoncello</span>
      <span class="item-price">€3.00</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Amaro del Capo</span>
      <span class="item-price">€3.50</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Amaro Lucano</span>
      <span class="item-price">€3.50</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Grappa</span>
      <span class="item-price">€4.00</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Sambuca</span>
      <span class="item-price">€3.50</span>
    </div>
  </div>
  <div class="item">
    <div class="item-header">
      <span class="item-name">Mirto</span>
      <span class="item-price">€3.50</span>
    </div>
  </div>
</section>


  <footer>
    © 2025 Pizzeria Palato Partenopeo - Tutti i diritti riservati
  </footer>

  <script>
    // Script per mostrare/nascondere ingredienti al click
    document.querySelectorAll('.item').forEach(item => {
      item.addEventListener('click', () => {
        item.classList.toggle('active');
      });
    });
  </script>
</body>
</html>
