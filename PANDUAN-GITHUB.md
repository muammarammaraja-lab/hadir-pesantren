# 🚀 Upload HadiR ke GitHub Pages
## Gratis · HTTPS Otomatis · Kamera Bisa Jalan

---

## LANGKAH 1 — Daftar GitHub

1. Buka **https://github.com**
2. Klik **"Sign up"**
3. Isi username (contoh: `hadir-pesantren`), email, password
4. Verifikasi email
5. Pilih plan **Free**

---

## LANGKAH 2 — Buat Repository Baru

1. Setelah login, klik tombol **"+"** pojok kanan atas
2. Pilih **"New repository"**
3. Isi:
   - **Repository name:** `hadir-pesantren`
   - **Description:** Sistem Presensi Yayasan Al-Ikhlas
   - Pilih **Public** ✅
   - Centang **"Add a README file"** ✅
4. Klik **"Create repository"**

---

## LANGKAH 3 — Upload File

Di halaman repository, klik **"Add file"** → **"Upload files"**

Upload 3 file ini:
| File Asli | Rename Jadi |
|---|---|
| `hadir-app.html` | `index.html` ← **WAJIB diganti nama!** |
| `hadir-admin.html` | `admin.html` |
| `PANDUAN-SETUP.md` | `README.md` (opsional) |

> ⚠️ File `hadir-app.html` HARUS direname jadi `index.html`
> agar otomatis terbuka saat URL dikunjungi

Setelah upload, isi kotak **"Commit changes"**:
- Tulis: `Upload aplikasi HadiR`
- Klik **"Commit changes"**

---

## LANGKAH 4 — Aktifkan GitHub Pages

1. Di halaman repository, klik **"Settings"** (tab paling kanan)
2. Scroll ke bawah, cari menu **"Pages"** di sidebar kiri
3. Di bagian **"Branch"**, pilih:
   - Branch: **main**
   - Folder: **/ (root)**
4. Klik **"Save"**
5. Tunggu 1-2 menit

---

## LANGKAH 5 — URL Sudah Aktif! 🎉

URL aplikasi Anda:
```
https://USERNAME.github.io/hadir-pesantren/
```

Contoh jika username `budi123`:
```
https://budi123.github.io/hadir-pesantren/          ← Aplikasi staf
https://budi123.github.io/hadir-pesantren/admin.html ← Panel admin
```

Cek di Settings → Pages, akan muncul banner hijau:
**"Your site is live at https://..."**

---

## LANGKAH 6 — Install di HP Staf (PWA)

Bagikan URL ke semua staf via WhatsApp/grup.

### Android (Chrome):
1. Buka URL di Chrome
2. Tap menu **⋮** pojok kanan atas
3. Tap **"Add to Home screen"**
4. Tap **"Add"** → ikon HadiR muncul di layar utama ✅

### iPhone (Safari):
1. Buka URL di **Safari** (bukan Chrome!)
2. Tap tombol **Share** 📤 di bawah layar
3. Scroll → tap **"Add to Home Screen"**
4. Tap **"Add"** → ikon muncul di layar utama ✅

---

## LANGKAH 7 — Isi Konfigurasi Supabase

Setelah Supabase siap (ikuti PANDUAN-SETUP.md), edit file di GitHub:

1. Buka file `index.html` di repository
2. Klik ikon **pensil** ✏️ (Edit file)
3. Cari teks:
   ```
   const SUPABASE_URL = 'ISI_URL_ANDA_DI_SINI';
   const SUPABASE_KEY = 'ISI_ANON_KEY_ANDA_DI_SINI';
   ```
4. Ganti dengan URL dan Key dari Supabase Anda
5. Klik **"Commit changes"**
6. Tunggu 1 menit → otomatis update!

Lakukan hal yang sama untuk `admin.html`.

---

## TIPS

- **Update file:** Tinggal upload ulang file yang sama, GitHub otomatis update
- **Kamera bisa jalan:** GitHub Pages pakai HTTPS otomatis ✅
- **Custom domain:** Bisa pakai domain sendiri (misal: `hadir.pesantren-anda.com`) di Settings → Pages → Custom domain
- **Cek status deploy:** Settings → Pages → lihat status build

---

## BUTUH BANTUAN?

Screenshot error atau pertanyaan → tanya ke Claude! 🙏
