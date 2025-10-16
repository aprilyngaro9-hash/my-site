<DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Aprilyn Garo | bread and pastry product</title>
  <style>
body 
    {
      background: #ffe4ec;
      font-family: "Segoe UI", Arial, sans-serif;
      margin: 0;
      color: #3a2e2e;
      display: flex;
      min-height: 100vh;
      flex-direction: column;
    }
    header {
      background: #ffb6d5;
      padding: 2rem 1rem 1rem 1rem;
      text-align: center;
      border-bottom: 2px solid #ff8cb7;
    }
    header h1 {
      margin: 0;
      font-size: 2.2rem;
      letter-spacing: 1px;
    }
    header p.title-sub {
      margin: 0.4rem 0 0 0;
      font-size: 1.1rem;
      font-weight: 600;
      color: #5a2334;
      text-transform: none;
    }
    nav {
      margin-top: 1rem;
    }
    nav a {
      color: #fff;
      background: #ff8cb7;
      padding: 0.45rem 0.9rem;
      margin: 0 0.3rem;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: background 0.2s;
      font-size: 0.95rem;
    }
    nav a:hover {
      background: #ff5b9f;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1.5rem;
      background: #fffafc;
      border-radius: 18px;
      box-shadow: 0 4px 16px 0 #ffd6eb4d;
      flex: 1 0 auto;
      width: calc(100% - 2rem);
    }
    section {
      margin: 1.2rem 0;
    }
    h2 {
      color: #d72660;
      margin-bottom: 0.6rem;
    }
    .intro {
      font-size: 1rem;
      color: #3a2e2e;
      margin-bottom: 0.8rem;
    }
    .cta {
      display: inline-block;
      background: #ff8cb7;
      color: #fff;
      padding: 0.5rem 1rem;
      border-radius: 22px;
      text-decoration: none;
      font-weight: 700;
      transition: background 0.2s;
      margin-top: 0.5rem;
    }
    .cta:hover {
      background: #ff5b9f;
    }
    ul.products-list {
      list-style: none;
      padding-left: 0;
      margin-top: 0.5rem;
    }
    ul.products-list li {
      margin: 0.8rem 0;
      font-size: 1.05rem;
      color: #b94b74;
      font-weight: 500;
      background: #ffe4ec;
      padding: 0.9rem 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 8px 0 #ffd6eb3d;
    }
    .product-title {
      font-weight: bold;
      color: #d72660;
      font-size: 1.05rem;
      display: block;
      margin-bottom: 0.2rem;
    }
    .product-desc {
      font-weight: normal;
      color: #3a2e2e;
      font-size: 0.98rem;
      margin-left: 0.3rem;
    }
    footer {
      text-align: center;
      padding: 1rem 0.5rem;
      color: #6a2b42;
      font-size: 0.95rem;
      background: transparent;
      border-top: 1px solid #ffd6eb6b;
    }
    footer .email {
      display: block;
      margin-top: 0.4rem;
      color: #5a2334;
      font-weight: 700;
      text-decoration: none;
    }
@media (max-width: 600px) {
        main {
        margin: 1rem;
        padding: 1rem;
      }
      header h1 { font-size: 1.8rem; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Aprilyn Garo</h1>
    <p class="title-sub">bread and pastry product</p>
    <nav>
      <a href="#about">About</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About</h2>
      <p class="intro">I love making delicious bread and pastries and sharing them with others.</p>
      <a class="cta" href="#products">Explore here</a>
    </section>

<section id="products">
      <h2>Products</h2>
      <ul class="products-list">
        <li>
          <span class="product-title">Cinnamon Roll</span>
          <span class="product-desc">Warm, soft roll swirled with cinnamon and a light glaze.</span>
        </li>
        <li>
          <span class="product-title">Dinner Roll</span>
          <span class="product-desc">Small, fluffy rolls brushed with butter for a tender bite.</span>
        </li>
        <li>
          <span class="product-title">Brownies</span>
          <span class="product-desc">Dense, chocolatey squares with a rich, fudgy center.</span>
        </li>
        <li>
          <span class="product-title">Bento Cake</span>
          <span class="product-desc">Miniature cakes decorated for gifting and sharing.</span>
        </li>
        <li>
          <span class="product-title">Petit Fours</span>
          <span class="product-desc">Tiny, elegant bites finished with colorful icing.</span>
        </li>
      </ul>
    </section>

<section id="contact">
      <h2>Contact</h2>
      <p class="intro">Want to order or collaborate? Reach out via email below.</p>
      <a class="cta" href="mailto:aprilyngaro9@gmail.com">Email Me</a>
    </section>
  </main>

 <footer>
    designed for bread and pastry product
    <a class="email" href="mailto:aprilyngaro9@gmail.com">aprilyngaro9@gmail.com</a>
  </footer>
</body>
</html>

