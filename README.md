# 💍 Undangan Pernikahan Digital Premium (Free Template)

Template undangan pernikahan digital berbasis web statis (HTML, CSS, JS) dengan desain *clean*, minimalis, dan estetik ala *glassmorphism*. Dibuat untuk mudah digunakan dan dikustomisasi oleh siapa saja tanpa perlu pemahaman coding yang mendalam.

**Project by:** Draftgraphy

---

## ✨ Fitur Utama
- **Video Background:** Menggunakan video sebagai latar belakang utama yang berjalan otomatis.
- **Clean & Minimalist Design:** Elemen UI tembus pandang (*outline/glassmorphism*) yang mewah.
- **Auto-Scrolling Gallery:** Cukup masukkan foto ke folder dengan angka berurutan, sistem akan menyusun dan menggulungnya secara otomatis.
- **Built-in Audio Player:** Musik latar yang berputar mulus dengan kontrol *play/pause* estetik.
- **Bilingual Copywriting:** Teks estetik dalam bahasa Indonesia & Inggris.
- **Fully Responsive:** Tampilan rapi di layar HP (Mobile), Tablet, maupun Laptop/PC.

---

## 📁 Struktur Folder

Untuk mulai menggunakan template ini, pastikan susunan folder Anda seperti di bawah ini:

```text
📁 undangan-pernikahan/
├── 📄 index.html                # File utama (Edit teks, nama, dan tanggal di sini)
├── 📄 README.md                 # Petunjuk penggunaan ini
└── 📁 asset/
    ├── 📁 audio/
    │   └── 🎵 song.mp3          # File musik latar (Background music)
    ├── 📁 video/
    │   └── 🎬 sample.mp4        # File video background
    └── 📁 image/
        ├── 📁 bride/
        │   ├── 🖼️ man.jpg       # Foto mempelai pria
        │   └── 🖼️ woman.jpg     # Foto mempelai wanita
        └── 📁 galery/
            ├── 🖼️ 1.jpg         # Foto galeri 1
            ├── 🖼️ 2.jpg         # Foto galeri 2
            ├── 🖼️ 3.jpg         # Foto galeri 3
            └── 🖼️ ... (dan seterusnya)
```

---

## 🛠️ Cara Kustomisasi (Langkah demi Langkah)

### 1. Mengganti Video Background
- Siapkan video potret/landscape yang Anda inginkan (sangat disarankan ukuran file di bawah 5MB agar loading cepat).
- Ubah nama video Anda menjadi **`sample.mp4`**.
- Pindahkan dan timpa (*replace*) file tersebut ke dalam folder: `asset/video/`

### 2. Mengganti Foto Mempelai
- Siapkan 2 foto terbaik untuk masing-masing mempelai.
- Ubah nama foto mempelai pria menjadi **`man.jpg`**.
- Ubah nama foto mempelai wanita menjadi **`woman.jpg`**.
- Masukkan kedua foto tersebut ke dalam folder: `asset/image/bride/`

### 3. Memasukkan Foto Pre-Wedding (Galeri)
Template ini dilengkapi fitur **Auto-Loader**. Anda tidak perlu memasukkan foto satu per satu ke dalam kode (HTML).
- Siapkan foto-foto galeri Anda dalam format **.jpg**.
- Ubah nama foto menjadi angka berurutan: **`1.jpg`**, **`2.jpg`**, **`3.jpg`**, dst.
- Masukkan semua foto tersebut ke dalam folder: `asset/image/galery/`
- *Website akan mendeteksi jumlah foto secara otomatis dan memutar galerinya!*

### 4. Mengganti Musik (Backsound)
- Siapkan lagu romantis pilihan Anda dalam format **.mp3**.
- Ubah nama lagunya menjadi **`song.mp3`**.
- Pindahkan ke dalam folder: `asset/audio/`

### 5. Mengedit Teks (Nama, Tanggal, dan Lokasi)
Untuk mengubah nama mempelai, tanggal acara, lokasi, dan nomor rekening, Anda perlu membuka file **`index.html`** menggunakan *Text Editor* (seperti Notepad, Notepad++, atau VS Code).

Tekan `Ctrl + F` (Cari) untuk mempermudah menemukan bagian ini:
- Cari kata **"Romeo"** dan **"Juliet"** lalu ganti dengan nama Anda berdua.
- Cari tanggal **"12 Desember 2026"** dan sesuaikan dengan tanggal pernikahan Anda.
- Cari bagian **"BCA"** atau **"MANDIRI"** untuk mengganti nomor rekening Angpao Digital.

---

## 🚀 Cara Menjalankan & Mempublikasikan
1. **Tes Lokal:** Cukup klik dua kali (*double-click*) pada file `index.html`. Website akan terbuka di browser Anda (Chrome/Safari).
2. **Publikasi Online (Gratis):** 
   Anda bisa mengupload seluruh folder ini (gratis) menggunakan layanan hosting statis seperti:
   - [GitHub Pages](https://pages.github.com/)
   - [Vercel](https://vercel.com/)
   - [Netlify](https://www.netlify.com/)

---
*Dibuat dengan ❤️ oleh Draftgraphy.*