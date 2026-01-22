# s21710491.github.io

Repository ini berisi proyek website statis yang dipublikasikan menggunakan **GitHub Pages**. Website dikembangkan dengan struktur file terpisah dan pendekatan sederhana menggunakan **HTML, CSS, dan JavaScript**, serta mengintegrasikan **Bootstrap** dan **Tailwind CSS** melalui CDN.

## Deskripsi Proyek

Proyek ini bertujuan untuk mendemonstrasikan proses perancangan dan deployment website statis menggunakan GitHub Pages dengan manajemen versi berbasis Git. Seluruh file disusun secara modular untuk menjaga keterbacaan kode, konsistensi struktur, serta kemudahan pengembangan lanjutan.

Website ini dapat dimanfaatkan sebagai:
- Halaman profil atau portofolio pribadi
- Dokumentasi proyek akademik
- Media presentasi tugas kuliah
- Landing page statis

## Teknologi yang Digunakan
- HTML5  
- CSS3  
- JavaScript  
- Bootstrap 5  
- Tailwind CSS  
- Git  
- GitHub Pages  

## Struktur Folder
```text
.
├── index.html
├── css/
│   └── custom.css
├── js/
│   └── script.js
├── assets/
│   └── (gambar atau file pendukung)
├── .gitignore
├── LICENSE
└── README.md
```

## Cara Menjalankan Secara Lokal
1. Clone repository ini:
```
git clone https://github.com/glennmandagi16/s21710491.github.io.git
```
2. Masuk ke direktori proyek:
```
cd s21710491.github.io
```
3. Buka file ```index.html``` menggunakan browser.
Website dapat dijalankan secara langsung tanpa server lokal atau konfigurasi tambahan.

## Deployment ke GitHub Pages
1. Pastikan seluruh file berada di branch main.
2. Push perubahan ke repository GitHub.
3. Masuk ke menu Settings → Pages.
4. Atur konfigurasi sebagai berikut:
   * Source: Deploy from a branch
   * Branch: main
   * Folder: /root
5. Simpan pengaturan.
Website akan tersedia pada alamat:
```
https://s21710491.github.io
```

## Catatan Implementasi
* **Bootstrap** digunakan untuk komponen UI seperti navbar, grid, dan tombol.
* **TailwindCSS** digunakan untuk pengaturan detail visual seperti warna, spasi, tipografi, dan efek visual.
* Integrasi dilakukan melalui CDN sehingga tidak memerlukan build tool tambahan.
* Urutan pemanggilan CSS diperhatikan untuk meminimalkan konflik gaya.
Pendekatan ini sesuai untuk proyek kecil hingga menengah yang membutuhkan stabilitas, kesederhanaan, dan kemudahan pemeliharaan.

## Tujuan Akademik
Proyek ini dikembangkan sebagai bagian dari pembelajaran
pengelolaan repository Git, deployment GitHub Pages,
dan pengembangan website statis.


![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
