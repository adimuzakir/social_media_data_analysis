# Analisis Data Media Sosial 
## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data media sosial untuk mengevaluasi pola interaksi, korelasi antara panjang teks postingan dengan jumlah interaksi, analisis sentimen, dan distribusi aktivitas berdasarkan platform. Data yang digunakan dalam proyek ini adalah data media sosial yang mencakup informasi tentang postingan, interaksi, platform, serta informasi pengguna. Dengan menggunakan teknik analisis data dan visualisasi, proyek ini membantu mengidentifikasi tren dalam aktivitas media sosial, pola interaksi, serta sentimen yang terkait dengan konten.
## Tujuan Proyek
1. Menganalisis frekuensi jumlah postingan berdasarkan waktu dalam sehari.
2. Mengevaluasi korelasi antara panjang teks postingan dengan jumlah interaksi (likes, komentar, dan shares).
3. Mengidentifikasi pengguna dengan dampak terbesar berdasarkan total interaksi.
4. Melakukan analisis sentimen untuk menentukan kategori sentimen (positif, negatif, atau netral).
5. Menganalisis distribusi postingan berdasarkan platform dan tren interaksi berdasarkan platform.
## Langkah-Langkah Proyek
### Data Preparation
- Mengimpor data dari file CSV dan meninjau struktur serta informasi dalam data.
- Mengubah format tanggal untuk kolom 'post_date' agar sesuai dengan analisis waktu.
- Menghapus atau menangani nilai yang hilang jika diperlukan.
### Analisis Frekuensi Postingan
- Menghitung frekuensi postingan berdasarkan jam dalam sehari.
- Menggunakan visualisasi barplot untuk menunjukkan jumlah postingan pada setiap jam.
### Korelasi Panjang Teks dan Interaksi
- Menghitung panjang teks postingan dan jumlah total interaksi (likes, komentar, dan shares).
- Membuat scatter plot untuk melihat hubungan antara panjang teks postingan dan jumlah interaksi.
- Menentukan apakah ada korelasi signifikan antara panjang teks dan jumlah interaksi.
### Pengguna dengan Total Interaksi Tertinggi
- Mengelompokkan data berdasarkan pengguna dan menghitung total interaksi untuk masing-masing pengguna.
- Mengidentifikasi pengguna dengan total interaksi tertinggi.
- Menggunakan visualisasi barplot untuk menunjukkan 10 pengguna dengan total interaksi tertinggi.
### Analisis Sentimen
- Menggunakan TextBlob untuk menganalisis sentimen dari teks postingan.
- Mengkategorikan sentimen menjadi positif, negatif, atau netral berdasarkan skor polaritas.
- Menggunakan visualisasi countplot untuk menunjukkan distribusi kategori sentimen.
- Menggunakan visualisasi pie chart untuk menunjukkan persentase distribusi sentimen.
### Analisis Berdasarkan Platform
- Menghitung distribusi postingan berdasarkan platform (misalnya, Facebook, Twitter, Instagram).
- Menggunakan barplot untuk menunjukkan jumlah postingan untuk setiap platform.
- Menganalisis tren interaksi berdasarkan jam dalam sehari dan platform yang digunakan.
- Menggunakan barplot untuk menunjukkan rata-rata interaksi per jam untuk setiap platform.
- Membuat visualisasi untuk rata-rata interaksi berdasarkan interval 4 jam dan platform.
## Hasil dan Temuan
- **Frekuensi Postingan**: Frekuensi postingan hampir merata di setiap jam dalam sehari, dengan puncak tertinggi pada jam 15 dan jam 22. Hal ini menunjukkan aktivitas yang konsisten sepanjang hari, dengan dua periode puncak aktivitas di sore dan malam hari.
- **Korelasi Panjang Teks dan Interaksi**: Scatter plot menunjukkan tidak ada korelasi signifikan antara panjang teks dan jumlah interaksi. Hal ini menunjukkan bahwa panjang teks bukanlah faktor penentu dalam meningkatkan interaksi.
- **Pengguna dengan Total Interaksi Tertinggi**: Pengguna dengan dampak terbesar memiliki total interaksi tertinggi, menunjukkan pengaruh yang kuat dalam komunitas media sosial.
- **Analisis Sentimen**: Distribusi sentimen menunjukkan persentase yang signifikan untuk sentimen netral, dengan sentimen positif dan negatif yang lebih rendah.
- **Analisis Berdasarkan Platform**: Distribusi postingan menunjukkan variasi aktivitas di berbagai platform. Rata-rata interaksi berdasarkan platform menunjukkan perbedaan tren interaksi untuk setiap platform.

## Kesimpulan
Proyek ini memberikan wawasan yang berharga tentang pola aktivitas media sosial, korelasi antara panjang teks postingan dan interaksi, serta analisis sentimen. Hasil analisis ini dapat digunakan oleh tim pemasaran atau tim media sosial untuk mengoptimalkan strategi konten, mengidentifikasi pengguna berpengaruh, dan memahami tren aktivitas di berbagai platform. Selain itu, analisis ini juga membantu dalam mengidentifikasi waktu terbaik untuk memposting konten.
