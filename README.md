<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Saya - Fredi Wijaya</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="cursor-dot"></div>
    <div class="cursor-outline"></div>

    <nav class="navbar">
        <div class="container">
            <a href="#" class="nav-logo">
                FW <i class="fas fa-feather-alt"></i>
            </a>
            <ul class="nav-menu">
                <li><a href="#hero">Beranda</a></li>
                <li><a href="#tentang">Tentang Saya</a></li>
                <li><a href="#proyek">Proyek</a></li>
                <li><a href="#kontak">Kontak</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <header id="hero" class="hero-section">
        <div class="hero-content">
            <h1 class="hero-title">Halo, Saya <span class="highlight">Fredi Wijaya</span></h1>
            <p class="hero-subtitle">Seorang Freelancer yang kreatif dan bersemangat.</p>
            <a href="#proyek" class="btn-primary">Lihat Karya Saya</a>
        </div>
        <div class="hero-scroll-down">
            <a href="#tentang">
                <span></span>
                <span></span>
                <span></span>
            </a>
        </div>
    </header>

    <section id="tentang" class="tentang-section section-animate"> <div class="container">
            <h2 class="section-title">Tentang Saya</h2>
            <div class="tentang-content">
                <div class="tentang-gambar">
                    <img src="img/foto1.jpg" alt="Foto Fredi Wijaya"> </div>
                <div class="tentang-teks">
                    <p>Selamat datang di portofolio saya! Saya adalah seorang Freelancer yang masih ber status Fresh Graduate dari lulusan Universitas Nusantara PGRI Kediri.</p>
                    <p>Keahlian utama saya meliputi: Data Mining, Problem Solving, Editor video maupun foto. Saya senang belajar hal baru dan berkolaborasi dalam tim untuk mencapai tujuan bersama.</p>
                    <p>Hobi saya yaitu bermain game, bermain musik dan menikmati kopi.</p>
                    <div class="social-links">
                        <a href="[GANTI_DENGAN_LINK_LINKEDIN_ANDA]" target="_blank" aria-label="LinkedIn" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
                        <a href="[GANTI_DENGAN_LINK_GITHUB_ANDA]" target="_blank" aria-label="GitHub" title="GitHub"><i class="fab fa-github"></i></a>
                        <a href="https://www.instagram.com/frediiw_?igsh=MzNlNGNkZWQ4Mg==" target="_blank" aria-label="Instagram" title="Instagram"><i class="fab fa-instagram"></i></a>
                        <a href="https://www.facebook.com/share/1AbYooEvQh/" target="_blank" aria-label="Facebook" title="Facebook"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://www.tiktok.com/@fridiww?_t=ZS-8waFphv4QQ4&_r=1" target="_blank" aria-label="TikTok" title="TikTok"><i class="fab fa-tiktok"></i></a>
                        <a href="mailto:frediw14@gmail.com" aria-label="Email" title="Email"><i class="fas fa-envelope"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="proyek" class="proyek-section section-animate"> <div class="container">
            <h2 class="section-title">Proyek Unggulan</h2>
            <div class="proyek-grid">
                <div class="proyek-item">
                    <img src="img/Semnas.png" alt="Proyek Artikel Semnas">
                    <div class="proyek-overlay">
                        <h3>Artikel Semnas Inotek</h3>
                        <p>Projek artikel semnas inotek 2025 UN PGRI Kediri.</p>
                        <a href="https://colab.research.google.com/drive/1X1Z6y2HSoka-5_Mo64DaYHZLRDpuFgDk" target="_blank" class="btn-secondary">Lihat Detail</a>
                    </div>
                </div>
                <div class="proyek-item">
                    <img src="img/Advan.jpg" alt="Proyek Analisis Sentimen David Gadgetin">
                    <div class="proyek-overlay">
                        <h3>Analisis Sentimen Youtube</h3>
                        <p>Program analisis sentimen Channel Youtube David Gadgetin.</p>
                        <a href="https://colab.research.google.com/drive/1Cg7S-0XBFC8XYZDpelXs1xboPorZ9PIS" target="_blank" class="btn-secondary">Lihat Detail</a>
                    </div>
                </div>
                <div class="proyek-item">
                    <img src="img/Axioo.jpg" alt="Proyek Analisis Sentimen Jagat Review">
                    <div class="proyek-overlay">
                        <h3>Analisis Sentimen Youtube</h3>
                        <p>Program analisis sentimen Channel Youtube Jagat Review.</p>
                        <a href="https://colab.research.google.com/drive/10OB8omdrGHLkCdZq-QOfWaXyWsZl7IqG" target="_blank" class="btn-secondary">Lihat Detail</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="kontak" class="kontak-section section-animate"> <div class="container">
            <h2 class="section-title">Hubungi Saya</h2>
            <p class="kontak-subjudul">Tertarik untuk berkolaborasi atau ada pertanyaan? Jangan ragu untuk menghubungi saya.</p>
            <form action="https://formspree.io/f/xpwdeodl" method="POST" class="kontak-form"> <div class="form-group">
                    <input type="text" name="nama" placeholder="Nama Anda" required>
                </div>
                <div class="form-group">
                    <input type="email" name="email" placeholder="Email Anda" required>
                </div>
                <div class="form-group">
                    <textarea name="pesan" placeholder="Pesan Anda" rows="5" required></textarea>
                </div>
                <button type="submit" class="btn-primary">Kirim Pesan</button>
            </form>
        </div>
    </section>

    <footer class="footer section-animate"> <div class="container">
            <p>&copy; <span id="tahun"></span> Fredi Wijaya. Dibuat dengan <i class="fas fa-heart"></i> dan semangat.</p> </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
