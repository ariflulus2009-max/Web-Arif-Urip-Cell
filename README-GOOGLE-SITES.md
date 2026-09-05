# ARIF URIP CELL — GOOGLE SITES V1

Versi ini memakai **tampilan website Arif Urip Cell yang sama** sebagai aplikasi HTML.
Google Sites dipakai sebagai halaman online/wadah, bukan sebagai editor desain utama.

## Cara memasang di Google Sites

1. Upload folder/isi ZIP ini ke hosting web yang menyediakan URL HTTPS.
   Contoh yang mudah: GitHub Pages, Cloudflare Pages, Netlify, atau hosting sendiri.
2. Setelah `index.html` sudah mempunyai URL HTTPS, buka Google Sites.
3. Pilih **Sisipkan / Embed → URL**.
4. Masukkan URL aplikasi dengan tambahan:
   `?embed=1`
5. Atur ukuran embed sesuai kebutuhan halaman.

Contoh bentuk URL:
`https://DOMAIN-ANDA/index.html?embed=1`

> Google Sites tidak menjalankan file ZIP/HTML lokal secara langsung. HTML perlu mempunyai URL HTTPS terlebih dahulu, kemudian URL tersebut di-embed ke Google Sites.

## Yang dipertahankan dari V1

- Tampilan katalog Arif Urip Cell
- Pencarian dan filter
- Login admin demo
- Tambah/edit/hapus produk
- Import Excel/CSV
- Preview import
- Export CSV
- Stok toko dan stok VITUU
- Sinkronisasi VITUU berbasis CSV
- Tombol WhatsApp
- Tampilan responsif untuk HP

## Catatan penting tentang data

Versi ini **masih menggunakan localStorage browser**, sama seperti V1.
Artinya perubahan stok yang dilakukan di satu perangkat/browser **belum otomatis terlihat di perangkat pelanggan atau perangkat admin lain**.

Jadi Google Sites hanya menyelesaikan sisi **publikasi/tampilan online**.
Untuk stok yang benar-benar online dan tersimpan bersama, tahap berikutnya perlu mengganti localStorage dengan database online (misalnya Google Sheets + Apps Script atau Firebase).

## Login demo

Username: `admin`
Password: `admin123`

## Template

`template-import-produk.xlsx` tetap disertakan.
