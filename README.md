<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>הלל גולד | Halel Gold - מפיצי ריח ומוצרי ניקוי</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@300;400;700&display=swap" rel="stylesheet">
</head>
<body>

    <header>
        <div class="logo">HALEL GOLD</div>
        <nav>
            <ul>
                <li><a href="#home">בית</a></li>
                <li><a href="#products">קטלוג מוצרים</a></li>
                <li><a href="#contact">הזמנות</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>הלל גולד</h1>
            <p>מוצרי ניקוי פרימיום ומערכות ריח חכמות לבית ולעסק</p>
            <a href="#products" class="btn">לצפייה בקולקציה</a>
        </div>
    </section>

    <section id="products" class="products">
        <h2>המוצרים שלנו</h2>
        <div class="product-grid">
            <div class="product-card">
                <div class="product-image">מפיץ ריח חכם</div>
                <h3>מערכת ריח חכמה</h3>
                <p>שליטה מלאה דרך האפליקציה בניחוח החלל שלך.</p>
                <button class="order-btn" onclick="sendOrder('מפיץ ריח חכם')">הזמנה מהירה</button>
            </div>
            <div class="product-card">
                <div class="product-image">מוצרי ניקוי</div>
                <h3>נוזל ניקוי פרימיום</h3>
                <p>ניחוח עוצמתי ואיכות ניקוי ללא פשרות.</p>
                <button class="order-btn" onclick="sendOrder('נוזל ניקוי פרימיום')">הזמנה מהירה</button>
            </div>
        </div>
    </section>

    <footer>
        <p>הלל גולד &copy; 2026 | שירות לקוחות: נופר ביטון</p>
    </footer>

    <script>
        function sendOrder(product) {
            const phone = "972500000000"; // כאן נעדכן את המספר של נופר
            const text = encodeURIComponent(`שלום, אני מעוניין להזמין את המוצר: ${product}`);
            window.open(`https://wa.me/${phone}?text=${text}`, '_blank');
        }
    </script>
</body>
</html>
