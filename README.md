
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vishal Rajput - Matrimonial Profile</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;800&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --gold: #D4AF37;
            --deep-gold: #B8860B;
            --rose-gold: #E8B4CB;
            --cream: #FFF8DC;
            --ivory: #FFFFF0;
            --burgundy: #800020;
            --deep-burgundy: #4A0E1B;
            --soft-pink: #F8E8E8;
            --wedding-white: #FEFEFE;
            --shadow-gold: rgba(212, 175, 55, 0.3);
            --shadow-soft: rgba(0, 0, 0, 0.1);
            --shadow-elegant: rgba(128, 0, 32, 0.2);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, var(--cream) 0%, var(--ivory) 50%, var(--soft-pink) 100%);
            min-height: 100vh;
            position: relative;
            overflow-x: hidden;
        }
        h1 a { display: none !important;  }

        /* Wedding Pattern Background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                radial-gradient(circle at 25% 25%, rgba(212, 175, 55, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 75% 75%, rgba(232, 180, 203, 0.1) 0%, transparent 50%);
            background-size: 100px 100px;
            z-index: -2;
            animation: patternFloat 20s ease-in-out infinite;
        }

        @keyframes patternFloat {
            0%, 100% { transform: translate(0, 0) rotate(0deg); }
            33% { transform: translate(10px, -10px) rotate(1deg); }
            66% { transform: translate(-10px, 10px) rotate(-1deg); }
        }

        /* Floating Wedding Elements */
        .floating-elements {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .wedding-element {
            position: absolute;
            color: var(--gold);
            opacity: 0.15;
            animation: floatWedding 12s ease-in-out infinite;
        }

        .wedding-element:nth-child(1) { top: 10%; left: 10%; font-size: 2rem; animation-delay: 0s; }
        .wedding-element:nth-child(2) { top: 20%; right: 15%; font-size: 1.5rem; animation-delay: 2s; }
        .wedding-element:nth-child(3) { top: 60%; left: 5%; font-size: 2.5rem; animation-delay: 4s; }
        .wedding-element:nth-child(4) { bottom: 20%; right: 10%; font-size: 1.8rem; animation-delay: 6s; }
        .wedding-element:nth-child(5) { bottom: 40%; left: 20%; font-size: 2rem; animation-delay: 8s; }

        @keyframes floatWedding {
            0%, 100% { transform: translateY(0px) rotate(0deg); opacity: 0.1; }
            50% { transform: translateY(-20px) rotate(5deg); opacity: 0.2; }
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 2rem;
        }

        /* Ornate Header */
        .header {
            text-align: center;
            margin-bottom: 3rem;
            position: relative;
            padding: 2rem 0;
        }

        .ornate-divider {
            font-size: 3rem;
            color: var(--gold);
            margin: 1rem 0;
            text-shadow: 2px 2px 4px var(--shadow-gold);
        }

        .site-title {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--burgundy);
            margin-bottom: 0.5rem;
            text-shadow: 1px 1px 3px var(--shadow-soft);
        }

        .site-subtitle {
            font-size: 1.2rem;
            color: var(--deep-gold);
            font-weight: 300;
            font-style: italic;
        }

        /* Hero Wedding Card */
        .hero-card {
            background: var(--wedding-white);
            border-radius: 2rem;
            padding: 4rem 2rem;
            margin-bottom: 3rem;
            box-shadow: 0 20px 60px var(--shadow-soft);
            border: 3px solid transparent;
            background-clip: padding-box;
            position: relative;
            overflow: hidden;
        }

        .hero-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            padding: 3px;
            background: linear-gradient(45deg, var(--gold), var(--rose-gold), var(--gold));
            border-radius: inherit;
            margin: -3px;
            z-index: -1;
        }

        .hero-card::after {
            content: '♥';
            position: absolute;
            top: 2rem;
            right: 2rem;
            font-size: 2rem;
            color: var(--rose-gold);
            animation: heartPulse 2s ease-in-out infinite;
        }

        @keyframes heartPulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }

        .profile-section {
            text-align: center;
            position: relative;
        }

        .profile-frame {
            position: relative;
            display: inline-block;
            margin-bottom: 2rem;
        }

        .profile-image {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--gold) 0%, var(--rose-gold) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 5rem;
            color: white;
            border: 8px solid var(--wedding-white);
            box-shadow: 0 0 0 4px var(--gold), 0 20px 40px var(--shadow-elegant);
            position: relative;
            z-index: 2;
        }

        .profile-ornament {
            position: absolute;
            top: -15px;
            right: -15px;
            width: 50px;
            height: 50px;
            background: var(--burgundy);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--gold);
            font-size: 1.5rem;
            z-index: 3;
            animation: ornamentFloat 3s ease-in-out infinite;
        }

        @keyframes ornamentFloat {
            0%, 100% { transform: rotate(0deg) translateY(0); }
            50% { transform: rotate(5deg) translateY(-5px); }
        }

        .groom-name {
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, var(--burgundy) 0%, var(--deep-gold) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px var(--shadow-soft);
        }

        .groom-title {
            font-size: 1.4rem;
            color: var(--burgundy);
            font-weight: 500;
            margin-bottom: 2rem;
        }

        .wedding-status {
            background: linear-gradient(135deg, var(--burgundy) 0%, var(--deep-burgundy) 100%);
            color: var(--gold);
            padding: 1rem 2.5rem;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 600;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            box-shadow: 0 10px 25px var(--shadow-elegant);
            border: 2px solid var(--gold);
        }

        /* Wedding Info Cards */
        .wedding-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 2.5rem;
            margin-bottom: 3rem;
        }

        .wedding-info-card {
            background: var(--wedding-white);
            border-radius: 1.5rem;
            padding: 2.5rem;
            box-shadow: 0 15px 35px var(--shadow-soft);
            border-top: 5px solid var(--gold);
            position: relative;
            transition: all 0.4s ease;
            overflow: hidden;
        }

        .wedding-info-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(212, 175, 55, 0.1), transparent);
            transition: left 0.8s ease;
        }

        .wedding-info-card:hover::before {
            left: 100%;
        }

        .wedding-info-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 50px var(--shadow-elegant);
        }

        .card-header-wedding {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 2rem;
            padding-bottom: 1rem;
            border-bottom: 2px solid var(--cream);
        }

        .wedding-icon {
            width: 70px;
            height: 70px;
            background: linear-gradient(135deg, var(--burgundy) 0%, var(--deep-burgundy) 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            color: var(--gold);
            box-shadow: 0 8px 20px var(--shadow-elegant);
            position: relative;
        }

        .wedding-icon::after {
            content: '';
            position: absolute;
            top: -3px;
            left: -3px;
            right: -3px;
            bottom: -3px;
            border: 2px solid var(--gold);
            border-radius: 50%;
            opacity: 0.5;
        }

        .card-title-wedding {
            font-family: 'Playfair Display', serif;
            font-size: 1.8rem;
            font-weight: 600;
            color: var(--burgundy);
            margin: 0;
        }

        .wedding-info-list {
            list-style: none;
        }

        .wedding-info-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.2rem 0;
            border-bottom: 1px solid rgba(212, 175, 55, 0.2);
            transition: all 0.3s ease;
            position: relative;
        }

        .wedding-info-item::before {
            content: '❋';
            position: absolute;
            left: -1.5rem;
            color: var(--gold);
            opacity: 0;
            transition: all 0.3s ease;
        }

        .wedding-info-item:hover {
            padding-left: 1.5rem;
            background: linear-gradient(90deg, var(--cream), transparent);
        }

        .wedding-info-item:hover::before {
            opacity: 1;
            left: 0;
        }

        .info-label-wedding {
            font-weight: 500;
            color: var(--burgundy);
            font-size: 1rem;
        }

        .info-value-wedding {
            font-weight: 600;
            color: var(--deep-gold);
            background: linear-gradient(135deg, var(--deep-gold) 0%, var(--gold) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        /* Romantic Quote Section */
        .quote-wedding {
            background: linear-gradient(135deg, var(--burgundy) 0%, var(--deep-burgundy) 100%);
            color: var(--gold);
            text-align: center;
            padding: 4rem 2rem;
            border-radius: 2rem;
            margin-bottom: 3rem;
            position: relative;
            overflow: hidden;
            box-shadow: 0 20px 40px var(--shadow-elegant);
        }

        .quote-wedding::before {
            content: '❝';
            position: absolute;
            top: -1rem;
            left: 50%;
            transform: translateX(-50%);
            font-size: 8rem;
            opacity: 0.2;
            font-family: serif;
        }

        .quote-wedding::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle fill="rgba(212,175,55,0.1)" cx="20" cy="20" r="2"/><circle fill="rgba(212,175,55,0.1)" cx="80" cy="40" r="1.5"/><circle fill="rgba(212,175,55,0.1)" cx="50" cy="70" r="1"/><circle fill="rgba(212,175,55,0.1)" cx="30" cy="90" r="2"/></svg>');
            background-size: 100px 100px;
        }

        .quote-text-wedding {
            font-family: 'Playfair Display', serif;
            font-size: 2.2rem;
            font-weight: 400;
            font-style: italic;
            line-height: 1.6;
            position: relative;
            z-index: 1;
            margin-bottom: 1rem;
        }

        .quote-author {
            font-size: 1rem;
            opacity: 0.8;
            font-weight: 300;
        }

        /* Contact Wedding Section */
        .contact-wedding {
            background: var(--wedding-white);
            border-radius: 2rem;
            padding: 3rem;
            box-shadow: 0 20px 50px var(--shadow-soft);
            border: 2px solid var(--cream);
            position: relative;
        }

        .contact-wedding::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, var(--gold), var(--rose-gold), var(--burgundy), var(--gold));
            border-radius: inherit;
            z-index: -1;
            animation: borderGlow 3s ease-in-out infinite;
        }

        @keyframes borderGlow {
            0%, 100% { opacity: 0.7; }
            50% { opacity: 1; }
        }

        .contact-title-wedding {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--burgundy);
            margin-bottom: 3rem;
            position: relative;
        }

        .contact-title-wedding::after {
            content: '♦ ♦ ♦';
            position: absolute;
            bottom: -1rem;
            left: 50%;
            transform: translateX(-50%);
            color: var(--gold);
            font-size: 1rem;
        }

        .contact-wedding-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .contact-wedding-card {
            background: linear-gradient(135deg, var(--cream) 0%, var(--ivory) 100%);
            border-radius: 1.5rem;
            padding: 2rem;
            display: flex;
            align-items: center;
            gap: 1.5rem;
            transition: all 0.4s ease;
            border: 2px solid transparent;
            box-shadow: 0 10px 25px var(--shadow-soft);
        }

        .contact-wedding-card:hover {
            transform: translateY(-5px) scale(1.02);
            border-color: var(--gold);
            box-shadow: 0 20px 40px var(--shadow-elegant);
            background: linear-gradient(135deg, var(--ivory) 0%, var(--wedding-white) 100%);
        }

        .contact-icon-wedding {
            width: 80px;
            height: 80px;
            background: linear-gradient(135deg, var(--burgundy) 0%, var(--deep-burgundy) 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            color: var(--gold);
            box-shadow: 0 10px 25px var(--shadow-elegant);
            border: 3px solid var(--wedding-white);
            position: relative;
        }

        .contact-icon-wedding::after {
            content: '';
            position: absolute;
            top: -5px;
            left: -5px;
            right: -5px;
            bottom: -5px;
            border: 1px solid var(--gold);
            border-radius: 50%;
            opacity: 0.6;
        }

        .contact-wedding-info h3 {
            font-family: 'Playfair Display', serif;
            color: var(--burgundy);
            font-weight: 600;
            margin-bottom: 0.5rem;
            font-size: 1.3rem;
        }

        .contact-wedding-info p {
            color: var(--deep-gold);
            font-weight: 500;
            font-size: 1rem;
        }

        /* Footer Blessing */
        .wedding-blessing {
            text-align: center;
            margin-top: 3rem;
            padding: 2rem;
            font-family: 'Playfair Display', serif;
            font-style: italic;
            color: var(--burgundy);
            font-size: 1.2rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                padding: 1rem;
            }
            
            .groom-name {
                font-size: 2.5rem;
            }
            
            .wedding-grid {
                grid-template-columns: 1fr;
                gap: 2rem;
            }
            
            .contact-wedding-grid {
                grid-template-columns: 1fr;
            }
            
            .quote-text-wedding {
                font-size: 1.8rem;
            }

            .profile-image {
                width: 180px;
                height: 180px;
                font-size: 4rem;
            }
        }
    </style>
</head>
<body>
    <div class="floating-elements">
        <div class="wedding-element">❋</div>
        <div class="wedding-element">♥</div>
        <div class="wedding-element">❦</div>
        <div class="wedding-element">❅</div>
        <div class="wedding-element">✾</div>
    </div>

    <div class="container">
        <!-- Ornate Header -->
        <header class="header">
            <div class="ornate-divider">❦ ❋ ❦</div>
            <h1 class="site-title">Matrimonial Profile</h1>
            <p class="site-subtitle">A journey towards finding the perfect life partner</p>
            <div class="ornate-divider">❦ ❋ ❦</div>
        </header>

        <!-- Hero Wedding Card -->
        <section class="hero-card">
            <div class="profile-section">
                <div class="profile-frame">
                    <div class="profile-image">
                        <i class="fas fa-user"></i>
                    </div>
                    <div class="profile-ornament">
                        <i class="fas fa-crown"></i>
                    </div>
                </div>
                <h1 class="groom-name">Vishal Rajput</h1>
                <p class="groom-title">Software Engineer & Devoted Son</p>
                <div class="wedding-status">
                    <i class="fas fa-heart"></i>
                    Seeking Life Partner
                </div>
            </div>
        </section>

        <!-- Wedding Information Grid -->
        <section class="wedding-grid">
            <div class="wedding-info-card">
                <div class="card-header-wedding">
                    <div class="wedding-icon">
                        <i class="fas fa-user-circle"></i>
                    </div>
                    <h2 class="card-title-wedding">Personal Details</h2>
                </div>
                <ul class="wedding-info-list">
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Date of Birth</span>
                        <span class="info-value-wedding">17th April, 2001</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Age</span>
                        <span class="info-value-wedding">24 years</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Height</span>
                        <span class="info-value-wedding">5 feet 8 inches</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Build</span>
                        <span class="info-value-wedding">Slim (54 KG)</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Blood Group</span>
                        <span class="info-value-wedding">A Positive</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Religion & Caste</span>
                        <span class="info-value-wedding">Hindu Rajput</span>
                    </li>
                </ul>
            </div>

            <div class="wedding-info-card">
                <div class="card-header-wedding">
                    <div class="wedding-icon">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <h2 class="card-title-wedding">Education & Career</h2>
                </div>
                <ul class="wedding-info-list">
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Qualification</span>
                        <span class="info-value-wedding">Bachelor of Arts in English Literature</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">University</span>
                        <span class="info-value-wedding">Devi Ahilya Vishwavidyalaya (DAVV) Indore</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Specialization</span>
                        <span class="info-value-wedding">Computer Programming</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Profession</span>
                        <span class="info-value-wedding">Software Engineer</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Company</span>
                        <span class="info-value-wedding"> ULTRA TEND 71-75 Shelton Street, London, England GB</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Annual Income</span>
                        <span class="info-value-wedding">₹4.2 Lakhs per annum</span>
                    </li>
                </ul>
            </div>

            <div class="wedding-info-card">
                <div class="card-header-wedding">
                    <div class="wedding-icon">
                        <i class="fas fa-home"></i>
                    </div>
                    <h2 class="card-title-wedding">Family Background</h2>
                </div>
                <ul class="wedding-info-list">
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Father's Name</span>
                        <span class="info-value-wedding">Shri Bheem Singh Chouhan</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Mother's Name</span>
                        <span class="info-value-wedding">Smt. Sudha Bhai Chouhan</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Siblings</span>
                        <span class="info-value-wedding">Two Sisters</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Family Type</span>
                        <span class="info-value-wedding">Single Family</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Family Status</span>
                        <span class="info-value-wedding">Well Settled</span>
                    </li>
                </ul>
            </div>

            <div class="wedding-info-card">
                <div class="card-header-wedding">
                    <div class="wedding-icon">
                        <i class="fas fa-heart"></i>
                    </div>
                    <h2 class="card-title-wedding">Lifestyle & Preferences</h2>
                </div>
                <ul class="wedding-info-list">
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Hobbies & Interests</span>
                        <span class="info-value-wedding">Chess, Singing</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Languages Known</span>
                        <span class="info-value-wedding">English, Hindi</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Food Habits</span>
                        <span class="info-value-wedding">Pure Vegetarian</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Smoking & Drinking</span>
                        <span class="info-value-wedding">Neither</span>
                    </li>
                    <li class="wedding-info-item">
                        <span class="info-label-wedding">Hometown</span>
                        <span class="info-value-wedding">Barwaha, Madhya Pradesh</span>
                    </li>
                </ul>
            </div>
        </section>

        <!-- Romantic Quote Section -->
        <section class="quote-wedding">
            <p class="quote-text-wedding">
                "Marriage is not just about finding the right person, but being the right person for someone special."
            </p>
            <p class="quote-author">— Seeking a partner who values culture, family, and companionship</p>
        </section>

        <!-- Contact Wedding Section -->
        <section class="contact-wedding">
            <h2 class="contact-title-wedding">Connect With Our Family</h2>
            <div class="contact-wedding-grid">
                <div class="contact-wedding-card">
                    <div class="contact-icon-wedding">
                        <i class="fas fa-phone"></i>
                    </div>
                    <div class="contact-wedding-info">
                        <h3>Phone Contact</h3>
                        <p>+91 9977999178</p>
                    </div>
                </div>

                <div class="contact-wedding-card">
                    <div class="contact-icon-wedding">
                        <i class="fas fa-envelope"></i>
                    </div>
                    <div class="contact-wedding-info">
                        <h3>Email Address</h3>
                        <p>vishalrajputt88@gmail.com</p>
                    </div>
                </div>

                <div class="contact-wedding-card">
                    <div class="contact-icon-wedding">
                        <i class="fas fa-map-marker-alt"></i>
                    </div>
                    <div class="contact-wedding-info">
                        <h3>Family Residence</h3>
                           <p> Taranagar Colony Barwana 451115 </p>
                     
