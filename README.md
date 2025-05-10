<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ma Boutique</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    .produits {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 2rem;
    }
    .produit {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 1rem;
      width: 200px;
      text-align: center;
    }
    .produit img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .produit button {
      background-color: #28a745;
      color: white;
      border: none;
      padding: 10px;
      margin-top: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    .produit button:hover {
      background-color: #218838;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue dans ma boutique</h1>
  </header>
  <section class="produits">
    <div class="produit">
      <img src="https://via.placeholder.com/200x150" alt="Produit 1">
      <h3>Produit 1</h3>
      <p>10 €</p>
      <button>Ajouter au panier</button>
    </div>
    <div class="produit">
      <img src="https://via.placeholder.com/200x150" alt="Produit 2">
      <h3>Produit 2</h3>
      <p>15 €</p>
      <button>Ajouter au panier</button>
    </div>
  </section>
</body>
</html>
