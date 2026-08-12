# techzone-responsive-redesign

TechZone Responsive Redesign
Repository ini berisi hasil perbaikan desain web statis (HTML & CSS) menjadi sepenuhnya responsif. Proyek ini dikerjakan sebagai bagian dari asesmen/tugas mata kuliah terkait Desain Responsif (Sub-CPMK-1.3).

📌 Deskripsi Proyek
Tujuan utama dari proyek ini adalah menganalisis dan memperbaiki masalah desain pada halaman web "TechZone Lab" yang sebelumnya kaku (fixed-width) dan memiliki masalah visual saat ditampilkan di perangkat mobile (seperti elemen yang tumpang tindih dan horizontal scrolling).

Perbaikan dilakukan dengan menerapkan praktik CSS modern untuk memastikan halaman dapat beradaptasi dengan mulus pada berbagai ukuran layar (Desktop, Tablet, dan Smartphone).

🛠️ Teknologi yang Digunakan
HTML5: Digunakan untuk memperbarui struktur semantik halaman dan penambahan tag fungsional (seperti meta viewport).
CSS3:
Flexbox & CSS Grid: Untuk membuat sistem tata letak (layout) multi-kolom yang dinamis tanpa menggunakan float.
Media Queries: Mengatur breakpoint desain untuk Desktop, Tablet (max-width: 992px), dan Mobile (max-width: 768px).
Fluid Typography: Menggunakan properti clamp() untuk ukuran font agar fleksibel terhadap lebar layar.

✨ Fitur Perbaikan Utama
Dukungan Mobile Penuh: Mengubah lebar kaku 1200px menjadi fluid container yang menyesuaikan batas layar.
Navigasi Dinamis: Menambahkan navigasi hamburger menu (dropdown vertikal) khusus untuk pengguna perangkat seluler.
Pencegahan Tumpang Tindih: Menghapus koordinat absolut kaku pada elemen .badge agar sejajar rapi dalam barisan navigasi.
Grid Otomatis: Menggunakan properti grid-template-columns: repeat(auto-fit, minmax(...)) pada bagian Layanan dan Tim, sehingga jumlah kolom berkurang dan bertambah sendiri sesuai ketersediaan ruang layar.
