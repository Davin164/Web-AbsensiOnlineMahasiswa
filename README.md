# 🧑‍🎓 Sistem Absensi Mahasiswa Berbasis Website

Proyek ini merupakan **web absensi mahasiswa sederhana** yang dibangun menggunakan **HTML, CSS, dan JavaScript murni (native)** tanpa backend.  
Data absensi saat ini disimpan menggunakan **localStorage (array JavaScript)**, namun struktur kodenya sudah disiapkan agar dapat dengan mudah diintegrasikan ke **database seperti MySQL atau API backend (misalnya dengan PHP atau Node.js)**.

---

## 🚀 Fitur Utama

- ✅ **Login Mahasiswa** menggunakan NIM & Nama
- 🕒 **Menampilkan waktu real-time** pada halaman login dan absensi
- 📝 **Absensi per mata kuliah** untuk mahasiswa
- 💾 **Penyimpanan otomatis** data absensi ke localStorage browser
- 📊 **Panel Admin** dengan statistik:
  - Total Mahasiswa
  - Jumlah Hadir dan Tidak Hadir Hari Ini
  - Tingkat Kehadiran (%)
- 📂 **Konversi Data ke Excel (.xlsx)**  
  Data absensi dapat **diekspor ke file Excel** dengan sekali klik tombol **“Export to Excel”**, menggunakan library [SheetJS (XLSX)](https://sheetjs.com/).  
  Fitur ini memudahkan analisis data absensi menggunakan Microsoft Excel atau Google Sheets.
- 🗑️ **Clear All Data** untuk menghapus seluruh data absensi dari localStorage

---

## 🛠️ Teknologi yang Digunakan

| Komponen | Teknologi |
|-----------|------------|
| Struktur halaman | HTML 5 |
| Desain / Styling | CSS 3 |
| Logika / Data | JavaScript |
| Penyimpanan sementara | localStorage Browser (Array) |
| Konversi / Ekspor Excel | [SheetJS (XLSX)](https://sheetjs.com/) |

---

## 💡 Rencana Pengembangan

Fitur-fitur berikut direncanakan untuk versi berikutnya:

- 🔗 Integrasi database **MySQL / MariaDB**
- 🌐 Backend menggunakan **PHP Native / Laravel / Node.js**
- 🔒 Sistem login dengan autentikasi & role (Mahasiswa/Admin)
- 📱 Desain responsive (mobile friendly)
- 📈 Dashboard statistik absensi yang lebih interaktif
- 🧾 Riwayat absensi per mahasiswa

---

## 📂 Struktur Folder
/project-folder
│
├── index.html # Halaman utama web
├── Style.css # File styling tampilan
└── README.md # Dokumentasi proyek

---

## ⚙️ Cara Menjalankan

1. Download atau clone repository ini:
   ```bash
   git clone https://github.com/username/nama-repo.git
2. Buka folder project.
3. Jalankan langsung index.html di browser (klik dua kali atau via Live Server di VSCode).
4. Aplikasi akan berjalan langsung di browser tanpa server tambahan.

🧑‍💻 Kontributor

Nama: Davin Gabriel J
Status: Mahasiswa Sistem Informasi
Kampus: Universitas Sriwijaya

📜 Lisensi
Proyek ini bersifat open-source dan dapat dikembangkan lebih lanjut sesuai keinginan pribadi.
Silakan gunakan, modifikasi, dan pelajari untuk keperluan pendidikan atau proyek pribadi.
