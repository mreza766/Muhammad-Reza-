<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Saya - GitHub Pages</title>
    <style>
        :root{--p:#007bff;--d:#333;--l:#f8f9fa;--s:#28a745}
        *{margin:0;padding:0;box-sizing:border-box}
        body{font-family:system-ui,line-height:1.6;color:var(--d);overflow-x:hidden}
        header{position:fixed;top:0;left:0;right:0;background:rgba(255,255,255,.95);backdrop-filter:blur(10px);z-index:100;padding:1rem 0;box-shadow:0 2px 20px rgba(0,0,0,.1)}
        nav{max-width:1200px;margin:0 auto;display:flex;justify-content:space-between;align-items:center;padding:0 2rem}
        .logo{font-weight:700;font-size:1.5rem;color:var(--p)}
        .nav-links{display:flex;gap:2rem;list-style:none}
        .nav-links a{color:var(--d);text-decoration:none;font-weight:500;transition:color .3s}
        .nav-links a:hover{color:var(--p)}
        .hero{min-height:100vh;background:linear-gradient(135deg,var(--p),#6610f2);display:flex;align-items:center;justify-content:center;text-align:center;color:white;padding:0 2rem}
        .hero-content{max-width:800px}
        .hero h1{font-size:clamp(3rem,8vw,6rem);margin-bottom:1rem;text-shadow:2px 2px 10px rgba(0,0,0,.3)}
        .hero p{font-size:1.3rem;margin-bottom:2rem;opacity:.9}
        .cta{background:var(--s);color:white;padding:1rem 2rem;border-radius:50px;font-size:1.1rem;font-weight:600;text-decoration:none;display:inline-block;box-shadow:0 10px 30px rgba(40,167,69,.4);transition:all .3s}
        .cta:hover{transform:translateY(-3px);box-shadow:0 15px 40px rgba(40,167,69,.5)}
        .features{padding:100px 2rem;background:var(--l)}
        .container{max-width:1200px;margin:0 auto}
        .features h2{text-align:center;font-size:2.5rem;margin-bottom:4rem;color:var(--d)}
        .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:2rem}
        .card{background:white;padding:2.5rem;border-radius:20px;box-shadow:0 10px 40px rgba(0,0,0,.1);text-align:center;transition:transform .3s}
        .card:hover{transform:translateY(-10px)}
        .card h3{font-size:1.5rem;margin-bottom:1rem;color:var(--p)}
        footer{padding:3rem 2rem;background:var(--d);color:white;text-align:center}
        @media(max-width:768px){.nav-links{display:none}}
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Portfolio</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Halo Dunia! 👋</h1>
            <p>Website pertama saya live pakai GitHub Pages - GRATIS selamanya!</p>
            <a href="#features" class="cta">Lihat Fitur</a>
        </div>
    </section>

    <section class="features" id="features">
        <div class="container">
            <h2>Kenapa GitHub Pages? 🚀</h2>
            <div class="grid">
                <div class="card">
                    <h3>⚡ Super Cepat</h3>
                    <p>CDN global, loading <1 detik di seluruh dunia</p>
                </div>
                <div class="card">
                    <h3>💰 100% Gratis</h3>
                    <p>No hosting fee, unlimited bandwidth forever</p>
                </div>
                <div class="card">
                    <h3>🔒 HTTPS Gratis</h3>
                    <p>SSL otomatis, aman dan profesional</p>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact">
        <p>&copy; 2024 Portfolio Saya. Dibuat dengan ❤️ dan GitHub Pages</p>
    </footer>
</body>
</html>
