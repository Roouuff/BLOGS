# BlogKu - Blog Pribadi Muhammad Abdul Rouf 📝

Website blog pribadi modern dengan sistem login sederhana yang dibuat menggunakan Bootstrap 5 dan JavaScript.

## 📋 Deskripsi

BlogKu adalah platform blog pribadi yang menampilkan profil, project-project, dan informasi kontak. Website ini dilengkapi dengan halaman login dan 5 halaman detail project individual.

## ✨ Fitur Utama

- **🔐 Sistem Login** - Login sederhana dengan validasi JavaScript
- **📱 Responsive Design** - Tampilan optimal di semua perangkat (mobile, tablet, desktop)
- **🎨 Modern UI** - Menggunakan Bootstrap 5 dengan gradient background
- **📊 Project Showcase** - 5 project cards dengan halaman detail masing-masing
- **📬 Contact Form** - Form kontak dengan validasi dan alert
- **🔗 Social Media Integration** - Link ke berbagai platform sosial media
- **🌊 SVG Wave Dividers** - Pemisah section yang aesthetic
- **⚡ Smooth Navigation** - Sticky navbar dengan smooth scrolling

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur halaman
- **CSS3** - Styling (Bootstrap + Custom CSS)
- **JavaScript** - Interaktivitas dan validasi
- **Bootstrap 5.3.3** - Framework CSS
- **Bootstrap Icons** - Icon library

## 📁 Struktur File

```
BLOGS/
│
├── index.html              # Halaman utama blog
├── login.html              # Halaman login
├── p1.html                 # Halaman detail project 1
├── p2.html                 # Halaman detail project 2
├── p3.html                 # Halaman detail project 3
├── p4.html                 # Halaman detail project 4
├── p5.html                 # Halaman detail project 5
│
├── img/                    # Folder gambar
│   ├── download.jpg        # Gambar thumbnail project
│   ├── pjk.png            # Gambar project detail
│   └── pol.png            # Foto profil
│
├── assets/                 # Folder assets
│   ├── css/               # Folder CSS
│   │   ├── bootstrap.min.css
│   │   ├── bootstrap-grid.css
│   │   ├── bootstrap-grid.css.map
│   │   └── ... (file Bootstrap CSS lainnya)
│   │
│   └── js/                # Folder JavaScript
│       ├── bootstrap.bundle.min.js
│       └── ... (file Bootstrap JS lainnya)
│
└── README.md              # Dokumentasi project
```

## 🚀 Cara Menjalankan

1. **Clone atau Download** repository ini
2. **Pastikan struktur folder** sesuai dengan yang tertera di atas
3. **Buka file `index.html`** di browser favorit Anda
4. Website siap digunakan! 🎉

## 🔑 Kredensial Login

Untuk mengakses sistem login, gunakan kredensial berikut:

```
Email: admin@gmail.com
Password: 12345
```

> **Note:** Kredensial juga ditampilkan di console browser pada halaman login

## 📄 Halaman-Halaman

### 1. **index.html** - Halaman Utama

Halaman utama blog yang berisi:

- **Navbar** dengan menu navigasi dan social media icons
- **Jumbotron/Hero Section** dengan foto profil dan tagline
- **About Section** dengan deskripsi singkat
- **Projects Section** dengan 5 project cards
- **Contact Section** dengan form kontak
- **Footer** dengan copyright

### 2. **login.html** - Halaman Login

- Form login dengan validasi JavaScript
- Gradient background modern
- Redirect ke index.html setelah login berhasil
- Alert untuk login gagal

### 3. **p1.html - p5.html** - Halaman Detail Project

- Card dengan gambar project
- Deskripsi project
- Tombol back ke halaman utama
- Tanggal publikasi

## 🎨 Customization

### Mengubah Warna

Edit gradient background di file HTML atau CSS:

```css
background: linear-gradient(135deg, #4facfe, #00f2fe);
```

### Mengganti Foto Profil

Replace file `img/pol.png` dengan foto Anda

### Mengganti Gambar Project

- Thumbnail: Replace `img/download.jpg`
- Detail: Replace `img/pjk.png`

### Mengubah Kredensial Login

Edit di file `login.html`:

```javascript
if (email == "admin@gmail.com" && password == "12345") {
  // Ubah email dan password di sini
}
```

### Menambah/Mengurangi Project

1. Edit section projects di `index.html`
2. Buat file baru `p6.html`, `p7.html`, dst.
3. Sesuaikan link di card project

## 🌐 Social Media Links

Website ini terhubung dengan platform:

- 📘 Facebook
- 📷 Instagram
- 🧵 Threads
- 🎥 YouTube
- 💼 LinkedIn
- 🎵 TikTok
- ✈️ Telegram

Update link social media di `index.html` pada bagian navbar:

```html
<a href="https://www.instagram.com/roouuf_" class="text-white">
  <i class="bi bi-instagram"></i>
</a>
```

## ⚙️ Fitur JavaScript

### 1. Login Validation

```javascript
function login(event) {
  event.preventDefault();
  let email = document.getElementById("email").value;
  let password = document.getElementById("password").value;

  if (email == "admin@gmail.com" && password == "12345") {
    alert("Login berhasil!");
    window.location.href = "index.html";
  } else {
    alert("Email atau Password salah!");
  }
}
```

### 2. Contact Form Alert

```javascript
function showAlert(event) {
  event.preventDefault();
  alert("Pesan berhasil dikirim! Terima kasih sudah menghubungi saya 😊");
}
```

## 📱 Responsive Breakpoints

Website menggunakan Bootstrap responsive grid:

- **Mobile**: < 768px
- **Tablet**: 768px - 991px
- **Desktop**: > 992px

## 🔧 Perbaikan yang Disarankan

1. **Backend Integration**
   - Koneksi ke database untuk menyimpan data login
   - Backend API untuk contact form
   - Session management untuk login

2. **Security**
   - Hash password (jangan simpan plain text)
   - HTTPS untuk production
   - CSRF protection

3. **Features**
   - Search functionality
   - Comments system
   - Blog post categories
   - Pagination untuk projects

4. **Performance**
   - Image optimization
   - Lazy loading untuk gambar
   - Minify CSS dan JavaScript

5. **SEO**
   - Meta description
   - Open Graph tags
   - Sitemap.xml
   - robots.txt

## 📝 Bootstrap Components yang Digunakan

- ✅ Navbar (Fixed Top)
- ✅ Cards
- ✅ Forms
- ✅ Buttons
- ✅ Grid System
- ✅ Jumbotron (Custom)
- ✅ Icons (Bootstrap Icons)

## 🎯 Browser Support

Website kompatibel dengan:

- ✅ Google Chrome (Latest)
- ✅ Mozilla Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Microsoft Edge (Latest)
- ✅ Opera (Latest)

## 📄 License

© 2026 Muhammad Abdul Rouf. All rights reserved.

## 🤝 Kontribusi & Feedback

Saran dan feedback sangat diterima! Silakan hubungi melalui:

- 📧 **Email**: muhammadarrouf052@gmail.com
- 📷 **Instagram**: [@roouuf\_](https://www.instagram.com/roouuf_?igsh=Z2Qxcm5sMXVqcWRt)
- 💼 **LinkedIn**: [Profile](https://www.linkedin.com/login/in)
- 🐙 **GitHub**: [Roouuff](https://github.com/Roouuff)

## 📞 Contact Information

Untuk pertanyaan atau kolaborasi, hubungi:

**Muhammad Abdul Rouf**

- Content Creator | Web Developer | AI Engineer
- Based in Indonesia 🇮🇩

---

**Made with ❤️ by Muhammad Abdul Rouf**

_BlogKu © 2026_

# BLOGS
