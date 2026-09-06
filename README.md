<!DOCTYPE html>

<html lang="pt-BR">
<head>
  <!-- =========================
       CONFIGURAÇÕES / ANALYTICS
       ========================= -->

  <!-- Google Analytics 4 -->

  <script async src="https://www.googletagmanager.com/gtag/js?id=G-K5H9RC0MXK"></script>

  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'G-K5H9RC0MXK');
  </script>

  <!-- Google AdSense -->

 <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-9815147455829969"
     crossorigin="anonymous"></script>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Corujão dos Bruxos | Jogos, Reviews, Guias, Notícias e Dicas</title>

<meta
name="description"
content="Corujão dos Bruxos: jogos, reviews, guias, requisitos, dicas, builds, códigos, notícias e informações do mundo gamer."

>

<meta
name="keywords"
content="jogos, games, guias de jogos, notícias gamer, códigos, builds, requisitos de jogos, jogos grátis, esports"

>

  <meta name="robots" content="index, follow">

  <link rel="canonical" href="https://corujaodosbruxos.com/">

  <!-- Fontes -->

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link
    href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@300;400;600;700&family=Yellowtail&display=swap"
    rel="stylesheet"
  >

  <!-- Font Awesome -->

  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
  >

  <style>
    /* =========================
       VARIÁVEIS
       ========================= */

    :root {
      --bg-principal: #0A0A0A;
      --bg-card: #141414;
      --bg-card-hover: #1E1E1E;

      --cor-primaria: #E31B23;
      --cor-primaria-hover: #b81219;

      --cor-destaque: #FFD700;
      --cor-destaque-hover: #e6c200;

      --texto-branco: #FFFFFF;
      --texto-cinza: #A0A0A0;
      --texto-claro: #CCCCCC;

      --verde: #25D366;

      --fonte-titulo: 'Bebas Neue', sans-serif;
      --fonte-corpo: 'Montserrat', sans-serif;
      --fonte-cursiva: 'Yellowtail', cursive;

      --transicao: all .3s cubic-bezier(.25,.8,.25,1);
    }

    /* =========================
       RESET
       ========================= */

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: var(--bg-principal);
      color: var(--texto-branco);
      font-family: var(--fonte-corpo);
      line-height: 1.6;
      overflow-x: hidden;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    button,
    input,
    select {
      font-family: var(--fonte-corpo);
    }

    button {
      cursor: pointer;
      border: 0;
      outline: 0;
    }

    img {
      max-width: 100%;
    }

    .container {
      width: 100%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }

    .hidden {
      display: none !important;
    }

    .muted {
      color: var(--texto-cinza);
    }

    /* =========================
       BOTÕES
       ========================= */

    .btn {
      display: inline-block;
      padding: 12px 24px;
      border-radius: 5px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1px;
      transition: var(--transicao);
    }

    .btn-primary {
      background: var(--cor-primaria);
      color: #fff;
    }

    .btn-primary:hover {
      background: var(--cor-primaria-hover);
      transform: translateY(-2px);
    }

    .btn-gold {
      background: var(--cor-destaque);
      color: #000;
    }

    .btn-gold:hover {
      background: var(--cor-destaque-hover);
      transform: translateY(-2px);
    }

    .btn-secondary {
      background: transparent;
      border: 1px solid rgba(255,255,255,.15);
      color: #fff;
    }

    .btn-secondary:hover {
      border-color: var(--cor-destaque);
      color: var(--cor-destaque);
    }

    /* =========================
       TEXTOS
       ========================= */

    .script {
      font-family: var(--fonte-cursiva);
      color: var(--cor-destaque);
      font-size: 2rem;
    }

    .section {
      padding: 100px 0 60px;
    }

    .section-header {
      text-align: center;
      margin-bottom: 42px;
    }

    .section-header h2 {
      font-family: var(--fonte-titulo);
      font-size: 3.5rem;
      letter-spacing: 2px;
    }

    .section-header p:last-child {
      color: var(--texto-cinza);
      max-width: 760px;
      margin: 10px auto 0;
    }

    /* =========================
       HEADER
       ========================= */

    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 1000;

      background: rgba(10,10,10,.94);
      backdrop-filter: blur(10px);

      border-bottom: 1px solid rgba(255,255,255,.06);

      height: 80px;
    }

    .nav {
      height: 80px;

      display: flex;
      align-items: center;
      justify-content: space-between;

      gap: 20px;
    }

    .logo {
      font-family: var(--fonte-titulo);
      font-size: 2rem;
      letter-spacing: 2px;
      white-space: nowrap;
    }

    .logo span {
      color: var(--cor-primaria);
    }

    .nav-menu {
      display: flex;
      gap: 22px;
      list-style: none;
      align-items: center;
    }

    .nav-menu a {
      font-size: .85rem;
      font-weight: 700;
      text-transform: uppercase;
      color: var(--texto-cinza);
      transition: var(--transicao);
      cursor: pointer;
    }

    .nav-menu a:hover,
    .nav-menu a.active {
      color: var(--cor-destaque);
    }

    /* =========================
       HOME / HERO
       ========================= */

    .hero {
      min-height: 680px;

      padding-top: 80px;

      display: flex;
      align-items: center;
      text-align: center;

      background:
        linear-gradient(
          rgba(10,10,10,.68),
          rgba(10,10,10,.94)
        ),
        url('imagens/hero-bg.jpg') center/cover;
    }

    .hero-content {
      max-width: 850px;
      margin: auto;
    }

    .hero h1 {
      font-family: var(--fonte-titulo);
      font-size: clamp(3.5rem, 8vw, 6rem);
      line-height: 1;
      letter-spacing: 3px;
    }

    .hero p {
      color: #ccc;
      font-size: 1.1rem;
      margin: 20px auto 28px;
      max-width: 760px;
    }

    .hero-buttons {
      display: flex;
      justify-content: center;
      gap: 14px;
      flex-wrap: wrap;
    }

    /* =========================
       GRIDS
       ========================= */

    .stats-grid,
    .cards-grid,
    .category-grid,
    .article-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 22px;
    }

    .stats-grid {
      margin-top: -55px;
      position: relative;
    }

    /* =========================
       CARDS
       ========================= */

    .stat-card,
    .game-card,
    .category-card,
    .content-card {
      background: var(--bg-card);
      border: 1px solid rgba(255,255,255,.06);
      border-radius: 12px;
      overflow: hidden;
    }

    .stat-card {
      padding: 26px;
      text-align: center;
    }

    .stat-card i {
      font-size: 2rem;
      color: var(--cor-destaque);
      margin-bottom: 10px;
    }

    .stat-card h3,
    .category-card h3 {
      font-family: var(--fonte-titulo);
      font-size: 1.8rem;
    }

    .category-card {
      padding: 25px;
      transition: var(--transicao);
    }

    .category-card:hover,
    .game-card:hover {
      transform: translateY(-5px);
      border-color: var(--cor-destaque);
    }

    .category-card i {
      font-size: 2rem;
      color: var(--cor-primaria);
      margin-bottom: 12px;
    }

    /* =========================
       JOGOS
       ========================= */

    .game-card {
      transition: var(--transicao);
    }

    .game-img {
      height: 190px;
      position: relative;
      overflow: hidden;
      background: #0d0d0d;
    }

    .game-img img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: var(--transicao);
      display: block;
    }

    .game-card:hover .game-img img {
      transform: scale(1.05);
    }

    .badge {
      position: absolute;
      top: 12px;
      right: 12px;

      background: var(--cor-primaria);

      padding: 5px 10px;

      border-radius: 20px;

      font-size: .72rem;
      font-weight: 700;
    }

    .game-body {
      padding: 20px;
    }

    .game-body h3 {
      font-family: var(--fonte-titulo);
      font-size: 1.9rem;
    }

    .game-meta {
      display: flex;
      flex-wrap: wrap;
      gap: 7px;
      margin: 12px 0;
    }

    .pill {
      border: 1px solid rgba(255,255,255,.12);
      border-radius: 20px;

      padding: 4px 9px;

      color: #ccc;
      font-size: .72rem;
    }

    .game-body .btn {
      margin-top: 10px;
    }

    /* =========================
       BUSCA
       ========================= */

    .toolbar {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      justify-content: center;
      margin-bottom: 30px;
    }

    .toolbar input,
    .toolbar select {
      background: #101010;

      border: 1px solid rgba(255,255,255,.15);

      color: #fff;

      padding: 12px 14px;

      border-radius: 6px;

      min-width: 220px;
    }

    .toolbar input:focus,
    .toolbar select:focus {
      border-color: var(--cor-destaque);
      outline: none;
    }

    /* =========================
       CONTENT
       ========================= */

    .content-card {
      padding: 26px;
    }

    .content-card h3 {
      font-family: var(--fonte-titulo);
      font-size: 1.7rem;
      margin-bottom: 8px;
    }

    .content-card a {
      color: var(--cor-destaque);
      font-weight: 700;
    }

    /* =========================
       DETALHES DOS JOGOS
       ========================= */

    .game-detail {
      display: none;
    }

    .game-detail.active {
      display: block;
      animation: fadeIn .35s ease;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(10px);
      }

      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .detail-hero {
      background: var(--bg-card);

      padding: 35px;

      border-radius: 12px;

      border: 1px solid rgba(255,255,255,.06);

      margin-bottom: 25px;
    }

    .detail-hero img {
      width: 100%;
      max-height: 360px;

      object-fit: cover;

      border-radius: 10px;

      margin-bottom: 22px;
    }

    .detail-hero h2 {
      font-family: var(--fonte-titulo);
      font-size: 4rem;
      line-height: 1;
    }

    .detail-columns {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 22px;
    }

    .info-list {
      list-style: none;
    }

    .info-list li {
      padding: 9px 0;

      border-bottom: 1px solid rgba(255,255,255,.07);

      color: #ccc;
    }

    .info-list strong {
      color: #fff;
    }

    .game-detail-footer {
      margin-top: 25px;
      text-align: center;
    }

    /* =========================
       NEWSLETTER
       ========================= */

    .newsletter {
      background: var(--bg-card);

      padding: 38px;

      border-radius: 12px;

      border: 1px solid rgba(255,255,255,.06);

      display: grid;

      grid-template-columns: 1.2fr 1fr;

      gap: 30px;

      align-items: center;
    }

    .form {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .form input,
    .form select {
      background: #0d0d0d;

      color: #fff;

      border: 1px solid rgba(255,255,255,.12);

      padding: 13px;

      border-radius: 5px;
    }

    .form input:focus,
    .form select:focus {
      border-color: var(--cor-destaque);
      outline: none;
    }

    /* =========================
       FOOTER
       ========================= */

    footer {
      background: #050505;

      padding: 50px 0 25px;

      border-top: 1px solid rgba(255,255,255,.06);
    }

    .footer-grid {
      display: grid;

      grid-template-columns: 2fr 1fr 1fr;

      gap: 30px;
    }

    .footer-links {
      list-style: none;

      color: var(--texto-cinza);

      line-height: 2;
    }

    .footer-links a:hover {
      color: var(--cor-destaque);
    }

    /* =========================
       WHATSAPP
       ========================= */

    .whatsapp {
      position: fixed;

      right: 25px;
      bottom: 25px;

      width: 58px;
      height: 58px;

      border-radius: 50%;

      background: var(--verde);

      display: flex;
      align-items: center;
      justify-content: center;

      font-size: 1.8rem;

      z-index: 999;

      box-shadow: 0 5px 20px rgba(0,0,0,.4);

      transition: var(--transicao);
    }

    .whatsapp:hover {
      transform: scale(1.08);
    }

    /* =========================
       MENSAGEM SEM RESULTADOS
       ========================= */

    .no-results {
      display: none;

      text-align: center;

      padding: 40px 20px;

      color: var(--texto-cinza);
    }

    .no-results i {
      font-size: 3rem;

      color: var(--cor-destaque);

      margin-bottom: 15px;
    }

    /* =========================
       RESPONSIVO
       ========================= */

    @media (max-width: 900px) {

      .nav-menu {
        display: none;
      }

      .detail-columns,
      .newsletter,
      .footer-grid {
        grid-template-columns: 1fr;
      }

      .section {
        padding-top: 90px;
      }

      .hero {
        min-height: 620px;
      }

      .stats-grid {
        margin-top: -30px;
      }

    }

    @media (max-width: 600px) {

      .container {
        padding: 0 15px;
      }

      header,
      .nav {
        height: 70px;
      }

      .logo {
        font-size: 1.5rem;
      }

      header .btn {
        padding: 9px 12px;
        font-size: .7rem;
      }

      .hero {
        padding-top: 70px;
        min-height: 580px;
      }

      .hero h1 {
        font-size: 3.4rem;
      }

      .hero p {
        font-size: .95rem;
      }

      .section-header h2 {
        font-size: 2.8rem;
      }

      .detail-hero h2 {
        font-size: 3rem;
      }

      .toolbar input,
      .toolbar select {
        width: 100%;
        min-width: 0;
      }

      .whatsapp {
        right: 15px;
        bottom: 15px;
      }

    }
  </style>

</head>

<body>

  <!-- =========================
       HEADER
       ========================= -->

  <header>

```
<div class="container nav">

  <a
    class="logo"
    href="#home"
    onclick="navigateTo('home')"
  >
    <i class="fa-solid fa-owl"></i>
    CORUJÃO <span>DOS BRUXOS</span>
  </a>

  <ul class="nav-menu">

    <li>
      <a
        class="nav-link active"
        href="#home"
        onclick="navigateTo('home')"
      >
        Home
      </a>
    </li>

    <li>
      <a
        class="nav-link"
        href="#jogos"
        onclick="navigateTo('jogos')"
      >
        Jogos
      </a>
    </li>

    <li>
      <a
        class="nav-link"
        href="#guias"
        onclick="navigateTo('guias')"
      >
        Guias
      </a>
    </li>

    <li>
      <a
        class="nav-link"
        href="#noticias"
        onclick="navigateTo('noticias')"
      >
        Notícias
      </a>
    </li>

    <li>
      <a
        class="nav-link"
        href="#sobre"
        onclick="navigateTo('sobre')"
      >
        Sobre
      </a>
    </li>

  </ul>

  <a
    class="btn btn-primary"
    href="#novidades"
    onclick="navigateTo('novidades')"
  >
    Newsletter
  </a>

</div>
```

  </header>

  <main>

```
<!-- =========================
     HOME
     ========================= -->

<section
  id="home"
  class="page section"
  style="padding-top:80px"
>

  <div class="hero">

    <div class="container hero-content">

      <div class="script">
        O portal gamer dos Bruxos
      </div>

      <h1>
        JOGOS, GUIAS &amp; NOTÍCIAS
      </h1>

      <p>
        Encontre informações úteis sobre seus jogos favoritos:
        requisitos, plataformas, dicas, builds, códigos,
        guias, novidades e muito mais.
      </p>

      <div class="hero-buttons">

        <a
          class="btn btn-primary"
          href="#jogos"
          onclick="navigateTo('jogos')"
        >
          Explorar Jogos
        </a>

        <a
          class="btn btn-gold"
          href="#guias"
          onclick="navigateTo('guias')"
        >
          Ver Guias
        </a>

      </div>

    </div>

  </div>


  <div class="container">

    <!-- ESTATÍSTICAS -->

    <div class="stats-grid">

      <div class="stat-card">

        <i class="fa-solid fa-gamepad"></i>

        <h3>
          Catálogo Gamer
        </h3>

        <p class="muted">
          Jogos organizados por gênero e plataforma.
        </p>

      </div>


      <div class="stat-card">

        <i class="fa-solid fa-book-open"></i>

        <h3>
          Guias Práticos
        </h3>

        <p class="muted">
          Conteúdo pensado para resolver dúvidas reais.
        </p>

      </div>


      <div class="stat-card">

        <i class="fa-solid fa-magnifying-glass"></i>

        <h3>
          Pesquisa Rápida
        </h3>

        <p class="muted">
          Encontre o jogo e a informação que procura.
        </p>

      </div>

    </div>


    <!-- CATEGORIAS -->

    <div
      class="section-header"
      style="margin-top:85px"
    >

      <div class="script">
        Encontre seu próximo assunto
      </div>

      <h2>
        CATEGORIAS
      </h2>

      <p>
        Conteúdo dividido por intenção de busca para facilitar
        a navegação.
      </p>

    </div>


    <div class="category-grid">

      <a
        class="category-card"
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('category_click',{category:'Jogos'})"
      >

        <i class="fa-solid fa-dice"></i>

        <h3>
          Jogos
        </h3>

        <p class="muted">
          Fichas, plataformas, gêneros e informações.
        </p>

      </a>


      <a
        class="category-card"
        href="#guias"
        onclick="navigateTo('guias');trackEvent('category_click',{category:'Guias'})"
      >

        <i class="fa-solid fa-scroll"></i>

        <h3>
          Guias
        </h3>

        <p class="muted">
          Dicas, builds, chefes, mapas e tutoriais.
        </p>

      </a>


      <a
        class="category-card"
        href="#noticias"
        onclick="navigateTo('noticias');trackEvent('category_click',{category:'Noticias'})"
      >

        <i class="fa-solid fa-newspaper"></i>

        <h3>
          Notícias
        </h3>

        <p class="muted">
          Lançamentos, atualizações e novidades.
        </p>

      </a>


      <a
        class="category-card"
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('category_click',{category:'Gratis'})"
      >

        <i class="fa-solid fa-gift"></i>

        <h3>
          Jogos Grátis
        </h3>

        <p class="muted">
          Descubra opções gratuitas e promoções.
        </p>

      </a>

    </div>

  </div>

</section>


<!-- =========================
     JOGOS
     ========================= -->

<section
  id="jogos"
  class="page section container hidden"
>

  <div class="section-header">

    <div class="script">
      Explore o catálogo
    </div>

    <h2>
      JOGOS
    </h2>

    <p>
      Use a busca para encontrar páginas e informações sobre jogos.
    </p>

  </div>


  <!-- FILTROS -->

  <div class="toolbar">

    <input
      id="gameSearch"
      type="search"
      placeholder="Buscar jogo..."
      aria-label="Buscar jogo"
      oninput="filterGames()"
    >

    <select
      id="genreFilter"
      onchange="filterGames()"
      aria-label="Filtrar por gênero"
    >

      <option value="">
        Todos os gêneros
      </option>

      <option value="RPG">
        RPG
      </option>

      <option value="FPS">
        FPS
      </option>

      <option value="Ação">
        Ação
      </option>

      <option value="Estratégia">
        Estratégia
      </option>

    </select>


    <select
      id="platformFilter"
      onchange="filterGames()"
      aria-label="Filtrar por plataforma"
    >

      <option value="">
        Todas as plataformas
      </option>

      <option value="PC">
        PC
      </option>

      <option value="PlayStation">
        PlayStation
      </option>

      <option value="Xbox">
        Xbox
      </option>

      <option value="Mobile">
        Mobile
      </option>

    </select>

  </div>


  <!-- CARDS -->

  <div
    class="cards-grid"
    id="gamesGrid"
  >


    <!-- ELDEN RING -->

    <article
      class="game-card"
      data-game="elden ring"
      data-genre="RPG"
      data-platform="PC PlayStation Xbox"
    >

      <div class="game-img">

        <img
          src="imagens/elden-ring.jpg"
          alt="Elden Ring"
          loading="lazy"
        >

        <span class="badge">
          RPG
        </span>

      </div>


      <div class="game-body">

        <h3>
          Elden Ring
        </h3>

        <p class="muted">
          Guias, builds, chefes, armas, requisitos e informações
          do universo de Elden Ring.
        </p>

        <div class="game-meta">

          <span class="pill">
            PC
          </span>

          <span class="pill">
            PlayStation
          </span>

          <span class="pill">
            Xbox
          </span>

        </div>

        <button
          class="btn btn-primary"
          onclick="openGame('elden-ring')"
        >
          Ver informações
        </button>

      </div>

    </article>


    <!-- VALORANT -->

    <article
      class="game-card"
      data-game="valorant"
      data-genre="FPS"
      data-platform="PC"
    >

      <div class="game-img">

        <img
          src="imagens/valorant.jpg"
          alt="Valorant"
          loading="lazy"
        >

        <span class="badge">
          FPS
        </span>

      </div>


      <div class="game-body">

        <h3>
          Valorant
        </h3>

        <p class="muted">
          Agentes, mapas, lineups, configurações,
          meta e conteúdo competitivo.
        </p>

        <div class="game-meta">

          <span class="pill">
            PC
          </span>

          <span class="pill">
            eSports
          </span>

        </div>

        <button
          class="btn btn-primary"
          onclick="openGame('valorant')"
        >
          Ver informações
        </button>

      </div>

    </article>


    <!-- CYBERPUNK -->

    <article
      class="game-card"
      data-game="cyberpunk 2077"
      data-genre="RPG"
      data-platform="PC PlayStation Xbox"
    >

      <div class="game-img">

        <img
          src="imagens/cyberpunk-2077.jpg"
          alt="Cyberpunk 2077"
          loading="lazy"
        >

        <span class="badge">
          RPG
        </span>

      </div>


      <div class="game-body">

        <h3>
          Cyberpunk 2077
        </h3>

        <p class="muted">
          Builds, missões, escolhas, mods, requisitos
          e segredos de Night City.
        </p>

        <div class="game-meta">

          <span class="pill">
            PC
          </span>

          <span class="pill">
            PlayStation
          </span>

          <span class="pill">
            Xbox
          </span>

        </div>

        <button
          class="btn btn-primary"
          onclick="openGame('cyberpunk')"
        >
          Ver informações
        </button>

      </div>

    </article>


    <!-- MINECRAFT -->

    <article
      class="game-card"
      data-game="minecraft"
      data-genre="Ação"
      data-platform="PC PlayStation Xbox Mobile"
    >

      <div class="game-img">

        <img
          src="imagens/minecraft.jpg"
          alt="Minecraft"
          loading="lazy"
        >

        <span class="badge">
          Sandbox
        </span>

      </div>


      <div class="game-body">

        <h3>
          Minecraft
        </h3>

        <p class="muted">
          Receitas, sementes, encantamentos, farms,
          comandos e dicas para sobreviver.
        </p>

        <div class="game-meta">

          <span class="pill">
            PC
          </span>

          <span class="pill">
            Console
          </span>

          <span class="pill">
            Mobile
          </span>

        </div>

        <button
          class="btn btn-primary"
          onclick="openGame('minecraft')"
        >
          Ver informações
        </button>

      </div>

    </article>


    <!-- FORTNITE -->

    <article
      class="game-card"
      data-game="fortnite"
      data-genre="Ação"
      data-platform="PC PlayStation Xbox Mobile"
    >

      <div class="game-img">

        <img
          src="imagens/fortnite.jpg"
          alt="Fortnite"
          loading="lazy"
        >

        <span class="badge">
          Battle Royale
        </span>

      </div>


      <div class="game-body">

        <h3>
          Fortnite
        </h3>

        <p class="muted">
          Temporadas, mapas, estratégias, itens,
          atualizações e dicas para melhorar.
        </p>

        <div class="game-meta">

          <span class="pill">
            PC
          </span>

          <span class="pill">
            Console
          </span>

          <span class="pill">
            Mobile
          </span>

        </div>

        <button
          class="btn btn-primary"
          onclick="openGame('fortnite')"
        >
          Ver informações
        </button>

      </div>

    </article>


    <!-- LOL -->

    <article
      class="game-card"
      data-game="league of legends lol"
      data-genre="Estratégia"
      data-platform="PC"
    >

      <div class="game-img">

        <img
          src="imagens/league-of-legends.jpg"
          alt="League of Legends"
          loading="lazy"
        >

        <span class="badge">
          MOBA
        </span>

      </div>


      <div class="game-body">

        <h3>
          League of Legends
        </h3>

        <p class="muted">
          Campeões, builds, runas, tier lists,
          estratégias e atualizações.
        </p>

        <div class="game-meta">

          <span class="pill">
            PC
          </span>

          <span class="pill">
            eSports
          </span>

        </div>

        <button
          class="btn btn-primary"
          onclick="openGame('lol')"
        >
          Ver informações
        </button>

      </div>

    </article>


    <!-- MISTFALL -->

    <article
      class="game-card"
      data-game="mistfall hunter mistfall"
      data-genre="RPG"
      data-platform="PC PlayStation Xbox"
    >

      <div class="game-img">

        <img
          src="imagens/mistfall-hunter.jpg"
          alt="Mistfall Hunter"
          loading="lazy"
        >

        <span class="badge">
          NOVO
        </span>

      </div>


      <div class="game-body">

        <h3>
          Mistfall Hunter
        </h3>

        <p class="muted">
          Action RPG de fantasia sombria com extração,
          PvE/PvP, classes, loot e combate em terceira pessoa.
        </p>

        <div class="game-meta">

          <span class="pill">
            PC
          </span>

          <span class="pill">
            PlayStation
          </span>

          <span class="pill">
            Xbox
          </span>

        </div>

        <button
          class="btn btn-primary"
          onclick="openGame('mistfall')"
        >
          Ver informações
        </button>

      </div>

    </article>

  </div>


  <div
    id="noResults"
    class="no-results"
  >

    <i class="fa-solid fa-magnifying-glass"></i>

    <h3>
      Nenhum jogo encontrado
    </h3>

    <p>
      Tente pesquisar por outro nome, gênero ou plataforma.
    </p>

  </div>


  <!-- =========================
       DETALHES
       ========================= -->

  <div
    id="gameDetails"
    style="margin-top:35px"
  >


    <!-- BOTÃO FECHAR -->

    <div
      id="closeGameArea"
      class="game-detail-footer hidden"
    >

      <button
        class="btn btn-secondary"
        onclick="closeGame()"
      >
        <i class="fa-solid fa-arrow-left"></i>
        Voltar para jogos
      </button>

    </div>


    <!-- MISTFALL -->

    <div
      id="detail-mistfall"
      class="game-detail"
    >

      <div class="detail-hero">

        <img
          src="imagens/mistfall-hunter.jpg"
          alt="Mistfall Hunter"
        >

        <div class="script">
          Novo no Corujão
        </div>

        <h2>
          Mistfall Hunter
        </h2>

        <p class="muted">
          Fantasia sombria, extração e ação em terceira pessoa.
        </p>

      </div>


      <div class="detail-columns">

        <div class="content-card">

          <h3>
            Sobre o jogo
          </h3>

          <p>
            Mistfall Hunter é um action RPG de extração
            ambientado em um universo de fantasia sombria.
          </p>

          <p style="margin-top:12px">
            O jogador pode atuar sozinho ou em equipe,
            combinar habilidades, talentos e equipamentos
            e tentar sair da área de combate com seu saque.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Informações
          </h3>

          <ul class="info-list">

            <li>
              <strong>Gênero:</strong>
              Action RPG / Extraction
            </li>

            <li>
              <strong>Desenvolvedora:</strong>
              Bellring Games
            </li>

            <li>
              <strong>Publicadora:</strong>
              Skystone Games
            </li>

            <li>
              <strong>Plataformas:</strong>
              PC, PlayStation 5 e Xbox Series X|S
            </li>

            <li>
              <strong>Modos:</strong>
              PvE, PvP, solo e cooperação
            </li>

          </ul>

        </div>

      </div>


      <div
        class="article-grid"
        style="margin-top:22px"
      >

        <div class="content-card">

          <h3>
            Guias
          </h3>

          <p class="muted">
            Classes, builds, equipamentos, extração
            e dicas para iniciantes.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Temporadas
          </h3>

          <p class="muted">
            Acompanhe mapas, classes, recompensas
            e mudanças do jogo.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Notícias
          </h3>

          <p class="muted">
            Atualizações, patches e novidades da comunidade.
          </p>

        </div>

      </div>

    </div>


    <!-- ELDEN RING -->

    <div
      id="detail-elden-ring"
      class="game-detail"
    >

      <div class="detail-hero">

        <div class="script">
          Guia do jogo
        </div>

        <h2>
          Elden Ring
        </h2>

        <p class="muted">
          Central de informações para jogadores.
        </p>

      </div>


      <div class="detail-columns">

        <div class="content-card">

          <h3>
            Conteúdos
          </h3>

          <p>
            Melhores builds, chefes, armas, classes,
            dicas para iniciantes, exploração
            e conteúdos relacionados.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Informações
          </h3>

          <ul class="info-list">

            <li>
              <strong>Gênero:</strong>
              RPG de ação
            </li>

            <li>
              <strong>Plataformas:</strong>
              PC, PlayStation, Xbox
            </li>

            <li>
              <strong>Conteúdo:</strong>
              Guias e dicas
            </li>

          </ul>

        </div>

      </div>


      <div
        class="article-grid"
        style="margin-top:22px"
      >

        <div class="content-card">

          <h3>
            Informação rápida
          </h3>

          <p class="muted">
            RPG de ação focado em exploração,
            combate e construção de personagem.
          </p>

          <p style="margin-top:10px">
            <strong>Ideal para:</strong>
            fãs de desafios, exploração e RPG.
          </p>

        </div>


        <div class="content-card">

          <h3>
            O que consultar
          </h3>

          <p class="muted">
            Builds, classes, armas, chefes,
            mapas, itens, missões e dicas.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Análise
          </h3>

          <p class="muted">
            Espaço para futuras análises editoriais
            sobre jogabilidade, narrativa, gráficos,
            desempenho e custo-benefício.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Transparência
          </h3>

          <p class="muted">
            Conteúdos patrocinados e relações comerciais
            serão identificados claramente.
          </p>

        </div>

      </div>

    </div>


    <!-- VALORANT -->

    <div
      id="detail-valorant"
      class="game-detail"
    >

      <div class="detail-hero">

        <div class="script">
          Guia competitivo
        </div>

        <h2>
          Valorant
        </h2>

        <p class="muted">
          Agentes, mapas, estratégias e conteúdo competitivo.
        </p>

      </div>


      <div class="detail-columns">

        <div class="content-card">

          <h3>
            Conteúdos
          </h3>

          <p>
            Guias de agentes, lineups, mapas,
            configurações, estratégias
            e acompanhamento do meta.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Informações
          </h3>

          <ul class="info-list">

            <li>
              <strong>Gênero:</strong>
              FPS tático
            </li>

            <li>
              <strong>Plataforma:</strong>
              PC
            </li>

            <li>
              <strong>Foco:</strong>
              Competitivo
            </li>

          </ul>

        </div>

      </div>


      <div
        class="article-grid"
        style="margin-top:22px"
      >

        <div class="content-card">

          <h3>
            Informação rápida
          </h3>

          <p class="muted">
            FPS tático competitivo baseado em agentes
            com habilidades próprias e partidas em equipe.
          </p>

        </div>


        <div class="content-card">

          <h3>
            O que consultar
          </h3>

          <p class="muted">
            Agentes, mapas, lineups, configurações,
            armas, estratégias e mudanças do meta.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Análise
          </h3>

          <p class="muted">
            Espaço para acompanhar jogabilidade,
            desempenho, acessibilidade e evolução competitiva.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Transparência
          </h3>

          <p class="muted">
            Conteúdos patrocinados e relações comerciais
            devem ser identificados claramente.
          </p>

        </div>

      </div>

    </div>


    <!-- CYBERPUNK -->

    <div
      id="detail-cyberpunk"
      class="game-detail"
    >

      <div class="detail-hero">

        <div class="script">
          Explore Night City
        </div>

        <h2>
          Cyberpunk 2077
        </h2>

        <p class="muted">
          Guias de builds, missões, escolhas e exploração.
        </p>

      </div>


      <div class="detail-columns">

        <div class="content-card">

          <h3>
            Conteúdos
          </h3>

          <p>
            Builds, missões, equipamentos, escolhas,
            segredos, mods e informações de desempenho.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Informações
          </h3>

          <ul class="info-list">

            <li>
              <strong>Gênero:</strong>
              RPG
            </li>

            <li>
              <strong>Plataformas:</strong>
              PC, PlayStation, Xbox
            </li>

            <li>
              <strong>Conteúdo:</strong>
              Guias e dicas
            </li>

          </ul>

        </div>

      </div>


      <div
        class="article-grid"
        style="margin-top:22px"
      >

        <div class="content-card">

          <h3>
            Informação rápida
          </h3>

          <p class="muted">
            RPG de ação ambientado em um futuro distópico,
            com exploração, narrativa e progressão.
          </p>

        </div>


        <div class="content-card">

          <h3>
            O que consultar
          </h3>

          <p class="muted">
            Builds, missões, escolhas, equipamentos,
            habilidades, segredos e desempenho.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Análise
          </h3>

          <p class="muted">
            Espaço para futuras análises sobre narrativa,
            gameplay, gráficos, desempenho técnico
            e custo-benefício.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Transparência
          </h3>

          <p class="muted">
            Separaremos opinião editorial,
            informação factual e conteúdo comercial.
          </p>

        </div>

      </div>

    </div>


    <!-- MINECRAFT -->

    <div
      id="detail-minecraft"
      class="game-detail"
    >

      <div class="detail-hero">

        <div class="script">
          Construa e sobreviva
        </div>

        <h2>
          Minecraft
        </h2>

        <p class="muted">
          Dicas, comandos, farms, encantamentos e exploração.
        </p>

      </div>


      <div class="detail-columns">

        <div class="content-card">

          <h3>
            Conteúdos
          </h3>

          <p>
            Receitas, comandos, sementes, farms,
            encantamentos, biomas e dicas de sobrevivência.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Informações
          </h3>

          <ul class="info-list">

            <li>
              <strong>Gênero:</strong>
              Sandbox
            </li>

            <li>
              <strong>Plataformas:</strong>
              PC, consoles e mobile
            </li>

            <li>
              <strong>Conteúdo:</strong>
              Guias
            </li>

          </ul>

        </div>

      </div>


      <div
        class="article-grid"
        style="margin-top:22px"
      >

        <div class="content-card">

          <h3>
            Informação rápida
          </h3>

          <p class="muted">
            Sandbox de construção e sobrevivência
            com exploração, criação e enorme liberdade.
          </p>

        </div>


        <div class="content-card">

          <h3>
            O que consultar
          </h3>

          <p class="muted">
            Comandos, receitas, sementes, farms,
            encantamentos, biomas e progressão.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Comunidade
          </h3>

          <p class="muted">
            Futuramente poderão ser incluídas sementes
            enviadas por leitores, avaliações e dicas.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Transparência
          </h3>

          <p class="muted">
            Informações comerciais e recomendações
            serão identificadas claramente.
          </p>

        </div>

      </div>

    </div>


    <!-- FORTNITE -->

    <div
      id="detail-fortnite"
      class="game-detail"
    >

      <div class="detail-hero">

        <div class="script">
          Battle Royale
        </div>

        <h2>
          Fortnite
        </h2>

        <p class="muted">
          Estratégias, atualizações e novidades.
        </p>

      </div>


      <div class="detail-columns">

        <div class="content-card">

          <h3>
            Conteúdos
          </h3>

          <p>
            Temporadas, itens, mapas,
            estratégias, desafios e novidades.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Informações
          </h3>

          <ul class="info-list">

            <li>
              <strong>Gênero:</strong>
              Battle Royale
            </li>

            <li>
              <strong>Plataformas:</strong>
              PC, consoles e mobile
            </li>

            <li>
              <strong>Conteúdo:</strong>
              Notícias e guias
            </li>

          </ul>

        </div>

      </div>


      <div
        class="article-grid"
        style="margin-top:22px"
      >

        <div class="content-card">

          <h3>
            Informação rápida
          </h3>

          <p class="muted">
            Battle Royale com temporadas,
            atualizações frequentes, eventos
            e diferentes experiências de jogo.
          </p>

        </div>


        <div class="content-card">

          <h3>
            O que consultar
          </h3>

          <p class="muted">
            Temporadas, itens, mapas,
            desafios, estratégias e mudanças recentes.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Atualizações
          </h3>

          <p class="muted">
            Central para acompanhar novidades
            e mudanças importantes.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Transparência
          </h3>

          <p class="muted">
            Publicidade, patrocínios e conteúdo
            comercial serão identificados.
          </p>

        </div>

      </div>

    </div>


    <!-- LEAGUE OF LEGENDS -->

    <div
      id="detail-lol"
      class="game-detail"
    >

      <div class="detail-hero">

        <div class="script">
          Meta competitivo
        </div>

        <h2>
          League of Legends
        </h2>

        <p class="muted">
          Campeões, builds, runas e estratégias.
        </p>

      </div>


      <div class="detail-columns">

        <div class="content-card">

          <h3>
            Conteúdos
          </h3>

          <p>
            Builds, runas, campeões, tier lists,
            estratégias e novidades competitivas.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Informações
          </h3>

          <ul class="info-list">

            <li>
              <strong>Gênero:</strong>
              MOBA
            </li>

            <li>
              <strong>Plataforma:</strong>
              PC
            </li>

            <li>
              <strong>Foco:</strong>
              Estratégia e eSports
            </li>

          </ul>

        </div>

      </div>


      <div
        class="article-grid"
        style="margin-top:22px"
      >

        <div class="content-card">

          <h3>
            Informação rápida
          </h3>

          <p class="muted">
            MOBA competitivo baseado em equipes,
            campeões, objetivos e estratégia.
          </p>

        </div>


        <div class="content-card">

          <h3>
            O que consultar
          </h3>

          <p class="muted">
            Campeões, builds, runas, tier lists,
            itens, estratégias e mudanças do meta.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Conteúdo competitivo
          </h3>

          <p class="muted">
            Espaço para acompanhar tendências,
            campeonatos e mudanças relevantes.
          </p>

        </div>


        <div class="content-card">

          <h3>
            Transparência
          </h3>

          <p class="muted">
            Avaliações e recomendações serão
            diferenciadas de publicidade
            e conteúdo patrocinado.
          </p>

        </div>

      </div>

    </div>

  </div>

</section>


<!-- =========================
     GUIAS
     ========================= -->

<section
  id="guias"
  class="page section container hidden"
>

  <div class="section-header">

    <div class="script">
      Resolva sua dúvida
    </div>

    <h2>
      GUIAS
    </h2>

    <p>
      Conteúdos que podem virar páginas individuais
      e receber tráfego de buscas específicas.
    </p>

  </div>


  <div class="article-grid">

    <article class="content-card">

      <h3>
        Guias para iniciantes
      </h3>

      <p class="muted">
        Passo a passo para começar melhor
        em jogos populares.
      </p>

      <a
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('guide_click',{guide:'iniciantes'})"
      >
        Explorar jogos →
      </a>

    </article>


    <article class="content-card">

      <h3>
        Melhores builds
      </h3>

      <p class="muted">
        Estratégias, equipamentos e combinações
        para diferentes estilos.
      </p>

      <a
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('guide_click',{guide:'builds'})"
      >
        Ver catálogo →
      </a>

    </article>


    <article class="content-card">

      <h3>
        Requisitos de jogos
      </h3>

      <p class="muted">
        Informações para descobrir se seu PC
        consegue rodar determinado jogo.
      </p>

      <a
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('guide_click',{guide:'requisitos'})"
      >
        Pesquisar jogo →
      </a>

    </article>


    <article class="content-card">

      <h3>
        Códigos e comandos
      </h3>

      <p class="muted">
        Central para códigos,
        comandos e dicas úteis.
      </p>

      <a
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('guide_click',{guide:'codigos'})"
      >
        Pesquisar jogo →
      </a>

    </article>


    <article class="content-card">

      <h3>
        Tier Lists
      </h3>

      <p class="muted">
        Organização de personagens, armas
        e opções conforme o contexto do jogo.
      </p>

      <a
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('guide_click',{guide:'tier-list'})"
      >
        Explorar →
      </a>

    </article>


    <article class="content-card">

      <h3>
        Jogos grátis
      </h3>

      <p class="muted">
        Descubra títulos gratuitos
        e conteúdos relacionados.
      </p>

      <a
        href="#jogos"
        onclick="navigateTo('jogos');trackEvent('guide_click',{guide:'gratis'})"
      >
        Explorar →
      </a>

    </article>

  </div>

</section>


<!-- =========================
     NOTÍCIAS
     ========================= -->

<section
  id="noticias"
  class="page section container hidden"
>

  <div class="section-header">

    <div class="script">
      Fique atualizado
    </div>

    <h2>
      NOTÍCIAS &amp; NOVIDADES
    </h2>

    <p>
      Espaço para publicar conteúdos recorrentes
      sobre lançamentos, atualizações e eventos.
    </p>

  </div>


  <div class="article-grid">

    <article class="content-card">

      <h3>
        Novos lançamentos
      </h3>

      <p class="muted">
        Página temática para acompanhar próximos jogos
        e datas de lançamento.
      </p>

    </article>


    <article class="content-card">

      <h3>
        Atualizações e patches
      </h3>

      <p class="muted">
        Resumo de mudanças, novidades
        e alterações relevantes.
      </p>

    </article>


    <article class="content-card">

      <h3>
        eSports
      </h3>

      <p class="muted">
        Torneios, equipes, campeonatos
        e novidades competitivas.
      </p>

    </article>


    <article class="content-card">

      <h3>
        Ofertas e jogos grátis
      </h3>

      <p class="muted">
        Espaço para destacar oportunidades
        e novidades semanais.
      </p>

    </article>

  </div>

</section>


<!-- =========================
     SOBRE
     ========================= -->

<section
  id="sobre"
  class="page section container hidden"
>

  <div class="section-header">

    <div class="script">
      Quem somos
    </div>

    <h2>
      SOBRE O CORUJÃO DOS BRUXOS
    </h2>

    <p>
      Um portal gamer criado para entregar
      informação rápida, conteúdo confiável
      e entretenimento para diferentes perfis de jogadores.
    </p>

  </div>


  <div class="detail-columns">

    <div class="content-card">

      <div class="script">
        Nossa missão
      </div>

      <h3>
        Informação que ajuda o jogador
      </h3>

      <p class="muted">
        Nossa missão é reunir e apresentar informações
        relevantes sobre jogos de forma clara,
        acessível e organizada, ajudando o público
        a tomar decisões melhores sobre o que jogar,
        como jogar e quais novidades acompanhar.
      </p>

      <p
        class="muted"
        style="margin-top:14px"
      >
        Atendemos desde o jogador casual, que quer
        descobrir rapidamente se um jogo vale a pena,
        até o público hardcore, que procura guias
        aprofundados, análises técnicas
        e informações detalhadas.
      </p>

    </div>


    <div class="content-card">

      <div class="script">
        Nossa visão
      </div>

      <h3>
        Ser referência em conteúdo gamer
      </h3>

      <p class="muted">
        Nossa visão é construir, nos próximos anos,
        uma das plataformas brasileiras mais completas
        para descoberta e consulta de informações
        sobre games, reconhecida pela qualidade,
        atualização, transparência
        e experiência do usuário.
      </p>

    </div>

  </div>


  <div
    class="content-card"
    style="margin-top:22px"
  >

    <div class="script">
      Nossos valores
    </div>

    <h3>
      Os princípios que orientam o portal
    </h3>


    <div
      class="article-grid"
      style="margin-top:18px"
    >

      <div>

        <h3>
          Credibilidade
        </h3>

        <p class="muted">
          Buscar informações verificáveis,
          separar fatos de opinião e deixar claro
          quando um conteúdo é patrocinado.
        </p>

      </div>


      <div>

        <h3>
          Qualidade
        </h3>

        <p class="muted">
          Produzir conteúdos úteis,
          bem organizados e relevantes.
        </p>

      </div>


      <div>

        <h3>
          Transparência
        </h3>

        <p class="muted">
          Informar possíveis relações comerciais,
          publicidade, patrocínios
          e critérios de avaliação.
        </p>

      </div>


      <div>

        <h3>
          Atualização
        </h3>

        <p class="muted">
          Acompanhar lançamentos, patches,
          mudanças de meta e novidades da indústria.
        </p>

      </div>


      <div>

        <h3>
          Respeito à comunidade
        </h3>

        <p class="muted">
          Valorizar diferentes estilos de jogo
          e incentivar discussões saudáveis.
        </p>

      </div>


      <div>

        <h3>
          Inovação
        </h3>

        <p class="muted">
          Evoluir ferramentas, formatos
          e experiências.
        </p>

      </div>

    </div>

  </div>


  <div
    class="section-header"
    style="margin-top:55px"
  >

    <div class="script">
      O que oferecemos
    </div>

    <h2>
      QUATRO PILARES DE CONTEÚDO
    </h2>

    <p>
      Nosso conteúdo foi estruturado para combinar
      informação rápida, profundidade,
      entretenimento e confiança.
    </p>

  </div>


  <div class="article-grid">

    <div class="content-card">

      <i
        class="fa-solid fa-bolt"
        style="font-size:2rem;color:var(--cor-primaria)"
      ></i>

      <h3>
        1. Conteúdo de qualidade e atualizado
      </h3>

      <p class="muted">
        Notícias de última hora, anúncios,
        trailers, datas de lançamento,
        atualizações da indústria, reviews,
        guias, tutoriais, builds,
        colecionáveis, conquistas,
        opiniões e reportagens.
      </p>

    </div>


    <div class="content-card">

      <i
        class="fa-solid fa-mobile-screen-button"
        style="font-size:2rem;color:var(--cor-primaria)"
      ></i>

      <h3>
        2. Experiência do usuário
      </h3>

      <p class="muted">
        Navegação simples, organização por plataforma
        e gênero, páginas rápidas,
        experiência otimizada para celular
        e informações fáceis de consultar.
      </p>

    </div>


    <div class="content-card">

      <i
        class="fa-solid fa-comments"
        style="font-size:2rem;color:var(--cor-primaria)"
      ></i>

      <h3>
        3. Comunidade e engajamento
      </h3>

      <p class="muted">
        Queremos criar espaço para comentários,
        avaliações dos usuários, discussões,
        troca de experiências e recursos de comunidade.
      </p>

    </div>


    <div class="content-card">

      <i
        class="fa-solid fa-shield-halved"
        style="font-size:2rem;color:var(--cor-primaria)"
      ></i>

      <h3>
        4. Transparência e credibilidade
      </h3>

      <p class="muted">
        Pretendemos deixar claro quando uma cópia
        foi fornecida, quando existe patrocínio
        e quais critérios são utilizados nas análises.
      </p>

    </div>

  </div>

</section>


<!-- =========================
     NEWSLETTER
     ========================= -->

<section
  id="novidades"
  class="page section container hidden"
>

  <div class="newsletter">

    <div>

      <div class="script">
        Receba novidades
      </div>

      <h2
        style="
          font-family:var(--fonte-titulo);
          font-size:3rem
        "
      >
        NEWSLETTER GAMER
      </h2>

      <p class="muted">
        Receba novidades, guias e conteúdos selecionados.
      </p>

    </div>


    <form
      class="form"
      onsubmit="handleNewsletter(event)"
    >

      <input
        id="nome"
        type="text"
        placeholder="Seu nome"
        autocomplete="name"
        required
      >

      <input
        id="email"
        type="email"
        placeholder="Seu melhor e-mail"
        autocomplete="email"
        required
      >

      <select
        id="origem"
      >

        <option value="google">
          Google
        </option>

        <option value="instagram">
          Instagram
        </option>

        <option value="youtube">
          YouTube
        </option>

        <option value="tiktok">
          TikTok
        </option>

        <option value="outro">
          Outro
        </option>

      </select>


      <button
        class="btn btn-primary"
        type="submit"
      >
        Inscrever-se
      </button>

    </form>

  </div>

</section>
```

  </main>

  <!-- =========================
       FOOTER
       ========================= -->

  <footer>

```
<div class="container footer-grid">

  <div>

    <div class="logo">

      <i class="fa-solid fa-owl"></i>

      CORUJÃO

    </div>

    <p class="muted">
      Games, guias, notícias e informações
      em um só lugar.
    </p>

  </div>


  <div>

    <h3>
      Links
    </h3>

    <ul class="footer-links">

      <li>
        <a
          href="#home"
          onclick="navigateTo('home')"
        >
          Home
        </a>
      </li>

      <li>
        <a
          href="#jogos"
          onclick="navigateTo('jogos')"
        >
          Jogos
        </a>
      </li>

      <li>
        <a
          href="#guias"
          onclick="navigateTo('guias')"
        >
          Guias
        </a>
      </li>

      <li>
        <a
          href="#noticias"
          onclick="navigateTo('noticias')"
        >
          Notícias
        </a>
      </li>

      <li>
        <a
          href="#sobre"
          onclick="navigateTo('sobre')"
        >
          Sobre
        </a>
      </li>

    </ul>

  </div>


  <div>

    <h3>
      Contato
    </h3>

    <p class="muted">
      CorujaodosBruxoes@gmail.com
    </p>

    <p class="muted">
      SuportCorujao@gmail.com
    </p>

  </div>

</div>


<div
  class="container"
  style="
    text-align:center;
    margin-top:35px;
    padding-top:20px;
    border-top:1px solid rgba(255,255,255,.06);
    color:var(--texto-cinza);
    font-size:.8rem
  "
>

  © 2026 Corujão dos Bruxos.
  Todos os direitos reservados.

</div>
```

  </footer>

  <!-- =========================
       WHATSAPP
       ========================= -->

  <!--
    IMPORTANTE:
    Troque 5511999999999 pelo seu número real.
    Formato:
    código do país + DDD + número
    sem espaços, parênteses ou símbolos.
  -->

<a
class="whatsapp"
href="https://wa.me/5511999999999"
target="_blank"
rel="noopener noreferrer"
aria-label="WhatsApp"

>

```
<i class="fa-brands fa-whatsapp"></i>
```

  </a>

  <!-- =========================
       JAVASCRIPT
       ========================= -->

  <script>

    /* =========================
       GOOGLE ANALYTICS
       ========================= */

    function trackEvent(name, params = {}) {

      if (typeof gtag === 'function') {

        gtag('event', name, params);

      }

    }


    /* =========================
       NAVEGAÇÃO
       ========================= */

    function navigateTo(viewId) {

      const pages = document.querySelectorAll('.page');

      pages.forEach(function(page) {

        page.classList.add('hidden');

      });


      const target = document.getElementById(viewId);

      if (!target) {

        return;

      }


      target.classList.remove('hidden');


      /* Atualiza menu */

      document
        .querySelectorAll('.nav-link')
        .forEach(function(link) {

          link.classList.remove('active');

        });


      const activeLink = document.querySelector(
        '.nav-link[href="#' + viewId + '"]'
      );


      if (activeLink) {

        activeLink.classList.add('active');

      }


      /* Fecha detalhes de jogos quando sai da página */

      if (viewId !== 'jogos') {

        closeGame(false);

      }


      /* Scroll */

      window.scrollTo({
        top: 0,
        behavior: 'smooth'
      });


      /* Analytics */

      trackEvent(
        'page_section_view',
        {
          section: viewId
        }
      );


      /* Atualiza URL sem recarregar */

      if (history.pushState) {

        history.pushState(
          null,
          '',
          '#' + viewId
        );

      }

    }


    /* =========================
       ABRIR JOGO
       ========================= */

    function openGame(game) {

      /* Remove detalhes ativos */

      document
        .querySelectorAll('.game-detail')
        .forEach(function(detail) {

          detail.classList.remove('active');

        });


      /* Localiza detalhe */

      const detail = document.getElementById(
        'detail-' + game
      );


      if (!detail) {

        return;

      }


      /* Mostra detalhe */

      detail.classList.add('active');


      /* Mostra botão voltar */

      const closeArea =
        document.getElementById('closeGameArea');

      if (closeArea) {

        closeArea.classList.remove('hidden');

      }


      /* Scroll até detalhe */

      document
        .getElementById('gameDetails')
        .scrollIntoView({
          behavior: 'smooth',
          block: 'start'
        });


      /* Analytics */

      trackEvent(
        'game_view',
        {
          game_name: game
        }
      );

    }


    /* =========================
       FECHAR DETALHE
       ========================= */

    function closeGame(shouldScroll = true) {

      document
        .querySelectorAll('.game-detail')
        .forEach(function(detail) {

          detail.classList.remove('active');

        });


      const closeArea =
        document.getElementById('closeGameArea');


      if (closeArea) {

        closeArea.classList.add('hidden');

      }


      if (shouldScroll) {

        const gamesSection =
          document.getElementById('jogos');


        if (gamesSection) {

          gamesSection.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
          });

        }

      }

    }


    /* =========================
       FILTRO DOS JOGOS
       ========================= */

    function filterGames() {

      const searchInput =
        document.getElementById('gameSearch');

      const genreInput =
        document.getElementById('genreFilter');

      const platformInput =
        document.getElementById('platformFilter');


      if (!searchInput ||
          !genreInput ||
          !platformInput) {

        return;

      }


      const search =
        searchInput.value
          .toLowerCase()
          .trim();


      const genre =
        genreInput.value;


      const platform =
        platformInput.value;


      const cards =
        document.querySelectorAll(
          '#gamesGrid .game-card'
        );


      let visibleCards = 0;


      cards.forEach(function(card) {

        const game =
          (card.dataset.game || '')
          .toLowerCase();


        const cardGenre =
          card.dataset.genre || '';


        const cardPlatform =
          card.dataset.platform || '';


        const matchSearch =
          !search ||
          game.includes(search);


        const matchGenre =
          !genre ||
          cardGenre === genre;


        const matchPlatform =
          !platform ||
          cardPlatform.includes(platform);


        const visible =
          matchSearch &&
          matchGenre &&
          matchPlatform;


        card.style.display =
          visible ? '' : 'none';


        if (visible) {

          visibleCards++;

        }

      });


      /* Mensagem quando não encontrou */

      const noResults =
        document.getElementById('noResults');


      if (noResults) {

        noResults.style.display =
          visibleCards === 0
            ? 'block'
            : 'none';

      }


      /* Analytics */

      trackEvent(
        'game_filter',
        {
          search: search,
          genre: genre,
          platform: platform
        }
      );

    }


    /* =========================
       NEWSLETTER
       ========================= */

    function handleNewsletter(event) {

      event.preventDefault();


      const nome =
        document.getElementById('nome').value.trim();


      const origem =
        document.getElementById('origem').value;


      trackEvent(
        'newsletter_signup',
        {
          source: origem
        }
      );


      alert(
        'Obrigado pelo cadastro, ' +
        nome +
        '! Em breve você receberá nossas novidades.'
      );


      event.target.reset();

    }


    /* =========================
       NAVEGAÇÃO PELO HASH
       ========================= */

    function loadFromHash() {

      const hash =
        window.location.hash.replace('#', '');


      const validPages = [
        'home',
        'jogos',
        'guias',
        'noticias',
        'sobre',
        'novidades'
      ];


      if (validPages.includes(hash)) {

        navigateTo(hash);

      } else {

        navigateTo('home');

      }

    }


    /* =========================
       BOTÃO VOLTAR DO NAVEGADOR
       ========================= */

    window.addEventListener(
      'popstate',
      function() {

        loadFromHash();

      }
    );


    /* =========================
       INICIALIZAÇÃO
       ========================= */

    document.addEventListener(
      'DOMContentLoaded',
      function() {

        loadFromHash();

      }
    );

  </script>

</body>
</html>                     
