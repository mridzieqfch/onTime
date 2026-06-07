# Online Timer - Laboratorium SAQ

Aplikasi timer online yang dirancang khusus untuk kebutuhan Universitas SAQ, dengan antarmuka modern dan responsif.

## Fitur Utama

- ⏱️ **Timer Interaktif** - Atur durasi waktu dengan mudah
- 🎨 **Desain Modern** - Antarmuka yang bersih dan user-friendly menggunakan Tailwind CSS
- 📱 **Responsive** - Dapat diakses di berbagai perangkat (desktop, tablet, mobile)
- ⚡ **Real-time Animation** - Animasi smooth dengan efek digit roll yang menarik
- 🎯 **Preset Waktu** - Tombol pintas untuk durasi waktu umum
- 🔔 **Notifikasi** - Pemberitahuan ketika waktu habis

## Teknologi yang Digunakan

- **HTML5** - Struktur halaman
- **CSS3** - Styling dan animasi (Tailwind CSS)
- **JavaScript** - Logika aplikasi
- **Font** - Inter (Google Fonts)

## Struktur Proyek

```
TIMER/
├── docs/
│   └── index.html      # File utama aplikasi
└── README.md           # Dokumentasi (file ini)
```

## Cara Menggunakan

1. Buka file `docs/index.html` di browser favorit Anda
2. Atur durasi timer dengan memasukkan nilai jam, menit, dan detik
3. Klik tombol **Start** untuk memulai timer
4. Timer akan berjalan dan menghitung mundur hingga waktu habis
5. Gunakan tombol **Pause/Resume** untuk menghentikan atau melanjutkan
6. Klik **Reset** untuk mengatur ulang timer

## Fitur Preset

Aplikasi menyediakan tombol preset untuk durasi waktu yang umum digunakan:

- 1 Menit
- 5 Menit
- 10 Menit
- 15 Menit
- 30 Menit
- 1 Jam

## Kompatibilitas

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## Catatan Pengembangan

- Menggunakan `font-variant-numeric: tabular-nums` untuk konsistensi lebar angka pada display timer
- Animasi digit roll per karakter memberikan pengalaman visual yang lebih menarik
- Input number spinner dinonaktifkan untuk kontrol yang lebih baik

## Lisensi

Digunakan untuk keperluan Universitas SAQ

---

Dikembangkan dengan ❤️ untuk Universitas SAQ
