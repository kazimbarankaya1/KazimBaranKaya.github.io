# KazimBaranKaya.github.io

<!doctype html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#100d1c">
  <meta name="description" content="Kabaka GameTech — animasyon, 3D tasarım ve oyun teknolojileri portföyü">
  <title>Kabaka | GameTech Studio</title>
  <link rel="stylesheet" href="css/style.css">
  <script src="js/main.js" defer></script>
</head>
<body>
  <header class="header">
    <a class="brand" href="index.html">K<span>KABAKA</span></a>
    <button class="menu-button" id="menuButton" aria-label="Menüyü aç">☰</button>
    <nav id="nav">
      <a href="#projects" data-tr="Projeler" data-en="Projects">Projeler</a>
      <a href="#about" data-tr="Hakkımda" data-en="About">Hakkımda</a>
      <a href="#skills" data-tr="Yetenekler" data-en="Skills">Yetenekler</a>
      <a href="#contact" data-tr="İletişim" data-en="Contact">İletişim</a>
      <button id="languageButton" class="language-button">EN</button>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="hero-copy">
        <p class="eyebrow">GAMETECH · DESIGN · ANIMATION</p>
        <h1 id="heroTitle">Fikirleri <span>oynanabilir</span> dünyalara dönüştürüyorum.</h1>
        <p id="heroText">2D animasyon, 3D modelleme ve oyun teknolojileriyle yeni dünyalar oluşturuyorum.</p>
        <a class="button" href="#projects" data-tr="Projelerimi keşfet ↘" data-en="Explore my work ↘">Projelerimi keşfet ↘</a>
      </div>
      <div class="hero-art" aria-label="Kabaka tasarım görseli">
        <div class="orbit"></div>
        <div class="cube">K</div>
        <div class="floating-label">IDEA → BUILD → PLAY</div>
      </div>
    </section>

    <div class="ticker">2D ANIMATION ✳ 3D ART ✳ GAME SYSTEMS ✳ INTERACTIVE WORLDS ✳</div>

    <section class="section" id="projects">
      <p class="eyebrow" data-tr="SEÇİLMİŞ ÇALIŞMALAR" data-en="SELECTED WORK">SEÇİLMİŞ ÇALIŞMALAR</p>
      <h2 data-tr="Projelerim" data-en="My Projects">Projelerim</h2>
      <p class="section-intro" data-tr="Animasyon, 3D sanat ve oyun teknolojileri." data-en="Animation, 3D art and game technology.">Animasyon, 3D sanat ve oyun teknolojileri.</p>

      <div class="filters">
        <button class="filter active" data-filter="all" data-tr="Tümü" data-en="All">Tümü</button>
        <button class="filter" data-filter="animation" data-tr="2D Animasyon" data-en="2D Animation">2D Animasyon</button>
        <button class="filter" data-filter="3d" data-tr="3D Modelleme" data-en="3D Modeling">3D Modelleme</button>
        <button class="filter" data-filter="gametech" data-tr="GameTech" data-en="GameTech">GameTech</button>
      </div>

      <div class="project-grid" id="projectGrid"></div>
      <p class="hint" data-tr="Bunlar başlangıç örnekleridir. Gerçek çalışmalarını eklediğinde açıklamaları güncelle." data-en="These are starter examples. Update the descriptions when you add your own work.">Bunlar başlangıç örnekleridir. Gerçek çalışmalarını eklediğinde açıklamaları güncelle.</p>
    </section>

    <section class="about" id="about">
      <div class="section about-inner">
        <div>
          <p class="eyebrow" data-tr="HAKKIMDA" data-en="ABOUT ME">HAKKIMDA</p>
          <h2 id="aboutTitle">Sanat ile teknolojinin <span>kesişiminde.</span></h2>
        </div>
        <p id="aboutText">Bilgisayar Destekli Tasarım ve Animasyon öğrencisiyim. Krita, Blender ve Unity ile animasyonlar, 3D varlıklar ve oyun sistemleri geliştirmeyi öğreniyorum. Hedefim Kabaka markası altında faydalı GameTech ürünleri oluşturmak.</p>
      </div>
    </section>

    <section class="section" id="skills">
      <p class="eyebrow" data-tr="ARAÇ KUTUSU" data-en="TOOLKIT">ARAÇ KUTUSU</p>
      <h2 data-tr="Neler üretiyorum?" data-en="What I Create">Neler üretiyorum?</h2>
      <div class="skills-grid">
        <article class="skill">
          <div class="skill-icon">✳</div>
          <h3 data-tr="2D Animasyon" data-en="2D Animation">2D Animasyon</h3>
          <p data-tr="Sprite sheet, kare kare animasyon ve oyun efektleri." data-en="Sprite sheets, frame-by-frame animation and game effects.">Sprite sheet, kare kare animasyon ve oyun efektleri.</p>
          <span>Krita · GIF · PNG</span>
        </article>
        <article class="skill">
          <div class="skill-icon">◇</div>
          <h3 data-tr="3D Modelleme" data-en="3D Modeling">3D Modelleme</h3>
          <p data-tr="Low-poly çevreler, oyun varlıkları ve ürün görselleştirme." data-en="Low-poly environments, game assets and product visualization.">Low-poly çevreler, oyun varlıkları ve ürün görselleştirme.</p>
          <span>Blender · FBX · OBJ</span>
        </article>
        <article class="skill">
          <div class="skill-icon">⌘</div>
          <h3>GameTech</h3>
          <p data-tr="Oyun prototipleri, geliştirici araçları ve yeniden kullanılabilir sistemler." data-en="Game prototypes, developer tools and reusable systems.">Oyun prototipleri, geliştirici araçları ve yeniden kullanılabilir sistemler.</p>
          <span>Unity · C# · Tools</span>
        </article>
      </div>
    </section>

    <section class="contact" id="contact">
      <p class="eyebrow" data-tr="BİRLİKTE ÜRETELİM" data-en="LET'S CREATE">BİRLİKTE ÜRETELİM</p>
      <h2 data-tr="Bir fikrin mi var?" data-en="Have an idea?">Bir fikrin mi var?</h2>
      <p data-tr="Proje, freelance iş veya iş birliği için benimle iletişime geç." data-en="Contact me about projects, freelance work or collaboration.">Proje, freelance iş veya iş birliği için benimle iletişime geç.</p>
      <a class="button" id="emailLink" href="mailto:epostan@example.com" data-tr="E-posta gönder ↗" data-en="Send an email ↗">E-posta gönder ↗</a>
      <p class="hint" data-tr="Yayınlamadan önce e-posta adresini js/main.js dosyasında değiştir." data-en="Change your email in js/main.js before publishing.">Yayınlamadan önce e-posta adresini js/main.js dosyasında değiştir.</p>
    </section>
  </main>

  <footer>
    <a class="brand" href="#">K<span>KABAKA</span></a>
    <p>© <span id="year"></span> Kabaka GameTech</p>
    <a href="#top" data-tr="Yukarı çık ↑" data-en="Back to top ↑">Yukarı çık ↑</a>
  </footer>
</body>
</html>


