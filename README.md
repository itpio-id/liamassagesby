# liamassagesby

Website statis Lia Massage Surabaya. `index.html` adalah satu-satunya halaman yang dipakai untuk hosting; `ipehpijat.html` dan `ipehchrome.html` tetap disimpan sebagai versi alternatif dan tidak ikut di-deploy.

## Preview lokal

Jalankan server statis dari folder ini, lalu buka alamat lokalnya:

```powershell
python -m http.server 8000
```

Buka `http://localhost:8000`.

## Deploy

Folder deploy Vercel berisi `index.html` dan aset yang dirujuk dari `assets/images/`, tanpa langkah build.

## Isi

- `assets/images/` — gambar dan logo situs
- `assets/source/` — file sumber aset
- `PHOTO-CREDITS.md` — kredit dan lisensi foto
- `ipehheadshot.jpeg`, `namecard.jpeg`, dan gambar di folder utama — aset tambahan proyek
- `robots.txt`, `sitemap.xml`, dan `llms.txt` — aturan crawler dan discovery
- `SEO-GEO-AUDIT.html` — temuan audit teknis serta copy profil direktori
