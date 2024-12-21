<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محمد النيف</title>
    <style>
        /* 🌟 إعدادات الصفحة العامة 🌟 */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: url('https://i.imgur.com/HRgK0NP.jpeg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow: hidden;
            position: relative;
        }

        /* طبقة شفافة فوق الخلفية */
        body::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
            z-index: -1;
        }

        /* 🌟 الصورة الشخصية 🌟 */
        .profile-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #ffd700; /* إطار ذهبي */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            animation: fadeIn 1.5s ease-in-out;
            transition: transform 0.3s ease, filter 0.3s ease;
        }

        .profile-image:hover {
            transform: scale(1.1); /* تكبير */
            filter: hue-rotate(90deg); /* تغيير الألوان */
        }

        /* 🌟 العنوان الرئيسي 🌟 */
        h1 {
            font-size: 2rem;
            margin-top: 20px;
            animation: fadeInUp 1.5s ease-out;
        }

        /* 🌟 النصوص العادية 🌟 */
        p {
            font-size: 1.2rem;
            margin-top: 10px;
            animation: fadeInUp 1.5s ease-out;
        }

        /* 🌟 النص التسويقي 🌟 */
        .promo-text {
            font-size: 1.2rem;
            font-weight: bold;
            margin-top: 10px;
            color: #ffd700; /* ذهبي */
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
            animation: fadeIn 1.5s ease-in-out;
        }

        /* 🌟 روابط التواصل الاجتماعي 🌟 */
        .links {
            margin-top: 20px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            animation: fadeInUp 1.5s ease-out;
        }

        .links a {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 10px 20px;
            font-size: 1rem;
            color: #fff;
            background: #444;
            text-decoration: none;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            transition: background 0.3s ease, transform 0.2s ease;
        }

        .links a:hover {
            background: #ffd700; /* ذهبي */
            transform: translateY(-3px);
        }

        .links img {
            width: 25px;
            height: 25px;
        }

        /* 🌟 زر شراء الرواية 🌟 */
        .buy-btn {
            margin-top: 20px;
            padding: 10px 20px;
            background: #ffd700; /* ذهبي */
            color: #000; /* نص أسود */
            font-size: 1rem;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s, transform 0.2s;
        }

        .buy-btn:hover {
            background: #e6b800; /* لون ذهبي أغمق قليلاً */
            transform: scale(1.05);
        }

        /* 🌟 حقوق النشر 🌟 */
        footer {
            margin-top: 40px;
            font-size: 0.9rem;
            color: #ccc;
            text-align: center;
            padding: 10px 0;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
            width: 100%;
            background: rgba(0, 0, 0, 0.6);
        }

        footer a {
            color: #ffd700;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* 🌟 دعم الهواتف 🌟 */
        @media (max-width: 768px) {
            .profile-image {
                width: 100px;
                height: 100px;
            }
            h1 {
                font-size: 1.5rem;
            }
            p {
                font-size: 1rem;
            }
            .links a {
                font-size: 0.9rem;
                padding: 8px 15px;
            }
        }

        /* 🌟 التأثيرات الحركية 🌟 */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <!-- 🌟 صورة شخصية 🌟 -->
    <img src="https://i.imgur.com/J0DlDOX.jpeg" alt="صورة محمد النيف" class="profile-image">

    <!-- 🌟 العنوان والنصوص 🌟 -->
    <h1>محمد النيف</h1>
    <p>لطلب رواية "ظلال الخيبة" تواصل معي</p>
    <p class="promo-text">✨ استمتع بروايتي الجديدة وكن جزءًا من القصة! 📖✨</p>

    <!-- 🌟 روابط التواصل الاجتماعي 🌟 -->
    <div class="links">
        <a href="https://wa.me/966554796524" target="_blank" rel="noopener noreferrer">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
            تواصل عبر واتساب
        </a>
        <a href="https://www.instagram.com/lnyf6597" target="_blank" rel="noopener noreferrer">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
            Instagram
        </a>
        <a href="https://www.snapchat.com/add/lnyf6597" target="_blank" rel="noopener noreferrer">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c4/Snapchat_logo.png" alt="Snapchat">
            Snapchat
        </a>
        <a href="https://www.tiktok.com/@lnyf6597" target="_blank" rel="noopener noreferrer">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/69/Tiktok_logo.png" alt="TikTok">
            TikTok
        </a>
        <a href="https://www.youtube.com/@lnyf6597" target="_blank" rel="noopener noreferrer">
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube">
            YouTube
        </a>
    </div>

    <!-- 🌟 زر شراء الرواية 🌟 -->
    <a href="https://wa.me/966554796524" target="_blank" class="buy-btn">📚 اطلب رواية "ظلال الخيبة" الآن</a>

    <!-- 🌟 حقوق النشر 🌟 -->
    <footer>
        <p>© 2024. للتواصل: 966594307565</p>
    </footer>
</body>
</html>
