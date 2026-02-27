**Project Overview**
- **Name:** Atha | Portfolio — single-page personal portfolio.
- **Purpose:** Menampilkan profil singkat, keterampilan, pengalaman, dan sertifikat.

**Technologies**
- **HTML:** Struktur halaman (`index.html`).
- **CSS:** Styling kustom (`style.css`).
- **Bootstrap 5:** Grid, responsive utilities, dan komponen ringan (ditautkan via CDN).

**File Structure**
- `index.html`: markup halaman utama (navbar, hero, about, skills, certificates, footer).
- `style.css`: semua aturan gaya kustom (tema, layout, responsive tweaks).
- `images/`: aset gambar yang digunakan di About & Certificates.

**Sections & Features**
- **Navbar:** Link internal ke setiap section. Styling flex untuk center vertikal; class `.nav-menu` mengontrol layout tautan.
- **Hero / Home:** Judul pembuka dan deskripsi singkat. Berada di `#home`.
- **About:** Gambar profil + deskripsi; di-layout menggunakan Bootstrap grid (`row` + `col-`) agar responsif.
- **Skills:** Section terpisah `#skills` dengan progress bars kustom (`.progress-bar`, `.progress-fill`). Background bertema (`.bg-strawberry` yang diubah jadi soft matcha).
- **Certificates:** Kartu sertifikat menggunakan grid CSS (`.card-grid`) dan gaya card sederhana.
- **Footer:** Credits sederhana.

**Notes & Tips**
- Untuk mengubah warna tema matcha, edit variabel warna di `style.css` pada class `.bg-strawberry`.
- Jika ingin menambah interaktivitas (mis. animasi, filter gambar), pertimbangkan menambahkan JavaScript atau framework ringan (Vue/React).

**How to run locally**
1. Buka folder proyek di file explorer.
2. Klik dua kali `index.html` atau buka di browser.

**Git / Deployment**
- Untuk mem-push ke repo yang sudah ada:

```bash
git init            # (jika belum ada)
git add .
git commit -m "initial commit"
git remote add origin <remote_url>
git branch -M main
git push -u origin main
```

**Want changes?**
- Beritahu saya bagian mana yang mau diubah (warna, layout, responsivitas, atau menambahkan script).