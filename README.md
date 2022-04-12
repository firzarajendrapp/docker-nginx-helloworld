# Overview
Repository ini memiliki 2 file, sebagai berikut:
- File nginx.conf, adalah konfigurasi utama dari program nginx
- File hello-world.html, adalah file teks html

# Tugas
Buat sebuah mekanisme (mempergunakan docker) yang akan mengautomasikan hal-hal sebagai berikut:
- Download standar image dari nginx di dockerhub.com (https://hub.docker.com/_/nginx), lalu
- Muat kedua file (nginx.conf & hello-world.html) kedalam image tersebut, lalu
- Jalankan (run) image tersebut di port 8888, lalu
- Pastikan ketika http://localhost:8888/ menyajikan file hello-world.html.

## Dasar Penilaian
Nilai penuh bisa didapat ketika tugas ini diselesaikan secara benar, lalu extra points bisa didapatkan dengan menambahkan beberapa fitur/fungsionalitas seperti dibawah ini:
- Mekanisme pembaruan sertifikat SSL
- Nginx berjalan di https
- Redireksi http ke https
- dan lain lain

# Pengumpulan
Kirim semua file konfigurasi yang ada, termasuk juga `docker-compose.yml` dan `Dockerfile`, jika ada. Jangan lupa untuk menyebutkan fitur yang telah di tambahan untuk point extra, ketika melakukan submisi tugas ini.