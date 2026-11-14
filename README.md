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

### 4. Video Explainer Cermin Cekung
- File utama: [explainer-cermin-cekung/index.html](explainer-cermin-cekung/index.html)
- Animasi 28 detik, **7 langkah**: pengenalan objek dan cermin, sinar sejajar, sinar pantul melalui F, sinar melalui F, sinar pantul sejajar, titik perpotongan, dan kesimpulan bayangan.
- Dapat diputar, dijeda, diulang, digeser waktunya, dipilih langkahnya, dan diubah kecepatannya langsung pada browser.
- Dibangun menggunakan **HTML, SVG, CSS, JavaScript**, bukan video MP4 atau Remotion. Tidak memerlukan build, backend, atau paket React.
- Contoh matematis: `s=90 cm`, `f=30 cm`, `h=30 cm`; bayangan `s′=45 cm`, `M=−0,5`, `h′=−15 cm`. Berlaku untuk sinar paraksial.

### 5. Visual Explainer Cermin Cekung dengan React
- File utama: [explainer-react-cermin-cekung/index.html](explainer-react-cermin-cekung/index.html).
- Gaya visual **dokumenter/editorial orisinal**, tanpa cuplikan, logo, gambar, musik, atau font pihak lain.
- **React 18.3.1** menggunakan komponen `Illustration`, `PlaybackControls`, `ChapterSidebar`, dan `DataCard`. State pemutaran React menyelaraskan SVG, teks, timeline, serta kontrol interaktif.
- Durasi **48 detik, 7 tahap**. Fitur: putar, jeda, ulangi, pilih tahap, ubah kecepatan, dan geser waktu.
- Dibuat sebagai halaman HTML statis untuk GitHub Pages tanpa npm, Vite, atau build lokal. **React dan ReactDOM dimuat dari CDN**, sehingga koneksi internet diperlukan saat membuka halaman. Berbeda dengan eksplainer ke-04 yang berbasis JavaScript dan SVG biasa.
- Materi contoh tetap sama agar mudah dibandingkan: `s=90 cm`, `f=30 cm`, `h=30 cm`; bayangan `s′=45 cm`, `M=−0,5`, `h′=−15 cm`.
- Hanya untuk model geometris dengan pendekatan sinar paraksial. Ini **animasi web**, belum file video MP4.

Semua halaman simulasi memiliki tautan kembali ke [halaman utama](index.html) dan tautan ke [kanal YouTube BengkelMaFiA](https://www.youtube.com/channel/UCQFua4WLQyzhN3pi0H-nfvA).

## Membuka simulasi

Buka salah satu file `cermin-datar/index.html`, `cermin-cekung/index.html`, `cermin-cembung/index.html`, `explainer-cermin-cekung/index.html`, atau `explainer-react-cermin-cekung/index.html` di Chrome, Edge, atau browser modern lainnya. Tidak memerlukan backend, akun, atau pustaka eksternal.

Jika GitHub Pages diaktifkan dengan sumber **main / (root)**, halaman depan berada di URL project Pages dan simulasi berada di subdirektori `/cermin-datar/`, `/cermin-cekung/`, `/cermin-cembung/`, `/explainer-cermin-cekung/`, dan `/explainer-react-cermin-cekung/`.

> **Catatan publikasi:** Repository ini awalnya private. Ketersediaan GitHub Pages untuk repository private bergantung pada paket GitHub. GitHub Free memerlukan repository public untuk GitHub Pages. Jangan ubah visibility tanpa meninjau apa yang akan dibagikan.

## Pengembangan selanjutnya

Tambahkan simulasi baru dalam subfolder tersendiri (misalnya `hukum-newton/index.html`), lalu buat tautannya pada `index.html` di root repository.
