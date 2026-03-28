# Ecomerse-shop
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Book Store | Twoja Biblioteka Cyfrowa</title>
    <style>
        :root {
            --primary-color: #2563eb;
            --dark-color: #1e293b;
            --light-color: #f8fafc;
            --accent-color: #10b981;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--light-color);
            color: var(--dark-color);
        }

        header {
            background-color: white;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
        }

        nav a {
            margin-left: 20px;
            text-decoration: none;
            color: var(--dark-color);
            font-weight: 500;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(135deg, #2563eb 0%, #7c3aed 100%);
            color: white;
        }

        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .card {
            background: white;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-10px);
        }

        .book-cover {
            width: 150px;
            height: 200px;
            background-color: #ddd;
            margin: 0 auto 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 4px;
            font-weight: bold;
            color: #666;
            border: 1px solid #eee;
        }

        .price {
            font-size: 1.25rem;
            font-weight: bold;
            color: var(--primary-color);
            margin: 10px 0;
        }

        .btn {
            background-color: var(--accent-color);
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            width: 100%;
        }

        .payments {
            margin-top: 50px;
            text-align: center;
            padding: 30px;
            background: #fff;
            border-top: 1px solid #eee;
        }

        .payment-icons {
            font-size: 0.9rem;
            color: #64748b;
            margin-top: 10px;
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.8rem;
            color: #94a3b8;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">E-BookStore 📚</div>
    <nav>
        <a href="#">Sklep</a>
        <a href="#">Moje Konto</a>
        <a href="#">Koszyk (0)</a>
    </nav>
</header>

<section class="hero">
    <h1>Zdobądź wiedzę w kilka sekund</h1>
    <p>Najlepsze ebooki o programowaniu i rozwoju osobistym.</p>
</section>

<div class="container">
    <div class="product-grid">
        <div class="card">
            <div class="book-cover">JS PRO</div>
            <h3>Mastering JavaScript</h3>
            <p>Od podstaw do seniora.</p>
            <div class="price">49,00 PLN</div>
            <button class="btn">Dodaj do koszyka</button>
        </div>

        <div class="card">
            <div class="book-cover" style="background-color: #fef3c7;">AI DEV</div>
            <h3>Sztuczna Inteligencja</h3>
            <p>Praktyczny przewodnik.</p>
            <div class="price">67,00 PLN</div>
            <button class="btn">Dodaj do koszyka</button>
        </div>

        <div class="card">
            <div class="book-cover" style="background-color: #dcfce7;">MINDSET</div>
            <h3>Nawyki Sukcesu</h3>
            <p>Zmień swoje myślenie.</p>
            <div class="price">35,00 PLN</div>
            <button class="btn">Dodaj do koszyka</button>
        </div>
    </div>
</div>

<section class="payments">
    <h3>Bezpieczne płatności</h3>
    <p>Obsługujemy najpopularniejsze metody płatności:</p>
    <div class="payment-icons">
        <span>✅ BLIK</span>
        <span>✅ Przelewy24</span>
        <span>✅ Karty Płatnicze (Visa/Mastercard)</span>
        <span>✅ Google Pay / Apple Pay</span>
        <span>✅ PayPal</span>
    </div>
</section>

<footer>
    &copy; 2026 E-BookStore. Wszystkie prawa zastrzeżone.
</footer>

</body>
</html>
