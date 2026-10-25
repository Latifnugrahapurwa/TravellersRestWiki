# Wiki Personal Travellers Rest

Situs statis satu halaman (tanpa build): panduan kaya & sukses, rumus reputasi, kamar sewa, harga resep, skill tree, guide per level.

## Deploy ke Vercel
1. Buat repo GitHub baru, unggah seluruh isi folder ini (`index.html` harus di root).
2. Di Vercel: Add New > Project > impor repo.
3. Framework Preset: **Other**. Build Command dan Output Directory dikosongkan. Deploy.

## Memperbarui
Edit `index.html`, commit, push; Vercel otomatis deploy ulang. Data resep dan talent ada di blok `<script>` paling bawah (variabel `F`, `D`, `T`). Perbarui tanggal di footer setiap kali data berubah.

## Menambah gambar
Unduh ikon yang dibutuhkan, taruh di `images/`, rujuk dengan path relatif (`images/nama.png`), dan catat sumbernya di `NOTICE.md`. Jangan hotlink langsung dari server wiki.

## Lisensi
Lihat `NOTICE.md`.
