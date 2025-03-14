<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adobe Acrobat</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }

        header {
            background-color: #ff0000;
            color: white;
            padding: 50px 0;
            text-align: center;
        }

        header h1 {
            font-size: 3em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        .cta-button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ffffff;
            color: #ff0000;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }

        .cta-button:hover {
            background-color: #ffcccc;
        }

        .features {
            padding: 50px 0;
            background-color: #f4f4f4;
        }

        .features h2 {
            text-align: center;
            margin-bottom: 40px;
        }

        .feature {
            text-align: center;
            margin-bottom: 20px;
        }

        .feature h3 {
            color: #ff0000;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Adobe Acrobat</h1>
            <p>اكتشف القوة الكاملة لتحويل الملفات إلى PDF بسهولة</p>
            <a href="#" class="cta-button">تحميل الآن</a>
        </div>
    </header>

    <section class="features">
        <div class="container">
            <h2>الميزات الرئيسية</h2>
            <div class="feature">
                <h3>تحويل الملفات إلى PDF</h3>
                <p>حول مستنداتك إلى PDF بنقرة واحدة!</p>
            </div>
            <div class="feature">
                <h3>تحرير ملفات PDF</h3>
                <p>قم بتعديل النصوص والصور في ملفات PDF بسهولة.</p>
            </div>
            <div class="feature">
                <h3>توقيع المستندات إلكترونيًا</h3>
                <p>وقع المستندات بسرعة وأمان.</p>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 Adobe Acrobat. جميع الحقوق محفوظة.</p>
        </div>
    </footer>

    <script>
        document.querySelector('.cta-button').addEventListener('click', function() {
            alert('تحميل Adobe Acrobat سيبدأ قريباً!');
        });
    </script>
</body>
</html>
