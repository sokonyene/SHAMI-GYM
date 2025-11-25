-project-folder/
├── index.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shami Gym | Home</title>
  <link rel="stylesheet" href="styles/style.css" />
  <meta name="description" content="Shami Gym—train smarter with expert coaches, modern equipment, and community energy." />
</head>
<body>
  <header class="site-header">
    <div class="container header-wrap">
      <a class="logo" href="index.html">
        <img src="images/logo.png" />
        <span>Shami Gym</span>
      </a>
      <nav class="site-nav" aria-label="Main navigation">
        <ul>
          <li><a class="active" href="index.html">Home</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <button class="nav-toggle" aria-label="Toggle menu">☰</button>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container">
        <h1>Train smarter. Feel stronger.</h1>
        <p>Coaching, community, and clean facilities—built around your goals.</p>
        <div class="cta-group">
          <a class="btn btn-primary" href="services.html">View Services</a>
          <a class="btn btn-outline" href="contact.html">Book a Free Trial</a>
        </div>
      </div>
    </section>

    <section class="carousel" aria-label="Image carousel">
      <!-- Accessible, HTML/CSS-only slider using radio inputs -->
      <div class="container slider">
        <input type="radio" name="slider" id="slide-1" checked aria-hidden="true" />
        <input type="radio" name="slider" id="slide-2" aria-hidden="true" />
        <input type="radio" name="slider" id="slide-3" aria-hidden="true" />

        <div class="slides">
          <div class="slide">
            <img src=" images/slider1.jpg" />
            <div class="caption">Strength training area with modern equipment</div>
          </div>
          <div class="slide">
            <img src="images/slider2.jpg" />
            <div class="caption">High-energy HIIT classes that push your limits</div>
          </div>
          <div class="slide">
            <img src="images/slider3.jpg" />
            <div class="caption">Personal coaching tailored to your goals</div>
          </div>
        </div>

        <div class="controls" role="tablist" aria-label="Carousel controls">
          <label for="slide-1" role="tab" aria-controls="slide-1">1</label>
          <label for="slide-2" role="tab" aria-controls="slide-2">2</label>
          <label for="slide-3" role="tab" aria-controls="slide-3">3</label>
        </div>
      </div>
    </section>

    <section class="intro">
      <div class="container grid-3">
        <article class="card">
          <img class="icon" src="images/logo.png" />
          <h3>Expert coaches</h3>
          <p>Certified trainers who design programs that fit your body, time, and goals.</p>
        </article>
        <article class="card">
          <img class="images/logo.png" />
          <h3>Clean, modern space</h3>
          <p>Well-ventilated rooms, sanitized equipment, and seamless check-ins.</p>
        </article>
        <article class="card">
          <img class="icon" src="images/logo.png" />
          <h3>Community energy</h3>
          <p>Group classes and events to keep you accountable and motivated.</p>
        </article>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-grid">
      <div>
        <h4>Shami Gym</h4>
        <p>Kata, Matugga, Central Region, Uganda</p>
      </div>
      <nav aria-label="Footer navigation">
        <ul class="footer-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <div class="social">
        <a href="#" aria-label="Tiktok">TT</a>
        <a href="#" aria-label="Instagram">IG</a>
        <a href="#" aria-label="X">X</a>
      </div>
    </div>
    <div class="copyright">
      © 2025 Shami Gym. Developed by Okonyene Shawn Michael.
    </div>
  </footer>

  <script>
    // Optional: make the mobile nav toggle functional without extra libraries
    const toggle = document.querySelector('.nav-toggle');
    const nav = document.querySelector('.site-nav');
    toggle.addEventListener('click', () => {
      nav.classList.toggle('open');
    });
  </script>
</body>
</html>

├── services.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shami Gym | Services</title>
  <link rel="stylesheet" href="styles/style.css" />
  <meta name="description" content="Explore Shami Gym services: personal training, group classes, and nutrition coaching." />
</head>
<body>
  <header class="site-header">
    <div class="container header-wrap">
      <a class="logo" href="index.html">
        <img src="images/logo.png" />
        <span>Shami Gym</span>
      </a>
      <nav class="site-nav" aria-label="Main navigation">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a class="active" href="services.html">Services</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <button class="nav-toggle" aria-label="Toggle menu">☰</button>
    </div>
  </header>

  <main>
    <section class="page-hero">
      <div class="container">
        <h1>Services</h1>
        <p>Programs that meet you where you are—and take you where you want to go.</p>
      </div>
    </section>

    <section class="services-list">
      <div class="container grid-3">
        <article class="card">
          <img class="service-image" src="images/slider3.jpg" alt="Personal training session" />
          <h3>Personal training</h3>
          <p>One-on-one coaching with custom plans, form checks, and progress tracking.</p>
          <ul class="ticks">
            <li>Initial assessment</li>
            <li>Weekly sessions</li>
            <li>Goal-based progression</li>
          </ul>
        </article>

        <article class="card">
          <img class="service-image" src="images/slider2.jpg" alt="Group HIIT class" />
          <h3>Group classes</h3>
          <p>HIIT, strength circuits, mobility flows, and dance cardio—fun, fast, and effective.</p>
          <ul class="ticks">
            <li>Beginner-friendly options</li>
            <li>Certified instructors</li>
            <li>Flexible schedule</li>
          </ul>
        </article>

        <article class="card">
          <img class="service-image" src=" images/slider1.jpg" />
          <h3>Nutrition coaching</h3>
          <p>Balanced plans and habit coaching to fuel your training and recovery.</p>
          <ul class="ticks">
            <li>Meal guidance</li>
            <li>Body composition tracking</li>
            <li>Ongoing support</li>
          </ul>
        </article>
      </div>
    </section>

    <section class="cta-band">
      <div class="container">
        <h2>Ready to start?</h2>
        <p>Book a free consultation and we’ll build your plan.</p>
        <a class="btn btn-primary" href="contact.html">Book now</a>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-grid">
      <div>
        <h4>Shami Gym</h4>
        <p>Katta, Matugga, Central Region, Uganda</p>
      </div>
      <nav aria-label="Footer navigation">
        <ul class="footer-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <div class="social">
        <a href="#" aria-label="Tiktok">TT</a>
        <a href="#" aria-label="Instagram">IG</a>
        <a href="#" aria-label="X">X</a>
      </div>
    </div>
    <div class="copyright">
      © 2025 Shami Gym. Developed by Okonyene Shawn Michael.
    </div>
  </footer>

  <script>
    const toggle = document.querySelector('.nav-toggle');
    const nav = document.querySelector('.site-nav');
    toggle.addEventListener('click', () => {
      nav.classList.toggle('open');
    });
  </script>
</body>
</html>

├── about.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PulseFit Gym | About</title>
  <link rel="stylesheet" href="styles/style.css" />
  <meta name="description" content="Learn about PulseFit Gym—our history, mission, team, and values." />
</head>
<body>
  <header class="site-header">
    <div class="container header-wrap">
      <a class="logo" href="index.html">
        <img src="images/logo.png" />
        <span>Shami Gym</span>
      </a>
      <nav class="site-nav" aria-label="Main navigation">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a class="active" href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <button class="nav-toggle" aria-label="Toggle menu">☰</button>
    </div>
  </header>

  <main>
    <section class="page-hero">
      <div class="container">
        <h1>About Shami Gym</h1>
        <p>We started as a small community gym with a big mission: make fitness feel personal.</p>
      </div>
    </section>

    <section class="history">
      <div class="container grid-2">
        <div>
          <h2>Our story</h2>
          <p>Founded in 2020, Shami Gym began with a simple idea—combine expert coaching with a welcoming space where anyone can train confidently.</p>
          <p>Today, we serve beginners and athletes alike with programs that adapt to your lifestyle and goals.</p>
        </div>
        <div class="values">
          <h2>Our values</h2>
          <ul class="ticks">
            <li>Integrity in coaching</li>
            <li>Community first</li>
            <li>Progress over perfection</li>
            <li>Clean, safe environment</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="team">
      <div class="container">
        <h2>Meet the team</h2>
        <div class="grid-3">
          <article class="card">
            <img class="avatar" src="images/logo.png" />
            <h3>Robert “Coach” Kazibwe</h3>
            <p>Head Coach, Strength & Conditioning</p>
          </article>
          <article class="card">
            <img class="avatar" src="images/logo.png" />
            <h3>Maggie Davisha</h3>
            <p>Group Fitness Lead, Mobility & HIIT</p>
          </article>
          <article class="card">
            <img class="avatar" src="images/logo.png" />
            <h3>Hamza Male</h3>
            <p>Nutrition Coach, Habit Change</p>
          </article>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-grid">
      <div>
        <h4>Shami Gym</h4>
        <p>Katta, Matugga, Central Region, Uganda</p>
      </div>
      <nav aria-label="Footer navigation">
        <ul class="footer-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <div class="social">
        <a href="#" aria-label="TikTok">TT</a>
        <a href="#" aria-label="Instagram">IG</a>
        <a href="#" aria-label="X">X</a>
      </div>
    </div>
    <div class="copyright">
      © 2025 Shami Gym. Developed by Okonyene Shawn Michael.
    </div>
  </footer>

  <script>
    const toggle = document.querySelector('.nav-toggle');
    const nav = document.querySelector('.site-nav');
    toggle.addEventListener('click', () => {
      nav.classList.toggle('open');
    });
  </script>
</body>
</html>

├── contact.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Shami Gym | Contact</title>
  <link rel="stylesheet" href="styles/style.css" />
  <meta name="description" content="Get in touch with Shami Gym—contact form, location, phone, and email." />
</head>
<body>
  <header class="site-header">
    <div class="container header-wrap">
      <a class="logo" href="index.html">
        <img src="images/logo.png" />
        <span>Shami Gym</span>
      </a>
      <nav class="site-nav" aria-label="Main navigation">
        <ul>
          <li><a href="index.html">Home</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="about.html">About</a></li>
          <li><a class="active" href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <button class="nav-toggle" aria-label="Toggle menu">☰</button>
    </div>
  </header>

  <main>
    <section class="page-hero">
      <div class="container">
        <h1>Contact us</h1>
        <p>We’d love to hear from you. Book a visit or ask a question.</p>
      </div>
    </section>

    <section class="contact-grid">
      <div class="container grid-2">
        <form class="contact-form" action="#" method="post">
          <h2>Send a message</h2>
          <div class="form-field">
            <label for="name">Name</label>
            <input id="name" name="name" type="text" placeholder="Your name" required />
          </div>
          <div class="form-field">
            <label for="email">Email</label>
            <input id="email" name="email" type="email" placeholder="you@example.com" required />
          </div>
          <div class="form-field">
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="6" placeholder="How can we help?" required></textarea>
          </div>
          <button class="btn btn-primary" type="submit">Send</button>
        </form>

        <div class="contact-info">
          <h2>Visit & call</h2>
          <p><strong>Address:</strong> Katta, Matugga, Central Region, Uganda</p>
          <p><strong>Phone:</strong> +256 769038935</p>
          <p><strong>Email:</strong> hello@shamigym.com</p>

          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container footer-grid">
      <div>
        <h4>Shami Gym</h4>
        <p>Katta, Matugga, Central Region, Uganda</p>
      </div>
      <nav aria-label="Footer navigation">
        <ul class="footer-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="services.html">Services</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
      <div class="social">
        <a href="#" aria-label="Tiktok">TT</a>
        <a href="#" aria-label="Instagram">IG</a>
        <a href="#" aria-label="X">X</a>
      </div>
    </div>
    <div class="copyright">
      © 2025 Shami Gym. Developed by Okonyene Shawn Michael.
    </div>
  </footer>

  <script>
    const toggle = document.querySelector('.nav-toggle');
    const nav = document.querySelector('.site-nav');
    toggle.addEventListener('click', () => {
      nav.classList.toggle('open');
    });
  </script>
</body>
</html>

├── styles/
│   └── style.css:root {
  --bg: #0f1220;
  --surface: #171a2e;
  --primary: #5ee3b1;
  --primary-700: #1aa67b;
  --text: #e7eaf6;
  --muted: #a9afc6;
  --accent: #ffd166;
}

/* Base */
*,
*::before,
*::after { box-sizing: border-box; }

html { scroll-behavior: smooth; }

body {
  margin: 0;
  font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, "Helvetica Neue", Arial, sans-serif;
  color: var(--text);
  background: linear-gradient(180deg, #0b0e1a 0%, #0f1220 100%);
  line-height: 1.6;
}

img { max-width: 100%; display: block; }

.container {
  width: 100%;
  max-width: 1100px;
  margin: 0 auto;
  padding: 0 16px;
}

/* Header & Nav */
.site-header {
  position: sticky; top: 0; z-index: 10;
  background: rgba(23, 26, 46, 0.9);
  backdrop-filter: blur(8px);
  border-bottom: 1px solid #252a45;
}

.header-wrap {
  display: flex; align-items: center; justify-content: space-between;
  min-height: 64px;
}

.logo { display: flex; align-items: center; gap: 10px; color: var(--text); text-decoration: none; font-weight: 700; }
.logo img { width: 36px; height: 36px; object-fit: contain; }

.site-nav ul {
  display: flex; gap: 20px;
  list-style: none; margin: 0; padding: 0;
}

.site-nav a {
  color: var(--text); text-decoration: none; padding: 8px 10px; border-radius: 6px;
}

.site-nav a:hover { background: #1f2342; }

.site-nav a.active {
  background: var(--primary); color: #0b0e1a; font-weight: 700;
}

.nav-toggle {
  display: none;
  background: transparent; color: var(--text); border: 1px solid #2a3056;
  padding: 6px 10px; border-radius: 6px; cursor: pointer;
}

/* Hero */
.hero {
  padding: 72px 0 40px;
  text-align: center;
}
.hero h1 { font-size: 2.4rem; margin: 0 0 10px; }
.hero p { color: var(--muted); margin: 0 0 20px; }

.cta-group { display: inline-flex; gap: 12px; }

.btn {
  display: inline-block; text-decoration: none; border-radius: 10px; padding: 12px 16px; font-weight: 700;
}

.btn-primary { background: var(--primary); color: #0b0e1a; }
.btn-primary:hover { background: var(--primary-700); color: white; }

.btn-outline { border: 2px solid var(--primary); color: var(--primary); }
.btn-outline:hover { background: #16213e; }

/* Carousel slider (CSS-only) */
.carousel { padding: 20px 0 40px; }
.slider { position: relative; }
.slider input { display: none; }

.slides {
  position: relative; overflow: hidden; border-radius: 14px; border: 1px solid #232844;
}

.slide {
  position: absolute; inset: 0; opacity: 0; transition: opacity 0.6s ease;
}
.slide img { width: 100%; height: 360px; object-fit: cover; }
.slide .caption {
  position: absolute; left: 16px; bottom: 16px; background: rgba(0,0,0,0.45);
  padding: 8px 12px; border-radius: 8px; font-size: 0.95rem;
}

#slide-1:checked ~ .slides .slide:nth-child(1),
#slide-2:checked ~ .slides .slide:nth-child(2),
#slide-3:checked ~ .slides .slide:nth-child(3) {
  opacity: 1; position: relative;
}

.controls {
  display: flex; gap: 8px; justify-content: center; margin-top: 12px;
}
.controls label {
  width: 28px; height: 28px; display: grid; place-items: center;
  border: 1px solid #2a3056; border-radius: 50%; color: var(--muted); cursor: pointer;
}
.controls label:hover { background: #1f2342; }

/* Intro & cards */
.intro { padding: 40px 0; }
.grid-3 {
  display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px;
}
.grid-2 {
  display: grid; grid-template-columns: repeat(2, 1fr); gap: 24px;
}
.card {
  background: var(--surface); border: 1px solid #232844; border-radius: 14px; padding: 20px;
}
.icon, .avatar, .service-image { border-radius: 10px; }
.avatar { width: 96px; height: 96px; object-fit: cover; margin-bottom: 10px; }
.service-image { width: 100%; height: 200px; object-fit: cover; }

/* Lists */
.ticks { list-style: none; padding: 0; margin: 12px 0 0; }
.ticks li { padding-left: 22px; position: relative; margin: 8px 0; color: var(--muted); }
.ticks li::before {
  content: "✔"; position: absolute; left: 0; color: var(--primary);
}

/* Page hero */
.page-hero { padding: 56px 0 20px; text-align: center; }
.page-hero p { color: var(--muted); }

/* CTA band */
.cta-band { padding: 40px 0; text-align: center; }
.cta-band p { color: var(--muted); }

/* Contact */
.contact-grid { padding: 24px 0 60px; }
.contact-form, .contact-info { background: var(--surface); border: 1px solid #232844; border-radius: 14px; padding: 20px; }
.form-field { margin-bottom: 16px; }
label { display: block; margin-bottom: 6px; font-weight: 600; }
input, textarea {
  width: 100%; padding: 10px 12px; background: #0f1429; color: var(--text);
  border: 1px solid #2a3056; border-radius: 10px;
}
input:focus, textarea:focus { outline: 2px solid var(--primary); }

.map { margin-top: 16px; }
.map-note { color: var(--muted); font-size: 0.9rem; }

/* Footer */
.site-footer { border-top: 1px solid #252a45; margin-top: 40px; }
.footer-grid {
  display: grid; grid-template-columns: 2fr 1fr 1fr; gap: 20px; padding: 20px 0;
}
.footer-links { list-style: none; padding: 0; margin: 0; }
.footer-links li { margin: 6px 0; }
.footer-links a { color: var(--text); text-decoration: none; }
.footer-links a:hover { text-decoration: underline; }

.social a {
  display: inline-flex; align-items: center; justify-content: center;
  width: 32px; height: 32px; border: 1px solid #2a3056; border-radius: 50%;
  color: var(--muted); text-decoration: none; margin-right: 8px;
}
.social a:hover { background: #1f2342; color: var(--text); }

.copyright {
  border-top: 1px solid #252a45;
  text-align: center; padding: 12px; color: var(--muted);
}

/* Responsive */
@media (max-width: 900px) {
  .grid-3 { grid-template-columns: 1fr 1fr; }
  .footer-grid { grid-template-columns: 1fr 1fr; }
  .slides .slide img { height: 280px; }
}
@media (max-width: 640px) {
  .grid-3, .grid-2 { grid-template-columns: 1fr; }
  .site-nav ul { display: none; }
  .site-nav.open ul { display: flex; flex-direction: column; gap: 8px; padding: 12px; }
  .nav-toggle { display: inline-block; }
  .hero h1 { font-size: 2rem; }
}

├── images/
│   ├── logo.png

│   ├── slider1.jpg

│   ├── slider2.jpg

│   └── slider3.jpg

└── README.txt
https://sokonyene.github.io/shami-gym/

