# Absen Intra & Ekstrakurikuler

Susunan file (semua di tingkat paling atas repo GitHub):
- index.html  : tampilan aplikasi
- package.json
- api/        : admin.js, student.js, ping.js, _lib.js (server dan database)

Tidak ada vercel.json dan tidak ada folder public. Di Vercel: Framework Preset = Other, Root Directory kosong, hubungkan database Neon (prefix kosong), lalu Redeploy.
Cek server: buka /api/ping di alamat Vercel Anda.
Login admin: admin / admin123 (segera ganti di Pengaturan).
