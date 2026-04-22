<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vishal Rajput — Matrimonial Biodata</title>
 <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Paytone+One&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Paytone+One&family=Urbanist:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <style>
    :root {
      --gold:   #C9A84C;
      --gold2:  #E8C96A;
      --gold3:  #F5E0A0;
      --dark:   #0E0B07;
      --dark2:  #16120C;
      --dark3:  #1E1810;
      --cream:  #F7F0DF;
      --cream2: #EDE0C4;
      --red:    #8B1A1A;
      --muted:  #9C8B6A;
      --border: rgba(201,168,76,0.28);
      --border2:rgba(201,168,76,0.1);
    }
    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      background: var(--dark);
      color: var(--cream);
      min-height: 100vh;
    }
 .markdown-body>*:first-child { display: none !important; } 
    /* ── TOP STRIP ── */
    .top-strip {
      height: 4px;
      background: linear-gradient(90deg, var(--red), var(--gold), var(--gold2), var(--gold), var(--red));
    }

    /* ══ BANNER ══ */
    .banner {
      position: relative;
      width: 100%;
      height: 580px;
      overflow: hidden;
    }

    /* Full bleed bg photo */
    .banner-bg {
      position: absolute;
      inset: 0;
      z-index: 0;
    }
    .banner-bg img {
     width: 100%;
    height: 100%;
    object-fit: contain;
    object-position: right;
    display: block;
    }
    /* Dark fade left-to-right so text is readable */
    .banner-bg::after {
      content: '';
      position: absolute;
      inset: 0;
      background:
        linear-gradient(to right,
          rgba(14,11,7,0.97) 0%,
          rgba(14,11,7,0.90) 28%,
          rgba(14,11,7,0.55) 52%,
          rgba(14,11,7,0.12) 72%,
          rgba(14,11,7,0.0)  100%
        ),
        linear-gradient(to top,
          rgba(14,11,7,0.75) 0%,
          transparent 38%
        );
    }

    /* Ornamental border frame */
    .banner-frame {
      position: absolute;
      inset: 14px;
      z-index: 2;
      pointer-events: none;
      border: 1px solid rgba(201,168,76,0.22);
    }
    .banner-frame::before {
      content: '';
      position: absolute;
      inset: 5px;
      border: 1px solid rgba(201,168,76,0.1);
    }
    /* Corner ornaments */
    .corner {
      position: absolute;
      width: 26px; height: 26px;
    }
    .corner svg { width: 100%; height: 100%; }
    .tl { top:-1px; left:-1px; }
    .tr { top:-1px; right:-1px; transform:scaleX(-1); }
    .bl { bottom:-1px; left:-1px; transform:scaleY(-1); }
    .br { bottom:-1px; right:-1px; transform:scale(-1); }

    /* Left text */
    .banner-content {
      position: relative;
      z-index: 3;
      height: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 3rem 5%;
      max-width: 560px;
    }

    .banner-om {
      font-size: 2.2rem;
      color: var(--gold2);
      margin-bottom: 0.5rem;
      opacity: 0.9;
    }
    .banner-tag {
      display: inline-flex;
      align-items: center;
      gap: 0.65rem;
      font-size: 0.58rem;
      font-weight: 600;
      letter-spacing: 0.26em;
      text-transform: uppercase;
      color: var(--gold2);
      margin-bottom: 1.3rem;
    }
    .banner-tag::before,
    .banner-tag::after {
      content: '';
      display: inline-block;
      height: 1px;
      width: 28px;
      background: linear-gradient(to right, transparent, var(--gold));
    }
    .banner-tag::after { background: linear-gradient(to left, transparent, var(--gold)); }

    .banner-intro {
      font-style: italic;
      font-size: 1.05rem;
      color: var(--muted);
      margin-bottom: 0.15rem;
    }
    .banner-name {
      font-size: clamp(3rem, 6.5vw, 5rem);
      font-weight: 700;
      line-height: 1;
      color: var(--cream);
      margin-bottom: 0.3rem;
      text-shadow: 0 3px 25px rgba(0,0,0,0.7);
    }
    .banner-name .sname { color: var(--gold2); }

    .divider-orn {
      display: flex;
      align-items: center;
      gap: 0.7rem;
      margin: 0.9rem 0 1rem;
    }
    .divider-orn .dl {
      height: 1px;
      width: 80px;
      background: linear-gradient(to right, var(--gold), transparent);
    }
    .divider-orn .ds {
      font-style: normal;
      color: var(--gold);
      font-size: 0.6rem;
      letter-spacing: 0.4rem;
    }

    .banner-role {
      
      font-size: 0.78rem;
      letter-spacing: 0.15em;
      color: var(--gold3);
      margin-bottom: 1.6rem;
    }

    .banner-pills {
      display: flex;
      flex-wrap: wrap;
      gap: 0.42rem;
      margin-bottom: 1.8rem;
    }
    .bpill {
      border: 1px solid rgba(201,168,76,0.32);
      background: rgba(201,168,76,0.06);
      color: var(--gold3);
      
      font-size: 0.8rem;
      padding: 0.2rem 0.82rem;
      border-radius: 1px;
    }

    .banner-meta {
      display: flex;
      flex-wrap: wrap;
      gap: 0.35rem 1.4rem;
      font-size: 0.8rem;
      color: var(--muted);
    }
    .banner-meta span { display: flex; align-items: center; gap: 0.35rem; }

    /* ── ORN DIVIDER ── */
    .orn-divider {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 1rem;
      padding: 1.3rem 5%;
      background: var(--dark2);
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
    }
    .orn-divider .ol {
      flex: 1; max-width: 340px; height: 1px;
      background: linear-gradient(to right, transparent, var(--gold), transparent);
    }
    .orn-divider .os {
      
      font-size: 1.2rem;
      color: var(--gold2);
      letter-spacing: 0.6rem;
    }

    /* ══ MAIN ══ */
    .main {
      max-width: 1080px;
      margin: 0 auto;
      padding: 2.5rem 5% 3rem;
    }

    .sec-head {
      display: flex;
      align-items: center;
      gap: 1rem;
      margin-bottom: 1.6rem;
    }
    .sec-title {
      
      font-size: 0.68rem;
      font-weight: 600;
      letter-spacing: 0.24em;
      text-transform: uppercase;
      color: var(--gold2);
      white-space: nowrap;
    }
    .sec-line {
      flex: 1; height: 1px;
      background: linear-gradient(to right, var(--gold), transparent);
    }

    .grid-2 {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.3rem 1.8rem;
    }

    .scard {
      background: rgba(255,255,255,0.022);
      border: 1px solid var(--border);
      padding: 1.6rem 1.8rem;
      position: relative;
    }
    .scard::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; height: 2px;
      background: linear-gradient(90deg, var(--gold), var(--gold2), transparent);
    }
    .scard::after {
      content: '';
      position: absolute;
      bottom: 0; right: 0;
      width: 28px; height: 28px;
      border-bottom: 1px solid rgba(201,168,76,0.45);
      border-right:  1px solid rgba(201,168,76,0.45);
    }

    .stitle {
      
      font-size: 1.05rem;
      font-weight: 700;
      font-style: italic;
      color: var(--gold2);
      margin-bottom: 1.1rem;
      padding-bottom: 0.7rem;
      border-bottom: 1px solid var(--border2);
      letter-spacing: 0.02em;
    }

    .row {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      padding: 0.52rem 0;
      border-bottom: 1px dashed rgba(201,168,76,0.09);
      gap: 1rem;
    }
    .row:last-child { border-bottom: none; }
    .lbl {
      font-size: 0.77rem;
      color: var(--muted);
      
      flex-shrink: 0;
    }
    .val {
      font-size: 0.87rem;
      font-weight: 500;
      
      color: var(--cream2);
      text-align: right;
    }
    .val.gold { color: var(--gold2); font-weight: 600; }

    /* ── QUOTE ── */
    .quote-section {
      margin: 1.8rem 0 0;
      position: relative;
      text-align: center;
      padding: 2.5rem 4rem;
      background: linear-gradient(135deg, var(--dark3), #1A130A);
      border: 1px solid var(--border);
    }
    .quote-section::before {
      content: '';
      position: absolute;
      inset: 6px;
      border: 1px solid rgba(201,168,76,0.08);
      pointer-events: none;
    }
    .quote-big {
      
      font-size: 5rem;
      color: var(--gold);
      opacity: 0.13;
      line-height: 0.5;
      position: absolute;
      top: 2rem; left: 2.5rem;
    }
    .quote-text {
      
      font-size: 1.32rem;
      font-style: italic;
      color: var(--cream2);
      line-height: 1.75;
      position: relative;
      z-index: 1;
    }
    .quote-author {
      
      font-size: 0.6rem;
      letter-spacing: 0.22em;
      color: var(--gold);
      margin-top: 1.1rem;
    }

    /* ── CONTACT ── */
    .contact-wrap {
      background: var(--dark2);
      border-top: 1px solid var(--border);
      padding: 2rem 5%;
    }
    .contact-head {
      
      font-size: 0.6rem;
      letter-spacing: 0.25em;
      color: var(--gold);
      text-align: center;
      margin-bottom: 1.4rem;
    }
    .contact-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1rem;
      max-width: 900px;
      margin: 0 auto;
    }
    .citem {
      display: flex;
      align-items: center;
      gap: 1rem;
      padding: 1rem 1.2rem;
      border: 1px solid var(--border);
      background: rgba(201,168,76,0.025);
      position: relative;
      transition: border-color 0.3s;
    }
    .citem::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; height: 1px;
      background: linear-gradient(90deg, transparent, var(--gold), transparent);
    }
    .citem:hover { border-color: rgba(201,168,76,0.55); }
    .cicon {
      width: 38px; height: 38px;
      background: linear-gradient(135deg, var(--red), #6B1010);
      display: flex; align-items: center; justify-content: center;
      font-size: 1rem; flex-shrink: 0;
    }
    .clbl {
      
      font-size: 0.52rem;
      letter-spacing: 0.14em;
      color: var(--muted);
      margin-bottom: 0.2rem;
    }
    .cval {
      
      font-size: 0.88rem;
      color: var(--cream);
    }

    .bottom-strip {
      height: 4px;
      background: linear-gradient(90deg, var(--red), var(--gold), var(--gold2), var(--gold), var(--red));
    }
    .bottom-text {
      text-align: center;
      padding: 1.2rem;
      
      font-size: 0.52rem;
      letter-spacing: 0.28em;
      color: var(--muted);
      background: var(--dark);
      border-top: 1px solid var(--border2);
    }

    h1, h2, h3, h4, h5, h6 {  font-family: "Paytone One", sans-serif; font-weight: 400 !important;
  font-weight: 400; }

  span, p, button, a, div { font-family: "Urbanist", sans-serif; }

    @media (max-width: 700px) {
    .banner-om { display: none; }
    .banner-tag { display: none; }
      .banner { height: auto; min-height: 520px; }
      .banner-content { padding: 1rem 1.2rem;
        max-width: 100%;
     justify-content: end;
    min-height: 520px; }
      .banner-name { font-size: 3rem; }
      .grid-2 { grid-template-columns: 1fr; }
      .contact-grid { grid-template-columns: 1fr; }
      .quote-section { padding: 2rem 1.5rem; }
      .main { padding: 2rem 1rem; }
      .banner-bg img {
  
    object-position: right top; }
    .banner-role { display: none; }
    }
    
  </style>
</head>
<body>

<div class="top-strip"></div>

<!-- ═══ BANNER ═══ -->
<div class="banner">

  <div class="banner-bg">
    <img src="https://cdn.shopify.com/s/files/1/0815/6364/8255/files/vishal-profile.jpg?v=1776848804" alt="Vishal Rajput"/>
  </div>

  <!-- Ornamental frame corners -->
  <div class="banner-frame">
    <div class="corner tl">
      <svg viewBox="0 0 26 26" fill="none">
        <path d="M1 25 L1 1 L25 1" stroke="#C9A84C" stroke-width="1.5" stroke-opacity="0.65"/>
        <path d="M1 13 L7 13" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <path d="M13 1 L13 7" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <circle cx="1" cy="1" r="1.8" fill="#C9A84C" fill-opacity="0.55"/>
      </svg>
    </div>
    <div class="corner tr">
      <svg viewBox="0 0 26 26" fill="none">
        <path d="M1 25 L1 1 L25 1" stroke="#C9A84C" stroke-width="1.5" stroke-opacity="0.65"/>
        <path d="M1 13 L7 13" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <path d="M13 1 L13 7" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <circle cx="1" cy="1" r="1.8" fill="#C9A84C" fill-opacity="0.55"/>
      </svg>
    </div>
    <div class="corner bl">
      <svg viewBox="0 0 26 26" fill="none">
        <path d="M1 25 L1 1 L25 1" stroke="#C9A84C" stroke-width="1.5" stroke-opacity="0.65"/>
        <path d="M1 13 L7 13" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <path d="M13 1 L13 7" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <circle cx="1" cy="1" r="1.8" fill="#C9A84C" fill-opacity="0.55"/>
      </svg>
    </div>
    <div class="corner br">
      <svg viewBox="0 0 26 26" fill="none">
        <path d="M1 25 L1 1 L25 1" stroke="#C9A84C" stroke-width="1.5" stroke-opacity="0.65"/>
        <path d="M1 13 L7 13" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <path d="M13 1 L13 7" stroke="#C9A84C" stroke-width="0.7" stroke-opacity="0.45"/>
        <circle cx="1" cy="1" r="1.8" fill="#C9A84C" fill-opacity="0.55"/>
      </svg>
    </div>
  </div>

  <div class="banner-content">
    <div class="banner-om">ॐ</div>
    <div class="banner-tag">Hindu Matrimonial Biodata</div>
    <div class="banner-intro">I'm</div>
    <h1 class="banner-name">Vishal <span class="sname">Chouhan</span></h1>
    <div class="divider-orn">
      <span class="dl"></span>
      <span class="ds">✦ ✦ ✦</span>
    </div>
    <div class="banner-role">Software Engineer &nbsp;·&nbsp; Ultra Tend, London UK</div>
    <div class="banner-pills">
      <span class="bpill">Age 25</span>
      <span class="bpill">5'8" · 54 kg</span>
      <span class="bpill">Hindu · Rajput</span>
      <span class="bpill">Gotra: Vats</span>
      <span class="bpill">Pure Vegetarian</span>
      <span class="bpill">Never Married</span>
    </div>
    <div class="banner-meta">
      <span>🎂 Born 17 April 2001</span>
      <span>📍 Barwaha, Madhya Pradesh</span>
      <span>🩸 A Positive</span>
    </div>
  </div>
</div>

<div class="orn-divider">
  <div class="ol"></div>
  <div class="os">❧ &nbsp; ॐ &nbsp; ❧</div>
  <div class="ol" style="background:linear-gradient(to left,transparent,var(--gold),transparent)"></div>
</div>

<!-- ═══ DETAILS ═══ -->
<div class="main">
  <div class="sec-head">
    <span class="sec-title">Biodata Details</span>
    <span class="sec-line"></span>
  </div>

  <div class="grid-2">
    <div class="scard">
      <div class="stitle">👤 &nbsp; Personal Details</div>
      <div class="row"><span class="lbl">Date of Birth</span><span class="val">17 April, 2001</span></div>
      <div class="row"><span class="lbl">Age</span><span class="val gold">25 Years</span></div>
      <div class="row"><span class="lbl">Height</span><span class="val">5 Feet 8 Inches</span></div>
      <div class="row"><span class="lbl">Weight / Build</span><span class="val">54 KG · Slim</span></div>
      <div class="row"><span class="lbl">Blood Group</span><span class="val">A Positive</span></div>
      <div class="row"><span class="lbl">Religion</span><span class="val">Hindu</span></div>
      <div class="row"><span class="lbl">Caste</span><span class="val">Rajput</span></div>
      <div class="row"><span class="lbl">Gotra</span><span class="val gold">Vats</span></div>
      <div class="row"><span class="lbl">Hometown</span><span class="val">Barwaha, Madhya Pradesh</span></div>
    </div>

    <div class="scard">
      <div class="stitle">🎓 &nbsp; Education & Career</div>
      <div class="row"><span class="lbl">Qualification</span><span class="val">B.A. English Literature</span></div>
      <div class="row"><span class="lbl">University</span><span class="val">DAVV, Indore</span></div>
      <div class="row"><span class="lbl">Specialization</span><span class="val">Computer Programming</span></div>
      <div class="row"><span class="lbl">Profession</span><span class="val gold">Software Engineer</span></div>
      <div class="row"><span class="lbl">Company</span><span class="val">Ultra Tend, London UK</span></div>
      <div class="row"><span class="lbl">Annual Income</span><span class="val gold">₹ 4.2 Lakhs p.a.</span></div>
    </div>

    <div class="scard">
      <div class="stitle">🏠 &nbsp; Family Background</div>
      <div class="row"><span class="lbl">Father's Name</span><span class="val">Shri Bheem Singh Chouhan</span></div>
      <div class="row"><span class="lbl">Mother's Name</span><span class="val">Smt. Sudha Bhai Chouhan</span></div>
      <div class="row"><span class="lbl">Siblings</span><span class="val">Two Sisters</span></div>
      <div class="row"><span class="lbl">Family Type</span><span class="val">Nuclear Family</span></div>
      <div class="row"><span class="lbl">Family Status</span><span class="val gold">Well Settled</span></div>
      <div class="row"><span class="lbl">Residence</span><span class="val">Taranagar Colony, Barwaha 451115</span></div>
    </div>

    <div class="scard">
      <div class="stitle">✨ &nbsp; Lifestyle & Interests</div>
      <div class="row"><span class="lbl">Food Preference</span><span class="val">Pure Vegetarian</span></div>
      <div class="row"><span class="lbl">Smoking</span><span class="val">No</span></div>
      <div class="row"><span class="lbl">Drinking</span><span class="val">No</span></div>
      <div class="row"><span class="lbl">Languages Known</span><span class="val">Hindi, English</span></div>
      <div class="row"><span class="lbl">Hobbies</span><span class="val">Chess, Singing</span></div>
    </div>
  </div>

  <div class="quote-section">
    <div class="quote-big">"</div>
    <p class="quote-text">
      Seeking a life partner who values family, culture, and togetherness —<br/>
      someone to grow with, every single day.
    </p>
    <div class="quote-author">— Vishal Rajput</div>
  </div>
</div>

<!-- ═══ CONTACT ═══ -->
<div class="contact-wrap">
  <div class="contact-head">✦ &nbsp; Get In Touch &nbsp; ✦</div>
  <div class="contact-grid">
    <div class="citem">
      <div class="cicon">📞</div>
      <div>
        <div class="clbl">Phone</div>
        <div class="cval">+91 9977999178</div>
      </div>
    </div>
    <div class="citem">
      <div class="cicon">✉️</div>
      <div>
        <div class="clbl">Email</div>
        <div class="cval">vishalrajputt88@gmail.com</div>
      </div>
    </div>
    <div class="citem">
      <div class="cicon">📍</div>
      <div>
        <div class="clbl">Address</div>
        <div class="cval">Taranagar Colony, Barwaha 451115</div>
      </div>
    </div>
  </div>
</div>

<div class="bottom-strip"></div>
<div class="bottom-text">✦ &nbsp; Matrimonial Biodata — Vishal Rajput &nbsp; ✦ &nbsp; Barwaha, Madhya Pradesh &nbsp; ✦</div>

</body>
</html>
