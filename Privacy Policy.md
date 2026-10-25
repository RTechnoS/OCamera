# Kebijakan Privasi (Privacy Policy) - OCamera

**Terakhir diperbarui:** 25 Oktober 2026

Aplikasi **OCamera** ("kami", "aplikasi") berkomitmen untuk melindungi privasi pengguna. Dokumen ini menjelaskan bagaimana kami mengelola data pada perangkat Anda.

---

## 1. Prinsip Utama Privasi
- **100% Pemrosesan di Perangkat (On-Device):** Seluruh foto, video, metadata, dan stempel waktu (*timestamp*) diproses secara lokal langsung di perangkat Android Anda.
- **Tanpa Iklan & Tanpa Pelacak (No Ads, No Trackers):** OCamera tidak menyematkan SDK analitik pihak ketiga, SDK pelacak perilaku, maupun SDK jaringan periklanan.
- **Data Tidak Dikirim ke Server:** Kami tidak memiliki server penyimpanan data eksternal untuk menyimpan foto, video, ataupun identitas Anda.

---

## 2. Izin yang Digunakan & Alasannya

Aplikasi OCamera meminta izin sistem Android berikut semata-mata untuk fungsi utama aplikasi:

| Izin Sistem (*Permission*) | Tujuan Penggunaan |
| :--- | :--- |
| **Kamera (`android.permission.CAMERA`)** | Diperlukan untuk mengambil foto dan merekam video dengan bidikan lensa perangkat. |
| **Mikrofon (`android.permission.RECORD_AUDIO`)** | Diperlukan untuk merekam audio bersamaan dengan perekaman video. Audio tidak pernah direkam saat memotret foto. |
| **Lokasi Akurat & Perkiraan (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`)** | Diperlukan untuk membaca koordinat GPS, ketinggian (*altitude*), akurasi, dan alamat jalan agar dapat dicetak sebagai stempel *watermark* pada foto/video dan disimpan ke metadata EXIF atas persetujuan pengguna. Lokasi **hanya dibaca saat aplikasi sedang aktif dibuka (foreground)** dan tidak pernah dilacak di latar belakang (*no background tracking*). |
| **Internet (`android.permission.INTERNET`)** | Digunakan hanya untuk mengunduh ubin peta mini (*mini-map tile*) dan menerjemahkan koordinat GPS menjadi nama jalan (*reverse geocoding*). Tidak ada data pribadi atau foto yang diunggah ke internet. |
| **Getaran (`android.permission.VIBRATE`)** | Memberikan umpan balik haptic saat menekan tombol rana kamera (*shutter*) dan mengunci fokus. |
| **Penyimpanan Eksternal (`WRITE_EXTERNAL_STORAGE` maks. Android 9)** | Pada Android 9 ke bawah, izin ini diperlukan untuk menyimpan foto dan video ke folder publik `Pictures/OCamera` dan `Movies/OCamera`. Pada Android 10 ke atas, aplikasi menggunakan *Scoped Storage* (`MediaStore`) tanpa memerlukan izin penyimpanan khusus. |

---

## 3. Keamanan Data & Waktu Otomatis (Anti-Tamper)
OCamera membaca status pengaturan waktu otomatis perangkat (`Settings.Global.AUTO_TIME`) untuk memastikan keabsahan waktu pada dokumentasi kerja lapangan Anda. Data ini hanya divalidasi secara lokal untuk mencegah manipulasi tanggal/jam manual.

---

## 4. Perlindungan Anak
Aplikasi kami tidak ditujukan secara khusus untuk anak-anak di bawah usia 13 tahun, dan kami tidak pernah mengumpulkan data pribadi apa pun dari pengguna dari segala usia.

---

## 5. Hubungi Kami
Jika Anda memiliki pertanyaan mengenai kebijakan privasi ini atau penggunaan aplikasi OCamera, Anda dapat menghubungi pengembang melalui:
- **Email:** support@ocamera.app (atau email akun Google Play Console Anda)
- **Website:** https://ocamera.app

