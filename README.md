[gemini-code-1777919194933.html](https://github.com/user-attachments/files/27372406/gemini-code-1777919194933.html)
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

    <!-- תפריט ניווט -->
    <header>
        <div class="logo">HALEL GOLD</div>
        <nav>
            <ul>
                <li><a href="#home">בית</a></li>
                <li><a href="#products">מוצרים</a></li>
                <li><a href="#contact">צור קשר</a></li>
            </ul>
        </nav>
    </header>

    <!-- באנר ראשי -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>הלל גולד</h1>
            <p>חוויית ניחוח יוקרתית ומוצרי ניקוי פרימיום לבית ולעסק</p>
            <a href="#products" class="btn">לצפייה בקטלוג</a>
        </div>
    </section>

    <!-- קטלוג מוצרים -->
    <section id="products" class="products">
        <h2>המוצרים שלנו</h2>
        <div class="product-grid">
            <!-- מוצר 1 -->
            <div class="product-card">
                <div class="product-image">תמונה כאן</div>
                <h3>מפיץ ריח חכם</h3>
                <p>שליטה מלאה דרך האפליקציה בניחוח הבית.</p>
                <span class="price">₪450</span>
                <button class="order-btn" onclick="sendOrder('מפיץ ריח חכם')">הזמן עכשיו</button>
            </div>
            <!-- מוצר 2 -->
            <div class="product-card">
                <div class="product-image">תמונה כאן</div>
                <h3>נוזל ניקוי פרימיום</h3>
                <p>ניחוח עוצמתי שנשאר לאורך זמן.</p>
                <span class="price">₪60</span>
                <button class="order-btn" onclick="sendOrder('נוזל ניקוי פרימיום')">הזמן עכשיו</button>
            </div>
        </div>
    </section>

    <!-- צור קשר -->
    <footer id="contact">
        <p>הלל גולד &copy; 2026 | כל הזכויות שמורות</p>
        <p>מעוניינים בייעוץ? התקשרו אלינו או שלחו הודעה</p>
    </footer>

    <script>
        function sendOrder(productName) {
            const phone = "972500000000"; // כאן מחליפים למספר הטלפון של העסק
            const message = `שלום הלל גולד, אני מעוניין להזמין את המוצר: ${productName}`;
            window.open(`https://wa.me/${phone}?text=${encodeURIComponent(message)}`, '_blank');
        }
    </script>
</body>
</html>
