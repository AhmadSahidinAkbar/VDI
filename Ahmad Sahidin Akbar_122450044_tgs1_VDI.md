#Tugas Resume Visualisasi Data dan Informasi

Nama : Ahmad Sahidin Akbar</br>
NIM : 122450044</br>
Dosen Pengampu : Ahmad Luky Ramdani S.Kom., M.Kom
<br/>
<br/>

# <div align="center">Making Data Visualization more Efficient and Effective</div>
<br/>
<br/>

## Introduction
Mengubah data abstrak menjadi representasi visual yang lebih mudah dipahami, Visualisasi data menjadi alat penting dalam dunia bisnis modern untuk membantu pengambilan keputusan. Ketika volume, kecepatan, dan kompleksitas data meningkat, visualisasi data yang efektif dan efisien menjadi sangat penting. Memeriksa berbagai cara dan pendekatan yang dapat digunakan untuk meningkatkan efisiensi dan efektivitas pembuatan visualisasi data, dengan berkonsentrasi pada spesifikasi visualisasi, pendekatan efisien untuk visualisasi data, dan saran untuk visualisasi.

## Alur dalam Melakukan Visualisasi Data
Dalam kebanyakan kasus, jalur visualisasi data terdiri dari beberapa tahap iteratif, yang mencakup:
<ol>
<li>Pengambilan Data: Menemukan sumber data yang diinginkan untuk mendapatkan data yang dibutuhkan.</li>
<li>Persiapan Data: Prosedur untuk memproses data yang dikumpulkan agar dapat divisualisasikan termasuk normalisasi nilai, interpolasi nilai yang hilang, dan perbaikan entri yang salah.</li>
<li>Manipulasi Data: Memilih data untuk divisualisasikan dan melakukan operasi tambahan, seperti penggabungan dan pengelompokan.</li>
<li>Pemetaan Data: Memetakan data ke elemen geometris seperti titik dan garis, dengan warna, posisi, dan ukuran disertakan.</li>
</ol>

Rendering adalah proses mengubah data geometris menjadi visualisasi yang dapat dilihat pengguna.

## Spesifikasi Visualisasi
Cara pengguna menentukan kebutuhan mereka untuk menghasilkan visualisasi disebut spesifikasi visualisasi, yang terdiri dari tiga komponen utama:
<ol>
<li>Data: Rekaman yang akan diungkapkan dan operasi yang dilakukan padanya, seperti pengelompokan dan penyortiran.</li>
<li>Tanda Visual (Marks): Bentuk data visual seperti garis, titik, atau batang.</li>

Pemetaan adalah proses menghubungkan data ke tanda visual untuk menghasilkan gambar yang tepat
</ol>

## Kategorisasi Visualisasi Data
Bahasa visualisasi data dikategorikan menurut tingkat ekspresivitas dan kemudahan penggunaan mereka:
<ol>
<li>Bahasa Tingkat Rendah: Meskipun membutuhkan pemahaman yang lebih mendalam, pengguna memiliki kontrol penuh atas semua elemen pemetaan. D3 dan Vega adalah contohnya.</li>
<li>Bahasa Tinggi: Memberikan banyak detail, membuatnya lebih mudah digunakan, tetapi ada beberapa keterbatasannya. ggplot2 dan Vega-Lite adalah contohnya.</li>
<li>Operasi Visual Berbasis GUI: Menawarkan antarmuka pengguna grafis yang memudahkan visualisasi tanpa menulis kode, seperti Tableau dan Microsoft Power BI.</li>
</ol>

## Pendekatan Efisien untuk Visualisasi Data
Metode ini menggunakan berbagai teknik untuk mempercepat visualisasi data dan meningkatkan skala:
<ol>
<li>Penerjemahan Kueri: Menggunakan sistem DBMS untuk menghasilkan visualisasi dengan menggunakan kueri SQL.</li>
<li>Integrasi dengan Sistem Manajemen Basis Data (DBMS): Menggabungkan sistem visualisasi dengan basis data untuk meningkatkan efisiensi.</li>
<li>Penyimpanan Kolom dan Penggunaan Indeks: Menggunakan indeks untuk mempercepat pemrosesan data dan menyimpan data dalam format kolom.</li>
<li>Komputasi Paralel: Penggunaan komputasi paralel mempercepat eksekusi kueri pada dataset besar.</li>
<li>Prediksi dan Prefetching: Menggunakan teknik prediksi untuk menyiapkan data yang mungkin diperlukan untuk langkah visualisasi berikutnya.</li>
</ol>

## Rekomendasi Visualisasi
Rekomendasi visualisasi membantu pengguna memilih atau menyempurnakan visualisasi yang sesuai berdasarkan spesifikasi atau referensi visualisasi yang tidak lengkap:
<ol>
<li>Spesifikasi yang Tidak Lengkap: Sistem dapat melengkapi atau memberikan rekomendasi visualisasi sesuai dengan spesifikasi pengguna.</li>
<li>Rekomendasi Berdasarkan Perilaku: Sistem membuat rekomendasi visualisasi berdasarkan pola interaksi pengguna.</li>
<li>Rekomendasi yang Dipersonalisasi: Atur rekomendasi visualisasi sesuai dengan preferensi dan data historis setiap pengguna.</li>
</ol>

## Other Research Directions

### Persiapan Data untuk Visualisasi
Untuk memastikan bahwa data yang akan divisualisasikan bersih dan siap untuk digunakan, persiapan data mencakup tindakan seperti normalisasi nilai, perbaikan entri yang salah, interpolasi nilai yang hilang, dan operasi lainnya.

### Benchmark untuk Visualisasi Data
Benchmarking visualisasi data adalah proses untuk mengevaluasi kinerja alat dan teknik visualisasi untuk memastikan bahwa mereka bekerja dengan baik dan efektif. Ini melibatkan pengujian berbagai teknik visualisasi pada berbagai dataset untuk mengukur kecepatan, skalabilitas, dan kualitas visualisasi yang dihasilkan.

### Visualisasi Data untuk Aplikasi Terkait Basis Data
Berbagai aplikasi terkait basis data, seperti Excel, Google Sheets, dan Oracle Data Visualization Desktop, menggunakan teknik visualisasi untuk membantu pengguna mengolah dan menganalisis data secara visual, yang memudahkan proses pengambilan keputusan dan eksplorasi data.












