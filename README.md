# Faqat-sen-uchun
[intel.html](https://github.com/user-attachments/files/34846607/intel.html)
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <title>Siz uchun...</title>
    <!-- CSS faylni ulaymiz -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="karta">
        <!-- Yurakcha belgisi -->
        <div class="yurak">❤️</div>
        
        <h1>Assalomu alaykum!</h1>
        <p>Bu sahifa faqat siz uchun, eng samimiy tilaklarim va iliq tuyg'ularim ila yaratildi.</p>
        
        <div class="gul">🌸 ✨ 🌸</div>

        <!-- Havola -->
        <a href="https://github.com" class="tugma">Qalbim sahifasi</a>
    </div>
</body>
</html>/* 1. Orqa fon: pushti va binafsha ranglarning mayin uyg'unligi */
body {
    background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 99%, #fecfef 100%);
    height: 100vh;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}

/* 2. Oq rangli, chetlari yumshoq quti (karta) */
.karta {
    background-color: rgba(255, 255, 255, 0.9);
    padding: 40px;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    max-width: 400px;
    width: 90%;
}

/* 3. Sarlavha rangi */
h1 {
    color: #d63384;
    font-size: 28px;
    margin-bottom: 15px;
}

/* 4. Matn dizayni */
p {
    color: #666666;
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 25px;
}

/* 5. Yurakchaga doimiy urish (pulsatsiya) animatsiyasini berish */
.yurak {
    font-size: 50px;
    animation: yurak-urishi 1.2s infinite;
}

/* Yurak qanday sakrashi/urishi */
@keyframes yurak-urishi {
    0% { transform: scale(1); }
    50% { transform: scale(1.25); }
    100% { transform: scale(1); }
}

/* Gul elementiga nafislik */
.gul {
    font-size: 22px;
    margin-bottom: 25px;
}

/* 6. Romantik tugma */
.tugma {
    display: inline-block;
    background: linear-gradient(45deg, #ff758c, #ff7eb3);
    color: white;
    text-decoration: none;
    padding: 12px 25px;
    border-radius: 25px;
    font-weight: bold;
    box-shadow: 0 4px 15px rgba(255, 117, 140, 0.4);
    transition: 0.3s; /* Silliq o'zgarish uchun */
}

/* Sichqoncha tugmaga borganda kattalashishi */
.tugma:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 20px rgba(255, 117, 140, 0.6);
}

