# Analisis Kehilangan Tutupan Pohon di Provinsi Bengkulu (2001–2025)

## Deskripsi Proyek

Proyek ini menganalisis perubahan kehilangan tutupan pohon (*tree cover loss*) di Provinsi Bengkulu selama periode 2001–2025 menggunakan Python dan Google Colab.

Analisis dilakukan untuk memahami pola kehilangan tutupan pohon dari tahun ke tahun, membandingkan rata-rata kehilangan pada periode lima tahunan, serta mengidentifikasi kecenderungan perubahan selama periode pengamatan.

## Tujuan

- Menganalisis perubahan kehilangan tutupan pohon tahunan di Provinsi Bengkulu.
- Mengidentifikasi tahun dengan kehilangan tertinggi dan terendah.
- Membandingkan rata-rata kehilangan tutupan pohon dalam periode lima tahunan.
- Mengamati kecenderungan perubahan jangka panjang melalui analisis tren.

## Sumber Data

Data diperoleh dari [Global Nature Watch](https://www.globalnaturewatch.org/), dengan wilayah analisis Provinsi Bengkulu, Indonesia, dan periode pengamatan 2001–2025.

Data tahunan yang digunakan mencakup tahun pengamatan dan luas kehilangan tutupan pohon dalam hektare.

## Metode Analisis

1. Pengumpulan dan pemuatan data CSV.
2. Pemeriksaan struktur, kelengkapan, dan konsistensi data.
3. Visualisasi kehilangan tutupan pohon tahunan.
4. Perhitungan rata-rata bergerak lima tahunan.
5. Perbandingan rata-rata kehilangan antarperiode lima tahunan.
6. Analisis perubahan tahunan dalam hektare dan persentase.
7. Analisis tren linear dan interpretasi hasil.

## Hasil Utama

Berdasarkan pengolahan data awal:

- Periode pengamatan mencakup 25 tahun, yaitu 2001–2025.
- Kehilangan tutupan pohon tahunan tertinggi tercatat pada 2023, sekitar 29.913 hektare.
- Kehilangan tutupan pohon tahunan terendah tercatat pada 2003, sekitar 8.104 hektare.
- Rata-rata kehilangan tahunan meningkat dari sekitar 14.370 hektare pada periode 2001–2005 menjadi sekitar 23.239 hektare pada periode 2021–2025.

Angka dan visualisasi akhir akan disesuaikan dengan hasil yang tersimpan dalam notebook dan file keluaran proyek.

## Tools

- Python
- Google Colab
- Pandas
- Matplotlib
- NumPy

## Struktur Proyek

- `deteksi_deforestasi.ipynb` — notebook analisis.
- `data/` — data masukan dan dokumentasi sumber data.
- `outputs/` — grafik, tabel, dan ringkasan hasil analisis.

## Keterbatasan

Kehilangan tutupan pohon (*tree cover loss*) tidak selalu identik dengan deforestasi permanen. Analisis ini berfokus pada pola temporal dan belum membuktikan penyebab perubahan yang diamati.

## Lisensi dan Penggunaan Data

Sebelum menggunakan ulang atau mendistribusikan data, periksa ketentuan penggunaan dan atribusi dari penyedia data. Cantumkan sumber data saat hasil proyek digunakan dalam laporan atau penelitian lain.
