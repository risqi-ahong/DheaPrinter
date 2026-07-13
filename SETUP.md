# 🚀 Panduan Setup GitHub Pages - Dhea Printer

## Status Saat Ini
✅ Semua file sudah terupload ke repository  
✅ Repository bersifat PUBLIC  
✅ Branch main sudah siap  

## ⚡ Langkah-Langkah Mengaktifkan GitHub Pages

### Opsi 1: Auto-Enable via Repository Settings (RECOMMENDED)

1. **Buka Settings Repository**
   - Pergi ke: https://github.com/risqi-ahong/DheaPrinter
   - Klik tab **"Settings"** (ikon gear di kanan atas)

2. **Aktifkan GitHub Pages**
   - Di sidebar kiri, scroll ke bawah
   - Cari dan klik **"Pages"**
   
3. **Konfigurasi Source**
   - Di section "Build and deployment"
   - **Source**: Pilih **"Deploy from a branch"**
   - **Branch**: Pilih **"main"** dan folder **"/ (root)"**
   - Klik **"Save"**

4. **Tunggu Deployment**
   - GitHub akan mulai build (1-2 menit)
   - Refresh halaman Settings
   - Cari notifikasi biru dengan URL seperti:
     ```
     Your site is live at https://risqi-ahong.github.io/DheaPrinter/
     ```

### Opsi 2: Menggunakan GitHub Actions (Sudah Setup)

Workflow GitHub Actions sudah dikonfigurasi di `.github/workflows/pages.yml`
- Workflow otomatis berjalan setiap kali ada push ke branch main
- Tidak perlu konfigurasi manual lagi

### Opsi 3: Cek Status via CLI (Jika sudah login ke Git)

```bash
# Clone repository lokal
git clone https://github.com/risqi-ahong/DheaPrinter.git
cd DheaPrinter

# Cek status
git status
```

## ✨ File yang Sudah Terupload

| File | Ukuran | Status |
|------|--------|--------|
| `index.html` | 15.4 KB | ✅ Aktif |
| `styles.css` | 11.3 KB | ✅ Aktif |
| `script.js` | 5.5 KB | ✅ Aktif |
| `manifest.json` | 668 B | ✅ Aktif |
| `_config.yml` | 220 B | ✅ Aktif |
| `README.md` | 4.3 KB | ✅ Aktif |
| `.gitignore` | 258 B | ✅ Aktif |
| `.github/workflows/pages.yml` | 895 B | ✅ Aktif |

## 🎯 URL Website Setelah Enable Pages

```
https://risqi-ahong.github.io/DheaPrinter/
```

## ⚠️ Troubleshooting

### GitHub Pages tidak muncul di Settings?

**Solusi:**
1. Pastikan repository **PUBLIC** (bukan Private)
2. Repository harus memiliki minimal 1 commit (✅ sudah ada 8 commits)
3. Tunggu beberapa detik, lalu refresh halaman Settings

### Masih error setelah Enable Pages?

**Coba:**
1. Disable Pages (unchecked), tunggu 1 menit
2. Enable kembali Pages
3. Pastikan branch "main" dipilih

### Website blank atau error 404?

**Cek:**
1. File `index.html` ada di root repository ✅
2. Semua CSS dan JS ter-link dengan benar ✅
3. Tunggu 5-10 menit untuk GitHub Pages fully deploy
4. Clear browser cache (Ctrl+Shift+Delete)

## 🔗 Links Penting

- **Repository**: https://github.com/risqi-ahong/DheaPrinter
- **GitHub Pages URL**: https://risqi-ahong.github.io/DheaPrinter/ (after enabled)
- **Raw Files**: https://raw.githubusercontent.com/risqi-ahong/DheaPrinter/main/

## 📞 Support

Jika masih ada masalah:
1. Hubungi Dhea Printer: **088215102978**
2. Email: **info@dheaprinter.com**
3. Atau buka Issue di repository

---

**Catatan**: Setelah GitHub Pages diaktifkan, website akan otomatis update setiap kali ada push ke branch main.

**Dibuat**: 13 Juli 2026
