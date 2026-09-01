# 🚀 Sistem Pemantauan Status Server & Uptime Kuma Siap Pakai

[![Lisensi: Open Source](https://img.shields.io/badge/Lisensi-Open%20Source-blue.svg)](#)
[![Deployment: Docker Compose](https://img.shields.io/badge/Deploy-Docker%20Compose-2496ED.svg?logo=docker&logoColor=white)](#)
[![Status: Siap Pakai](https://img.shields.io/badge/Status-Produksi%20Siap%20Pakai-brightgreen.svg)](#)
[![Developer: Muhammad Fikri](https://img.shields.io/badge/Developer-Muhammad%20Fikri-blue.svg)](#)

Platform pemantauan ketersediaan layanan dan latensi jaringan real-time dengan status page publik interaktif, notifikasi multi-kanal (Telegram, Discord, Email), dan sertifikat SSL otomatis.

---

## ⚡ Fitur Utama & Keunggulan Arsitektur
- **Instalasi Sekali Klik:** Dilengkapi skrip otomasi interaktif `install.sh` untuk deployment instan.
- **Konfigurasi Produksi Aman:** Template `.env.example` dengan variabel lingkungan terisolasi dan izin file yang aman.
- **Manajemen Siklus Hidup Layanan:** Termasuk skrip pemeliharaan mandiri (`scripts/backup.sh`, `scripts/restore.sh`, dan update berkala).
- **Kepatuhan Lisensi Open-Source:** Mengikuti lisensi resmi pengembang hulu (*upstream license compliant*).

---

## 🚀 Panduan Instalasi & Penggunaan Cepat

### 1. Kloning Repositori
```bash
git clone https://github.com/muhammadfikri-dev/uptime-kuma-monitoring-stack.git
cd uptime-kuma-monitoring-stack
```

### 2. Konfigurasi Lingkungan
Salin file template konfigurasi dan sesuaikan variabel yang diperlukan:
```bash
cp .env.example .env
nano .env
```

### 3. Menjalankan Layanan
Jalankan skrip instalasi otomatis atau gunakan Docker Compose secara langsung:
```bash
chmod +x install.sh
./install.sh
# Atau eksekusi langsung via docker compose:
docker compose up -d
```

---

## 🛠️ Manajemen & Pemeliharaan Kontainer

- **Melihat Status Layanan:** `docker compose ps`
- **Melihat Log Real-time:** `docker compose logs -f`
- **Mematikan Layanan:** `docker compose down`
- **Membuat Backup Data:** `./scripts/backup.sh`

---

## 📄 Lisensi
Didistribusikan di bawah lisensi resmi open-source. Dikembangkan dan dikonfigurasi untuk standar industri oleh **Muhammad Fikri**.

---

<p align="center">
  Dibuat dengan ❤️ oleh <b>Muhammad Fikri Dev</b>
</p>
