🏥 INFO JADWAL PRAKTEK DOKTER SPESIALIS

<div align="center">

https://img.shields.io/badge/RSU-Siaga_Medika_Purbalingga-blue?style=for-the-badge&logo=hospital&logoColor=white
https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge
https://img.shields.io/badge/Version-2.0-purple?style=for-the-badge

Sistem informasi jadwal praktek dokter spesialis real-time dengan tampilan modern dan responsif

🚀 Live Demo • 📋 Fitur • 🎨 Tampilan • 🛠️ Instalasi

</div>

✨ Features

🎯 Core Features

· 📊 Tampilan Real-time - Update otomatis setiap 10 detik
· 🎨 UI Modern - Desain dengan palet warna biru-ungu-pink yang aesthetic
· 📱 Responsive Design - Optimal di semua device (Desktop, Tablet, Mobile, TV)
· ♿ Aksesibilitas - Support screen reader dan keyboard navigation
· ⚡ Performance - Caching data dan lazy loading

🏥 Status Praktek Dokter

Status Warna Keterangan
🟢 BUKA Hijau Dokter sedang praktek
🟠 PENUH Oranye Kuota pasien penuh
🔵 SELESAI Biru Praktek telah selesai
🟣 CUTI Ungu Dokter sedang cuti
🔴 TIDAK Merah Tidak praktek
⚫ TIDAK ADA POLI Abu-abu Poli tidak tersedia

🛠️ Technical Features

· 🔄 Auto Refresh - Data terupdate secara berkala
· 💾 Cache System - Penyimpanan data sementara
· 📡 Offline Support - Tetap bisa melihat data cache saat offline
· 🎭 Skeleton Loading - UX loading yang smooth
· ✨ Particle Effects - Background animasi yang elegant

🎨 Preview

🖥️ Desktop View

https://via.placeholder.com/800x450/283593/FFFFFF?text=Desktop+View+-+RSU+Siaga+Medika

📱 Mobile View

https://via.placeholder.com/350x700/5c6bc0/FFFFFF?text=Mobile+View+-+Jadwal+Dokter

🎯 Color Palette

```css
Primary: #283593 (Deep Blue)
Secondary: #5c6bc0 (Medium Purple)
Accent: #ec407a (Vibrant Pink)
Background: #f5f5f5 (Light Gray)
```

🚀 Quick Start

Prerequisites

· Web browser modern (Chrome, Firefox, Safari, Edge)
· Koneksi internet untuk data real-time

Installation

1. Clone repository
   ```bash
   git clone https://github.com/username/jadwal-dokter-rsu.git
   cd jadwal-dokter-rsu
   ```
2. Serve dengan web server
   ```bash
   # Menggunakan Python
   python -m http.server 8000
   
   # Menggunakan Node.js
   npx serve .
   
   # Menggunakan PHP
   php -S localhost:8000
   ```
3. Buka di browser
   ```
   http://localhost:8000
   ```

📁 Project Structure

```
jadwal-dokter-rsu/
├── index.html              # Main application file
├── README.md              # Documentation
└── assets/                # Resource files (jika ada)
    ├── images/
    └── icons/
```

⚙️ Configuration

Environment Variables

File HTML sudah terkonfigurasi dengan default values:

```javascript
const REFRESH_INTERVAL = 10000;    // 10 detik
const CACHE_DURATION = 10000;      // 10 detik
const FETCH_TIMEOUT = 10000;       // 10 detik
```

Google Sheets Integration

Aplikasi terhubung dengan Google Sheets sebagai backend:

```javascript
const SHEET_URL = "https://script.google.com/macros/s/.../exec";
```

🎯 Usage

Untuk Pasien

1. Buka website di browser
2. Lihat jadwal dokter spesialis
3. Filter berdasarkan status (Buka/Tutup)
4. Dapatkan informasi real-time

Untuk Administrator

1. Update data di Google Sheets backend
2. Data akan otomatis terupdate di website
3. Monitoring melalui console browser

🔧 Customization

Mengubah Warna Tema

Edit CSS variables di :root:

```css
:root {
  --color-primary: #283593;    /* Warna utama */
  --color-secondary: #5c6bc0;  /* Warna sekunder */
  --color-accent: #ec407a;     /* Warna aksen */
}
```

Menyesuaikan Interval Refresh

Edit konstanta di JavaScript:

```javascript
const REFRESH_INTERVAL = 15000; // Ubah menjadi 15 detik
```

🌐 Browser Support

Browser Version Status
Chrome 60+ ✅ Supported
Firefox 55+ ✅ Supported
Safari 12+ ✅ Supported
Edge 79+ ✅ Supported
Opera 50+ ✅ Supported

📊 Performance

· Load Time: < 3 detik
· Memory Usage: < 50MB
· Data Transfer: < 500KB
· Compatibility: IE11+ (dengan polyfills)

🐛 Troubleshooting

Common Issues

1. Data tidak terupdate
   · Periksa koneksi internet
   · Clear browser cache
   · Check console untuk error
2. Tampilan tidak responsif
   · Refresh halaman
   · Clear cache CSS
3. Offline mode
   · Aplikasi akan menampilkan data cache terakhir

Debug Mode

Aktifkan console browser untuk melihat log:

```javascript
console.log('Debug info:', data);
```

🤝 Contributing

Kontribusi dipersilakan! Silakan:

1. Fork project ini
2. Buat feature branch (git checkout -b feature/AmazingFeature)
3. Commit changes (git commit -m 'Add some AmazingFeature')
4. Push ke branch (git push origin feature/AmazingFeature)
5. Open Pull Request

📝 Changelog

v2.0 (Current)

· ✅ Design system baru dengan palet warna aesthetic
· ✅ Multi-status support (BUKA, PENUH, SELESAI, CUTI, TIDAK, TIDAK ADA POLI)
· ✅ Performance optimization
· ✅ Enhanced accessibility

v1.0

· ✅ Basic functionality
· ✅ Real-time data updates
· ✅ Responsive design

🏥 About RSU Siaga Medika

RSU Siaga Medika Purbalingga adalah rumah sakit terpercaya yang menyediakan layanan kesehatan komprehensif dengan dokter-dokter spesialis berpengalaman.

📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

👥 Team

Developed with ❤️ by IT Department RSU Siaga Medika Purbalingga

---

<div align="center">

💙 Tetap Sehat, Tetap Produktif

"Kesehatan adalah investasi terbaik untuk masa depan yang cerah"

📍 RSU Siaga Medika Purbalingga
Jl. Contoh No. 123, Purbalingga • ☎️ (0281) 123456

[📞 Hubungi Kami] • [🗺️ Lokasi] • [💼 Karir]

</div>
