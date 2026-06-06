(https://github.com/user-attachments/files/28649203/index.html)
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dermae Beauty Circle — Join Now</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --rose: #e8826a;
    --rose-dark: #c95f47;
    --blush: #f7e4dd;
    --cream: #fdf6f0;
    --deep: #2a1a14;
    --muted: #7a5c52;
    --gold: #c9a96e;
    --green: #25D366;
    --green-dark: #1da851;
    --white: #ffffff;
    --shadow: 0 8px 40px rgba(42,26,20,0.12);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'DM Sans', sans-serif;
    background: var(--cream);
    color: var(--deep);
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* ── HERO ── */
  .hero {
    position: relative;
    background: linear-gradient(150deg, #fdf0ea 0%, #f9e0d4 40%, #f0cfc0 100%);
    padding: 60px 24px 50px;
    text-align: center;
    overflow: hidden;
  }

  .hero::before {
    content: '';
    position: absolute;
    top: -80px; right: -80px;
    width: 320px; height: 320px;
    background: radial-gradient(circle, rgba(232,130,106,0.18) 0%, transparent 70%);
    border-radius: 50%;
  }
  .hero::after {
    content: '';
    position: absolute;
    bottom: -60px; left: -60px;
    width: 240px; height: 240px;
    background: radial-gradient(circle, rgba(201,169,110,0.15) 0%, transparent 70%);
    border-radius: 50%;
  }

  /* Logo */
  .logo-wrap {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 28px;
    position: relative;
    z-index: 1;
  }
  .logo-icon {
    width: 48px; height: 48px;
    background: linear-gradient(135deg, var(--rose), var(--gold));
    border-radius: 14px;
    display: flex; align-items: center; justify-content: center;
    box-shadow: 0 4px 16px rgba(232,130,106,0.4);
  }
  .logo-icon svg { width: 26px; height: 26px; fill: white; }
  .logo-text {
    font-family: 'Playfair Display', serif;
    font-size: 22px;
    font-weight: 700;
    color: var(--deep);
    letter-spacing: 0.02em;
  }
  .logo-text span { color: var(--rose); }

  /* Badge */
  .badge {
    display: inline-block;
    background: linear-gradient(90deg, var(--rose), var(--gold));
    color: white;
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 5px 16px;
    border-radius: 100px;
    margin-bottom: 20px;
    position: relative; z-index: 1;
    animation: pulse-badge 2s infinite;
  }
  @keyframes pulse-badge {
    0%, 100% { box-shadow: 0 0 0 0 rgba(232,130,106,0.4); }
    50% { box-shadow: 0 0 0 8px rgba(232,130,106,0); }
  }

  .hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(28px, 7vw, 40px);
    font-weight: 700;
    line-height: 1.2;
    color: var(--deep);
    margin-bottom: 14px;
    position: relative; z-index: 1;
  }
  .hero h1 em {
    font-style: italic;
    color: var(--rose);
  }

  .hero-sub {
    font-size: 15px;
    color: var(--muted);
    line-height: 1.6;
    max-width: 340px;
    margin: 0 auto 28px;
    position: relative; z-index: 1;
  }

  /* Floating petals */
  .petal {
    position: absolute;
    width: 10px; height: 10px;
    background: rgba(232,130,106,0.25);
    border-radius: 50% 0 50% 0;
    animation: float-petal 6s ease-in-out infinite;
  }
  .petal:nth-child(1) { top:15%; left:8%; animation-delay:0s; }
  .petal:nth-child(2) { top:30%; right:10%; animation-delay:1.5s; width:7px; height:7px; }
  .petal:nth-child(3) { top:60%; left:5%; animation-delay:3s; width:6px; height:6px; }
  @keyframes float-petal {
    0%,100% { transform: translateY(0) rotate(0deg); }
    50% { transform: translateY(-14px) rotate(180deg); }
  }

  /* ── COUNTER STRIP ── */
  .counter-strip {
    background: linear-gradient(90deg, var(--rose-dark), var(--rose));
    color: white;
    text-align: center;
    padding: 14px 20px;
    font-size: 13px;
    font-weight: 500;
    letter-spacing: 0.01em;
  }
  .counter-strip strong { font-weight: 700; font-size: 15px; }

  /* ── PERKS ── */
  .section { padding: 36px 20px; }

  .section-title {
    font-family: 'Playfair Display', serif;
    font-size: 22px;
    font-weight: 600;
    text-align: center;
    margin-bottom: 24px;
    color: var(--deep);
  }
  .section-title span { color: var(--rose); }

  .perks-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 14px;
    max-width: 480px;
    margin: 0 auto;
  }

  .perk-card {
    background: white;
    border-radius: 18px;
    padding: 20px 16px;
    text-align: center;
    box-shadow: 0 4px 20px rgba(42,26,20,0.07);
    border: 1px solid rgba(232,130,106,0.1);
    transition: transform 0.2s, box-shadow 0.2s;
    animation: card-in 0.5s ease both;
  }
  .perk-card:nth-child(1){animation-delay:0.05s}
  .perk-card:nth-child(2){animation-delay:0.1s}
  .perk-card:nth-child(3){animation-delay:0.15s}
  .perk-card:nth-child(4){animation-delay:0.2s}
  .perk-card:nth-child(5){animation-delay:0.25s}
  .perk-card:nth-child(6){animation-delay:0.3s}
  @keyframes card-in {
    from { opacity:0; transform:translateY(18px); }
    to   { opacity:1; transform:translateY(0); }
  }
  .perk-card:active { transform: scale(0.97); }

  .perk-icon {
    font-size: 30px;
    margin-bottom: 10px;
    display: block;
  }
  .perk-label {
    font-size: 13px;
    font-weight: 600;
    color: var(--deep);
    line-height: 1.3;
  }
  .perk-desc {
    font-size: 11.5px;
    color: var(--muted);
    margin-top: 4px;
    line-height: 1.4;
  }

  /* wide card */
  .perk-card.wide {
    grid-column: span 2;
  }

  /* ── WELCOME OFFER ── */
  .offer-box {
    background: linear-gradient(135deg, #fff8f5, #ffeee7);
    border: 2px solid rgba(232,130,106,0.3);
    border-radius: 22px;
    padding: 26px 22px;
    margin: 0 20px 8px;
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  .offer-box::before {
    content: '✦';
    position: absolute;
    top: -10px; right: 16px;
    font-size: 60px;
    color: rgba(232,130,106,0.08);
  }
  .offer-tag {
    display: inline-block;
    background: var(--gold);
    color: white;
    font-size: 10px;
    font-weight: 700;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 4px 14px;
    border-radius: 100px;
    margin-bottom: 14px;
  }
  .offer-box h2 {
    font-family: 'Playfair Display', serif;
    font-size: 20px;
    color: var(--deep);
    margin-bottom: 10px;
    line-height: 1.25;
  }
  .offer-box p {
    font-size: 14px;
    color: var(--muted);
    line-height: 1.6;
  }
  .offer-highlight {
    display: inline-block;
    background: linear-gradient(90deg, var(--rose), var(--gold));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 700;
    font-size: 16px;
  }

  /* ── SOCIAL PROOF ── */
  .proof-section {
    padding: 28px 20px 10px;
    text-align: center;
  }
  .stars { font-size: 18px; letter-spacing: 2px; margin-bottom: 8px; }
  .proof-text {
    font-size: 13.5px;
    color: var(--muted);
    font-style: italic;
    max-width: 300px;
    margin: 0 auto;
    line-height: 1.5;
  }
  .proof-author {
    font-size: 12px;
    font-weight: 600;
    color: var(--rose);
    margin-top: 6px;
  }

  .avatars {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: -8px;
    margin: 16px 0 6px;
  }
  .avatar {
    width: 36px; height: 36px;
    border-radius: 50%;
    border: 2px solid white;
    background: linear-gradient(135deg, var(--rose), var(--gold));
    display: flex; align-items: center; justify-content: center;
    font-size: 14px;
    margin-left: -8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  }
  .avatar:first-child { margin-left: 0; }
  .member-count {
    font-size: 12.5px;
    color: var(--muted);
    text-align: center;
  }
  .member-count strong { color: var(--rose); }

  /* ── CTA BUTTONS ── */
  .cta-section {
    padding: 28px 24px 20px;
    text-align: center;
  }

  .cta-main {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    background: linear-gradient(135deg, var(--green), var(--green-dark));
    color: white;
    text-decoration: none;
    padding: 18px 28px;
    border-radius: 16px;
    font-size: 16px;
    font-weight: 600;
    letter-spacing: 0.01em;
    box-shadow: 0 6px 24px rgba(37,211,102,0.35);
    transition: transform 0.15s, box-shadow 0.15s;
    margin-bottom: 14px;
    width: 100%;
    max-width: 380px;
    margin-left: auto;
    margin-right: auto;
  }
  .cta-main:active {
    transform: scale(0.97);
    box-shadow: 0 3px 12px rgba(37,211,102,0.25);
  }
  .cta-main .wa-icon {
    width: 26px; height: 26px;
    background: white;
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .cta-main .wa-icon svg { width: 16px; height: 16px; }

  .cta-secondary {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    background: white;
    color: var(--green-dark);
    text-decoration: none;
    padding: 15px 24px;
    border-radius: 14px;
    font-size: 14.5px;
    font-weight: 600;
    border: 2px solid rgba(37,211,102,0.3);
    box-shadow: 0 4px 16px rgba(0,0,0,0.06);
    transition: transform 0.15s;
    width: 100%;
    max-width: 380px;
    margin: 0 auto 10px;
  }
  .cta-secondary:active { transform: scale(0.97); }
  .cta-secondary .wa-icon {
    width: 24px; height: 24px;
    background: var(--green);
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .cta-secondary .wa-icon svg { width: 14px; height: 14px; }

  .cta-note {
    font-size: 11.5px;
    color: var(--muted);
    margin-top: 4px;
  }

  /* ── URGENCY BAR ── */
  .urgency {
    background: var(--deep);
    color: white;
    text-align: center;
    padding: 16px 20px;
    font-size: 13px;
  }
  .urgency strong { color: var(--gold); }

  .progress-wrap {
    background: rgba(255,255,255,0.15);
    border-radius: 100px;
    height: 6px;
    max-width: 280px;
    margin: 10px auto 6px;
    overflow: hidden;
  }
  .progress-bar {
    height: 100%;
    background: linear-gradient(90deg, var(--gold), var(--rose));
    border-radius: 100px;
    width: 73%;
    animation: grow-bar 1.5s ease-out both;
  }
  @keyframes grow-bar {
    from { width: 0%; }
    to { width: 73%; }
  }
  .progress-label {
    font-size: 11px;
    opacity: 0.7;
    margin-top: 3px;
  }

  /* ── FOOTER ── */
  footer {
    background: #1a0f0b;
    color: rgba(255,255,255,0.5);
    text-align: center;
    padding: 24px 20px;
    font-size: 11px;
    line-height: 1.7;
  }
  footer a { color: rgba(255,255,255,0.65); text-decoration: underline; }
  .footer-logo {
    font-family: 'Playfair Display', serif;
    font-size: 16px;
    color: rgba(255,255,255,0.8);
    margin-bottom: 10px;
  }
  .footer-logo span { color: var(--rose); }
  .disclaimer {
    background: rgba(255,255,255,0.05);
    border-radius: 8px;
    padding: 10px 14px;
    margin-top: 12px;
    font-size: 10px;
    line-height: 1.6;
    color: rgba(255,255,255,0.4);
    border-left: 2px solid var(--rose);
  }

  /* ── DIVIDER ── */
  .divider {
    height: 1px;
    background: linear-gradient(90deg, transparent, rgba(232,130,106,0.25), transparent);
    margin: 4px 24px;
  }

  /* Scroll reveal */
  .reveal {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.55s ease, transform 0.55s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }
</style>
</head>
<body>

<!-- HERO -->
<section class="hero">
  <div class="petal"></div>
  <div class="petal"></div>
  <div class="petal"></div>

  <div class="logo-wrap">
    <div class="logo-icon">
      <!-- Leaf / beauty icon -->
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 2C7.58 2 4 7 4 12c0 2.8 1.2 5.3 3.1 7.1C8.5 20.6 10.2 21.5 12 22c1.8-.5 3.5-1.4 4.9-2.9C18.8 17.3 20 14.8 20 12c0-5-3.58-10-8-10zm0 18.2c-1.4-.4-2.7-1.2-3.8-2.3A8.03 8.03 0 016 12c0-3.9 2.7-8 6-8 3.3 0 6 4.1 6 8 0 2.3-.9 4.3-2.2 5.9-1.1 1.1-2.4 1.9-3.8 2.3z"/>
        <path d="M12 6c0 0-2 3-2 6s2 6 2 6 2-3 2-6-2-6-2-6z" opacity=".5"/>
      </svg>
    </div>
    <div class="logo-text">Derm<span>ae</span></div>
  </div>

  <div class="badge">✦ Exclusive Members Club</div>

  <h1>Glow more.<br><em>Spend less.</em><br>Join the circle.</h1>
  <p class="hero-sub">Cleaner, expert-backed skincare — with insider perks only our WhatsApp community gets.</p>

  <!-- Discount pill above CTA -->
  <div style="display:inline-flex;align-items:center;gap:7px;background:rgba(42,26,20,0.08);border:1.5px dashed var(--rose);border-radius:100px;padding:7px 16px;margin-bottom:16px;position:relative;z-index:1;">
    <span style="font-size:17px;">🎁</span>
    <span style="font-size:12.5px;font-weight:700;color:var(--rose-dark);letter-spacing:0.01em;">Join now &amp; get <u>20% OFF</u> your first order</span>
  </div>

  <!-- Primary CTA right in hero -->
  <a href="whatsapp://send?phone=1234567890&text=Hi%20Dermae%21%20I%27d%20love%20to%20join%20the%20Beauty%20Circle%20and%20claim%20my%2020%25%20welcome%20discount%20%F0%9F%8C%B8"
     onclick="this.href=(/iPhone|Android/i.test(navigator.userAgent)?'whatsapp://send?phone=1234567890':'https://wa.me/1234567890')+'&text=Hi%20Dermae%21%20I%27d%20love%20to%20join%20the%20Beauty%20Circle%20and%20claim%20my%2020%25%20welcome%20discount%20%F0%9F%8C%B8'"
     target="_blank" rel="noopener" class="cta-main" style="display:inline-flex; margin-bottom:0;">
    <span class="wa-icon">
      <svg viewBox="0 0 24 24" fill="#25D366" xmlns="http://www.w3.org/2000/svg">
        <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
      </svg>
    </span>
    <span>Claim 20% Off — Join on WhatsApp</span>
  </a>
</section>

<!-- COUNTER -->
<div class="counter-strip">
  🔥 <strong>73 of 100</strong> welcome spots claimed — only <strong>27 left</strong> with 20% off your first order!
</div>

<!-- PERKS -->
<section class="section reveal">
  <p class="section-title">What you get <span>inside ✦</span></p>
  <div class="perks-grid">
    <div class="perk-card">
      <span class="perk-icon">🚀</span>
      <div class="perk-label">Early Access</div>
      <div class="perk-desc">First to shop every new Dermae launch</div>
    </div>
    <div class="perk-card">
      <span class="perk-icon">💸</span>
      <div class="perk-label">Up to 50% Off</div>
      <div class="perk-desc">VIP-only discounts exclusive to the group</div>
    </div>
    <div class="perk-card">
      <span class="perk-icon">🧴</span>
      <div class="perk-label">Free Samples</div>
      <div class="perk-desc">Mini trial drops sent straight to you</div>
    </div>
    <div class="perk-card">
      <span class="perk-icon">⚡</span>
      <div class="perk-label">Flash Sales</div>
      <div class="perk-desc">Weekly deals — gone in hours</div>
    </div>
    <div class="perk-card">
      <span class="perk-icon">💬</span>
      <div class="perk-label">Live Q&A</div>
      <div class="perk-desc">Ask our skincare experts directly</div>
    </div>
    <div class="perk-card">
      <span class="perk-icon">✨</span>
      <div class="perk-label">Your Routine</div>
      <div class="perk-desc">Personalised skincare tips for your skin</div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- WELCOME OFFER -->
<section style="padding: 28px 0 10px;" class="reveal">
  <div class="offer-box">
    <div class="offer-tag">🎁 Welcome Offer</div>
    <h2>First 100 members get<br><span class="offer-highlight">20% extra off</span> + a<br>free trial serum</h2>
    <p>Join before the seats are gone and your very first order comes with an exclusive member discount <em>and</em> a complimentary trial-size serum — automatically.</p>
  </div>
</section>

<!-- SOCIAL PROOF -->
<section class="proof-section reveal">
  <div class="avatars">
    <div class="avatar">🌸</div>
    <div class="avatar">💄</div>
    <div class="avatar">🌿</div>
    <div class="avatar">✨</div>
    <div class="avatar">💅</div>
  </div>
  <p class="member-count"><strong>2,400+</strong> women already inside</p>
  <div style="height:16px;"></div>
  <div class="stars">★★★★★</div>
  <p class="proof-text">"The flash deals are insane — I got my favourite serum for half price and got notified before it even went live on the site!"</p>
  <p class="proof-author">— Rania K., Beauty Circle member</p>
</section>

<!-- URGENCY -->
<div class="urgency reveal">
  <div>⏳ <strong>Limited seats — closes when full</strong></div>
  <div class="progress-wrap"><div class="progress-bar"></div></div>
  <div class="progress-label">73 / 100 welcome seats filled</div>
</div>

<!-- CTA SECTION -->
<section class="cta-section reveal">
  <!-- Discount highlight box -->
  <div style="background:linear-gradient(135deg,#fff3ee,#ffeae0);border:2px solid rgba(232,130,106,0.35);border-radius:16px;padding:16px 18px;margin-bottom:22px;max-width:380px;margin-left:auto;margin-right:auto;">
    <div style="font-size:22px;font-weight:800;color:var(--rose-dark);font-family:'Playfair Display',serif;line-height:1;">20% OFF + Free Serum</div>
    <div style="font-size:12.5px;color:var(--muted);margin-top:5px;">Unlocked automatically when you join via WhatsApp — for the next <strong style="color:var(--rose-dark);">27 members only</strong></div>
  </div>

  <!-- Primary: join group — opens WA app on mobile, web on desktop -->
  <a id="btn-join"
     href="whatsapp://send?phone=1234567890&text=Hi%20Dermae%21%20I%27d%20love%20to%20join%20the%20Beauty%20Circle%20and%20claim%20my%2020%25%20welcome%20discount%20%F0%9F%8C%B8"
     target="_blank" rel="noopener" class="cta-main">
    <span class="wa-icon">
      <svg viewBox="0 0 24 24" fill="#25D366" xmlns="http://www.w3.org/2000/svg">
        <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
      </svg>
    </span>
    <span>Open WhatsApp &amp; Claim 20% Off</span>
  </a>

  <!-- Secondary: message directly -->
  <a id="btn-msg"
     href="whatsapp://send?phone=1234567890&text=Hi%20Dermae%2C%20please%20add%20me%20to%20the%20Beauty%20Circle%20group%20and%20apply%20my%2020%25%20welcome%20discount!"
     target="_blank" rel="noopener" class="cta-secondary">
    <span class="wa-icon">
      <svg viewBox="0 0 24 24" fill="white" xmlns="http://www.w3.org/2000/svg">
        <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
      </svg>
    </span>
    Message Us on WhatsApp Instead
  </a>

  <p class="cta-note">🔒 No spam · Leave anytime · Discount applied on first order</p>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">Derm<span>ae</span> Beauty</div>
  <div>© 2024 Dermae. All rights reserved.</div>
  <div style="margin-top:4px;">
    <a href="#">Privacy Policy</a> &nbsp;·&nbsp; <a href="#">Terms</a>
  </div>
  <div class="disclaimer">
    📋 <strong>Campaign notice:</strong> This page is part of the Dermae WhatsApp community growth campaign. WhatsApp links open the official WhatsApp app. Offers are subject to availability and valid while spots last. This page is intended to be used as part of a broader digital marketing campaign — please replace placeholder links with your official WhatsApp group or business number before publishing.
  </div>
</footer>

<script>
  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const io = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) { e.target.classList.add('visible'); io.unobserve(e.target); }
    });
  }, { threshold: 0.12 });
  reveals.forEach(r => io.observe(r));
</script>
</body>
</html>

# dermae-beauty-club
join the group
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-W2KXVJ20MS"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-W2KXVJ20MS');
</script>
