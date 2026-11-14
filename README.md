<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة العروض والمهام اليومية | اربح المكافآت</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary-blue: #0284c7;
            --dark-blue: #0369a1;
            --sky-blue: #38bdf8;
            --light-bg: #f0f9ff;
            --card-bg: #ffffff;
            --text-color: #0f172a;
            --gray-text: #64748b;
            --accent-green: #10b981;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Cairo', sans-serif;
        }

        body {
            background-color: var(--light-bg);
            color: var(--text-color);
            padding: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            width: 100%;
            max-width: 800px;
        }

        header {
            background: linear-gradient(135deg, var(--primary-blue), var(--dark-blue));
            color: white;
            padding: 25px 20px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 25px rgba(2, 132, 199, 0.2);
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 1.7rem;
            font-weight: 900;
            margin-bottom: 8px;
        }

        header p {
            font-size: 0.95rem;
            opacity: 0.9;
        }

        /* شريط الخطوات السريعة */
        .steps-bar {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin-bottom: 20px;
        }

        .step-box {
            background: var(--card-bg);
            padding: 15px 10px;
            border-radius: 14px;
            text-align: center;
            border: 1px solid #bae6fd;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.03);
        }

        .step-box i {
            font-size: 1.5rem;
            color: var(--primary-blue);
            margin-bottom: 8px;
        }

        .step-box h3 {
            font-size: 0.9rem;
            font-weight: 800;
            margin-bottom: 4px;
        }

        .step-box p {
            font-size: 0.78rem;
            color: var(--gray-text);
        }

        /* حاوية إعلان Adsterra */
        .ad-box {
            background: #ffffff;
            border: 2px dashed #cbd5e1;
            border-radius: 12px;
            padding: 12px;
            text-align: center;
            margin-bottom: 20px;
            color: var(--gray-text);
            font-size: 0.85rem;
        }

        /* حاوية حائط عروض Ayet Studios */
        .offerwall-card {
            background: var(--card-bg);
            border-radius: 18px;
            padding: 20px;
            box-shadow: 0 8px 25px rgba(15, 23, 42, 0.06);
            border: 1px solid #e0f2fe;
            margin-bottom: 20px;
        }

        .offerwall-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
            padding-bottom: 12px;
            border-bottom: 2px solid var(--light-bg);
        }

        .offerwall-header h2 {
            font-size: 1.2rem;
            font-weight: 800;
            color: var(--primary-blue);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .live-badge {
            background: #dcfce7;
            color: var(--accent-green);
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 700;
        }

        /* إطار عرض العروض */
        .iframe-wrapper {
            width: 100%;
            min-height: 600px;
            background: #f8fafc;
            border-radius: 12px;
            overflow: hidden;
            border: 1px solid #cbd5e1;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .iframe-wrapper iframe {
            width: 100%;
            height: 650px;
            border: none;
        }

        footer {
            text-align: center;
            font-size: 0.8rem;
            color: var(--gray-text);
            padding: 15px 0;
        }

        @media (max-width: 600px) {
            .steps-bar {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- ترويسة الصفحة -->
        <header>
            <h1><i class="fa-solid fa-gift"></i> مركز العروض والاستطلاعات اليومية</h1>
            <p>أكمل المهام البسيطة، جرب الألعاب الجديدة، أو شارك في الاستطلاعات المتاحة لبلدك</p>
        </header>

        <!-- خطوات العمل للزائر -->
        <div class="steps-bar">
            <div class="step-box">
                <i class="fa-solid fa-list-check"></i>
                <h3>1. اختر عرضاً</h3>
                <p>تصفح قائمة التطبيقات والألعاب المتاحة في الأسفل</p>
            </div>
            <div class="step-box">
                <i class="fa-solid fa-gamepad"></i>
                <h3>2. نفذ المطلوب</h3>
                <p>اتبع تعليمات العرض البسيطة بدقة</p>
            </div>
            <div class="step-box">
                <i class="fa-solid fa-circle-check"></i>
                <h3>3. إتمام المهمة</h3>
                <p>يتم احتساب إكمال العرض تلقائياً بعد الانتهاء</p>
            </div>
        </div>

        <!-- 💰 مكان وضع إعلان Adsterra العلوي (Banner) -->
        <div class="ad-box">
            <span>[ ضع هنا شفرة إعلان Adsterra - Banner ]</span>
        </div>

        <!-- قسم حائط عروض Ayet Studios -->
        <div class="offerwall-card">
            <div class="offerwall-header">
                <h2><i class="fa-solid fa-fire"></i> قائمة العروض المتاحة الآن</h2>
                <span class="live-badge">● متاح لبلدك</span>
            </div>

            <div class="iframe-wrapper">
                <!-- 🔴 استبدل الرابط أدناه برابط الـ Offerwall الخاص بك من لوحة تحكم Ayet Studios -->
                <iframe src="https://www.ayetstudios.com/offers/web_offerwall/YOUR_PLACEMENT_ID?external_identifier=user1" title="Ayet Studios Offerwall"></iframe>
            </div>
        </div>

        <footer>
            جميع حقوق النشر محفوظة © 2026 - منصة العروض والمكافآت
        </footer>
    </div>

    <!-- 💰 ضع كود إعلان Adsterra Social Bar هنا قبل إغلاق الصفحة -->

</body>
</html>
