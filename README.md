<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>הלל גולד | Halel Gold - מפיצי ריח ומוצרי ניקוי פרימיום</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@300;400;700&display=swap" rel="stylesheet">
</head>
<body>

    <header>
        <div class="logo">HALEL GOLD</div>
        <nav>
            <ul>
                <li><a href="#home">בית</a></li>
                <li><a href="#products">מוצרים</a></li>
                <li><a href="#contact">הזמנות</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>הלל גולד</h1>
            <p>חוויית ניחוח יוקרתית ומוצרי ניקוי פרימיום לבית ולעסק</p>
            <a href="#products" class="btn">לצפייה בקטלוג</a>
        </div>
    </section>

    <section id="products" class="products">
        <h2>הקולקציה שלנו</h2>
        <div class="product-grid">
            <div class="product-card">
                <div class="product-image">מפיץ ריח חכם</div>
                <h3>מערכת ריח חכמה</h3>
                <p>שליטה מלאה באפליקציה ליצירת האווירה המושלמת.</p>
                <button class="order-btn" onclick="sendOrder('מפיץ ריח חכם')">הזמן עכשיו</button>
            </div>
            <div class="product-card">
                <div class="product-image">מוצרי ניקוי</div>
                <h3>נוזל ניקוי פרימיום</h3>
                <p>ניקיון ללא פשרות בניחוחות יוקרתיים שנשארים לאורך זמן.</p>
                <button class="order-btn" onclick="sendOrder('נוזל ניקוי פרימיום')">הזמן עכשיו</button>
            </div>
        </div>
    </section>

    <footer>
        <p>הלל גולד &copy; 2026 | שירות לקוחות והזמנות: נופר ביטון</p>
    </footer>

    <script>
        function sendOrder(product) {
            // המספר של נופר ביטון כפי שמופיע במידע העסקי שלך
            const phone = "972502220198"; 
            const text = encodeURIComponent(`שלום הלל גולד, אני מעוניין להזמין: ${product}`);
            window.open(`https://wa.me/${phone}?text=${text}`, '_blank');
        }
    </script>
</body>
</html>
