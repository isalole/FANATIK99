# Fanatik99 — Paket Perbaikan SEO

Website statis responsif untuk domain utama `https://fanatik99.vercel.app/`.

## Isi paket
- `index.html` — halaman informasi dengan panduan pemeriksaan situs, keamanan akun, privasi, risiko layanan digital, FAQ, metadata SEO, canonical, Open Graph, dan data terstruktur WebSite.
- `robots.txt` — mengizinkan crawling dan menunjuk sitemap.
- `sitemap.xml` — sitemap URL utama dengan tanggal pembaruan.
- `favicon.svg` — ikon situs.
- `google029609a9c3f95b6c.html` — file verifikasi Search Console; pertahankan file ini.

## Deploy ke Vercel
1. Ekstrak ZIP.
2. Unggah isi folder `FANATIK99-main` ke repositori GitHub yang terhubung ke proyek Vercel, atau unggah proyek sesuai alur deployment yang kamu gunakan.
3. Untuk situs HTML statis, tidak perlu build command; gunakan folder root sebagai output jika diminta.
4. Deploy, lalu periksa:
   - `https://fanatik99.vercel.app/`
   - `https://fanatik99.vercel.app/robots.txt`
   - `https://fanatik99.vercel.app/sitemap.xml`

## Setelah deploy
1. Pastikan halaman utama mengembalikan HTTP 200 dan tidak mengalami redirect berulang.
2. Pastikan HTML live menampilkan canonical `https://fanatik99.vercel.app/`.
3. Pastikan tidak ada `noindex` dari HTML, header HTTP, atau konfigurasi hosting.
4. Di Google Search Console, jalankan **Test Live URL**. Jika dapat diakses dan pengindeksan diizinkan, minta pengindeksan ulang.
5. Kirim `https://fanatik99.vercel.app/sitemap.xml` melalui menu Sitemaps.

## Catatan penting
- Domain utama dan canonical sengaja dipertahankan pada `fanatik99.vercel.app`; jangan mencampurnya dengan `fanatik99.my.id` atau `fantik99.com` tanpa rencana migrasi yang benar.
- Tombol eksternal tetap menuju `https://fantik99.com/akzg`. Halaman menyatakan secara jelas bahwa tautan itu membuka domain berbeda dan tidak mengklaim telah memverifikasi identitas, izin, legalitas, atau keamanan tujuan.
- Pastikan seluruh keterangan dan pengungkapan di halaman sesuai dengan hubungan sebenarnya antara kamu dan situs tujuan.
- Sitemap membantu Google menemukan URL, tetapi tidak menjamin pengindeksan atau ranking. Google dapat memilih untuk tidak mengindeks halaman.
