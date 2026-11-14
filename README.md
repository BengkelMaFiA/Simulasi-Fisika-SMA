# Simulasi Fisika SMA — BengkelMaFiA

Laboratorium virtual berbasis HTML, CSS, dan JavaScript yang dapat dibuka melalui browser tanpa instalasi tambahan.

## Simulasi yang tersedia

### 1. Cermin Datar
- File utama: [cermin-datar/index.html](cermin-datar/index.html)
- **Mode hukum pemantulan:** ubah sudut datang `θᵢ`, amati sudut pantul `θᵣ` yang sama besar; keduanya diukur terhadap **garis normal**, bukan permukaan.
- **Mode pembentukan bayangan:** ubah jarak dan tinggi benda. Bayangan **maya, tegak, sama besar**, dan berada simetris di belakang cermin.
- Simulasi memperlihatkan sinar, garis normal, busur sudut, perpanjangan sinar maya, animasi, reset, dan ekspor diagram PNG.
- Konvensi: `θᵢ = θᵣ`, `s′ = −s`, `M = +1`, `h′ = h`.

### 2. Cermin Cekung
- File utama: [cermin-cekung/index.html](cermin-cekung/index.html)
- Geser benda **di luar C, tepat C, antara C dan F, tepat F, dan di dalam F**.
- Bandingkan bayangan nyata/maya, terbalik/tegak, diperbesar/diperkecil.
- Pada `s = f`, sinar pantul sejajar dan bayangan berada di tak hingga.
- Konvensi: `f > 0`, `s′ > 0` untuk bayangan nyata, `s′ < 0` untuk bayangan maya, dan `M = −s′/s`.

### 3. Cermin Cembung
- File utama: [cermin-cembung/index.html](cermin-cembung/index.html)
- Ubah **jarak benda**, **besar panjang fokus**, dan **tinggi benda**.
- Amati sinar utama, perpanjangan sinar maya, posisi bayangan, dan hasil numeriknya.
- Bayangan senantiasa **maya, tegak, diperkecil** untuk benda nyata di depan cermin.
- Konvensi: `f < 0`, `s′ < 0`, dan `0 < M < 1`.

Semua halaman simulasi memiliki tautan kembali ke [halaman utama](index.html) dan tautan ke [kanal YouTube BengkelMaFiA](https://www.youtube.com/channel/UCQFua4WLQyzhN3pi0H-nfvA).

## Membuka simulasi

Buka salah satu file `cermin-datar/index.html`, `cermin-cekung/index.html`, atau `cermin-cembung/index.html` di Chrome, Edge, atau browser modern lainnya. Tidak memerlukan backend, akun, atau pustaka eksternal.

Jika GitHub Pages diaktifkan dengan sumber **main / (root)**, halaman depan berada di URL project Pages dan simulasi berada di subdirektori `/cermin-datar/`, `/cermin-cekung/`, dan `/cermin-cembung/`.

> **Catatan publikasi:** Repository ini awalnya private. Ketersediaan GitHub Pages untuk repository private bergantung pada paket GitHub. GitHub Free memerlukan repository public untuk GitHub Pages. Jangan ubah visibility tanpa meninjau apa yang akan dibagikan.

## Pengembangan selanjutnya

Tambahkan simulasi baru dalam subfolder tersendiri (misalnya `hukum-newton/index.html`), lalu buat tautannya pada `index.html` di root repository.
