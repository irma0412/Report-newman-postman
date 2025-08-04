# API Testing Report - Postman Collection & Newman CLI 🚀

Hai! Ini adalah project API Testing Automation yang aku jalankan menggunakan Postman Collection & Newman CLI.

# Project ini bertujuan untuk:

- Membuat API Test Collection di Postman
- Menjalankan otomatisasi via Newman (Command Line Interface)
- Generate laporan testing dalam bentuk HTML Report

⚠️ Catatan: Untuk saat ini eksekusinya masih dilakukan manual melalui CLI, belum terhubung ke CI/CD Pipeline (seperti GitHub Actions atau Jenkins). Tapi flow testingnya sudah menggunakan prinsip otomasi. ✨

# 📂 Apa Aja Isinya?
HTML Report (Hasil Newman Run) → Bisa langsung dilihat di GitHub Pages Report Link

- Postman Collection → File JSON API Reqres.in.
- Postman Environment → File JSON Environment (Base URL, API Key, dll).

# 🔗 Coba Collection-nya?
Bisa import langsung ke Postman:
link nyusul yahh

🛠️ Cara Jalanin via Newman (Manual Execution)
Install Newman → npm install -g newman

# Run Collection dengan Environment →


newman run API_postman_collection.json -e env_postman.json -r htmlextra
Laporan HTML akan di-generate otomatis.