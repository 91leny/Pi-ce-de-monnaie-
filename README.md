# Pi-ce-de-monnaie-
Découvrez cette pièce rare émise en édition limitée par La Poste en 2020. Gravée avec précision, elle rend hommage au patrimoine postal français. Un véritable objet de collection pour les passionnés de numismatique
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Monnaies de La Poste</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    main {
      padding: 30px;
      max-width: 800px;
      margin: auto;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }
    h1 {
      font-size: 28px;
      margin-bottom: 10px;
    }
    p {
      font-size: 16px;
      line-height: 1.6;
    }
    .price {
      font-size: 20px;
      font-weight: bold;
      margin: 15px 0;
    }
    .paypal-button {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Monnaies de La Poste</h1>
    <p>Pièces de collection françaises</p>
  </header>

  <main>
    <h2>Pièce de collection – La Poste 2020</h2>
    <img src="piece.jpg" alt="Pièce de monnaie La Poste" />
    <p>Découvrez cette pièce rare émise en édition limitée par La Poste en 2020. Gravée avec précision, elle rend hommage au patrimoine postal français. Un véritable objet de collection pour les passionnés de numismatique.</p>
    <p class="price">Prix : 25 €</p>

    <!-- Bouton PayPal -->
    <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank" class="paypal-button">
      <input type="hidden" name="cmd" value="_xclick">
      <input type="hidden" name="business" value="lenyyy_912@icloud.com">
      <input type="hidden" name="item_name" value="Pièce de collection – La Poste 2020">
      <input type="hidden" name="amount" value="25.00">
      <input type="hidden" name="currency_code" value="EUR">
      <input type="submit" value="Acheter avec PayPal" style="padding: 10px 20px; background-color: #ffc439; border: none; border-radius: 5px; cursor: pointer; font-size: 16px;">
    </form>
  </main>
</body>
</html>
