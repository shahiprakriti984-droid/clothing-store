<!doctype html>
<html lang="ne">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>स्माइल गर्ल्स - Girls' Clothing Store, Nepal</title>
  <meta name="description" content="Smiles Girls — Trendy and comfortable clothing for girls in Nepal. New arrivals, traditional wear, and everyday styles." />

  <!-- Google font -->
  <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --accent:#f06292;
      --muted:#6b7280;
      --bg:#fbfbfd;
      --card:#ffffff;
      --radius:12px;
      --max-width:1100px;
      font-family: 'Nunito', system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:linear-gradient(180deg,#fff 0%, #fbfbfd 100%);
      color:#111827;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.4;
    }
    header{
      background:var(--card);
      position:sticky;
      top:0;
      z-index:10;
      border-bottom:1px solid #eee;
      backdrop-filter: blur(6px);
    }
    .container{
      max-width:var(--max-width);
      margin:0 auto;
      padding:1rem;
    }
    .topbar{
      display:flex;
      gap:1rem;
      align-items:center;
      justify-content:space-between;
    }
    .brand{
      display:flex;
      gap:.75rem;
      align-items:center;
      font-weight:700;
      color:var(--accent);
      font-size:1.15rem;
      text-decoration:none;
    }
    .brand .logo{
      width:44px;height:44px;border-radius:10px;background:linear-gradient(135deg,#ffd1e6,#ffcee3);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800;
      box-shadow:0 2px 8px rgba(0,0,0,0.06);
    }
    nav{
      display:flex;
      gap:1rem;
      align-items:center;
    }
    .btn{
      background:var(--accent);
      color:white;
      padding:.55rem .9rem;
      border-radius:999px;
      border:0;
      cursor:pointer;
      font-weight:600;
    }
    .search{
      margin-left:1rem;
      display:flex;
      align-items:center;
      gap:.5rem;
      background:#f8fafc;
      padding:.35rem .5rem;
      border-radius:999px;
      border:1px solid #eee;
    }
    .hero{
      display:grid;
      grid-template-columns:1fr 420px;
      gap:1.25rem;
      align-items:center;
      padding:2rem 0;
    }
    .hero-card{
      background:var(--card);
      padding:1.25rem;
      border-radius:var(--radius);
      box-shadow:0 8px 30px rgba(8,15,30,0.04);
    }
    .hero h1{
      margin:0 0 .5rem 0;
      font-size:1.9rem;
      line-height:1.05;
      color:#0f172a;
    }
    .hero p{color:var(--muted); margin:0 0 1rem 0}
    .cta-row{display:flex;gap:.75rem;flex-wrap:wrap}
    .features{display:flex;gap:.75rem;margin-top:1rem;flex-wrap:wrap}
    .feature{background:#fff;padding:.5rem .6rem;border-radius:10px;border:1px solid #f1f5f9;font-size:.9rem;color:var(--muted)}
    /* categories & products */
    .grid{
      display:grid;
      gap:1rem;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    }
    .category, .product{
      background:var(--card);
      border-radius:12px;
      padding:0.75rem;
      border:1px solid #f1f5f9;
      text-align:center;
    }
    .category img, .product img{width:100%;height:160px;object-fit:cover;border-radius:8px}
    .category h3{margin:.6rem 0 0 0;font-size:1rem}
    .product .title{font-weight:600;margin:.6rem 0}
    .price{color:var(--accent);font-weight:700}
    .old{color:#9ca3af;text-decoration:line-through;margin-left:.5rem;font-weight:500}
    footer{padding:2rem 0 3rem 0;color:#374151}
    .footer-grid{display:grid;grid-template-columns:1fr 1fr;gap:1rem;max-width:var(--max-width);margin:1rem auto 0 auto}
    @media (max-width:900px){
      .hero{grid-template-columns:1fr; padding:1rem 0}
      nav{display:none}
      .topbar{gap:.5rem}
      .footer-grid{grid-template-columns:1fr}
    }
    /* simple product badges */
    .badge{display:inline-block;background:#fff;padding:.25rem .5rem;border-radius:999px;border:1px solid #fee2e9;color:var(--accent);font-weight:700;font-size:.8rem}
    .small{font-size:.9rem;color:#6b7280}
    .socials{display:flex;gap:.5rem;align-items:center}
    a{text-decoration:none;color:inherit}
    .newsletter{display:flex;gap:.5rem}
    .newsletter input{padding:.6rem .65rem;border-radius:999px;border:1px solid #e6e9ee;flex:1}
    .map{height:160px;border-radius:8px;border:1px solid #eee;overflow:hidden}
  </style>
</head>
<body>
  <header>
    <div class="container topbar" role="banner">
      <a class="brand" href="#">
        <div class="logo" aria-hidden="true">SG</div>
        <div>
          <div>स्माइल गर्ल्स</div>
          <div style="font-size:.8rem;color:var(--muted)">Girls' Clothing • Kathmandu, Nepal</div>
        </div>
      </a>

      <nav aria-label="Primary navigation">
        <a href="#categories" class="small">Categories</a>
        <a href="#new-arrivals" class="small">New Arrivals</a>
        <a href="#best-sellers" class="small">Best Sellers</a>
        <a href="#contact" class="small">Contact</a>
      </nav>

      <div style="display:flex;align-items:center">
        <div class="search" role="search" aria-label="Site search">
          <input aria-label="Search products" placeholder="Search dresses, kurta, tops..." style="border:0;background:transparent;outline:none;font-size:.95rem">
        </div>
        <button class="btn" style="margin-left:.75rem">Shop Now</button>
      </div>
    </div>
  </header>

  <main class="container" role="main" aria-labelledby="main-title">
    <section class="hero" aria-label="Hero">
      <div class="hero-card" id="main-title">
        <h1>Trendy & Comfortable Clothing for Girls — Nepal Collection</h1>
        <p>From traditional Nepali kurta designs to everyday casual wear — curated for girls aged 3–18. Sustainable fabrics, local tailoring, and sizes that fit.</p>

        <div class="cta-row">
          <a class="btn" href="#new-arrivals">New Arrivals</a>
          <a href="#categories" style="align-self:center;color:var(--accent);font-weight:700">Browse Categories →</a>
        </div>

        <div class="features" aria-hidden="true">
          <div class="feature">Free delivery in Kathmandu over NPR 2,000</div>
          <div class="feature">Cash on delivery • eSewa • IME Pay</div>
          <div class="feature">Size guide & easy returns (7 days)</div>
        </div>
      </div>

      <aside class="hero-card" aria-label="Highlights">
        <h3 style="margin-top:0">Featured: Lokta Print Kurta</h3>
        <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?auto=format&fit=crop&w=800&q=60" alt="Featured girls kurta" style="width:100%;border-radius:8px;height:220px;object-fit:cover;margin:0.6rem 0">
        <p class="small">Hand-block printed motifs with comfortable cotton. Limited Nepali edition.</p>
        <div style="display:flex;gap:.6rem;margin-top:1rem">
          <span class="badge">Limited</span>
          <span class="small" style="margin-left:auto">Starts NPR 1,490</span>
        </div>
      </aside>
    </section>

    <section id="categories" style="padding:1.5rem 0">
      <h2 style="margin:.2rem 0 1rem 0">Popular Categories</h2>
      <div class="grid" aria-label="Product categories">
        <a class="category" href="#" aria-labelledby="cat1">
          <img src="https://images.unsplash.com/photo-1542831371-d531d36971e6?auto=format&fit=crop&w=800&q=60" alt="">
          <h3 id="cat1">Dresses & Frocks</h3>
          <div class="small">Playful prints & party wear</div>
        </a>

        <a class="category" href="#" aria-labelledby="cat2">
          <img src="https://images.unsplash.com/photo-1520975862033-9ee8e089f5c6?auto=format&fit=crop&w=800&q=60" alt="">
          <h3 id="cat2">Kurta & Traditional</h3>
          <div class="small">Classic Nepali & contemporary blends</div>
        </a>

        <a class="category" href="#" aria-labelledby="cat3">
          <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=800&q=60" alt="">
          <h3 id="cat3">Tops & Tees</h3>
          <div class="small">Everyday comfort</div>
        </a>

        <a class="category" href="#" aria-labelledby="cat4">
          <img src="https://images.unsplash.com/photo-1542060749-15d4b6c7c9d6?auto=format&fit=crop&w=800&q=60" alt="">
          <h3 id="cat4">Winter Essentials</h3>
          <div class="small">Warm layers for chilly Nepali winters</div>
        </a>
      </div>
    </section>

    <section id="new-arrivals" style="padding:1.5rem 0">
      <h2 style="margin:.2rem 0 1rem 0">New Arrivals</h2>
      <div class="grid" aria-live="polite">
        <article class="product" aria-labelledby="p1">
          <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title" id="p1">Floral Summer Dress</div>
          <div class="small">Soft cotton — sizes 3-12</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 1,290</span>
            <span class="old">NPR 1,590</span>
          </div>
        </article>

        <article class="product" aria-labelledby="p2">
          <img src="https://images.unsplash.com/photo-1531853125190-2f5b9a6f0b1d?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title" id="p2">Kids Knit Sweater</div>
          <div class="small">Warm & cozy</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 1,490</span>
          </div>
        </article>

        <article class="product" aria-labelledby="p3">
          <img src="https://images.unsplash.com/photo-1520975698513-532d9f8b0c6d?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title" id="p3">Printed Kurta Set</div>
          <div class="small">Traditional prints, modern cuts</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 2,350</span>
          </div>
        </article>

        <article class="product" aria-labelledby="p4">
          <img src="https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title" id="p4">Denim Skirt</div>
          <div class="small">Everyday casual</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 990</span>
          </div>
        </article>
      </div>
    </section>

    <section id="best-sellers" style="padding:1.5rem 0">
      <h2 style="margin:.2rem 0 1rem 0">Best Sellers</h2>
      <div class="grid">
        <article class="product">
          <img src="https://images.unsplash.com/photo-1472417583565-62e7bdeda490?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title">Party Sequined Frock</div>
          <div class="small">Perfect for birthdays</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 1,990</span>
          </div>
        </article>

        <article class="product">
          <img src="https://images.unsplash.com/photo-1485965120184-e220f721d03e?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title">Everyday Leggings</div>
          <div class="small">Stretchable & durable</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 490</span>
          </div>
        </article>

        <article class="product">
          <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title">Handloom Kurta</div>
          <div class="small">Local artisans</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 2,750</span>
          </div>
        </article>

        <article class="product">
          <img src="https://images.unsplash.com/photo-1534751516642-a1af1ef9eac9?auto=format&fit=crop&w=800&q=60" alt="">
          <div class="title">Rainproof Jacket</div>
          <div class="small">Lightweight for monsoon</div>
          <div style="margin-top:.6rem">
            <span class="price">NPR 1,690</span>
          </div>
        </article>
      </div>
    </section>

    <section id="contact" style="padding:1.5rem 0">
      <h2 style="margin:.2rem 0 1rem 0">Contact & Store Info</h2>
      <div class="grid" style="align-items:start">
        <div style="background:var(--card);padding:1rem;border-radius:12px;border:1px solid #f1f5f9">
          <h3 style="margin-top:0">Visit Us</h3>
          <p class="small">Kumaripati, Lalitpur, Kathmandu<br>Open: Mon–Sat 10:00–19:00</p>
          <p class="small">Phone: +977 9801-XXXXXX • Email: hello@smilegirls.np</p>
          <div style="margin-top:1rem">
            <strong>Payment:</strong>
            <div class="small">eSewa • IME Pay • Cash on Delivery</div>
          </div>
        </div>

        <div style="background:var(--card);padding:1rem;border-radius:12px;border:1px solid #f1f5f9">
          <h3 style="margin-top:0">Stay in touch</h3>
          <p class="small">Subscribe for offers, new collections, and Nepali festive discounts.</p>
          <form class="newsletter" onsubmit="event.preventDefault();alert('Thank you for subscribing!');" aria-label="Newsletter signup">
            <input type="email" required placeholder="Your email address" aria-label="Email address">
            <button class="btn" type="submit">Subscribe</button>
          </form>

          <div style="margin-top:1rem" class="socials" aria-hidden="true">
            <a href="#" aria-label="Facebook">Facebook</a>
            <a href="#" aria-label="Instagram">Instagram</a>
            <a href="#" aria-label="TikTok">TikTok</a>
          </div>
        </div>

        <div class="map" style="grid-column:1 / -1;margin-top:.8rem">
          <!-- Replace with an embedded map if desired -->
          <iframe title="Store location map" src="https://www.google.com/maps/embed?pb=!1m18" style="border:0;width:100%;height:100%" loading="lazy"></iframe>
        </div>
      </div>
    </section>
  </main>

  <footer aria-label="Footer">
    <div class="container">
      <div style="display:flex;align-items:center;justify-content:space-between;gap:1rem;flex-wrap:wrap">
        <div style="display:flex;gap:.75rem;align-items:center">
          <div class="logo" style="width:44px;height:44px;border-radius:8px">SG</div>
          <div>
            <div style="font-weight:700">स्माइल गर्ल्स</div>
            <div class="small">Handpicked styles for young girls in Nepal</div>
          </div>
        </div>

        <div class="small">© <span id="year"></span> Smiles Girls • Made with love in Nepal</div>
      </div>

      <div class="footer-grid" style="margin-top:1.25rem">
        <div>
          <h4 style="margin:0 0 .5rem 0">Customer Care</h4>
          <ul style="padding-left:1rem;margin:0;color:var(--muted)">
            <li>Shipping & Returns</li>
            <li>Size Guide</li>
            <li>Payment Options</li>
            <li>Contact Support</li>
          </ul>
        </div>

        <div>
          <h4 style="margin:0 0 .5rem 0">Policies</h4>
          <ul style="padding-left:1rem;margin:0;color:var(--muted)">
            <li>Privacy Policy</li>
            <li>Terms of Service</li>
            <li>Refund Policy</li>
          </ul>
        </div>
      </div>
    </div>
  </footer>

  <script>
    // small helper: set year and keyboard-accessible focus ring
    document.getElementById('year').textContent = new Date().getFullYear();

    // basic keyboard a11y: allow Enter on category cards
    document.querySelectorAll('.category, .product').forEach(el=>{
      el.setAttribute('tabindex','0');
      el.addEventListener('keypress', (e)=>{
        if(e.key === 'Enter') {
          const link = el.querySelector('a') || el;
          link.click?.();
        }
      });
    });
  </script>
</body>
</html>
