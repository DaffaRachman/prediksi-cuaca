# Proyek Pertama Machine Learning Terapan | Weather Type Prediction for Safety Flight using Machine Learning

###### Disusun oleh : Muhammad Daffa Rachman

Proyek ini membangun model *machine learning* yang dapat memprediksi cuaca berdasarkan Weather Type

## 1. Project Domain

Keselamatan penerbangan merupakan aspek krusial dalam industri transportasi udara, mengingat kecelakaan pesawat dapat menimbulkan dampak besar baik dari segi korban jiwa maupun kerugian material. Pada tahun 2007, Badan Keselamatan Transportasi Nasional memperkirakan total hampir 24 juta jam terbang. Dari 24 juta jam tersebut, 6,84 dari setiap 100.000 jam terbang mengakibatkan kecelakaan pesawat terbang, dan 1,19 dari setiap 100.000 mengakibatkan kecelakaan fatal 【1 panish shea ravipudi】. 

Kecelakaan pada penerbangan dapat disebabkan oleh berbagai faktor, salah satunya adalah kondisi cuaca yang buruk. Cuaca yang tidak stabil, seperti kabut tebal, hujan deras, angin kencang, dan badai petir, dapat meningkatkan risiko kecelakaan, terutama saat pesawat lepas landas, dalam perjalanan, atau ketika hendak mendarat. Pada tahun 2017, National Business Aviation Association (NBAA) mengatakan bahwa cuaca berkontribusi sebanyak 35% kecelakaan pada penerbangan 【2 flight safety foundation】. Keselamatan penerbangan merupakan prasyarat penting untuk kegiatan penerbangan, diperlukan pemahaman terkait kondisi cuaca yang dapat mempengaruhi keselamatan penerbangan 【3 Jurnal Lembaga Ketahanan Nasional RepublikIndonesiaPENGARUH FAKTOR GEOGRAFIS】. 

National Centre for Amospheric Science (NCAS) ada beberapa faktor yang menyebabkan suatu cuaca yakni, temperatur, tekanan udara, keadaan awan, angin, dan kelembapan udara【4 NCAS】. Dengan memanfaatkan teknologi terkini dalam pemodelan cuaca dan sistem prediksi berbasis data historis, proyek ini bertujuan untuk mengembangkan sistem prediksi cuaca yang dapat membantu para pilot dan pengendali lalu lintas udara untuk membuat keputusan yang lebih tepat mengenai keamanan penerbangan. Prediksi yang akurat mengenai kondisi cuaca yang dapat mempengaruhi keselamatan penerbangan, seperti turbulensi, badai petir, atau kabut tebal, sangat penting untuk mengurangi risiko kecelakaan dan memastikan keselamatan para penumpang serta kru pesawat. 


### Bagaimana Masalah tersebut Diselesaikan?

#### 1. Pemanfaatan Teknologi Prediksi Cuaca
Penggunaan algoritma machine learning seperti Support Vector Machine (SVM) dan K-Nearest Neighbor (KNN) telah terbukti efektif dalam meningkatkan akurasi prediksi cuaca. Penelitian menunjukkan bahwa SVM, khususnya dengan teknik Synthetic Minority Over-sampling Technique (SMOTE), dapat mencapai akurasi hingga 83%, sementara KNN dapat mencapai akurasi hingga 89% dalam klasifikasi kondisi cuaca yang relevan untuk keselamatan penerbangan.【5 mahendra】【6 rangkuti】.

#### 2. Deteksi Dini Melalui Analisis Data
Dengan memanfaatkan dataset cuaca seperti Weather Type Classification dari Kaggle, berbagai parameter seperti temperatur, tekanan udara, keadaan awan, angin, dan kelembapan udara dapat digunakan untuk memprediksi cuaca 【4】. Model prediksi ini memungkinkan deteksi dini terhadap kondisi cuaca berisiko, sehingga pilot dan pengendali lalu lintas udara dapat mengambil keputusan yang lebih tepat untuk meningkatkan keselamatan penerbangan.

#### 3. Efisiensi Sistem Kesehatan
Teknologi prediksi cuaca berbasis data historis membantu pengelola lalu lintas udara dan maskapai dalam merencanakan jadwal penerbangan, memilih rute yang lebih aman, serta mengoptimalkan penggunaan sumber daya seperti bahan bakar dan kru. Dengan demikian, potensi keterlambatan dan pembatalan penerbangan akibat cuaca buruk dapat diminimalkan, serta keselamatan tetap terjaga.

#### 4. Dampak yang Diharapkan
Pendekatan berbasis teknologi prediksi cuaca ini diharapkan dapat secara signifikan menurunkan angka kecelakaan penerbangan yang disebabkan oleh faktor cuaca. Selain itu, sistem ini juga dapat mengurangi kerugian material dan korban jiwa, serta meningkatkan kepercayaan masyarakat terhadap transportasi udara yang aman dan andal. Keselamatan penerbangan merupakan prasyarat penting untuk kegiatan penerbangan, diperlukan pemahaman terkait kondisi cuaca yang dapat mempengaruhi keselamatan penerbangan 【3】.


### State Of The Art Penelitian Sebelumnya

1. Penelitian oleh Mahendra et al. (2024) Implementasi Machine Learning Untuk Memprediksi Cuaca Menggunakan Support Vector Machine

Penelitian yang dilakukan oleh Mahendra et al. (2024) berhasil menerapkan algoritma Support Vector Machine (SVM) dalam klasifikasi prediksi cuaca menggunakan dataset yang diambil dari Kaggle, salah satu platform terkemuka untuk analisis data dan kompetisi machine learning. Studi ini menekankan pentingnya tahapan preprocessing data, termasuk penanganan outlier dengan teknik Z-score, penyeimbangan data menggunakan Synthetic Minority Over-sampling Technique (SMOTE), serta normalisasi data sebelum pemodelan. Fitur-fitur utama yang digunakan meliputi suhu, tekanan udara, kecepatan angin, kelembapan udara, dan curah hujan, yang semuanya sangat relevan dalam mempengaruhi kondisi cuaca. Hasil penelitian menunjukkan bahwa penerapan SVM setelah preprocessing dan penyeimbangan data mampu menghasilkan akurasi prediksi sebesar 83%, yang menandakan performa model yang baik dan stabil tanpa indikasi overfitting maupun underfitting. Temuan ini menegaskan bahwa kombinasi preprocessing yang tepat dan pemilihan algoritma yang sesuai sangat berkontribusi dalam peningkatan akurasi dan kinerja model prediksi cuaca berbasis machine learning【5】.

2. Penelitian oleh Rangkuti et al. (2021) PENERAPAN ALGORITMA K-NEAREST NEIGHBOR (KNN) DALAM MEMPREDIKSI DAN MENGHITUNG TINGKAT AKURASI DATA CUACA DI INDONESIA

Penelitian yang dilakukan oleh Rangkuti et al. (2021) menerapkan algoritma K-Nearest Neighbor (KNN) untuk memprediksi dan menghitung tingkat akurasi data cuaca di Indonesia. Dataset yang digunakan terdiri dari 3.623 data dengan 28 atribut cuaca, seperti suhu, kelembapan, curah hujan, dan kecepatan angin, yang seluruhnya diperoleh dari National Centers for Environmental Information. Proses penelitian mencakup pembersihan data, seleksi fitur, serta pembagian data menjadi training dan testing dengan rasio 80:20. Model KNN yang dibangun menunjukkan tingkat akurasi prediksi sebesar 89%, yang menandakan kemampuan model dalam mengenali pola-pola cuaca secara efektif meskipun terdapat variasi dan noise pada data【6】.


## 2. Business Understanding

Pengembangan model prediksi cuaca berbasis machine learning memiliki potensi besar dalam meningkatkan efisiensi pengambilan keputusan, mendukung upaya pencegahan dini kecelakaan, dan memperkuat proses manajemen risiko penerbangan. Dengan kemampuan memberikan prediksi yang akurat, model ini dapat membantu berbagai pihak seperti pilot, pengendali lalu lintas udara, dan institusi penerbangan dalam mengidentifikasi risiko cuaca pada tahap awal. Hal ini memungkinkan implementasi langkah-langkah preventif yang diperlukan untuk mencegah kecelakaan atau gangguan operasional penerbangan akibat cuaca buruk.

Bagi pilot dan pengendali lalu lintas udara, keberadaan model ini akan berharga karena dapat membantu mereka dalam menentukan prioritas dan strategi penanganan penerbangan yang berisiko tinggi. Dengan informasi yang lebih tepat, mereka dapat membantu mengambil keputusan yang lebih cepat dan efektif, seperti mengubah rute atau menunda penerbangan. Selain itu, bagi institusi penerbangan, penerapan model ini dapat mengakibatkan pengurangan biaya operasional jangka panjang yang sering kali terkait dengan penanganan insiden cuaca, serta membantu dalam alokasi sumber daya yang lebih efisien. Dengan semua manfaat ini, pengembangan model prediksi cuaca bukan hanya sebuah inovasi teknologi, tetapi juga langkah penting dalam upaya meningkatkan keselamatan dan keandalan transportasi udara.

### Problem Statements
Berdasarkan latar belakang tersebut, masalah yang dapat diselesaikan dalam proyek ini adalah:
- Bagaimana membangun model machine learning dan deep learning yang efektif untuk memprediksi risiko cuaca buruk yang dapat mempengaruhi keselamatan penerbangan, dengan tingkat akurasi yang tinggi?
- AAlgoritma apa yang memberikan performa terbaik untuk prediksi cuaca berisiko di antara model pembelajaran mesin dan pembelajaran mendalam yang digunakan?

### Goals
Tujuan dari proyek ini meliputi:
- Membangun model prediksi risiko cuaca berbasis machine learning dan deep learning dengan tingkat akurasi tinggi untuk mendukung keselamatan penerbangan.
- Membandingkan performa berbagai algoritma untuk menentukan model terbaik dalam mendeteksi dan mengantisipasi risiko cuaca pada penerbangan.


### Solution Statements
#### 1. Analisis Data dan Preprocessing
- Analisis Univariate, Multivariate dan Bivariate: Untuk memahami distribusi data, hubungan antar fitur, serta mendeteksi outlier. Contohnya adalah memeriksa kolerasi antara variabel seperti temperatur, tekanan udara, keadaan awan, angin, dan kelembapan udara terhadap type cuaca.
- Data Cleaning dan Normalisasi: Membersihkan data dari nilai yang hilang atau tidak valid, dan menormalkan fitur numerik untuk memastikan konsistensi dalam pelatihan model.

#### 2. Implementasi Model Machine Learning
- Membangun beberapa model menggunakan algoritma berikut:
    * Logistic Regression: Digunakan sebagai baseline model untuk memprediksi jenis cuaca (seperti hujan, cerah, berawan, salju) dengan memahami hubungan linier antara variabel prediktor seperti suhu, kelembaban, dan kecepatan angin.
    * Random Forest: Algoritma ensemble yang mampu menangani data non-linear dan sangat efektif untuk memprediksi cuaca. Dapat menangani berbagai jenis fitur seperti kategori dan numerik, serta memberikan prediksi yang stabil dengan akurasi tinggi.
    * Support Vector Machine (SVM): Digunakan untuk memisahkan data cuaca berdasarkan margin optimal, terutama ketika data memiliki dimensi tinggi dan sulit dipisahkan secara linier. Dapat digunakan untuk prediksi cuaca berdasarkan berbagai fitur, seperti suhu dan kelembaban.
    * Naive Bayes: Algoritma probabilistik yang efisien untuk tugas klasifikasi sederhana.
    * K-Nearest Neighbors (KNN): Membandingkan data cuaca baru dengan data K terdekatnya dalam dataset. Algoritma ini sangat cocok untuk prediksi cuaca di mana kesamaan antara pengamatan dapat digunakan untuk memperkirakan kondisi cuaca berdasarkan data cuaca historis yang mirip.
    * XGBoost: Algoritma boosting yang memberikan performa tinggi dalam menangani data cuaca yang kompleks. Dikenal karena kemampuannya menangkap pola-pola yang sangat mendalam dan memberikan hasil prediksi cuaca yang sangat akurat, terutama dengan data yang besar dan beragam.

- Evaluasi Model:
    * Metrik seperti Akurasi, Precision, Recall dan F1-Score digunakan untuk mengevaluasi model, Metrik evaluasi yang ditekankan pada project ini adalah metrik evaluasi dengan menggunakan akurasi

## Data Understanding
### EDA - Deskripsi Variabel
**Informasi Datasets**


| Jenis | Keterangan |
| ------ | ------ |
| Title | _Weather Type Classification_ |
| Source | [Kaggle](https://www.kaggle.com/datasets/nikhil7280/weather-type-classification/data) |
| Maintainer | [Nikhil Narayan](https://www.kaggle.com/nikhil7280) |
| License | Data files © Original Authors |
| Visibility | Publik |
| Tags | _Beginer, Data Visualization, Classification, Exploratory Analysis, Weather and Climate_ |
| View | 60.8k |

![image]((https://drive.google.com/file/d/194k79NXgYsJMJzXSG_gsVBcvvlyqEFDO/view?usp=sharing))

Tabel 1. Informasi Dataset

Dilihat dari _Tabel 1. Informasi Dataset_ dataset ini berisi informasi sebagai berikut ini : 
- Dataset berupa CSV (Comma-Seperated Values).
- Dataset memiliki 13200 sample dengan 11 fitur.
- Dataset memiliki 5 fitur bertipe float64, 2 fitur bertipe o=int64 dan 4 fitur bertipe object.

### Variable - variable pada dataset
- Temperature (numeric): Suhu dalam derajat Celsius, dengan rentang dari suhu sangat dingin hingga sangat panas.
- Humidity (numeric): Persentase kelembaban, termasuk nilai di atas 100% untuk memperkenalkan nilai pencilan (outlier).
- Wind Speed (numeric): Kecepatan angin dalam kilometer per jam.
- Precipitation (%) (numeric): Persentase curah hujan, termasuk nilai outlier.
- Cloud Cover (categorical): Deskripsi tutupan awan.
- Atmospheric Pressure (numeric): Tekanan atmosfer dalam hPa, dengan rentang yang luas.
- UV Index (numeric): Indeks UV, menunjukkan kekuatan radiasi ultraviolet.
- Season (categorical): Musim saat data dicatat.
- Visibility (km) (numeric): Jarak pandang dalam kilometer, termasuk nilai yang sangat rendah atau sangat tinggi.
- Location (categorical): Tipe lokasi tempat data dicatat.
- Weather Type (categorical): Variabel target untuk klasifikasi, yang menunjukkan tipe cuaca.

### EDA - Univariate Analysis

![image](https://drive.google.com/file/d/1q5IFf4GpNnNO5p4Zwz9eAZQmEGTPnIuV/view?usp=sharing)

Gambar 1. Informasi Dataset

Gambar 1 merupakan informasi mengenai dataset yang digunakan :
Tabel diatas merupakan informasi mengenai dataset yang sigunakan :
- Kolom Temperature mencatat suhu dalam derajat Celsius. Rata-rata suhu adalah 19,13°C, dengan nilai minimum mencapai -25°C yang menunjukkan adanya suhu ekstrem yang mungkin disebabkan oleh kesalahan data atau kondisi yang sangat jarang. Nilai maksimum tercatat mencapai 109°C, yang merupakan nilai ekstrem dan perlu diperiksa lebih lanjut karena suhu tersebut sangat tinggi untuk kondisi normal. Median suhu berada pada angka 21°C, menunjukkan sebagian besar data berada pada kisaran suhu yang lebih normal.

- Kolom Humidity mencatat persentase kelembapan udara. Rata-rata kelembapan adalah 68,71%, dengan nilai minimum 20% dan maksimum 109%, yang menunjukkan adanya outlier. Nilai kelembapan di atas 100% bisa menunjukkan adanya kesalahan pengukuran atau data yang tidak konsisten. Median kelembapan berada pada 70%, menunjukkan bahwa setengah dari data berada pada tingkat kelembapan di bawah 70%.

- Kecepatan angin tercatat dengan rata-rata 9,83 km/jam. Nilai minimum menunjukkan kecepatan angin yang sangat rendah (0 km/jam), sedangkan nilai maksimum menunjukkan kecepatan angin yang tidak realistis (48,5 km/jam). Rata-rata kecepatan angin cukup moderat, namun data ini juga memiliki outlier yang perlu diperhatikan lebih lanjut.
- Kolom Precipitation (%) mengukur persentase curah hujan. Nilai rata-rata curah hujan adalah 53,64%, dengan nilai minimum 0% (tidak ada hujan) dan nilai maksimum 109%, yang menandakan adanya outlier. Ini menunjukkan bahwa sebagian besar data mencatatkan hujan dengan persentase moderat, namun juga terdapat outlier yang menunjukkan curah hujan yang sangat tinggi.
- Tekanan atmosfer tercatat dengan rata-rata 1005,83 hPa, dengan nilai minimum 800,12 hPa dan maksimum 1199,21 hPa. Rata-rata menunjukkan tekanan atmosfer yang cukup stabil, tetapi rentang nilai yang luas dapat menunjukkan variasi besar dalam data, termasuk kemungkinan outlier pada nilai maksimum.
- indeks UV, yang menunjukkan intensitas radiasi ultraviolet, memiliki rata-rata 4,01, dengan nilai minimum 0 dan maksimum 14. Nilai maksimum yang tinggi perlu diperiksa lebih lanjut, karena mungkin mencerminkan kejadian ekstrim atau kesalahan data. Median indeks UV adalah 3, yang menunjukkan kondisi UV pada kisaran sedang di sebagian besar data.
- Kolom Visibility mencatatkan jarak pandang dalam kilometer, dengan nilai rata-rata 5,46 km. Nilai minimum adalah 0 km dan maksimum mencapai 20 km, menunjukkan rentang jarak pandang yang sangat bervariasi, dengan kemungkinan besar adanya outlier.



![image](https://drive.google.com/file/d/1CxWG97oDFjZcUcNRshlHDWI_o3Aj8Mvk/view?usp=sharing)
Gambar 2. Pengecekan outlier pada dataset

Gambar 2 merupakan visualisasi exploratory data analysis dari pengecekan outlier pada dataset yang digunakan pada project ini adalah weather type. Berdasarkan boxplot yang ditampilkan, berikut adalah fitur yang menunjukkan adanya outlier yang jelas pada dataset ini:

- Terlihat jelas adanya outlier pada Temperature yang sangat tinggi (di atas 60°C) dan sangat rendah (di bawah 0°C). Nilai-nilai ini tidak realistis dan harus diperiksa lebih lanjut.

- Wind Speed (Kecepatan) angin menunjukkan adanya outlier yang cukup signifikan, dengan beberapa nilai mencapai lebih dari 30 km/jam, yang tidak lazim pada sebagian besar data.

- Terlihat outlier pada nilai UV Index yang sangat tinggi, mencapai 14. Sebagian besar data berada pada kisaran 0-7, sementara nilai lebih dari 7 adalah outlier yang perlu diperhatikan.

- Visibility (Jarak pandang) menunjukkan adanya outlier pada nilai yang sangat rendah (mungkin mendekati 0 km) dan sangat tinggi (mendekati 20 km). Ini menandakan bahwa beberapa nilai sangat jauh dari nilai-nilai lainnya.

- Atmospheric Pressure menunjukkan beberapa outlier pada nilai yang sangat rendah (di bawah 900 hPa) dan sangat tinggi (di atas 1100 hPa), yang mungkin mencerminkan kondisi cuaca yang tidak biasa atau kesalahan pengukuran.

Outlier pada fitur seperti Temperature, Wind Speed, UV Index, dan Visibility perlu dianalisis lebih lanjut, karena mereka bisa merusak distribusi data dan memengaruhi model prediksi. Untuk itu, perlu menggunakan metode seperti IQR (Interquartile Range) untuk menangani outlier dan memastikan data yang digunakan untuk analisis lebih konsisten dan valid.

![image](https://drive.google.com/file/d/1KCsnLArx2qHToI8hu1p2wCJn33zjV0Bk/view?usp=sharing)
Gambar 3. Persebaran data

Gambar 3 merupakan visualisasi exploratory data analysis dari persebaran data pada dataset yang digunakan pada project ini adalah weather type. 
Berdasarkan visualisasi distribusi pada gambar, berikut adalah penjelasan untuk beberapa fitur yang ada dalam dataset :

Distribusi variabel dalam dataset menunjukkan variasi yang baik dalam kebanyakan fitur, meskipun ada beberapa outlier yang perlu ditangani, seperti pada fitur Temperature, Wind Speed, Precipitation, dan UV Index. Selain itu, terdapat ketidakseimbangan pada fitur Season Count yang sangat didominasi oleh Winter, dan Cloud Cover yang lebih sering mencatatkan kondisi berawan. Metode SMOTE akan dilakukan untuk menangani value yang tidak seimbang.

### EDA - Multivariate Analysis

![image](https://drive.google.com/file/d/1_HUt7t7YePVFgoHmOfMj5NdxXj-0MkSA/view?usp=sharingg)
Gambar 4. Analisis Multivariate Matriks korelasi

Pada Gambar 4 Analisis Multivariate, dengan menggunakan matriks korelasi. beriku adalah penjelasan dari matriks korelasi :
- Humidity dan Precipitation memiliki korelasi positif yang kuat (0.64), yang menunjukkan bahwa semakin tinggi kelembaban, semakin tinggi pula kemungkinan curah hujan.
- Wind Speed memiliki korelasi positif dengan Precipitation (0.44), yang mengindikasikan bahwa kecepatan angin mungkin sedikit berpengaruh terhadap curah hujan.
- Temperature dan UV Index memiliki korelasi positif (0.37), yang menunjukkan bahwa suhu yang lebih tinggi cenderung terkait dengan peningkatan intensitas radiasi UV.
- Visibility memiliki korelasi negatif dengan Humidity (-0.48) dan Precipitation (-0.46), yang menunjukkan bahwa pada kondisi kelembaban atau hujan yang lebih tinggi, jarak pandang cenderung berkurang.

### EDA - Multivariate Analysis

![image](https://drive.google.com/file/d/107slZeH32LtxsT4POH94-KKuRLJUouQm/view?usp=sharing)
Gambar 5. Multivariate Analysis

Pada Gambar 5 Multivariate analysis digunakan untuk melihat hubungan setiap kolom. berikut adalah penjelasannya :
- -Beberapa kolom seperti Wind Speed dan Precipitation menunjukkan distribusi yang sangat terpusat, sedangkan variabel lain memiliki distribusi yang lebih normal.

- Beberapa variabel seperti Temperature dan Humidity atau Precipitation dan Wind Speed menunjukkan hubungan yang cukup kuat, yang dapat membantu dalam membangun model yang lebih efisien.

Dengan menggunakan Multivariate Analysis, dapat membantu mengevaluasi hubungan antar variabel dan distribusi data dalam dataset. Ini juga sangat membantu dalam mendeteksi pola dan korelasi yang bisa digunakan dalam analisis lebih lanjut atau pemodelan.

## Data Preparation
Berikut merupakan data preparation yang diterapkan pada project ini :

1. Data Gathering
Pada tahap ini, data diimport agar dapat dibaca dan diproses dengan baik menggunakan dataframe dari library Pandas. Proses ini penting untuk memastikan data yang dikumpulkan dapat diolah secara efisien dan akurat.

2. Pemeriksaan Missing Values
Langkah awal adalah memastikan tidak ada data yang hilang (missing values) pada dataset. Pemeriksaan dilakukan untuk mengetahui apakah terdapat kolom atau baris dengan nilai kosong. Jika terdapat missing values, langkah penanganan seperti imputasi (mengisi nilai kosong dengan rata-rata) perlu diterapkan untuk menjaga integritas dataset. Dalam kasus ini, hasil pemeriksaan menunjukkan tidak ada data yang hilang, sehingga tidak diperlukan langkah penanganan lebih lanjut untuk missing values.

3. Pemilahan Fitur (X) dan Label (Y)
Dataset dipisahkan menjadi dua bagian utama:
   - Fitur independen (X): Kolom yang digunakan untuk memprediksi hasil (dari kolom kedua hingga sebelum kolom terakhir).
   - Target label (Y): Kolom terakhir, yang merupakan output yang ingin diprediksi oleh model. Langkah ini penting untuk memisahkan variabel yang digunakan dalam analisis dan variabel target yang akan diprediksi.

4. Encoding Kategorikal
Fitur kategorikal, yang berupa data non-numerik seperti nama atau kategori, diubah menjadi representasi numerik menggunakan One-Hot Encoding dan Label Encoding. Pada dataset ini, kolom tertentu yang memiliki nilai kategorikal diterjemahkan menjadi representasi biner. Hal ini dilakukan untuk memastikan algoritma machine learning dapat memproses data tersebut. One-Hot Encoding dan LabelEncoding diterapkan pada kolom yang merupakan kolom kategori.

5. Pengecekan Dimensi Data
Setelah proses encoding, dimensi data diperiksa untuk memastikan bahwa jumlah fitur dan label sudah sesuai dengan yang diharapkan. Hal ini memastikan data telah diproses dengan benar dan siap untuk digunakan dalam tahap berikutnya.

6. Split Dataset
Dataset dibagi menjadi dua subset:
   - Data latih (training set): Digunakan untuk melatih model agar dapat mengenali pola dalam data.
   - Data uji (test set): Digunakan untuk mengevaluasi performa model pada data baru yang belum pernah dilihat sebelumnya.
Pembagian dilakukan dengan rasio 80:20, di mana 80% digunakan untuk pelatihan dan 20% untuk pengujian. Random state juga digunakan untuk memastikan hasil pembagian dataset konsisten di setiap eksekusi.

7. Penanganan Ketidakseimbangan Data dengan SMOTE
Ketidakseimbangan kelas sering menjadi masalah dalam dataset, terutama jika salah satu kelas target jauh lebih sedikit dibandingkan kelas lainnya. Dalam kasus ini, digunakan SMOTE (Synthetic Minority Over-sampling Technique) untuk menyeimbangkan data. Teknik ini menghasilkan sampel sintetik dari kelas minoritas dengan cara menginterpolasi antara contoh yang ada. Hasilnya adalah dataset yang lebih seimbang, memungkinkan model untuk mempelajari pola dari kedua kelas secara lebih efektif.
   - Sebelum penerapan SMOTE, ditampilkan jumlah data pada masing-masing kelas.
   - Setelah SMOTE, dataset di-resample sehingga jumlah data untuk setiap kelas menjadi seimbang.

## Modeling
Pada project ini menggunakan 8 algoritma machine learning yang diantaranya sebagai berikut :

## 1. **Logistic Regression**

**Logistic Regression** adalah metode statistik yang digunakan untuk klasifikasi biner dengan memodelkan probabilitas suatu kejadian. Model ini menghasilkan fungsi sigmoid untuk mengubah output regresi linier menjadi nilai antara 0 dan 1.

### Kelebihan
- **Mudah Diinterpretasikan**  
  Menyediakan probabilitas yang jelas untuk klasifikasi, memudahkan pemahaman hasil.
- **Cepat dan Efisien**  
  Proses pelatihan cepat, efektif untuk dataset kecil hingga menengah.
- **Penerapan Luas**  
  Sering digunakan di berbagai bidang seperti medis, pemasaran, dan ilmu sosial.

### Kekurangan
- **Asumsi Linearitas**  
  Kurang efektif untuk data dengan hubungan non-linear tanpa transformasi fitur.
- **Sensitif Terhadap Outlier**  
  Kinerja dapat terpengaruh oleh nilai pencilan dalam data.

### Parameter Utama
- **`C`**  
  Invers regularisasi (1/λ). Semakin kecil nilai `C`, semakin kuat regularisasi untuk menghindari overfitting.
- **`penalty`**  
  Jenis penalti pada koefisien model:  
  - `l1`: Penalti Lasso  
  - `l2`: Penalti Ridge  
  - `elasticnet`: Kombinasi penalti L1 dan L2  
  - `none`: Tanpa penalti.
- **`solver`**  
  Algoritma optimasi (misalnya, `liblinear` untuk dataset kecil).
- **`random_state`**  
  Untuk memastikan hasil dapat direplikasi.

---

## 2. **K-Nearest Neighbors (KNN)**

**KNN** adalah algoritma pembelajaran yang digunakan untuk klasifikasi dan regresi. Metode ini mencari `k` tetangga terdekat dan mengklasifikasikan data berdasarkan mayoritas kelas dari tetangga terdekat.

### Kelebihan
- **Mudah Dipahami dan Sederhana**  
  Konsep dasar mudah dipahami dan diimplementasikan.
- **Non-parametrik**  
  Tidak memerlukan model pelatihan yang rumit.

### Kekurangan
- **Lambat untuk Dataset Besar**  
  Kinerja menurun saat menghitung jarak terhadap seluruh dataset.
- **Sensitif terhadap Skala Fitur**  
  Memerlukan normalisasi fitur agar hasil tidak terdistorsi.

### Parameter Utama
- **`n_neighbors`**  
  Jumlah tetangga yang digunakan untuk klasifikasi.
- **`metric`**  
  Metode pengukuran jarak, seperti Euclidean atau Manhattan.
- **`weights`**  
  Menentukan apakah semua tetangga memiliki bobot sama atau berdasarkan jarak.
- **`p`**  
  Parameter untuk jarak Minkowski. `p=1` untuk Manhattan, `p=2` untuk Euclidean.

---

## 3. **Support Vector Machine (SVM)**

**SVM** adalah algoritma klasifikasi yang mencari hyperplane optimal untuk memisahkan data dari dua kelas. Dengan kernel, SVM juga dapat menangani data non-linier.

### Kelebihan
- **Efektif pada Dimensi Tinggi**  
  Sangat baik untuk ruang fitur yang memiliki dimensi tinggi.
- **Tahan Terhadap Overfitting**  
  Cenderung menghasilkan model yang mampu melakukan generalisasi dengan baik.

### Kekurangan
- **Lambat pada Dataset Besar**  
  Waktu pelatihan lebih lama karena kompleksitas perhitungan.
- **Memerlukan Penyesuaian Parameter yang Teliti**  
  Butuh pemilihan parameter `C` dan `gamma` yang hati-hati.

### Parameter Utama
- **`C`**  
  Mengontrol seberapa banyak kesalahan yang diizinkan.
- **`kernel`**  
  Jenis kernel yang digunakan, seperti `linear`, `rbf`, atau `poly`.
- **`gamma`**  
  Besarnya pengaruh data individu pada keputusan klasifikasi.
- **`degree`**  
  Tingkat polinomial untuk kernel polynomial.
- **`random_state`**  
  Untuk hasil yang konsisten.

---

## 4. **Naive Bayes (Bernoulli)**

**Naive Bayes (Bernoulli)** adalah algoritma klasifikasi probabilistik yang digunakan untuk dataset biner, mengasumsikan bahwa fitur dalam dataset mengikuti distribusi Bernoulli.

### Kelebihan
- **Cepat dan Efisien**  
  Proses pelatihan dan prediksi sangat cepat.
- **Cocok untuk Data Biner**  
  Ideal untuk teks atau data biner.

### Kekurangan
- **Asumsi Independensi Fitur**  
  Asumsi ini jarang terpenuhi dalam kenyataan, yang dapat menurunkan akurasi.
- **Tidak Cocok untuk Data Kontinu**  
  Kinerja menurun bila diterapkan pada dataset kontinu.

### Parameter Utama
- **`alpha`**  
  Parameter smoothing Laplace untuk menghindari probabilitas nol.
- **`binarize`**  
  Ambang batas untuk binarisasi data input.

---

## 5. **Naive Bayes (Gaussian)**

**Naive Bayes (Gaussian)** adalah varian dari Naive Bayes yang digunakan untuk data kontinu, dengan asumsi bahwa fitur mengikuti distribusi Gaussian.

### Kelebihan
- **Efisien untuk Data Kontinu**  
  Sangat cocok untuk data numerik.
- **Tidak Memerlukan Tuning Parameter yang Rumit**  
  Hanya membutuhkan estimasi rata-rata dan varians.

### Kekurangan
- **Sensitif terhadap Deviations dari Asumsi Gaussian**  
  Kinerja bisa menurun jika data tidak mengikuti distribusi normal.
- **Asumsi Independensi Fitur**  
  Sama seperti Bernoulli.

### Parameter Utama
- **`var_smoothing`**  
  Menambahkan nilai kecil pada varians untuk menghindari pembagian nol.

---

## 6. **Decision Tree**

**Decision Tree** adalah algoritma yang membagi dataset berdasarkan fitur-fitur yang paling mempengaruhi keputusan, menggunakan struktur pohon untuk klasifikasi.

### Kelebihan
- **Mudah Diinterpretasikan**  
  Visualisasi pohon memudahkan pemahaman proses keputusan.
- **Tidak Memerlukan Normalisasi Fitur**  
  Dapat menangani fitur numerik dan kategorikal.

### Kekurangan
- **Rentan terhadap Overfitting**  
  Biasanya memerlukan pemangkasan atau teknik regulasi.
- **Sensitif terhadap Perubahan Data**  
  Perubahan kecil dalam data bisa mengubah pohon secara signifikan.

### Parameter Utama
- **`max_depth`**  
  Kedalaman maksimum pohon.
- **`min_samples_split`**  
  Minimum sampel yang dibutuhkan untuk membagi node.
- **`criterion`**  
  Ukuran kualitas pemisahan (Gini impurity atau entropy).
- **`splitter`**  
  Metode pemilihan split (`best` atau `random`).

---

## 7. **Random Forest**

**Random Forest** adalah metode ensemble yang menggunakan banyak decision tree untuk meningkatkan akurasi dan mengurangi overfitting.

### Kelebihan
- **Tahan terhadap Overfitting**  
  Lebih stabil dibandingkan decision tree tunggal.
- **Efektif untuk Dataset Besar**  
  Bekerja dengan baik pada dataset besar.

### Kekurangan
- **Kurang Interpretable**  
  Kompleksitas tinggi dibandingkan decision tree tunggal.
- **Lambat pada Dataset Besar**  
  Waktu pelatihan lebih lama dibandingkan dengan algoritma lainnya.

### Parameter Utama
- **`n_estimators`**  
  Jumlah pohon dalam ensemble.
- **`criterion`**  
  Fungsi split (Gini atau entropy).
- **`max_depth`**  
  Kedalaman maksimum pohon.
- **`min_samples_split`**  
  Sama seperti Decision Tree.

---

## 8. **XGBoost**

**XGBoost** adalah algoritma boosting yang mengoptimalkan gradient boosting dengan pendekatan yang efisien.

### Kelebihan
- **Cepat dan Efisien**  
  Mendukung optimisasi paralel dan memiliki performa tinggi.
- **Menangani Nilai Hilang dengan Baik**  
  Menangani nilai yang hilang secara otomatis.

### Kekurangan
- **Memerlukan Tuning Parameter yang Cermat**  
  Butuh pemilihan parameter yang hati-hati untuk hasil optimal.
- **Risiko Overfitting**  
  Rentan terhadap overfitting pada dataset yang besar jika tidak ditangani dengan baik.

### Parameter Utama
- **`learning_rate`**  
  Ukuran langkah pembelajaran.
- **`max_depth`**  
  Kedalaman maksimum pohon.
- **`n_estimators`**  
  Jumlah iterasi boosting.

##Evaluation
Menggunakan matriks evaluasi Accuracy	K-Fold Mean Accuracy	Std. Deviation	Precision	Recall	F1

Tabel 2. Evaluasi
Berikut adalah hasil evaluasi berbagai model prediksi cuaca berdasarkan beberapa metrik kinerja:

| Model            | Accuracy  | K-Fold Mean Accuracy | Std. Deviation | Precision | Recall  | F1      |
|------------------|-----------|----------------------|----------------|-----------|---------|---------|
| XGBoost          | 92.31%    | 91.15%               | 0.745945       | 0.923285  | 0.923082 | 0.923047 |
| Random Forest    | 91.82%    | 91.46%               | 0.978454       | 0.918535  | 0.918217 | 0.918300 |
| Decision Tree    | 90.91%    | 90.45%               | 0.970170       | 0.909134  | 0.909252 | 0.909131 |
| KNeighbors       | 89.73%    | 88.37%               | 0.977537       | 0.898640  | 0.897037 | 0.897472 |
| Logistic Regresion | 86.25%  | 84.04%               | 0.886568       | 0.864687  | 0.862150 | 0.861645 |
| SVM              | 83.94%    | 82.50%               | 0.914010       | 0.845519  | 0.838243 | 0.838937 |
| GaussianNB       | 81.06%    | 81.08%               | 0.895425       | 0.828575  | 0.808969 | 0.809858 |
| BernoulliNB      | 66.89%    | 66.39%               | 0.804032       | 0.705650  | 0.668794 | 0.680106 |

## Kesimpulan
Model XGBoost menunjukkan performa terbaik dengan akurasinya 92.31%, diikuti oleh Random Forest dengan 91.82% dan Decision Tree dengan 90.9%. Model-model ini unggul berkat kemampuannya dalam menangkap pola kompleks dan mengatasi variabilitas dalam data, dengan XGBoost dan Random Forest menggunakan teknik ensemble untuk mengurangi risiko overfitting. KNeighbors juga menunjukkan kinerja yang baik dengan akurasi 89.73%, meskipun sedikit lebih rendah dibandingkan model ensemble.

Sementara itu, model Logistic Regression dan SVM memberikan hasil yang lebih rendah, dengan SVM mencapai 83.93% dan Logistic Regression 86.25%. Meskipun hasilnya cukup baik, keduanya kalah dibandingkan dengan model ensemble yang lebih kompleks. Model GaussianNB dan BernoulliNB memiliki performa terendah, dengan GaussianNB mencatat 81.06% dan BernoulliNB hanya 66.89%, yang menunjukkan keterbatasan mereka dalam menangani data yang lebih kompleks.

Secara keseluruhan, XGBoost dan Random Forest tetap menjadi pilihan terbaik berdasarkan akurasi dan keseimbangan antara Precision, Recall, dan F1-Score, menunjukkan kemampuan mereka dalam menangani dataset yang lebih besar dan lebih beragam. Model seperti Decision Tree dan KNeighbors memberikan alternatif yang baik, tetapi dengan sedikit penurunan dalam performa, sedangkan model Logistic Regression dan SVM lebih cocok untuk kasus yang lebih sederhana dengan dataset yang lebih kecil.

## Kesimpulan Dampak Model Terhadap Business Understanding

## 1. Menjawab Problem Statements
Model yang dievaluasi telah berhasil menjawab sebagian besar problem statements.

- **Efektivitas Model Machine Learning dan Deep Learning**  
  Model XGBoost dan Random Forest menunjukkan performa terbaik dengan akurasi tinggi 92.31%.  
  Ini menunjukkan bahwa algoritma ensemble sangat efektif dalam memprediksi cuaca berdasarkan data historis.

- **Identifikasi Algoritma Terbaik**  
  Berdasarkan evaluasi, XGBoost dan Random Forest adalah algoritma unggulan yang memberikan hasil terbaik.  

## 2. Mencapai Goals
Tujuan dari proyek ini berhasil dicapai.

- **Pembangunan Model Akurasi Tinggi**  
  Dengan akurasi hingga 92.31%, proyek ini telah menghasilkan model prediksi cuaca yang sangat andal.

- **Perbandingan Performansi Algoritma**  
  Evaluasi menyeluruh terhadap berbagai algoritma memberikan pemahaman yang jelas tentang kekuatan dan kelemahan masing-masing metode.

## 3. Dampak Solusi Statement
Solusi yang dirancang berdampak signifikan terhadap hasil proyek.

- **Analisis Data dan Preprocessing**  
  Proses ini membantu dalam mengidentifikasi fitur-fitur penting yang relevan dengan weather type, temperature, wind speed, season.

- **Penerapan Algoritma Machine Learning**  
  Penggunaan berbagai model memberikan wawasan luas tentang pola prediksi cuaca dalam data.  
  Model ensemble seperti XGBoost dan Random Forest memberikan hasil terbaik.

- **Penanganan Ketidakseimbangan Data**  
  Teknik SMOTE memastikan bahwa model dapat menangani ketidak seimbangan dalam data, meningkatkan keadilan dalam prediksi.


## Daftar Pustaka

1. Panish | Shea | Ravipudi LLP. (2025). Aviation and Plane Crash Statistics. Diakses pada 18 Juni 2025, dari https://www.panish.law/aviation_accident_statistics.html
2. Weather Concerns for General Aviation. (2018). Flight Safety Foundation. Diakses pada 18 Juni 2025, dari https://flightsafety.org/asw-article/weather-concerns-for-general-aviation/
3. Basuki Rochmat, & Sukendra Martha. (2021). Pengaruh Faktor Geografis terhadap Keselamatan Penerbangan di Indonesia. Jurnal Lemhannas RI, 9(2), 13–23. https://doi.org/10.55960/jlri.v9i2.388
4. NCAS. (2024). What causes weather? Diakses pada 18 Juni 2025, dari https://ncas.ac.uk/learn/what-causes-weather/
5. Mahendra, M. F. R., Azizah, N. L., & Sumarno. (2024). Implementasi Machine Learning Untuk Memprediksi Cuaca Menggunakan Support Vector Machine. Jurnal Ilmiah Komputasi, 23(1), 45–50. https://doi.org/10.32409/jikstik.23.1.3499
6. Rangkuti, M. Y. R., Alfansyuri, M. V., & Gunawan, W. (2021). Penerapan Algoritma K-Nearest Neighbor (Knn) Dalam Memprediksi Dan Menghitung Tingkat Akurasi Data Cuaca Di Indonesia. Hexagon Jurnal Teknik Dan Sains, 2(2), 11–16. https://doi.org/10.36761/hexagon.v2i2.1082
