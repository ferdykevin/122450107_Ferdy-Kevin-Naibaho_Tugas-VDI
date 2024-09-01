# Resume Artikel

**Judul:** Making Data Visualization More Efficient and Effective: A Survey  
**Penulis:** Xuedi Qin, Yuyu Luo, Nan Tang, Guoliang Li  
**Diterbitkan di:** The VLDB Journal  
**Tahun:** 2019

## Abstrak
Visualisasi data telah menjadi komponen vital dalam dunia bisnis yang semakin didorong oleh data. Dengan meningkatnya volume, kecepatan, dan keragaman data, ada kebutuhan mendesak untuk teknik visualisasi yang tidak hanya efektif tetapi juga efisien dalam pemrosesan data dan penyajiannya. Artikel ini menyurvei berbagai teknik yang bertujuan untuk meningkatkan efisiensi dan efektivitas visualisasi data. Survei ini berfokus pada tiga aspek utama: spesifikasi visualisasi, pendekatan efisien untuk pemrosesan visualisasi, dan sistem rekomendasi visualisasi. Dengan adanya peningkatan teknik ini, pengguna dapat menghasilkan visualisasi yang lebih baik dan lebih cepat dalam skala yang lebih besar, yang pada akhirnya mendukung pengambilan keputusan yang lebih baik.

## Pendahuluan
Dalam beberapa dekade terakhir, visualisasi data telah mengalami perkembangan signifikan. Visualisasi mengubah data abstrak menjadi representasi visual yang intuitif, yang sangat membantu manusia dalam memahami dan menganalisis informasi. Dengan adanya data yang semakin melimpah, organisasi kini menggunakan visualisasi data sebagai alat penting dalam pengambilan keputusan strategis dan operasional. Visualisasi tidak hanya memberikan gambaran umum tentang data, tetapi juga memudahkan interpretasi hasil analisis data, yang sangat diperlukan oleh para ilmuwan data dan pembuat keputusan.

Kemajuan dalam teknologi visualisasi data telah dipengaruhi oleh berbagai komunitas, termasuk grafis komputer, komunitas visualisasi, dan komunitas basis data. Artikel ini mengulas berbagai kontribusi dari komunitas-komunitas ini dalam meningkatkan efisiensi dan efektivitas visualisasi data, serta tantangan yang dihadapi dalam mengatasi kompleksitas pemrosesan data dalam skala besar.

## Isi 

### 1. Spesifikasi Visualisasi
Spesifikasi visualisasi adalah langkah awal dalam proses visualisasi data yang menentukan bagaimana data akan dipetakan ke elemen-elemen visual seperti panjang, posisi, bentuk, dan warna. Spesifikasi ini sangat penting karena menentukan kualitas dan efektivitas visualisasi yang dihasilkan.

Beberapa bahasa visualisasi telah dikembangkan untuk membantu pengguna dalam menetapkan spesifikasi ini. Bahasa-bahasa ini bervariasi dalam tingkat detail yang diperlukan dari pengguna, mulai dari bahasa tingkat rendah yang memerlukan spesifikasi detail, hingga bahasa tingkat tinggi yang lebih mudah digunakan tetapi kurang fleksibel. Artikel ini membahas bagaimana berbagai bahasa visualisasi digunakan untuk menghasilkan visualisasi yang efisien dan efektif, serta tantangan dalam desain bahasa visualisasi tersebut.

### 2. Pendekatan Efisien untuk Visualisasi Data
Efisiensi adalah kunci dalam visualisasi data, terutama ketika bekerja dengan data dalam jumlah besar. Artikel ini mengulas berbagai pendekatan yang telah dikembangkan untuk meningkatkan efisiensi dalam proses visualisasi data. Beberapa pendekatan yang dibahas meliputi:

- **Integrasi Sistem Visualisasi dengan DBMS:** Mengintegrasikan sistem visualisasi dengan sistem manajemen basis data (DBMS) untuk mempercepat proses pengambilan dan pemrosesan data.
- **Penyimpanan Kolom dan Indeks:** Menggunakan penyimpanan berbasis kolom dan teknik indeks untuk mempercepat akses dan manipulasi data, yang sangat penting dalam skenario big data.
- **Komputasi Paralel:** Memanfaatkan komputasi paralel untuk memproses banyak tugas visualisasi secara bersamaan, sehingga mempercepat waktu respon.
- **Prediksi dan Prefetching:** Menggunakan teknik prediksi dan prefetching untuk memperkirakan data apa yang akan dibutuhkan pengguna selanjutnya, dan memuat data tersebut sebelumnya untuk mempercepat interaksi pengguna dengan visualisasi.

Artikel ini juga membahas solusi-solusi yang lebih baru seperti visualisasi data yang mendekati hasil akhir secara progresif, memungkinkan pengguna untuk segera melihat gambaran kasar dari data mereka yang kemudian disempurnakan seiring waktu.

### 3. Rekomendasi Visualisasi Data
Spesifikasi visualisasi yang tepat seringkali sulit untuk ditentukan, bahkan bagi para ahli. Oleh karena itu, sistem rekomendasi visualisasi menjadi semakin penting. Sistem ini dirancang untuk membantu pengguna dalam menemukan visualisasi yang paling relevan dan informatif berdasarkan data yang mereka miliki.

Artikel ini mengulas beberapa pendekatan dalam rekomendasi visualisasi, termasuk sistem yang dapat melengkapi spesifikasi visualisasi yang tidak lengkap atau memberikan saran visualisasi alternatif yang mungkin lebih menarik atau informatif. Pendekatan ini mencakup penggunaan algoritma pembelajaran mesin untuk mempelajari preferensi pengguna dan memberikan rekomendasi yang lebih disesuaikan, serta teknik berbasis aturan yang memanfaatkan pengetahuan yang ada tentang cara terbaik untuk memvisualisasikan jenis data tertentu.

## Kesimpulan
Visualisasi data adalah alat yang sangat berharga dalam analisis dan pengambilan keputusan berbasis data. Namun, dengan volume data yang semakin besar dan kebutuhan untuk interaksi yang semakin cepat, tantangan dalam menciptakan visualisasi yang efisien dan efektif menjadi lebih kompleks. Artikel ini menyoroti pentingnya integrasi antara teknologi visualisasi dan basis data, serta peran sistem rekomendasi dalam membantu pengguna menghasilkan visualisasi yang lebih baik. Dengan perkembangan teknologi dan metodologi yang dibahas dalam artikel ini, masa depan visualisasi data tampak cerah, dengan potensi untuk menjadi lebih efisien dan lebih efektif dalam mendukung kebutuhan bisnis dan ilmiah.

