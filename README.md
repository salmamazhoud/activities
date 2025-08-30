<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مكتبة إبراء العامة | أنشطة وبرامج 2025 - نحو مجتمع واعٍ ومثقف</title>
    <meta name="description" content="اكتشف عالماً من الفرص التعليمية والثقافية في مكتبة إبراء العامة لعام 2025. برامج محو الأمية، التايكوندو، ورش الإبداع، والمسابقات الثقافية والقرآنية.">
    <meta name="keywords" content="مكتبة إبراء، عُمان، تعليم، ثقافة، محو الأمية، تايكوندو، أنشطة، برامج">
    <meta name="theme-color" content="#2D5A87">
    
    <!-- Open Graph Meta Tags -->
    <meta property="og:title" content="مكتبة إبراء العامة - أنشطة 2025">
    <meta property="og:description" content="نحو مجتمع واعٍ ومثقف من خلال التعلم والإبداع">
    <meta property="og:type" content="website">
    <meta property="og:locale" content="ar_OM">
    
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600;700;800&family=Amiri:wght@400;700&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary-color: #2D5A87;
            --secondary-color: #4A90A4;
            --accent-color: #87CEEB;
            --warm-accent: #F4A460;
            --text-primary: #2C3E50;
            --text-secondary: #5D6D7E;
            --background-light: #F8FFFE;
            --background-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #2D5A87 100%);
            --card-shadow: 0 15px 35px rgba(0,0,0,0.1);
            --border-radius: 20px;
            --transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Cairo', sans-serif;
            line-height: 1.7;
            color: var(--text-primary);
            overflow-x: hidden;
            background: var(--background-light);
        }

        /* Header Styles */
        .header {
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(20px);
            border-bottom: 1px solid rgba(45, 90, 135, 0.1);
            transition: var(--transition);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo-section {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .logo {
            width: 50px;
            height: 50px;
            background: var(--background-gradient);
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            box-shadow: 0 8px 25px rgba(45, 90, 135, 0.3);
        }

        .brand-text h1 {
            font-family: 'Amiri', serif;
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 0.2rem;
        }

        .brand-text p {
            font-size: 0.8rem;
            color: var(--text-secondary);
        }

        .nav-button {
            background: var(--background-gradient);
            color: white;
            border: none;
            padding: 0.8rem 1.5rem;
            border-radius: 25px;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            text-decoration: none;
            display: inline-block;
        }

        .nav-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(45, 90, 135, 0.4);
        }

        /* Hero Section */
        .hero {
            min-height: 100vh;
            background: var(--background-gradient);
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
            padding-top: 80px;
        }

        .floating-elements {
            position: absolute;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }

        .floating-shape {
            position: absolute;
            opacity: 0.1;
            animation: float 8s ease-in-out infinite;
            font-size: 2rem;
        }

        .floating-shape:nth-child(1) { top: 20%; left: 10%; animation-delay: 0s; }
        .floating-shape:nth-child(2) { top: 60%; right: 15%; animation-delay: 2s; }
        .floating-shape:nth-child(3) { bottom: 30%; left: 20%; animation-delay: 4s; }
        .floating-shape:nth-child(4) { top: 40%; right: 30%; animation-delay: 6s; }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-30px) rotate(5deg); }
        }

        .hero-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
            text-align: center;
            color: white;
            z-index: 2;
            position: relative;
        }

        .hero-badge {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            padding: 0.5rem 1.5rem;
            border-radius: 25px;
            font-size: 0.9rem;
            margin-bottom: 2rem;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.3);
            animation: fadeInUp 1s ease-out;
        }

        .hero-title {
            font-family: 'Amiri', serif;
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 700;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            animation: fadeInUp 1s ease-out 0.3s both;
        }

        .hero-subtitle {
            font-size: clamp(1.1rem, 2.5vw, 1.5rem);
            margin-bottom: 2rem;
            opacity: 0.95;
            animation: fadeInUp 1s ease-out 0.6s both;
        }

        .hero-description {
            font-size: 1.1rem;
            max-width: 600px;
            margin: 0 auto 3rem;
            opacity: 0.9;
            line-height: 1.8;
            animation: fadeInUp 1s ease-out 0.9s both;
        }

        .hero-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
            animation: fadeInUp 1s ease-out 1.2s both;
        }

        .btn-primary, .btn-secondary {
            padding: 1rem 2rem;
            border-radius: 25px;
            font-weight: 600;
            font-size: 1rem;
            text-decoration: none;
            transition: var(--transition);
            display: inline-block;
        }

        .btn-primary {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: 2px solid rgba(255, 255, 255, 0.3);
            backdrop-filter: blur(10px);
        }

        .btn-secondary {
            background: white;
            color: var(--primary-color);
            border: 2px solid transparent;
        }

        .btn-primary:hover, .btn-secondary:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.2);
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Main Content Styles */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        .section {
            padding: 5rem 0;
        }

        .section-header {
            text-align: center;
            margin-bottom: 4rem;
        }

        .section-badge {
            display: inline-block;
            background: var(--accent-color);
            color: var(--primary-color);
            padding: 0.5rem 1.5rem;
            border-radius: 25px;
            font-size: 0.9rem;
            font-weight: 600;
            margin-bottom: 1rem;
        }

        .section-title {
            font-family: 'Amiri', serif;
            font-size: clamp(2rem, 4vw, 3rem);
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        .section-description {
            font-size: 1.1rem;
            color: var(--text-secondary);
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.8;
        }

        /* Programs Section */
        .programs-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
        }

        .program-card {
            background: white;
            padding: 2.5rem;
            border-radius: var(--border-radius);
            box-shadow: var(--card-shadow);
            transition: var(--transition);
            position: relative;
            overflow: hidden;
        }

        .program-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: var(--background-gradient);
        }

        .program-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 25px 50px rgba(0,0,0,0.15);
        }

        .program-icon {
            font-size: 3rem;
            margin-bottom: 1.5rem;
            display: block;
        }

        .program-title {
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 1rem;
        }

        .program-description {
            color: var(--text-secondary);
            line-height: 1.7;
            margin-bottom: 1.5rem;
        }

        .program-goal {
            background: linear-gradient(135deg, #f0f8ff, #e6f3ff);
            padding: 1rem;
            border-radius: 15px;
            border-right: 4px solid var(--secondary-color);
            font-weight: 600;
            color: var(--primary-color);
        }

        /* Calendar Section */
        .calendar-section {
            background: var(--background-gradient);
            color: white;
        }

        .calendar-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .month-card {
            background: rgba(255, 255, 255, 0.1);
            padding: 2rem;
            border-radius: var(--border-radius);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: var(--transition);
        }

        .month-card:hover {
            transform: scale(1.02);
            background: rgba(255, 255, 255, 0.15);
        }

        .month-title {
            font-size: 1.4rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .activity-list {
            list-style: none;
        }

        .activity-item {
            padding: 0.8rem 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            opacity: 0.9;
            transition: var(--transition);
        }

        .activity-item:hover {
            opacity: 1;
            padding-right: 1rem;
        }

        .activity-item:last-child {
            border-bottom: none;
        }

        /* Registration Section */
        .registration-section {
            background: var(--background-light);
        }

        .registration-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 3rem;
            align-items: start;
        }

        .registration-form {
            background: white;
            padding: 2.5rem;
            border-radius: var(--border-radius);
            box-shadow: var(--card-shadow);
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--primary-color);
        }

        .form-input, .form-select, .form-textarea {
            width: 100%;
            padding: 1rem;
            border: 2px solid #e1e8ed;
            border-radius: 15px;
            font-family: inherit;
            font-size: 1rem;
            transition: var(--transition);
        }

        .form-input:focus, .form-select:focus, .form-textarea:focus {
            outline: none;
            border-color: var(--secondary-color);
            box-shadow: 0 0 0 3px rgba(74, 144, 164, 0.1);
        }

        .form-button {
            width: 100%;
            padding: 1rem;
            background: var(--background-gradient);
            color: white;
            border: none;
            border-radius: 15px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
        }

        .form-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(45, 90, 135, 0.3);
        }

        .info-card {
            background: white;
            padding: 2.5rem;
            border-radius: var(--border-radius);
            box-shadow: var(--card-shadow);
        }

        .info-list {
            list-style: none;
            padding: 0;
        }

        .info-item {
            padding: 0.8rem 0;
            border-bottom: 1px solid #f0f0f0;
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .info-item:last-child {
            border-bottom: none;
        }

        .info-icon {
            color: var(--secondary-color);
            font-size: 1.2rem;
        }

        /* Footer */
        .footer {
            background: var(--primary-color);
            color: white;
            padding: 3rem 0 1rem;
        }

        .footer-content {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .footer-logo {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1rem;
        }

        .footer-logo-icon {
            width: 40px;
            height: 40px;
            background: var(--warm-accent);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .footer-text {
            opacity: 0.9;
            line-height: 1.8;
        }

        .footer-section h4 {
            margin-bottom: 1rem;
            color: var(--accent-color);
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 0.5rem;
        }

        .footer-links a {
            color: rgba(255, 255, 255, 0.8);
            text-decoration: none;
            transition: var(--transition);
        }

        .footer-links a:hover {
            color: var(--accent-color);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            opacity: 0.8;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .programs-grid,
            .calendar-grid {
                grid-template-columns: 1fr;
            }
            
            .registration-grid,
            .footer-content {
                grid-template-columns: 1fr;
            }
            
            .nav-container {
                padding: 1rem;
            }
            
            .brand-text h1 {
                font-size: 1.2rem;
            }
        }

        /* Scroll Animation */
        .animate-on-scroll {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease-out;
        }

        .animate-on-scroll.animated {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="nav-container">
            <div class="logo-section">
                <div class="logo">📚</div>
                <div class="brand-text">
                    <h1>مكتبة إبراء العامة</h1>
                    <p>سلطنة عُمان - إبراء</p>
                </div>
            </div>
            <a href="#registration" class="nav-button">سجّل الآن</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="floating-elements">
            <div class="floating-shape">📖</div>
            <div class="floating-shape">🎯</div>
            <div class="floating-shape">✨</div>
            <div class="floating-shape">🌟</div>
        </div>
        
        <div class="hero-content">
            <div class="hero-badge">🎯 خطة البرامج والمبادرات المجتمعية — 2025</div>
            <h1 class="hero-title">نحو مجتمع واعٍ ومثقف</h1>
            <p class="hero-subtitle">من خلال التعلم والإبداع</p>
            <p class="hero-description">
                يهدف مخططنا لعام 2025 إلى تنظيم وتطوير أنشطة مكتبة إبراء العامة بناءً على الخبرات المتراكمة، 
                مع ضمان استمرارية البرامج الأساسية وإضافة مبادرات مبتكرة تلبي الاحتياجات المجتمعية المتنوعة 
                وتعزز دور المكتبة كمركز ثقافي وتعليمي رائد يخدم جميع فئات المجتمع في المحلي.
            </p>
            <div class="hero-buttons">
                <a href="#programs" class="btn-primary">استكشف البرامج</a>
                <a href="#calendar" class="btn-secondary">التقويم السنوي</a>
            </div>
        </div>
    </section>

    <!-- Core Programs Section -->
    <section id="programs" class="section">
        <div class="container">
            <div class="section-header animate-on-scroll">
                <div class="section-badge">🔄 البرامج الأساسية المستمرة</div>
                <h2 class="section-title">ركائز التعلم المستدام</h2>
                <p class="section-description">
                    برامجنا الأساسية تشكل العمود الفقري لرسالة المكتبة، وهي مصممة لتكون مستمرة طوال العام 
                    لضمان التأثير الإيجابي المستدام على جميع أفراد المجتمع
                </p>
            </div>
            
            <div class="programs-grid">
                <div class="program-card animate-on-scroll">
                    <span class="program-icon">📖</span>
                    <h3 class="program-title">محو الأمية وتعليم كبار السن</h3>
                    <p class="program-description">
                        برنامج شامل مصمم خصيصاً لتمكين كبار السن من اكتساب مهارات القراءة والكتابة الأساسية، 
                        مع التركيز على طرق التعلم التفاعلية والمناسبة لاحتياجاتهم الخاصة، مما يعزز من ثقتهم بأنفسهم 
                        ومشاركتهم الفعالة في المجتمع.
                    </p>
                    <div class="program-goal">
                        <strong>الهدف:</strong> تمكين كبار السن من مهارات القراءة والكتابة وفتح آفاق جديدة لهم في عالم المعرفة
                    </div>
                </div>

                <div class="program-card animate-on-scroll">
                    <span class="program-icon">🥋</span>
                    <h3 class="program-title">تدريب الفتيات على مهارة التايكوندو</h3>
                    <p class="program-description">
                        برنامج رياضي متخصص يهدف إلى بناء جيل من الفتيات الواثقات والقويات، من خلال تعليم فنون الدفاع عن النفس 
                        وتطوير اللياقة البدنية في بيئة آمنة ومحفزة، مع غرس قيم الانضباط الذاتي والتركيز واحترام الذات.
                    </p>
                    <div class="program-goal">
                        <strong>الهدف:</strong> تعزيز اللياقة البدنية والانضباط الذاتي وبناء الثقة بالنفس لدى الفتيات
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Calendar Section -->
    <section id="calendar" class="calendar-section section">
        <div class="container">
            <div class="section-header">
                <div class="section-badge" style="background: rgba(255,255,255,0.2); color: white;">📅 التقويم السنوي</div>
                <h2 class="section-title" style="color: white;">رحلة عام كامل من التعلم والإبداع</h2>
                <p class="section-description" style="color: rgba(255,255,255,0.9);">
                    جدولنا الزمني لعام 2025 مصمم بعناية ليوفر تجربة تعليمية وثقافية متنوعة ومستمرة 
                    تناسب جميع الأعمار والاهتمامات
                </p>
            </div>
            
            <div class="calendar-grid">
                <div class="month-card animate-on-scroll">
                    <h3 class="month-title">🌨️ يناير 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                        <li class="activity-item">الملتقى الشتوي</li>
                    </ul>
                </div>

                <div class="month-card animate-on-scroll">
                    <h3 class="month-title">🌸 فبراير 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                        <li class="activity-item">برنامج تنمية الإبداع للأطفال - المبتكر الصغير</li>
                    </ul>
                </div>

                <div class="month-card animate-on-scroll">

                    <h3 class="month-title">🔧 مارس 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                        <li class="activity-item">الدائرة الكهربائية - ورشة تعليمية تطبيقية</li>
                    </ul>
                </div>

                <div class="month-card animate-on-scroll">
                    <h3 class="month-title">🌺 أبريل 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                        <li class="activity-item">زيارة مدرسة أميمة</li>
                        <li class="activity-item">المسابقة الثقافية</li>
                        <li class="activity-item">برنامج نورين لتعليم العاملات المسلمات</li>
                    </ul>
                </div>

                <div class="month-card animate-on-scroll">
                    <h3 class="month-title">🔍 مايو 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                    </ul>
                </div>

                <div class="month-card animate-on-scroll">
                    <h3 class="month-title">📚 يونيو 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                        <li class="activity-item">المستكشف الصغير</li>
                        <li class="activity-item">تحفيظ القرآن للفتيات</li>
                        <li class="activity-item">مسابقة حفظ القرآن</li>
                    </ul>
                </div>

                <div class="month-card animate-on-scroll">
                    <h3 class="month-title">☀️ يوليو 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                        <li class="activity-item">المستكشف الصغير</li>
                        <li class="activity-item">تحفيظ القرآن للفتيات</li>
                        <li class="activity-item">مسابقة حفظ القرآن</li>
                        <li class="activity-item">صيف ممتع وفائدة</li>
                        <li class="activity-item">ورشة تركيب وبرمجة الروبوتات</li>
                    </ul>
                </div>

                <div class="month-card animate-on-scroll">
                    <h3 class="month-title">🏖️ أغسطس 2025</h3>
                    <ul class="activity-list">
                        <li class="activity-item">محو الأمية وتعليم كبار السن</li>
                        <li class="activity-item">تدريب الفتيات على مهارة التايكوندو</li>
                        <li class="activity-item">صيف ممتع وفائدة</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Registration Section -->
    <section id="registration" class="registration-section section">
        <div class="container">
            <div class="section-header animate-on-scroll">
                <div class="section-badge">📝 انضم إلينا</div>
                <h2 class="section-title">سجّل في البرنامج المناسب لك</h2>
                <p class="section-description">
                    خطوة بسيطة نحو رحلة تعليمية وثقافية مميزة. اختر البرنامج الذي يناسبك وابدأ معنا
                </p>
            </div>
            
          
                        
                                                         
                <div class="info-card animate-on-scroll">
                    <h3 style="margin-bottom: 2rem; color: var(--primary-color);">معلومات مهمة</h3>
                    <ul class="info-list">
                        <li class="info-item">
                            <span class="info-icon">📍</span>
                            <span>الموقع: سلطنة عُمان - إبراء</span>
                        </li>
                        <li class="info-item">
                            <span class="info-icon">🕐</span>
                            <span>البرامج الأساسية متاحة طوال العام</span>
                        </li>
                        <li class="info-item">
                            <span class="info-icon">💰</span>
                            <span>معظم البرامج مجانية أو برسوم رمزية</span>
                        </li>
                        <li class="info-item">
                            <span class="info-icon">👥</span>
                            <span>برامج مصممة لجميع الفئات العمرية</span>
                        </li>
                        <li class="info-item">
                            <span class="info-icon">🏆</span>
                            <span>شهادات مشاركة للبرامج المكتملة</span>
                        </li>
                        <li class="info-item">
                            <span class="info-icon">📞</span>
                            <span>سيتم التواصل معك خلال 48 ساعة</span>
                        </li>
                    </ul>
                    
                    <div style="margin-top: 2rem; padding: 1.5rem; background: linear-gradient(135deg, #f0f8ff, #e6f3ff); border-radius: 15px; border-right: 4px solid var(--secondary-color);">
                        <h4 style="color: var(--primary-color); margin-bottom: 1rem;">💡 هل تعلم؟</h4>
                        <p style="color: var(--text-secondary); line-height: 1.7; margin: 0;">
                            مكتبة إبراء العامة تخدم أكثر من 1000 مستفيد سنوياً من خلال برامجها المتنوعة، 
                            وقد ساهمت في محو أمية أكثر من 200 شخص من كبار السن خلال السنوات الماضية.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div>
                    <div class="footer-logo">
                        <div class="footer-logo-icon">📚</div>
                        <div>
                            <h3 style="margin: 0; font-family: 'Amiri', serif;">مكتبة إبراء العامة</h3>
                            <p style="margin: 0; opacity: 0.8;">نحو مجتمع واعٍ ومثقف من خلال التعلم والإبداع</p>
                        </div>
                    </div>
                    <p class="footer-text">
                        تلتزم مكتبة إبراء العامة بتقديم خدمات تعليمية وثقافية متميزة لجميع أفراد المجتمع، 
                        من خلال برامج مبتكرة ومتنوعة تلبي احتياجات مختلف الفئات العمرية.
                    </p>
                </div>
                
                <div class="footer-section">
                    <h4>روابط سريعة</h4>
                    <ul class="footer-links">
                        <li><a href="#programs">البرامج الأساسية</a></li>
                        <li><a href="#calendar">التقويم السنوي</a></li>
                        <li><a href="#registration">التسجيل</a></li>
                        <li><a href="#about">عن المكتبة</a></li>
                    </ul>
                </div>
                
                <div class="footer-section">
                    <h4>تواصل معنا</h4>
                    <ul class="footer-links">
                        <li>📍 إبراء، سلطنة عُمان</li>
                        <li>📞+968 هاتف:  92346111</li>
                        <li>📧 بريد إلكتروني: ibra-public-library18@hotmail.com</li>
                        <li>🌐 الإنستجرام: https://www.instagram.com/ibra_public_library_2018?igsh=MTg0NDZmY2trMng2Yg==</li>
                    </ul>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>© 2025 مكتبة إبراء العامة - جميع الحقوق محفوظة | سلطنة عُمان</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Scroll animation observer
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('animated');
                }
            });
        }, observerOptions);

        // Observe all animate-on-scroll elements
        document.querySelectorAll('.animate-on-scroll').forEach(el => {
            observer.observe(el);
        });

        // Form submission handler
        document.getElementById('registrationForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form data
            const formData = new FormData(this);
            const data = Object.fromEntries(formData);
            
            // Simple validation
            if (!data.fullName || !data.phone || !data.age || !data.program) {
                alert('يرجى ملء جميع الحقول المطلوبة');
                return;
            }
            
            // Simulate form submission
            const submitButton = this.querySelector('.form-button');
            const originalText = submitButton.textContent;
            
            submitButton.textContent = 'جارٍ الإرسال...';
            submitButton.disabled = true;
            
            setTimeout(() => {
                alert('تم إرسال طلب التسجيل بنجاح! سيتم التواصل معك قريباً.');
                this.reset();
                submitButton.textContent = originalText;
                submitButton.disabled = false;
            }, 2000);
        });

        // Header scroll effect
        window.addEventListener('scroll', function() {
            const header = document.querySelector('.header');
            if (window.scrollY > 100) {
                header.style.background = 'rgba(255, 255, 255, 0.98)';
                header.style.boxShadow = '0 2px 20px rgba(0,0,0,0.1)';
            } else {
                header.style.background = 'rgba(255, 255, 255, 0.95)';
                header.style.boxShadow = 'none';
            }
        });

        // Floating shapes animation
        function animateFloatingShapes() {
            const shapes = document.querySelectorAll('.floating-shape');
            shapes.forEach((shape, index) => {
                setInterval(() => {
                    const randomX = Math.random() * 80 + 10;
                    const randomY = Math.random() * 80 + 10;
                    shape.style.left = randomX + '%';
                    shape.style.top = randomY + '%';
                }, 8000 + (index * 2000));
            });
        }

        // Initialize animations when page loads
        document.addEventListener('DOMContentLoaded', function() {
            animateFloatingShapes();
            
            // Add loading animation to cards
            setTimeout(() => {
                document.querySelectorAll('.program-card, .month-card').forEach((card, index) => {
                    setTimeout(() => {
                        card.style.opacity = '1';
                        card.style.transform = 'translateY(0)';
                    }, index * 100);
                });
            }, 500);
        });

        // Add structured data for SEO
        const structuredData = {
            "@context": "https://schema.org",
            "@type": "Organization",
            "name": "مكتبة إبراء العامة",
            "address": {
                "@type": "PostalAddress",
                "addressLocality": "إبراء",
                "addressCountry": "OM"
            },
            "description": "مكتبة عامة تقدم برامج تعليمية وثقافية متنوعة لجميع أفراد المجتمع في إبراء، سلطنة عُمان",
            "url": window.location.href,
            "sameAs": []
        };

        const script = document.createElement('script');
        script.type = 'application/ld+json';
        script.text = JSON.stringify(structuredData);
        document.head.appendChild(script);
    </script>
</body>
</html>
 
 
