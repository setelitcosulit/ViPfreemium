# ViPfreemium

ViPfreemium adalah modul untuk KernelSU (atau Magisk) yang dirancang untuk perangkat Android lainnya yang membutuhkan manajemen jaringan otomatis dan modifikasi sistem tingkat lanjut.

## Fitur Utama
* **Auto Network Reset:** Secara otomatis mereset konfigurasi Wi-Fi, IP Address, dan Bluetooth ke pengaturan bawaan pabrik setiap kali perangkat selesai booting.
* **Auto File Deployment:** Mendukung pembuatan folder otomatis dan penyalinan file kustom (seperti `Huawei.v2.sh`) langsung ke direktori sistem atau penyimpanan internal selama proses instalasi.
* **Log System:** Mencatat proses reset jaringan ke dalam file log agar Anda dapat memantau aktivitas modul.
* **Auto Update:** Mendukung pembaruan otomatis melalui fitur *Update Checker* KernelSU.

## Cara Instalasi & Deploy File Kustom
Modul ini mendukung *auto-deployment* file:
1. Modul akan otomatis membuat folder tujuan di `/sdcard/ViPfreemium/`.
2. Skrip pendukung akan diberikan izin akses (chmod 755) agar siap dieksekusi oleh sistem.

## Syarat Penggunaan
* Perangkat harus sudah di-root menggunakan **KernelSU** atau **Magisk**.
* Aplikasi KernelSU/Magisk versi terbaru.

## Cara Instalasi
1. Unduh file `ViPfreemium_v1.1.zip` dari bagian [Releases](https://github.com/setelitcosulit/ViPfreemium/releases).
2. Buka aplikasi KernelSU/Magisk.
3. Masuk ke menu **Modul**.
4. Pilih **Instal dari penyimpanan** dan cari file zip yang telah diunduh.
5. **Reboot** perangkat Anda setelah instalasi selesai.

## Verifikasi Instalasi
Untuk memastikan file telah tersalin dan folder telah dibuat:
1. Buka File Manager (MT Manager/MiXplorer).
2. Cek direktori `/sdcard/ViPfreemium/`.
3. Pastikan file kustom Anda (seperti `Huawei.v2.sh`) sudah ada di sana.

## Changelog
Lihat [changelog.md](changelog.md) untuk melihat daftar perubahan pada setiap versi.

---
*Dibuat oleh setelitcosulit*
