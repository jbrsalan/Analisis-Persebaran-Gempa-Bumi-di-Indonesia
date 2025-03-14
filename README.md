# Analisis Persebaran Gempa Bumi di Indonesia

## Justifikasi
Indonesia merupakan salah satu negara dengan aktivitas seismik tertinggi di dunia karena berada di Cincin Api Pasifik. Rata-rata, terjadi 22 gempa setiap hari di berbagai wilayah Indonesia. Analisis data gempa menjadi penting untuk memahami pola kejadian gempa dan mendukung upaya mitigasi bencana.

## Latar Belakang Masalah
Gempa bumi adalah fenomena alam yang sulit diprediksi, tetapi pola sebaran dan karakteristiknya dapat dianalisis melalui data historis. Dalam proyek ini, data gempa di Indonesia dianalisis untuk menjawab beberapa pertanyaan kunci terkait pola kejadian gempa dan faktor yang mempengaruhinya.

## Output Proyek
Proyek ini bertujuan untuk menjawab pertanyaan berikut:
1. **Apakah ada hubungan antara area dan kategori gempa?**
2. **Apakah ada anomali dari sebaran data magnitudo gempa?**
3. **Di mana saja area yang memiliki rekaman gempa berkategori besar terbanyak?**
4. **Bagaimana kedalaman pusat gempa mempengaruhi magnitudo gempa?**
5. **Apakah gempa terjadi pada jam tertentu?**
6. **Apakah gempa dengan kategori besar bisa diprediksi atau memiliki pola?**

## Data
### Sumber Dataset
- Dataset diambil dari [Kaggle - Earthquakes in Indonesia](https://www.kaggle.com/datasets/kekavigi/earthquakes-in-indonesia)
- Visualisasi tambahan tersedia di [Tableau Dashboard](https://public.tableau.com/app/profile/jabaris.maulana/viz/h8dsft_Milestone1_alan/PERSEBARANDATAGEMPA?publish=yes)

### Deskripsi Kolom Dataset
Dataset ini terdiri dari beberapa kolom utama:
1. **Tanggal**: Waktu kejadian gempa.
2. **Lokasi**: Titik koordinat (lintang dan bujur) serta nama wilayah.
3. **Magnitudo**: Kekuatan gempa dalam skala Richter.
4. **Kedalaman**: Kedalaman pusat gempa dalam kilometer.
5. **Kategori**: Klasifikasi gempa berdasarkan magnitudo (kecil, sedang, besar).

### Contoh Penggunaan
Dengan dataset ini, kita dapat mengidentifikasi wilayah dengan aktivitas seismik tinggi, mengamati pola kejadian gempa, serta mengeksplorasi hubungan antara magnitudo dan kedalaman.

## Metode
Metode yang digunakan dalam proyek ini meliputi:
- **Eksplorasi Data**: Analisis statistik dan visualisasi distribusi magnitudo, lokasi, dan kedalaman gempa.
- **Statistik Deskriptif**: Identifikasi pola umum dalam data.

## Teknologi yang Digunakan
### Manipulasi dan Analisis Data
- pandas - Manipulasi data
- numpy - Perhitungan numerik

### Visualisasi Data
- matplotlib - Pembuatan grafik
- seaborn - Visualisasi statistik
- tableau - Peta interaktif

## Target Pengguna
- **BMKG (Badan Meteorologi, Klimatologi, dan Geofisika)**: Untuk pemantauan dan peringatan dini.
- **Pemerintah dan Lembaga Kebencanaan**: Untuk mitigasi dan perencanaan kebencanaan.
- **Akademisi dan Peneliti**: Untuk studi seismologi dan geofisika.
- **Masyarakat Umum**: Untuk meningkatkan kesadaran dan kesiapsiagaan terhadap gempa.

## Kesimpulan
(Hasil analisis akan diperbarui setelah penelitian lebih lanjut)

---
**Catatan:** Dokumentasi ini akan terus diperbarui seiring dengan perkembangan proyek.