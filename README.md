# 3D School Map Template

Template peta sekolah 3D interaktif yang dibangun menggunakan **Three.js** dan **ES Modules**. Proyek ini menyediakan visualisasi kampus yang modern dengan fitur interaksi mendetail untuk setiap bangunan.

## 🚀 Fitur Utama

- **Visualisasi 3D Interaktif**: Navigasi bebas menggunakan mouse/touch (OrbitControls).
- **Detail Bangunan**: Panel informasi dinamis yang muncul saat kursor diarahkan ke bangunan tertentu.
- **Kontrol Penjelajahan**:
  - Reset Kamera untuk kembali ke pandangan utama.
  - Mode Auto-Rotate untuk presentasi otomatis.
- **Opsi Tampilan**:
  - Mode Wireframe untuk melihat struktur geometri.
  - Toggle Bayangan (Shadows) untuk performa atau estetika.
- **Responsif**: Desain UI yang menyesuaikan dengan ukuran layar (Desktop & Mobile).
- **Tanpa Build Tools**: Menggunakan ES Modules langsung dari CDN (Unpkg), tidak memerlukan `npm install` atau proses kompilasi.

## 🛠️ Teknologi yang Digunakan

- **Three.js (r158)**: Library utama untuk rendering 3D.
- **Vanilla JavaScript (ES Modules)**: Logika aplikasi.
- **CSS3**: Desain antarmuka (UI) dengan efek blur (backdrop-filter) dan animasi modern.
- **HTML5**: Struktur halaman.

## 📋 Daftar Bangunan dalam Template

1. **Main Administrative Complex**: Pusat administrasi dan resepsionis.
2. **Digital Learning Library**: Perpustakaan dengan fasilitas lab komputer.
3. **Athletic & Wellness Center**: Kompleks olahraga dan kolam renang.
4. **STEM Research Center**: Laboratorium sains tingkat lanjut.
5. **Primary Academic Hall**: Gedung kelas utama.
6. **Creative Arts Wing**: Area seni, musik, dan drama.
7. **Community Dining Hall**: Kantin dan area sosial.
8. **Performing Arts Theater**: Teater pertunjukan profesional.

## 📖 Cara Penggunaan

### Menjalankan Secara Lokal

Karena proyek ini menggunakan ES Modules, Anda perlu menjalankannya melalui web server (bukan hanya membuka file `.html` langsung di browser).

1. **Menggunakan VS Code (Live Server)**:
   - Instal ekstensi `Live Server`.
   - Klik kanan pada `index.html` dan pilih **Open with Live Server**.

2. **Menggunakan Python**:
   ```bash
   python -m http.server 8000
   ```
   Buka `http://localhost:8000` di browser Anda.

3. **Menggunakan Node.js (serve)**:
   ```bash
   npx serve .
   ```

### Navigasi
- **Klik Kiri + Seret**: Memutar kamera (Orbit).
- **Scroll**: Perbesar/Perkecil (Zoom).
- **Klik Kanan + Seret**: Menggeser posisi kamera (Pan).
- **Hover Bangunan**: Menampilkan informasi detail bangunan di panel samping.

## 📁 Struktur Proyek

```text
3d_school_map_template/
├── index.html    # Berisi HTML, CSS, dan Logika Three.js (Single File)
└── README.md     # Dokumentasi proyek
```

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE). Anda bebas untuk memodifikasi dan menggunakannya untuk keperluan pribadi maupun komersial.
