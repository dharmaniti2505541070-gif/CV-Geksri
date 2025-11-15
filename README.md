<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- 
      ============================================
      INSTRUKSI: Ganti [Nama Anda] dengan nama lengkap Anda
      Contoh: CV - John Doe
      ============================================
    -->
    <title>CV - Geksri</title>
    <!-- Link ke file CSS eksternal -->
    <link rel="stylesheet" href="styles.css" />
    <!-- Font Google untuk tipografi yang lebih menarik -->
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap"
      rel="stylesheet"
    />
    <!-- Font Awesome untuk ikon -->
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
    />
  </head>
  <body>
    <!-- 
      ============================================
      SECTION 1: NAVIGATION BAR
      ============================================
      PENJELASAN:
      - Navigation bar ini akan tetap terlihat saat scroll (sticky)
      - Berisi logo dan menu navigasi ke berbagai section
      - Responsive dengan hamburger menu untuk mobile
      
      INSTRUKSI PENGISIAN:
      1. Ganti [Nama Anda] di nav-logo dengan nama/brand Anda
      2. Menu navigasi sudah disesuaikan dengan section di bawah
      3. Jangan ubah href="#section" agar navigasi berfungsi
      ============================================
    -->
    <nav class="navbar" id="navbar">
      <div class="nav-container">
        <!-- Logo atau nama brand - GANTI [Nama Anda] -->
        <div class="nav-logo">
          <a href="#home">I Gusti Ayu Sri Dharmaniti</a>
        </div>

        <!-- Menu navigasi utama -->
        <ul class="nav-menu" id="nav-menu">
          <li class="nav-item">
            <a href="#home" class="nav-link active">Home</a>
          </li>
          <li class="nav-item">
            <a href="#about" class="nav-link">Tentang Saya</a>
          </li>
          <li class="nav-item">
            <a href="#skills" class="nav-link">Keahlian</a>
          </li>
          <li class="nav-item">
            <a href="#portfolio" class="nav-link">Portofolio</a>
          </li>
          <li class="nav-item">
            <a href="#education" class="nav-link">Pendidikan</a>
          </li>
          <li class="nav-item">
            <a href="#experience" class="nav-link">Pengalaman</a>
          </li>
          <li class="nav-item">
            <a href="#contact" class="nav-link">Kontak</a>
          </li>
        </ul>

        <!-- Hamburger menu untuk mobile (3 garis horizontal) -->
        <div class="nav-toggle" id="mobile-menu">
          <span class="bar"></span>
          <span class="bar"></span>
          <span class="bar"></span>
        </div>
      </div>
    </nav>

    <!-- 
      ============================================
      SECTION 2: HERO / HOME
      ============================================
      PENJELASAN:
      - Bagian pertama yang dilihat pengunjung (landing page)
      - Berisi foto profil, nama, profesi, dan deskripsi singkat
      - Dilengkapi tombol CTA dan social media links
      
      INSTRUKSI PENGISIAN:
      1. Ganti URL foto profil dengan foto Anda sendiri
         (Upload foto ke folder project atau gunakan link online)
      2. Ganti [Nama Lengkap Anda] dengan nama asli
      3. Edit array profesi di script.js untuk typing effect
      4. Tulis deskripsi singkat tentang diri Anda (2-3 kalimat)
      5. Update link social media dengan profil Anda
      
      TIPS:
      - Foto profil recommended: 300x300px, format JPG/PNG
      - Deskripsi sebaiknya tidak lebih dari 3 baris
      - Gunakan kata-kata yang menarik dan profesional
      ============================================
    -->
    <section id="home" class="hero">
      <div class="hero-container">
        <!-- 
          FOTO PROFIL
          INSTRUKSI: Ganti URL dengan path foto Anda
          Contoh: src="images/profile.jpg" atau src="https://link-foto.com/foto.jpg"
        -->
        <div class="hero-image">
          <img
            src="https://via.placeholder.com/300x300"
            alt="Foto Profil"
            class="profile-img"
          />
        </div>

        <!-- INFORMASI UTAMA -->
        <div class="hero-content">
          <!-- 
            NAMA ANDA
            INSTRUKSI: Ganti [Nama Lengkap Anda] dengan nama asli
          -->
          <h1 class="hero-title">
            Halo, Saya <span class="highlight">I Gusti Ayu Sri Dharmaniti</span>
          </h1>
          
          <!-- 
            PROFESI/TITLE (dengan typing effect)
            INSTRUKSI: Text ini akan berubah otomatis (lihat script.js)
            Edit array textArray di script.js untuk mengubah profesi yang ditampilkan
          -->
          <h2 class="hero-subtitle">
            <span class="typed-text"></span><span class="cursor">&nbsp;</span>
          </h2>
          
          <!-- 
            DESKRIPSI SINGKAT
            INSTRUKSI: Tulis 2-3 kalimat tentang diri Anda
            Ganti [profesi/bidang Anda] dan [keahlian utama]
            Contoh: "Saya adalah seorang Web Developer yang berpengalaman dalam..."
          -->
          <p class="hero-description">
            Saya sejak kecil selalu penasaran dengan cara kerja barang-barang elektronik.
            dari remote TV hingga smartphone,
            saya memilih Teknik Komputer di Teknik Elektro Unud karena ingin memahami lebih dari sekadar menjadi pengguna.
            saya ingin mampu merancang dan menciptakan teknologi itu sendiri.
          </p>

          <!-- 
            TOMBOL CALL-TO-ACTION
            INSTRUKSI: Tombol ini sudah terhubung ke section Contact dan Portfolio
            Tidak perlu diubah kecuali ingin mengganti text tombol
          -->
          <div class="hero-buttons">
            <a href="#contact" class="btn btn-primary">Hubungi Saya</a>
            <a href="#portfolio" class="btn btn-secondary">Lihat Portofolio</a>
          </div>

          <!-- 
            SOCIAL MEDIA LINKS
            INSTRUKSI: Ganti href="#" dengan URL profil social media Anda
            Contoh: href="https://linkedin.com/in/username"
            Hapus atau tambah social media sesuai kebutuhan
          -->
          <div class="social-links">
            <a href="#" class="social-link" target="_blank" title="LinkedIn">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="#" class="social-link" target="_blank" title="GitHub">
              <i class="fab fa-github"></i>
            </a>
            <a href="#" class="social-link" target="_blank" title="Instagram">
              <i class="fab fa-instagram"></i>
            </a>
            <a href="#" class="social-link" target="_blank" title="Email">
              <i class="fas fa-envelope"></i>
            </a>
          </div>
        </div>
      </div>

      <!-- Scroll indicator (panah ke bawah) -->
      <div class="scroll-indicator">
        <a href="#about">
          <i class="fas fa-chevron-down"></i>
        </a>
      </div>
    </section>

    <!-- 
      ============================================
      SECTION 3: TENTANG SAYA / ABOUT
      ============================================
      PENJELASAN:
      - Berisi profil lengkap dan informasi personal
      - Detail tentang background pendidikan dan pengalaman
      - Link download CV
      
      INSTRUKSI PENGISIAN:
      1. Tulis deskripsi lengkap tentang diri Anda (1 paragraf)
      2. Isi detail informasi: Nama, Lokasi, Email, Pendidikan
      3. Upload file CV Anda dan update link download
      4. Ganti gambar placeholder dengan foto/ilustrasi yang sesuai
      
      TIPS:
      - Ceritakan unique selling point Anda
      - Highlight pencapaian atau sertifikasi penting
      - Gunakan bahasa yang personal tapi profesional
      ============================================
    -->
    <section id="about" class="about">
      <div class="container">
        <div class="section-title">
          <h2>Tentang Saya</h2>
          <p>Kenali lebih dekat tentang background dan passion saya</p>
        </div>

        <div class="about-content">
          <!-- 
            INFORMASI PERSONAL
            INSTRUKSI: Tulis cerita tentang diri Anda di sini
          -->
          <div class="about-text">
            <h3>Profil Singkat</h3>
            <!-- 
              DESKRIPSI LENGKAP
              INSTRUKSI: Tulis 3-5 kalimat tentang:
              - Background pendidikan Anda
              - Pengalaman profesional
              - Keahlian dan passion
              - Apa yang membuat Anda unik
            -->
            <p>
              [Tulis deskripsi lengkap tentang diri Anda, background pendidikan,
              pengalaman, dan apa yang membuat Anda unik dalam bidang Anda.]
            </p>

            <!-- 
              DETAIL INFORMASI
              INSTRUKSI: Isi setiap detail dengan informasi Anda
              Tambah atau kurangi detail-item sesuai kebutuhan
            -->
            <div class="about-details">
              <div class="detail-item">
                <span class="detail-label">Nama:</span>
                <span class="detail-value">I Gusti Ayu Sri Dharmaniti</span>
              </div>
              <div class="detail-item">
                <span class="detail-label">Lokasi:</span>
                <span class="detail-value">Semarapura,Bali</span>
              </div>
              <div class="detail-item">
                <span class="detail-label">Email:</span>
                <span class="detail-value">ayusridharmaniti@gmail.com</span>
              </div>
              <div class="detail-item">
                <span class="detail-label">Pendidikan:</span>
                <span class="detail-value">S1, Universitas Udayana</span>
              </div>
            </div>

            <!-- 
              TOMBOL DOWNLOAD CV
              INSTRUKSI: 
              1. Upload file CV Anda (format PDF) ke folder project
              2. Ganti href="#" dengan "path/ke/CV-Anda.pdf"
              Contoh: href="files/CV-JohnDoe.pdf"
            -->
            <div class="about-buttons">
              <a href="#" class="btn btn-primary" download>
                <i class="fas fa-download"></i> Download CV
              </a>
            </div>
          </div>

          <!-- 
            GAMBAR ABOUT
            INSTRUKSI: Ganti dengan foto/ilustrasi yang mewakili Anda
            Bisa foto working, hobi, atau ilustrasi yang relevan
          -->
          <div class="about-image">
            <img src="https://via.placeholder.com/400x400" alt="About Image" />
          </div>
        </div>
      </div>
    </section>

    <!-- 
      ============================================
      SECTION 4: KEAHLIAN / SKILLS
      ============================================
      PENJELASAN:
      - Menampilkan technical skills dengan progress bar
      - Menampilkan soft skills dengan ikon
      - Skills akan ter-animasi saat di-scroll
      
      INSTRUKSI PENGISIAN:
      1. Tambah/kurangi skill-item sesuai keahlian Anda
      2. Sesuaikan persentase skill (data-width)
      3. Ganti ikon sesuai teknologi (cari di Font Awesome)
      4. Edit soft skills sesuai dengan kelebihan Anda
      
      TIPS:
      - Jujur dengan level skill (jangan berlebihan)
      - Fokus pada skill yang relevan dengan target pekerjaan
      - Update persentase: 
        * 90-100%: Expert/Mastery
        * 70-89%: Advanced
        * 50-69%: Intermediate
        * 30-49%: Basic
      ============================================
    -->
    <section id="skills" class="skills">
      <div class="container">
        <div class="section-title">
          <h2>Keahlian & Teknologi</h2>
          <p>Technologies dan tools yang saya kuasai</p>
        </div>

        <div class="skills-content">
          <!-- 
            TECHNICAL SKILLS
            INSTRUKSI: Copy-paste skill-item untuk menambah skill baru
          -->
          <div class="skills-category">
            <h3>Technical Skills</h3>
            <div class="skills-grid">
              <!-- 
                SKILL ITEM TEMPLATE
                INSTRUKSI untuk setiap skill:
                1. Ganti ikon (cari di fontawesome.com)
                2. Ganti nama skill di <h4>
                3. Update data-width="XX%" sesuai level Anda
                4. Update skill-percentage text sesuai data-width
                5. Copy seluruh div.skill-item untuk menambah skill baru
              -->
              <div class="skill-item">
                <div class="skill-icon">
                  <!-- INSTRUKSI: Ganti class ikon di sini -->
                  <i class="fab fa-html5"></i>
                </div>
                <!-- INSTRUKSI: Ganti nama teknologi -->
                <h4>HTML5</h4>
                <div class="skill-bar">
                  <!-- INSTRUKSI: Ganti persentase sesuai level Anda (0-100%) -->
                  <div class="skill-progress" data-width="10%"></div>
                </div>
                <!-- INSTRUKSI: Sesuaikan dengan data-width di atas -->
                <span class="skill-percentage">10%</span>
              </div>

              <div class="skill-item">
                <div class="skill-icon">
                  <i class="fab fa-css3-alt"></i>
                </div>
                <h4>CSS3</h4>
                <div class="skill-bar">
                  <div class="skill-progress" data-width="10%"></div>
                </div>
                <span class="skill-percentage">10%</span>
              </div>

              <div class="skill-item">
                <div class="skill-icon">
                  <i class="fab fa-js"></i>
                </div>
                <h4>JavaScript</h4>
                <div class="skill-bar">
                  <div class="skill-progress" data-width="10%"></div>
                </div>
                <span class="skill-percentage">10%</span>
              </div>

              <!-- Tambahkan skill lainnya sesuai kebutuhan -->
            </div>
          </div>

          <!-- 
            SOFT SKILLS
            INSTRUKSI: 
            1. Edit nama soft skill sesuai kelebihan Anda
            2. Ganti ikon sesuai skill (cari di Font Awesome)
            3. Tambah/kurangi soft-skill-item sesuai kebutuhan
          -->
          <div class="skills-category">
            <h3>Soft Skills</h3>
            <div class="soft-skills">
              <div class="soft-skill-item">
                <i class="fas fa-users"></i>
                <!-- INSTRUKSI: Ganti dengan soft skill Anda -->
                <span>Teamwork</span>
              </div>
              <div class="soft-skill-item">
                <i class="fas fa-lightbulb"></i>
                <span>Problem Solving</span>
              </div>
              <div class="soft-skill-item">
                <i class="fas fa-comments"></i>
                <span>Communication</span>
              </div>
              <div class="soft-skill-item">
                <i class="fas fa-clock"></i>
                <span>Time Management</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 
      ============================================
      SECTION 6: PENDIDIKAN / EDUCATION
      ============================================
      PENJELASAN:
      - Menampilkan riwayat pendidikan formal
      - Format card untuk setiap jenjang pendidikan
      - Bisa tambahkan sertifikasi atau pelatihan
      
      INSTRUKSI PENGISIAN:
      1. Isi jenjang pendidikan (S1, S2, SMA, dll)
      2. Nama institusi/universitas
      3. Jurusan/program studi
      4. Tahun masuk - lulus
      5. IPK/prestasi (opsional)
      
      TIPS:
      - Urutkan dari pendidikan terbaru ke terlama
      - Tambahkan sertifikasi penting jika ada
      - Bisa tambahkan logo universitas
      - Highlight prestasi akademik jika ada
      ============================================
    -->
    <section id="education" class="education">
      <div class="container">
        <div class="section-title">
          <h2>Pendidikan</h2>
          <p>Riwayat pendidikan formal dan sertifikasi</p>
        </div>

        <div class="education-content">
          <!-- 
            EDUCATION CARD 1 (Pendidikan Terbaru)
            INSTRUKSI: Isi dengan pendidikan tertinggi/terbaru
          -->

          <!-- 
            EDUCATION CARD 2 (Pendidikan Sebelumnya)
            INSTRUKSI: Copy education-card untuk menambah pendidikan lainnya
          -->
          <div class="education-card">
            <div class="education-icon">
              <i class="fas fa-graduation-cap"></i>
            </div>
            <div class="education-info">
              <h3>SMA</h3>
              <h4>SMA Negri 1 Semarapura</h4>
              <p class="education-major">
                <i class="fas fa-book"></i> IPA
              </p>
              <p class="education-year">
                <i class="fas fa-calendar"></i> 2022 - 2025
              </p>
            </div>
          </div>

          <!-- 
            INSTRUKSI: Copy seluruh <div class="education-card"> 
            untuk menambah riwayat pendidikan lainnya atau sertifikasi
          -->
        </div>
      </div>
    </section>

    <!-- 
      ============================================
      SECTION 8: KONTAK / CONTACT
      ============================================
      PENJELASAN:
      - Menampilkan informasi kontak lengkap
      - Form untuk pengunjung mengirim pesan
      - Form sudah ada validasi otomatis
      
      INSTRUKSI PENGISIAN:
      1. Update semua informasi kontak (alamat, phone, email)
      2. Form sudah berfungsi dengan JavaScript
      3. Jika ingin kirim email real, integrasikan dengan service
         (EmailJS, FormSpree, Netlify Forms, dll.)
      
      TIPS:
      - Gunakan email profesional
      - Bisa tambah info kontak lain (WhatsApp, Telegram, dll.)
      - Form akan show notifikasi saat berhasil
      ============================================
    -->
    <section id="contact" class="contact">
      <div class="container">
        <div class="section-title">
          <h2>Hubungi Saya</h2>
          <p>Mari berdiskusi tentang project atau kolaborasi yang menarik</p>
        </div>

        <div class="contact-content">
          <!-- 
            INFORMASI KONTAK KIRI
            INSTRUKSI: Ganti semua [...] dengan informasi kontak Anda
          -->
          <div class="contact-info">
            <h3>Informasi Kontak</h3>
            
            <!-- Contact Item 1: Alamat -->
            <div class="contact-item">
              <div class="contact-icon">
                <i class="fas fa-map-marker-alt"></i>
              </div>
              <div class="contact-details">
                <h4>Alamat</h4>
                <!-- INSTRUKSI: Ganti dengan alamat lengkap Anda -->
                <p>Jalan Sedap Malam,Klungkung, Bali</p>
              </div>
            </div>

            <!-- Contact Item 2: Telepon -->
            <div class="contact-item">
              <div class="contact-icon">
                <i class="fas fa-phone"></i>
              </div>
              <div class="contact-details">
                <h4>Telepon</h4>
                <!-- INSTRUKSI: Ganti dengan nomor telepon Anda -->
                <p>087865023341</p>
              </div>
            </div>

            <!-- Contact Item 3: Email -->
            <div class="contact-item">
              <div class="contact-icon">
                <i class="fas fa-envelope"></i>
              </div>
              <div class="contact-details">
                <h4>Email</h4>
                <!-- INSTRUKSI: Ganti dengan email Anda -->
                <p>ayusridharmaniti@gmail.com</p>
              </div>
            </div>
          </div>

          <!-- 
            CONTACT FORM (KANAN)
            PENJELASAN:
            - Form sudah ada validasi otomatis
            - Submit akan dihandle oleh JavaScript (lihat script.js)
            - Untuk kirim email real, integrasikan dengan service
            
            INSTRUKSI:
            - Form sudah siap pakai, tidak perlu diubah
            - Jika ingin kirim ke email, lihat script.js line ~220
          -->
          <div class="contact-form">
            <h3>Kirim Pesan</h3>
            <form id="contactForm">
              <!-- Input Nama -->
              <div class="form-group">
                <input
                  type="text"
                  id="name"
                  name="name"
                  placeholder="Nama Lengkap"
                  required
                />
              </div>
              
              <!-- Input Email -->
              <div class="form-group">
                <input
                  type="email"
                  id="email"
                  name="email"
                  placeholder="Email"
                  required
                />
              </div>
              
              <!-- Input Subject -->
              <div class="form-group">
                <input
                  type="text"
                  id="subject"
                  name="subject"
                  placeholder="Subject"
                  required
                />
              </div>
              
              <!-- Textarea Message -->
              <div class="form-group">
                <textarea
                  id="message"
                  name="message"
                  placeholder="Pesan Anda"
                  rows="5"
                  required
                ></textarea>
              </div>
              
              <!-- Submit Button -->
              <button type="submit" class="btn btn-primary">
                <i class="fas fa-paper-plane"></i> Kirim Pesan
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- 
      ============================================
      FOOTER
      ============================================
      PENJELASAN:
      - Bagian bawah website dengan copyright
      - Link social media tambahan
      - Informasi legal/credits
      
      INSTRUKSI:
      - Ganti [Nama Anda] dengan nama Anda
      - Update tahun copyright jika perlu
      - Update link social media
      ============================================
    -->
    <footer class="footer">
      <div class="container">
        <div class="footer-content">
          <div class="footer-text">
            <!-- INSTRUKSI: Ganti [Nama Anda] dan tahun jika perlu -->
            <p>&copy; 2025 Geksri. All rights reserved.</p>
          </div>
          
          <!-- 
            SOCIAL LINKS FOOTER
            INSTRUKSI: Ganti href="#" dengan URL social media Anda
            (sama seperti di Hero section)
          -->
          <div class="footer-social">
            <a href="#" class="social-link" title="LinkedIn">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="#" class="social-link" title="GitHub">
              <i class="fab fa-github"></i>
            </a>
            <a href="#" class="social-link" title="Instagram">
              <i class="fab fa-instagram"></i>
            </a>
          </div>
        </div>
      </div>
    </footer>

    <!-- 
      ============================================
      SCROLL TO TOP BUTTON
      ============================================
      PENJELASAN:
      - Tombol floating untuk kembali ke atas
      - Muncul otomatis saat scroll ke bawah
      - Smooth scroll ke top saat diklik
      
      INSTRUKSI: Tidak perlu diubah, sudah otomatis bekerja
      ============================================
    -->
    <div class="scroll-top" id="scrollTop">
      <i class="fas fa-chevron-up"></i>
    </div>

    <!-- 
      ============================================
      JAVASCRIPT
      ============================================
      PENJELASAN:
      - Menghubungkan file JavaScript eksternal
      - Berisi semua interactivity website
      
      INSTRUKSI: Jangan ubah lokasi script ini (harus di akhir body)
      Untuk edit functionality, buka file script.js
      ============================================
    -->
    <script src="script.js"></script>
  </body>
</html>
# CV-Geksri
