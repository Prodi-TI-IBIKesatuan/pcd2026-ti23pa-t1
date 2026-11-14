# Data

Dataset lengkap **tidak** disimpan di repo ini. Repo hanya berisi `sample/` (≤ 20 gambar yang sudah disensor) untuk contoh dan demo.

## Ringkasan

- Tautan folder Google Drive (akses terbatas): https://drive.google.com/drive/folders/1UrGjLPMuYD6hdA_Y2SSPOVw5D800sLV4?usp=sharing
- Jumlah citra: 401
- Foto sendiri per anggota: Alvio: 15, Jonathan: 19, Astria: 14, Tiurma: 15, Joshua: 16
- Sumber data tambahan dan lisensinya: Indonesian License Plate Detection Dataset (Zenodo, DOI: 10.5281/zenodo.15605718) — Lisensi Creative Commons Attribution 4.0 International (CC BY 4.0)
- Jumlah baris anotasi: [isi]
- Cara pengambilan foto (perangkat, waktu, lokasi umum): Smartphone, Siang - Sore - Malam, Parkiran

## Anotasi

Kotak lokasi pelat (x, y, lebar, tinggi dalam piksel) dan teks pelat tanpa spasi.

Simpan sebagai `anotasi.csv` di folder Drive, satu baris per citra (atau per pasangan), dengan kolom persis seperti [format_anotasi.csv](format_anotasi.csv). Baris contoh di berkas itu fiktif.

## Etika dan privasi

Wajah orang wajib diburamkan. Di data/sample, sebagian karakter pelat diburamkan. Teks pelat lengkap hanya disimpan di Drive. Jangan menulis NIM, nama orang lain, atau data pribadi lain di repo ini.
