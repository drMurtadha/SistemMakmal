# 🌐 Panduan Langkah Demi Langkah: Terbitkan ke GitHub Pages

## Prasyarat

- [ ] Akaun GitHub (percuma di github.com)
- [ ] Fail `index.html` siap
- [ ] Sambungan internet

---

## LANGKAH 1: Daftar Akaun GitHub

1. Pergi ke **https://github.com**
2. Klik **"Sign up"** (sudut kanan atas)
3. Masukkan:
   - Username (cth: `drMurtadha`)
   - E-mel
   - Kata laluan
4. Sahkan e-mel anda

---

## LANGKAH 2: Cipta Repository Baharu

1. Selepas log masuk, klik ikon **"+"** (sudut kanan atas)
2. Pilih **"New repository"**
3. Tetapkan:
   - **Repository name**: `SistemMakmal`
   - **Description**: Aplikasi Web Pengurusan Makmal
   - **Visibility**: ✅ Public (PENTING untuk GitHub Pages percuma)
   - **Add a README file**: ✅ Tandakan
4. Klik **"Create repository"**

---

## LANGKAH 3: Muat Naik Fail index.html

1. Dalam halaman repository, klik **"Add file"** → **"Upload files"**
2. Seret fail `index.html` ke kawasan muat naik, ATAU klik **"choose your files"**
3. Di bahagian **"Commit changes"**:
   - Tajuk: `Tambah aplikasi SistemMakmal`
4. Klik **"Commit changes"** (butang hijau)

---

## LANGKAH 4: Aktifkan GitHub Pages

1. Klik tab **"Settings"** (gear icon) dalam halaman repository
2. Dalam menu sebelah kiri, klik **"Pages"**
3. Di bawah **"Build and deployment"**:
   - **Source**: Deploy from a branch
   - **Branch**: `main`
   - **Folder**: `/ (root)`
4. Klik **"Save"**

---

## LANGKAH 5: Tunggu Deployment

1. Muat semula halaman Settings > Pages selepas 1–3 minit
2. Anda akan nampak mesej hijau:
   > ✅ Your site is live at **https://[username].github.io/SistemMakmal**

---

## LANGKAH 6: Akses dan Kongsi URL

URL awam anda: `https://[username].github.io/SistemMakmal`

Contoh: `https://drmurtadha.github.io/SistemMakmal`

### Cara Kemaskini Aplikasi

Setiap kali anda kemaskini `index.html`:
1. Pergi ke repository di GitHub
2. Klik pada fail `index.html`
3. Klik ikon pensel (Edit)
4. Buat perubahan
5. Klik "Commit changes"
6. Tunggu 1–2 minit — perubahan akan aktif secara automatik

---

## Penyelesaian Masalah

| Masalah | Penyelesaian |
|---------|-------------|
| URL tidak berfungsi | Tunggu 5 minit dan cuba semula |
| Halaman 404 | Pastikan fail bernama `index.html` (bukan `Index.html`) |
| Perubahan tidak nampak | Tekan Ctrl+Shift+R untuk muat semula cache |
| Repository Private | Tukar ke Public dalam Settings > Danger Zone > Change visibility |

---

*Untuk pertanyaan: murtadha@utm.my*
