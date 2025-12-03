# 📚 Portal SAS & Kisi-Kisi Ujian (Template Ruang GTK)

Selamat datang di **repository Portal SAS**. Proyek ini adalah **website statis (Landing Page)** yang dirancang untuk mempublikasikan dokumen ujian seperti **Kisi-kisi**, **Kartu Soal**, dan **Materi Pembelajaran** untuk jenjang **SMK/SMA**.

Desain menggunakan gaya **"Ruang GTK"** yang bersih, modern, dan responsif untuk semua perangkat (Desktop, Tablet, & Mobile).

---

## 🚀 Demo Live

Website dapat diakses melalui link berikut:

🔗 `https://kufy-dev.github.io/portal-sas/`

> *(Ganti link di atas setelah GitHub Pages aktif)*

---

## 📂 Struktur Mapel

Website ini menyajikan dokumen untuk 3 mata pelajaran:

### 💻 Informatika — `inf.html`

* Berisi Kisi-kisi dan Kartu Soal mapel Informatika.
* Menggunakan layout Tailwind CSS untuk tampilan tabel yang rapi.

### 🎨 Desain Grafis — `ddg.html`

* Berisi dokumen ujian Dasar Desain Grafis / Nirmana.
* Dilengkapi fitur **print-ready**.

### 📡 Teknologi Layanan Jaringan — `tlj.html`

* Berisi dokumen mapel TLJ & Infrastruktur Jaringan.

---

## 🛠️ Struktur File

```
/ (Root Directory)
├── index.html        # Halaman Utama (Landing Page)
├── inf.html          # Dokumen Informatika
├── ddg.html          # Dokumen Desain Grafis
├── tlj.html          # Dokumen TLJ
└── README.md         # Dokumentasi
```

---

## ⚙️ Cara Penggunaan & Instalasi

### 1. Upload ke GitHub

Pastikan file berikut diunggah ke root repository:

* `index.html`
* `inf.html`
* `ddg.html`
* `tlj.html`

### 2. Aktivasi GitHub Pages

Agar website online:

1. Masuk ke **Settings** repository.
2. Pilih menu **Pages**.
3. Pada bagian *Build and deployment > Branch*, pilih `main` (atau `master`).
4. Klik **Save**.
5. Tunggu beberapa saat hingga link muncul.

### 3. Kustomisasi Link

Jika nama file mapel diubah, jangan lupa ubah tautan di `index.html`.

**Contoh:**

```html
<a href="nama-file-baru.html" class="sas-item">...</a>
```

---

## ⚠️ Catatan Penting (Dependencies)

File HTML mapel (`inf.html`, `ddg.html`, `tlj.html`) menggunakan script eksternal:

```
<script src="/_sdk/element_sdk.js"></script>
```

Serta Tailwind CSS via CDN.

Perhatian:

> Jika fitur interaktif tidak muncul di GitHub Pages, kemungkinan `element_sdk.js` tidak ditemukan karena path absolut. Pastikan script dapat berjalan **standalone** tanpa dependensi lokal.

---

## 📝 Lisensi

Dibuat untuk keperluan pendidikan & administrasi sekolah.

Desain terinspirasi oleh UI **Ruang GTK**.

Dibuat dengan ❤️ untuk kemudahan administrasi guru.
