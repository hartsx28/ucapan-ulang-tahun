# ucapan-ulang-tahun
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun Reina Putri Azzahra</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f9f3f3;
            color: #333;
            text-align: center;
            padding: 50px;
            position: relative;
            overflow: hidden; /* Prevents overflow from moving hearts */
        }
        h1 {
            color: #ff69b4;
            font-size: 48px;
            animation: bounce 3s infinite;
        }
        p {
            font-size: 24px;
            margin: 20px 0;
            opacity: 0;
            animation: fadeIn 2s forwards;
        }
        p:nth-child(3) {
            animation-delay: 0.5s;
        }
        p:nth-child(4) {
            animation-delay: 2s;
        }
        p:nth-child(5) {
            animation-delay: 1.5s;
        }
        .flower {
            font-size: 50px;
            animation: swing 2s infinite;
        }
        .footer {
            margin-top: 50px;
            font-size: 20px;
            color: #555;
            opacity: 0;
            animation: fadeIn 2s forwards;
            animation-delay: 2s;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-20px); }
            60% { transform: translateY(-10px); }
        }

        @keyframes swing {
            0%, 100% { transform: rotate(0deg); }
            50% { transform: rotate(10deg); }
        }

        /* Heart Animation */
        .heart {
            position: absolute;
            width: 50px;
            height: 50px;
            background-color: pink; /* Warna pink muda */
            clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%);
            animation: moveHeart 10s linear infinite;
            opacity: 0.7;
        }

        @keyframes moveHeart {
            0% {
                transform: translateY(100vh) translateX(0);
            }
            100% {
                transform: translateY(-100vh) translateX(100vw);
            }
        }
    </style>
</head>
<body>
    <h1>Selamat Ulang Tahun, Sayanggg!</h1>
    <p>Di hari istimewa ini, abg pengen ingin mengucapkan:</p>
    <p>Semoga semua impianmu menjadi kenyataan,</p>
    <p>Semoga kebahagiaan selalu menyertaimu, Maaf juga atas abg yg selalu mood swing akhir-akhir ini yaaa</p>
    <p>Dan semoga kedepannya tetap sama-sama terus.</p>
    <p>Selamat ulang tahun, sayangku! 🎉</p>
    
    <div class="flower">
        🌸 🌼 🌺 🌻 🌷
    </div>

    <div class="footer">
        Dengan cinta,<br>
        
    </div>

    <!-- Heart Elements -->
    <div class="heart" style="top: 0; left: 10%; animation-delay: 0s;"></div>
    <div class="heart" style="top: 0; left: 30%; animation-delay: 2s;"></div>
    <div class="heart" style="top: 0; left: 50%; animation-delay: 4s;"></div>
    <div class="heart" style="top: 0; left: 70%; animation-delay: 6s;"></div>
    <div class="heart" style="top: 0; left: 90%; animation-delay: 8s;"></div>
</body>
</html>
