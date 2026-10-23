# Penerimaan Sampel – Laboratorium Tanah dan Lingkungan

Aplikasi web administrasi penerimaan sampel analisis, Laboratorium Tanah dan Lingkungan,
Fakultas Pertanian, Universitas Udayana.

## Isi formulir
1. Kop surat: Kementerian Pendidikan Tinggi, Sains, dan Teknologi · Universitas Udayana · Fakultas Pertanian · Laboratorium Tanah dan Lingkungan
2. Nama pengirim
3. Jenis sampel: Tanah, Pupuk, Kompos, POC, Air, Tanaman
4. Banyaknya sampel (per jenis, total dihitung otomatis)
5. Lokasi sampel
6. Tanggal taruh sampel

Biaya analisis: kategori pemohon A/B/C (Rincian Biaya Analisis Tanah 2022) dan daftar
centang 31 analisis tanah + 4 analisis jaringan tanaman. Harga, subtotal, total, dan terbilang
dihitung otomatis dan tercetak di tanda terima. Tarif ada di variabel `ANALISIS` dalam `index.html`.

Pengecualian kategori A: pilih "Dikerjakan oleh". Laboran = harga penuh kategori A.
Mahasiswa sendiri = potongan 40% dari harga total (dibayar 60%); potongan, total dibayar, dan
keterangannya hanya muncul di tanda terima bila dikerjakan mahasiswa.

Tambahan: nomor registrasi otomatis (`001/LTL-FP/X/2026`), tanda terima siap cetak A4
dengan kolom tanda tangan, register sampel dengan pencarian, dan ekspor CSV untuk Excel.

## Versi
- `index.html` — versi ringan (±28 KB), satu file, tanpa internet. Jalan di Windows 7:
  Internet Explorer 11, Chrome, dan Firefox lama.
- `versi-modern.html` — tampilan modern (butuh browser baru dan internet untuk font).

Keduanya memakai data register yang sama bila dibuka dari alamat yang sama.

## Pakai di Windows 7 tanpa internet
Salin `index.html` ke komputer lab, lalu buka dengan **Chrome atau Firefox**.
Internet Explorer 11 tidak bisa menyimpan register bila file dibuka langsung dari disk;
di IE11 buka lewat alamat GitHub Pages.

## Menjalankan
Buka `index.html` di browser, atau aktifkan GitHub Pages:
Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.

Data register tersimpan di browser (localStorage) pada perangkat yang dipakai.
Gunakan tombol **Unduh CSV** secara berkala sebagai cadangan.
