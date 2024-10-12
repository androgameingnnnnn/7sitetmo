<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>معلومات VPS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            padding: 20px;
            text-align: center;
        }
        .card {
            background-color: #fff;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            display: inline-block;
            width: 100%;
            max-width: 600px;
        }
        h3 {
            margin-bottom: 10px;
        }
        .no-vps {
            color: red;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="card-header">
            <h3>معلومات VPS 🌐</h3>
        </div>
        <div class="card-body" id="vps-info">
            <!-- سيتم إدراج معلومات VPS هنا -->
            <p>جارٍ تحميل المعلومات...</p>
        </div>
    </div>

    <script>
        fetch('http://play.nutro.cloud:25606/vps_info.php') // استبدل "your-backend-url" برابط خادمك
            .then(response => response.json())
            .then(data => {
                const vpsInfoDiv = document.getElementById('vps-info');
                if (data.error) {
                    vpsInfoDiv.innerHTML = `<h1 class="no-vps">${data.error}</h1>`;
                } else {
                    vpsInfoDiv.innerHTML = `
                        <p>شكرًا لشرائك VPS معنا! إليك تفاصيل الخادم الخاص بك:</p>
                        <h4>1. تفاصيل الوصول إلى الخادم 🖥️</h4>
                        <ul>
                            <li><strong>عنوان IP للخادم:</strong> ${data.ip}</li>
                            <li><strong>اسم المستخدم:</strong> root 💻</li>
                            <li><strong>الوصول عبر SSH:</strong> استخدم <code>ssh root@(${data.ip})</code></li>
                        </ul>
                        <h4>2. معلومات خطة VPS 📋</h4>
                        <ul>
                            <li><strong>الخطة:</strong> ${data.plan}</li>
                            <li><strong>دورة الفوترة:</strong> (اشترك)</li>
                            <li><strong>تاريخ الفوترة التالي:</strong> (منتهية)</li>
                        </ul>
                        <h4>3. إدارة الخادم ⚙️</h4>
                        <ul>
                            <li>يمكنك إدارة خادمك من خلال لوحة التحكم.</li>
                            <li>للمساعدة، يرجى التواصل مع الدعم الفني.</li>
                        </ul>
                    `;
                }
            })
            .catch(error => {
                document.getElementById('vps-info').innerHTML = `<h1 class="no-vps">خطأ في الاتصال بالـ Backend</h1>`;
                console.error('خطأ:', error);
            });
    </script>
</body>
</html>
