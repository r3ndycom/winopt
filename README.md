# 📝 Changelog – Windows Ultimate Optimizer [WUOptimizer]

## 🚀 [8.2] – 15 Sep 2025
### ✨ Perubahan Utama
- 🔒 **Validasi OS lebih ketat**
  - Menu 1–4 & 8 hanya bisa dijalankan di **Windows 11**
  - Menu 6 hanya untuk **Windows 10**
  - Pesan menu invalid diperbarui: `[!] Pilihan tidak valid hanya OS Windows 11`

- 🛠️ **Perbaikan Menu 3 & 4**
  - Tidak muncul error `'Klik'` dan `'tips'`
  - Simbol `[✓]` diganti `[OK]` agar kompatibel **Windows 10**

- 🗑️ **Menu 6 – Hapus Bloatware Windows 10 diperluas**
  - Menambahkan **Cortana, Copilot, Groove Music, Solitaire, Maps, Mail, Office, OneNote, Xbox, Xbox Game Tools**
  - Shortcut aplikasi dihapus otomatis
  - Proses aplikasi dimatikan sebelum uninstall agar tidak gagal
  - Penghapusan provisioning package agar aplikasi tidak muncul di user baru

- 🎨 **Konsistensi tampilan & simbol**
  - `[OK]` untuk status sukses
  - `[!]` untuk error atau validasi
  - `[*]` untuk proses berjalan

- 🛡️ **Peningkatan keamanan & stabilitas**
  - Script auto-elevate dijamin jalan sebagai Administrator
  - Semua perintah PowerShell menggunakan `-ErrorAction SilentlyContinue` untuk menghindari error saat aplikasi tidak ditemukan
