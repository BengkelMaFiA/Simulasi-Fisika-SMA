# Simulasi Fisika SMA — BengkelMaFiA

Laboratorium virtual berbasis HTML, CSS, dan JavaScript yang dapat dibuka melalui browser tanpa instalasi tambahan.

## Simulasi yang tersedia

### 1. Cermin Cembung
- File utama: [cermin-cembung/index.html](cermin-cembung/index.html)
- Ubah **jarak benda**, **panjang fokus**, dan **tinggi benda**.
- Amati **tiga sinar utama**, **perpanjangan sinar maya**, dan **posisi bayangan**.
- Periksa **jarak bayangan**, **perbesaran**, dan **tinggi bayangan** secara real-time.
- Tersedia animasi otomatis, reset, serta penyimpanan diagram ke PNG.

**Konvensi tanda:** untuk benda nyata di depan cermin cembung, `s > 0`, `f < 0`, `s' < 0`, dan `0 < M < 1`. Bayangan bersifat **maya, tegak, dan diperkecil**. Gunakan persamaan `1/f = 1/s + 1/s'` dan `M = -s'/s = h'/h`.

## Membuka simulasi

Buka `cermin-cembung/index.html` dalam Chrome, Edge, atau browser modern lainnya. Tidak memerlukan backend, akun, atau pustaka eksternal.

Jika GitHub Pages diaktifkan dengan sumber **main / (root)**, halaman depan berada di URL project Pages dan simulasi berada di subdirektori `/cermin-cembung/`.

> **Catatan publikasi:** Repository ini awalnya private. Ketersediaan GitHub Pages untuk repository private bergantung pada paket GitHub. GitHub Free memerlukan repository public untuk GitHub Pages. Jangan ubah visibility tanpa meninjau apa yang akan dibagikan.

## Pengembangan selanjutnya

Tambahkan simulasi baru dalam subfolder tersendiri (misalnya `hukum-newton/index.html`), lalu buat tautannya pada `index.html` di root repository.
