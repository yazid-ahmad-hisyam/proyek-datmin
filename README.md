# Rangkuman Hasil Analisis Klasterisasi K-Means

Dalam analisis ini, kita telah melakukan **klasterisasi** terhadap data sekolah-sekolah di kota Semarang berdasarkan dua variabel utama: **Jumlah Siswa (PD)** dan **Jumlah Kelas (Rombel)**. Algoritma yang digunakan adalah **K-Means**, dengan jumlah klaster optimal yang ditentukan melalui evaluasi menggunakan **Elbow Method** dan **Silhouette Score**.

## Hasil Klasterisasi
Setelah melakukan klasterisasi, data terbagi menjadi dua klaster utama:

- **Klaster 0**: 
  - Sekolah-sekolah dalam klaster ini cenderung memiliki **jumlah siswa yang lebih sedikit** (rata-rata sekitar 133 siswa) dan **jumlah kelas yang relatif lebih sedikit** (rata-rata sekitar 6 kelas).
  
- **Klaster 1**:
  - Sekolah-sekolah dalam klaster ini memiliki **jumlah siswa yang lebih banyak** (rata-rata sekitar 581 siswa) dan **jumlah kelas yang lebih banyak** (rata-rata sekitar 19 kelas).

## Visualisasi Hasil Klasterisasi
Visualisasi hasil klasterisasi menunjukkan sebaran sekolah-sekolah pada dua dimensi, yaitu jumlah siswa (PD) dan jumlah kelas (Rombel), dengan warna yang berbeda untuk masing-masing klaster. Hal ini memungkinkan kita untuk melihat pola distribusi sekolah yang dikelompokkan berdasarkan karakteristik yang serupa.

## Statistik Deskriptif Tiap Klaster
Berikut adalah statistik deskriptif untuk tiap klaster:
- **Klaster 0**:
  - Jumlah siswa (PD): Min = 20, Max = 392, Mean = 133.49
  - Jumlah kelas (Rombel): Min = 2, Max = 12, Mean = 6.52
  
- **Klaster 1**:
  - Jumlah siswa (PD): Min = 334, Max = 960, Mean = 581.56
  - Jumlah kelas (Rombel): Min = 13, Max = 29, Mean = 19.31

## Kesimpulan
Hasil klasterisasi ini menunjukkan dua kelompok sekolah yang memiliki karakteristik berbeda terkait jumlah siswa dan jumlah kelas. Sekolah-sekolah di **Klaster 0** cenderung lebih kecil, sementara sekolah-sekolah di **Klaster 1** lebih besar dalam hal jumlah siswa dan kelas.

Dataset yang sudah diberi label klaster ini dapat digunakan untuk analisis lebih lanjut, seperti perencanaan alokasi sumber daya dan kebijakan pendidikan yang lebih terfokus pada tiap klaster.