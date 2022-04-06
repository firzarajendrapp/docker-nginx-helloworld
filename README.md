# Overview
Directory ini berisi 2 file, sebagai berikut:
- File nginx.conf, adalah konfigurasi utama dari program nginx
- File index.html, adalah file teks html

# Tugas
Buat sebuah mekanisme (mempergunakan docker) yang akan mengautomasikan hal-hal sebagai berikut:
- Download standar image dari nginx di dockerhub.com (https://hub.docker.com/_/nginx), lalu
- Muat kedua file (nginx.conf & index.html) kedalam image tersebut, lalu
- Jalankan (run) image tersebut di port 8888, lalu
- Pastikan ketika http://localhost:8888/ menyajikan file index.html.

# Pengumpulan
Kirim semua file konfigurasi yang ada, termasuk juga `docker-compose.yml` dan `Dockerfile`, jika ada.