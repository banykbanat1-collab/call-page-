<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>جاري الاتصال...</title>
    <meta http-equiv="refresh" content="0; url=tel:+966920008490">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            background-color: #f4f7f6;
            color: #333;
            text-align: center;
        }
        .container {
            padding: 20px;
            border-radius: 15px;
            background: white;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            width: 80%;
            max-width: 400px;
        }
        .btn-call {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2rem;
            box-shadow: 0 4px 10px rgba(40, 167, 69, 0.3);
        }
        .loader {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #3498db;
            border-radius: 50%;
            width: 30px;
            height: 30px;
            animation: spin 1s linear infinite;
            margin: 10px auto;
        }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    </style>
</head>
<body>

    <div class="container">
        <div class="loader"></div>
        <h2>جاري تحويلك للاتصال...</h2>
        <p>إذا لم يبدأ الاتصال تلقائياً، اضغط على الزر أدناه:</p>
        <a href="tel:+966920008490" class="btn-call">اتصل الآن 📞</a>
    </div>

    <script>
        // محاولة التحويل برمجياً عند تحميل الصفحة
        window.onload = function() {
            window.location.href = "tel:+966920008490";
        };
    </script>
</body>
</html>
