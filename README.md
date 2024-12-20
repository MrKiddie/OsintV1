# Alat Investigasi OSINT (Open Source Intelligence)

Selamat datang di **Alat Investigasi OSINT**, sebuah tool sederhana yang ditulis menggunakan Bash untuk melakukan investigasi OSINT (Open Source Intelligence). Dengan alat ini, Anda bisa mencari berbagai informasi seperti akun e-wallet, mahasiswa, jejak email, informasi rekening bank, dan detail identitas (NIK).

## Fitur Utama
- **Pencarian Nomor Pembayaran e-wallet** (DANA, GOPAY, OVO, dll.)
- **Pencarian Data Mahasiswa** berdasarkan nama dan universitas
- **Jejak Email** untuk menemukan data terkait email tertentu
- **Cek Nomor Rekening Bank** untuk verifikasi akun bank
- **Cek Identitas NIK KTP** untuk mendapatkan informasi terkait NIK

## Persyaratan Sistem

Sebelum menjalankan alat ini, pastikan Anda telah menginstal beberapa dependensi berikut:

### Penjelasan tambahan:
1. **Install di Termux**: Bagian ini mencakup instruksi penginstalan untuk **npm**, **jq**, **curl**, dan **nik-parse** di **Termux** (untuk perangkat Android).
   - **npm** diinstall dengan `pkg install nodejs`.
   - **jq** diinstall dengan `pkg install jq`.
   - **curl** diinstall dengan `pkg install curl`.
   - **nik-parse** diinstall dengan `npm i nik-parse -g`.

2. **Install di Linux**: Instruksi penginstalan untuk **jq**, **curl**, dan **npm** di **Linux** (Ubuntu/Debian dan CentOS/RHEL) juga sudah dicantumkan.
   - **npm** diinstall dengan `apt install nodejs`.
   - **jq** diinstall dengan `apt install jq`.
   - **curl** diinstall dengan `apt install curl`.
   - **nik-parse** diinstall dengan `npm i nik-parse -g`.
