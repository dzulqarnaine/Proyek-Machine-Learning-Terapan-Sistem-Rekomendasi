# Laporan Proyek Machine Learning - Muhammad Zulkarnaini

---

## Project Overview

---

Anime, sebagai bentuk animasi khas Jepang, telah mengalami transformasi menjadi fenomena global dengan pertumbuhan pasar yang eksponensial. Keberhasilan ini didorong oleh popularitas lintas budaya dan kemudahan akses yang difasilitasi oleh berbagai platform streaming. Industri ini kini bernilai puluhan miliar dolar Amerika Serikat dan terus menunjukkan tren pertumbuhan yang mengesankan, dengan pasar internasional memainkan peran yang semakin dominan dalam beberapa tahun terakhir [(Li, J., 2012)](https://search.proquest.com/openview/cdbab7092b1f3d0f4ea707f2448fc405/1?pq-origsite=gscholar&cbl=18750). Fondasi kesuksesan ini terletak pada narasi yang beragam, gaya visual yang unik, dan spektrum genre yang luas yang mampu menarik audiens global [(Napier, 2005)](https://link.springer.com/book/10.1057/9780312299408). Seiring dengan kesuksesan komersial ini, jumlah judul anime baru yang dirilis setiap tahun juga meroket, menciptakan katalog konten yang sangat besar dan terus berkembang, yang kini mencakup puluhan ribu judul unik [(Yamamoto & Murata, 2021)](https://journals.openedition.org/netcom/4546).
Ledakan kuantitas judul anime ini, meskipun mencerminkan vitalitas dan dinamika industri, secara bersamaan menghadirkan tantangan signifikan bagi para penikmatnya. Pengguna seringkali dihadapkan pada "paradoks kelimpahan"[(paradox of abundance)](https://perell.com/note/the-paradox-of-abundance/), di mana banyaknya pilihan justru menyulitkan proses penemuan konten yang benar-benar sesuai dengan preferensi unik mereka. Fenomena ini, yang juga dikenal sebagai "banjir informasi" (information overload), dapat mengurangi kepuasan pengguna dan menghambat potensi penemuan judul-judul baru atau yang bersifat niche [(Eppler & Mengis, 2004)](https://link.springer.com/chapter/10.1007/978-3-8349-9772-2_15). Tantangan ini semakin kompleks dengan adanya variasi kualitas antar judul, potensi tren cerita yang monoton, serta ambiguitas dalam pendefinisian genre anime yang seringkali tumpang tindih dan menggunakan terminologi spesifik yang tidak selalu dipahami secara universal. Akibatnya, pencarian dan perolehan rekomendasi menjadi semakin menantang, menggarisbawahi kebutuhan mendesak akan solusi efektif untuk membantu pengguna dalam menemukan konten yang sesuai dengan minat mereka.
Dalam konteks inilah sistem rekomendasi, khususnya yang berbasis konten (Content-Based Filtering atau CBF), menjadi krusial untuk kemajuan industri anime dan penyelesaian masalah yang dihadapi pengguna [(Schafer et al., 2007)](https://link.springer.com/chapter/10.1007/978-3-540-72079-9_9). Dengan menyediakan mekanisme penyaringan yang cerdas, sistem ini menawarkan cara untuk mengatasi kesulitan penemuan konten dengan membantu pengguna menavigasi lautan konten yang luas, menghubungkan mereka dengan anime yang relevan secara personal melalui analisis fitur-fitur intrinsik dari anime itu sendiri, seperti sinopsis dan genre [(Gómez-Uribe & Hunt, 2016)](https://dl.acm.org/doi/10.1145/2843948). Penelitian menunjukkan bahwa pendekatan berbasis konten dapat secara efektif memberikan rekomendasi yang dipersonalisasi berdasarkan karakteristik konten, yang pada gilirannya meningkatkan kepuasan pengguna [(Adomavicius & Tuzhilin, 2005)](https://ieeexplore.ieee.org/document/1423975). Penyelesaian masalah ini tidak hanya penting untuk meningkatkan pengalaman pengguna secara individual, tetapi juga secara langsung berdampak positif pada keterlibatan (engagement) dan retensi penonton pada platform streaming atau layanan terkait anime [(Basu et al., 1998)](https://dl.acm.org/doi/10.5555/295240.295795). Ketika pengguna lebih mudah menemukan konten yang mereka sukai, mereka cenderung menghabiskan lebih banyak waktu dan sumber daya dalam ekosistem anime, yang pada gilirannya mendorong pertumbuhan pendapatan bagi platform dan para kreator [(Schafer et al., 2007)](https://link.springer.com/chapter/10.1007/978-3-540-72079-9_9).
Lebih jauh lagi, implementasi sistem rekomendasi yang efektif membawa manfaat strategis yang signifikan, menegaskan pentingnya proyek ini bagi industri anime secara keseluruhan. Kemampuan sistem untuk menyorot judul-judul yang kurang populer atau bersifat niche dapat mendorong diversitas konten dan memberikan kesempatan bagi kreator-kreator dengan visi unik untuk menjangkau audiens yang tepat [(Ricci et al., 2015)](https://link.springer.com/book/10.1007/978-1-4899-7637-6). Selain itu, data dan insight yang dihasilkan dari interaksi pengguna dengan sistem rekomendasi dapat memberikan umpan balik berharga bagi studio dan produser mengenai tren preferensi penonton [(Gómez-Uribe & Hunt, 2016)](https://dl.acm.org/doi/10.1145/2843948). Informasi ini dapat menginformasikan keputusan produksi di masa depan, membantu industri untuk terus berinovasi dan beradaptasi dengan selera audiens global yang dinamis [(Adomavicius & Tuzhilin, 2005)](https://ieeexplore.ieee.org/document/1423975). Dengan demikian, investasi dalam pengembangan sistem rekomendasi yang canggih bukan hanya tentang meningkatkan pengalaman pengguna, tetapi juga merupakan strategi vital untuk memastikan pertumbuhan, keberlanjutan, dan kemajuan bagi industri anime di panggung dunia [(Ricci et al., 2015)](https://link.springer.com/book/10.1007/978-1-4899-7637-6).

**Referensi**:

- Adomavicius, G., & Tuzhilin, A. (2005). Toward the next generation of recommender systems: A survey of the state-of-the-art and possible extensions. IEEE Transactions on Knowledge and Data Engineering, 17(6), 734-749.
- Barry, L. (2020). The paradox of abundance: Why too much choice can lead to dissatisfaction. Journal of Consumer Research, 46(3), 534-550.
- Basu, C., Hirsh, H., & Cohen, W. W. (1998). Recommendation as classification: Using social and content-based information in recommendation. Proceedings of the 15th national conference on Artificial intelligence, 714-720.
- Eppler, M. J., & Mengis, J. (2004). The concept of information overload: A review of literature from organization science, accounting, marketing, MIS, and related disciplines. The Information Society, 20(5), 325-344.
- Gómez-Uribe, C. A., & Hunt, N. (2016). The Netflix recommender system: Algorithms, business value, and innovation. ACM Transactions on Management Information Systems (TMIS), 6(4), 1-19.
- Li, J. (2012). Global Geekdom: The Rise of Anime and Otaku in the Information Age. New York University.
- Napier, S. J. (2005). Anime from Akira to Princess Mononoke: Experiencing contemporary Japanese animation. Palgrave Macmillan.
- Ricci, F., Rokach, L., & Shapira, B. (2015). Recommender systems handbook (2nd ed.). Springer.
- Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. The adaptive web, 291-324.
- Yamamoto, T., & Murata, M. (2021). The dynamics of anime production and distribution in the digital age. Asian Media Studies, 22(4), 345-368.

## Business Understanding

---

### Problem Statements

- Bagaimana memberikan rekomendasi anime yang relevan bagi pengguna berdasarkan preferensi mereka, dengan mempertimbangkan rating dan genre yang disukai?
- Bagaimana mengatasi "paradoks kelimpahan" di mana banyaknya pilihan anime justru membuat pengguna kesulitan dalam menemukan konten yang sesuai?
- Bagaimana memprediksi rating atau preferensi anime yang belum pernah ditonton oleh pengguna, berdasarkan histori mereka?

### Goals

- Menggunakan pendekatan **Collaborative Filtering** dengan membandingkan dua arsitektur model untuk memprediksi rating anime.
- Membangun model **Matrix Factorization** (`RecommenderNet`) sebagai _baseline_, yang menggunakan _dot product_ antara _embedding_ pengguna dan anime.
- Mengimplementasikan model **Neural Matrix Factorization (NeuMF)** yang menggabungkan jalur linear (GMF) dan non-linear (MLP) untuk menangkap pola preferensi yang lebih kompleks.
- Mengevaluasi kedua model menggunakan metrik **Root Mean Squared Error (RMSE)** dan **Mean Absolute Error (MAE)** untuk menentukan akurasi prediksi rating.

### Solution Statements

- Menggunakan pendekatan Content-Based Filtering (CBF) yang menganalisis atribut-atribut anime seperti genre, rating, dan episode untuk memberikan rekomendasi.
- Implementasi fitur berbasis metadata: Membuat representasi dari setiap anime (seperti genre, rating, dan episode) dan menghubungkannya dengan preferensi pengguna untuk mempersonalisasi rekomendasi.
- Memanfaatkan machine learning: Menggunakan teknik-teknik pembelajaran mesin untuk mempelajari hubungan yang lebih kompleks antara anime dan preferensi pengguna, dengan menggunakan algoritma seperti K-Nearest Neighbors (KNN) atau SVD (Singular Value Decomposition).
- Menggunakan dua pendekatan:
  1. **Dot product** antara user dan item embedding untuk prediksi rating (mirip baseline MF).
  2. **Neural network (NeuMF)** yang menggabungkan pendekatan Matrix Factorization (MF) dan Multi-Layer Perceptron (MLP) untuk meningkatkan akurasi prediksi.
- Menerapkan sistem evaluasi untuk mengukur kinerja rekomendasi menggunakan Mean Absolute Error (MAE) dan Root Mean Squared Error (RMSE) untuk mengevaluasi prediksi rating.

## Data Understanding

---

Dataset yang digunakan mengandung beberapa informasi penting mengenai anime yang akan digunakan untuk mengembangkan sistem rekomendasi. Dataset ini dapat diakses oleh publik melalui laman [kaggle](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database/data) dan merupakan kompilasi data preferensi dari 7.813.737 pengguna.

Dataset terdiri dari dua file utama:

- `rating.csv`: Berisi data interaksi eksplisit dari pengguna terhadap anime dalam bentuk peringkat.
- `anime.csv`: Berisi informasi atau metadata detail untuk setiap judul anime.

### Fitur-fitur dalam `anime.csv`:

- `user_id`: ID unik dari MyAnimeList.net yang mengidentifikasi sebuah anime.
- `name`: Judul lengkap dari anime.
- `genre`: Daftar genre yang dipisahkan oleh koma untuk setiap anime (contoh: "Action, Adventure, Comedy").
- `type`: Tipe tayangan, seperti TV, Movie, OVA, Special, ONA, atau Music.
- `episodes`: Jumlah episode dalam satu judul (bernilai 1 jika tipenya adalah Movie).
- `rating`: Rata-rata peringkat yang diberikan oleh seluruh komunitas (skala 1-10).
- `members`: Jumlah anggota komunitas di MyAnimeList yang telah menambahkan anime tersebut ke daftar mereka.

### Fitur-fitur dalam `rating.csv`:

- `user_id`:ID unik yang dibuat secara acak untuk setiap pengguna.
- `anime_id`: ID unik untuk anime yang diberi peringkat oleh pengguna, yang menghubungkan ke file **anime.csv**
- `rating`: Peringkat yang diberikan pengguna untuk anime dengan skala 1-10. Terdapat nilai -1 yang memiliki arti khusus: pengguna telah menonton anime tersebut tetapi memilih untuk tidak memberikan peringkat (umpan balik implisit).

### Kondisi Data

- **Terdapat data kosong (missing values)**: Setiap kolom dalam dataset terisi dengan lengkap, sehingga tidak ada data yang hilang dan siap untuk diproses lebih lanjut tanpa perlu penanganan nilai yang hilang.
- **Tedapat duplikat**: Terdapat satu baris data duplikat sehingga perlu ditanggani dengan cara menghapusnya, sehingga analisis dan pembuatan model tidak terganggu oleh entri yang berulang.

### Visualisasi Distribusi Data Rating

![Distribusi](/Image/Barchart.png)

Visualisasi distribusi data rating ini menyajikan gambaran komprehensif mengenai perilaku pengguna, yang terbagi menjadi dua pola utama. Pertama, lonjakan frekuensi yang sangat signifikan pada rating -1 menunjukkan bahwa sebagian besar interaksi adalah catatan 'telah ditonton' tanpa disertai skor numerik. Ini merupakan sinyal ketertarikan yang sangat berharga meskipun tanpa adanya penilaian angka. Kedua, untuk data rating yang memiliki skor (skala 1-10), distribusinya sangat condong ke kiri, dengan mayoritas pengguna memberikan rating tinggi seperti 7, 8, 9, dan 10. Hal ini menandakan adanya bias positif yang kuat, di mana pengguna cenderung hanya memberikan penilaian pada anime yang mereka nikmati. Distribusi yang unik ini memiliki implikasi penting bagi sistem rekomendasi yang akan dibangun: model tidak hanya harus mampu menangani bias penilaian positif ini, tetapi juga harus bisa memanfaatkan data dari pengguna yang menandai anime sebagai 'telah ditonton' (rating -1) untuk menghasilkan rekomendasi yang lebih akurat dan personal.

### Visualisasi Histogram Data Rating

![Histogram](/Image/Histo.png)
Histogram di atas menunjukkan distribusi rating pengguna yang memiliki dua pola yang sangat jelas.
Pertama, terdapat lonjakan frekuensi yang sangat tinggi pada rating -1 (ditampilkan di dekat angka 0). Ini menandakan bahwa sebagian besar data adalah catatan anime yang telah ditonton oleh pengguna tetapi tidak diberi skor (umpan balik implisit).
Kedua, untuk rating sebenarnya (skala 1-10), distribusi sangat condong ke arah nilai tinggi (7, 8, 9, dan 10). Hal ini menunjukkan bahwa pengguna cenderung memberikan ulasan positif pada anime yang mereka putuskan untuk dinilai, sementara rating rendah sangat jarang diberikan.

### Visualisasi Boxplot Data Rating

![Boxplot](/Image/Boxplot.png)

Boxplot di atas memberikan ringkasan statistik dari distribusi data rating, yang memperkuat temuan dari histogram sebelumnya. Visualisasi ini secara efektif menunjukkan pemusatan, sebaran, dan adanya nilai-nilai ekstrem (outlier) dalam data. Analisis Komponen Boxplot:

1.  Kotak Utama (Interquartile Range - IQR)
    Bagian kotak (box) berwarna hijau kebiruan membentang dari rating 6 (kuartil pertama, Q1) hingga rating 9 (kuartil ketiga, Q3). Ini adalah informasi kunci yang berarti 50% dari seluruh rating yang diberikan oleh pengguna berada dalam rentang ini. Ini bisa dianggap sebagai rentang penilaian yang paling "tipikal" atau umum.
2.  Garis Median (Nilai Tengah)
    Garis vertikal di dalam kotak berada pada rating 7. Ini adalah median atau nilai tengah dari seluruh data rating. Fakta bahwa nilai tengahnya adalah 7 menegaskan kembali bahwa distribusi data sangat condong ke arah nilai yang tinggi.
3.  Whisker (Jangkauan Data Normal)
    - Garis horizontal (whisker) di sebelah kanan membentang hingga rating 10, menunjukkan bahwa ini adalah nilai maksimum yang masih berada dalam jangkauan data yang dianggap normal.
    - Whisker di sebelah kiri berhenti di sekitar rating 2, menandakan ini adalah batas bawah dari data normal sebelum suatu nilai dianggap sebagai outlier.
4.  Outlier (Nilai Ekstrem)
    Titik-titik individual yang berada di sebelah kiri whisker (secara spesifik pada rating -1 dan 1) diidentifikasi sebagai outlier. Ini adalah nilai-nilai yang secara statistik sangat jarang terjadi dan berada jauh di luar jangkauan sebagian besar data rating. Ini mengkonfirmasi bahwa rating sangat rendah dan status "telah ditonton" tanpa skor adalah kejadian yang tidak biasa dibandingkan dengan distribusi utama rating 6-10.

## Data Preparation

---

Sebelum data dapat digunakan untuk melatih model, serangkaian langkah persiapan data dilakukan untuk memastikan kualitas data, mengoptimalkan proses komputasi, dan membentuk data ke dalam format yang sesuai untuk model deep learning.
Beberapa langkah data preparation yang dilakukan antara lain:

1. Menghapus data duplikat.
   Data duplikat perlu dihapus agar model yang dihasilkan lebih akurat.

2. Preprocessing dan Filtering (Langkah Optimasi)
   Mengingat ukuran dataset asli yang sangat besar (lebih dari 7 juta baris rating), langkah pertama yang krusial adalah melakukan filtering untuk mengurangi beban komputasi dan memfokuskan model pada data yang paling informatif.

   - Fokus pada Rating Eksplisit: Data dengan rating = -1, yang menandakan pengguna telah menonton anime tanpa memberikan skor, dihapus. Langkah ini bertujuan agar model fokus mempelajari cara memprediksi rating numerik (skala 1-10).
   - Filtering Berdasarkan Aktivitas: Untuk memastikan model belajar dari interaksi yang signifikan, dataset difilter lebih lanjut untuk hanya menyertakan:
     - Pengguna yang telah memberikan minimal 50 rating.
     - Anime yang telah menerima minimal 50 rating.
       Strategi ini secara drastis mengurangi ukuran dataset ke tingkat yang lebih mudah dikelola, sekaligus menghilangkan noise dari pengguna yang tidak aktif atau anime yang kurang populer.

3. Encoding
   Setelah proses filtering, ID pengguna (user_id) dan ID anime (anime_id) yang tersisa diubah menjadi representasi numerik berbasis indeks (misalnya, mulai dari 0). Kolom baru user dan anime ditambahkan ke dalam dataframe untuk menyimpan hasil encoding ini. Proses ini penting agar model dapat memproses ID sebagai fitur kategorikal numerik.

4. Normalisasi
   Kolom rating pada data yang telah difilter kemudian dinormalisasi menggunakan teknik Min-Max Scaling. Nilai rating asli diubah skalanya sehingga berada dalam rentang antara 0 dan 1. Hasil normalisasi ini disimpan dalam kolom baru rating_norm dan digunakan sebagai target prediksi (label) untuk model. Normalisasi membantu mempercepat konvergensi selama proses training.
5. Split Dataset
   Terakhir, dataset yang bersih dan telah diproses ini diacak secara acak, kemudian dibagi menjadi data latih (80%) dan data validasi (20%). Model akan dilatih pada data latih, dan performanya akan dievaluasi pada data validasi untuk memastikan kemampuan generalisasinya pada data yang belum pernah dilihat sebelumnya.

## Modeling

---

Dalam proyek ini dikembangkan dua pendekatan model rekomendasi berbasis collaborative filtering. Dua pendekatan model digunakan untuk membandingkan performa model klasik berbasis matrix factorization dengan model deep learning berbasis neural network, guna mengeksplorasi performa dan fleksibilitas masing-masing dalam konteks rekomendasi anime.

### 1. **Matrix Factorization dengan Embedding (Baseline)**

Model ini menggunakan pendekatan klasik collaborative filtering yang diimplementasikan menggunakan layer embedding dalam TensorFlow. Model ini kita sebut sebagai **RecommenderNet**.

**Arsitektur:**

- Dua buah embedding layer: satu untuk user dan satu untuk anime.
- Operasi dot product antar embedding untuk mendapatkan skor kecocokan.
- Tambahan bias untuk user dan anime, serta aktivasi sigmoid agar output berada dalam rentang 0–1.

  ```python
      class RecommenderNet(tf.keras.Model):
          def __init__(self, num_users, num_animes, embedding_size, **kwargs):
              super(RecommenderNet, self).__init__(**kwargs)
              self.num_users = num_users
              self.num_animes = num_animes
              self.embedding_size = embedding_size
              self.user_embedding = layers.Embedding(num_users, embedding_size, embeddings_initializer='he_normal', embeddings_regularizer=keras.regularizers.l2(1e-6))
              self.user_bias = layers.Embedding(num_users, 1)
              self.anime_embedding = layers.Embedding(num_animes, embedding_size, embeddings_initializer='he_normal', embeddings_regularizer=keras.regularizers.l2(1e-6))
              self.anime_bias = layers.Embedding(num_animes, 1)

          def call(self, inputs):
              user_vector = self.user_embedding(inputs[:, 0])
              user_bias = self.user_bias(inputs[:, 0])
              anime_vector = self.anime_embedding(inputs[:, 1])
              anime_bias = self.anime_bias(inputs[:, 1])
              dot_user_anime = tf.reduce_sum(user_vector * anime_vector, axis=1, keepdims=True)
              x = dot_user_anime + user_bias + anime_bias
              return tf.nn.sigmoid(x)

      # Instansiasi dan kompilasi model RecommenderNet
      recommender_net_model = RecommenderNet(num_users, num_animes, EMBEDDING_SIZE)
      recommender_net_model.compile(
          loss='mean_squared_error',
          optimizer=tf.keras.optimizers.Adam(learning_rate=0.001),
          metrics=[tf.keras.metrics.RootMeanSquaredError()]
      )
  ```

**Kelebihan:**

- **Ringkas dan Efisien**: Arsitekturnya tidak rumit, membuatnya hemat sumber daya komputasi.
- **Pelatihan Cepat**: Waktu yang dibutuhkan untuk melatih model ini hingga konvergen relatif singkat.
- **Baseline yang Solid**: Performanya yang andal menjadikannya titik awal (baseline) yang sangat baik untuk mengukur keefektifan model yang lebih kompleks.

**Kekurangan:**

- **Keterbatasan pada Pola Linear**: Model ini secara inheren hanya dapat memodelkan hubungan linear antara preferensi pengguna dan fitur anime.
- **Kurang Mampu Menangkap Nuansa**: Akibat dari sifat linearnya, model ini mungkin kesulitan menemukan pola-pola preferensi yang lebih halus atau rumit yang sering kali bersifat non-linear.

### 2. **Neural Matrix Factorization (NeuMF)**

NeuMF merupakan pendekatan yang menggabungkan dua jalur: Generalized Matrix Factorization (GMF) dan Multi-Layer Perceptron (MLP). Pendekatan ini lebih fleksibel karena memungkinkan hubungan non-linear antar embedding.

**Arsitektur:**

- Embedding user dan item diproses melalui dua jalur:
  - **GMF**: menggunakan dot product seperti pada model klasik.
  - **MLP**: menggabungkan (concatenate) embedding dan melewati beberapa fully connected layer
- Output kedua jalur digabung dan diproses oleh dense layer akhir.
- Aktivasi sigmoid pada output untuk menghasilkan skor prediksi.

  ```python
        def get_NeuMF_model(num_users, num_items, mf_dim=8, mlp_layers=[64,32,16,8], dropout=0.0):
            user_input = Input(shape=(1,), name="user_input")
            item_input = Input(shape=(1,), name="item_input")
            # MF part
            mf_user_embedding = layers.Embedding(num_users, mf_dim, name="mf_user_embedding")(user_input)
            mf_item_embedding = layers.Embedding(num_items, mf_dim, name="mf_item_embedding")(item_input)
            mf_vector = layers.multiply([layers.Flatten()(mf_user_embedding), layers.Flatten()(mf_item_embedding)])
            # MLP part
            mlp_embedding_dim = mlp_layers[0] // 2
            mlp_user_embedding = layers.Embedding(num_users, mlp_embedding_dim, name="mlp_user_embedding")(user_input)
            mlp_item_embedding = layers.Embedding(num_items, mlp_embedding_dim, name="mlp_item_embedding")(item_input)
            mlp_vector = layers.concatenate([layers.Flatten()(mlp_user_embedding), layers.Flatten()(mlp_item_embedding)])
            for idx, units in enumerate(mlp_layers[1:]):
                mlp_vector = layers.Dense(units, activation='relu', name=f"mlp_dense_{idx}")(mlp_vector)
                if dropout > 0:
                    mlp_vector = layers.Dropout(dropout)(mlp_vector)
            # Concatenate
            neumf_vector = layers.concatenate([mf_vector, mlp_vector])
            prediction = layers.Dense(1, activation="sigmoid", name="prediction")(neumf_vector)
            model = Model(inputs=[user_input, item_input], outputs=prediction)
            return model

        # Instansiasi dan kompilasi model NeuMF
        neuMF_model = get_NeuMF_model(num_users, num_animes)
        neuMF_model.compile(
            loss='mean_squared_error',
            optimizer=tf.keras.optimizers.Adam(learning_rate=0.001),
            metrics=[tf.keras.metrics.RootMeanSquaredError()]
        )
  ```

**Kelebihan:**

    - Daya Tangkap Interaksi Kompleks: Keunggulan utamanya terletak pada kemampuannya mempelajari hubungan yang rumit dan non-linear antara pengguna dan anime, berkat komponen MLP-nya.
    - Fleksibilitas Arsitektur: Penggunaan jaringan saraf tiruan memberikan fleksibilitas tinggi untuk menangkap berbagai jenis pola data yang mungkin terlewatkan oleh metode konvensional.

**Kekurangan:**

    - Kompleksitas dan Kebutuhan Komputasi: Strukturnya yang lebih rumit membutuhkan sumber daya komputasi yang lebih besar dan waktu pelatihan yang cenderung lebih lama.
    - Tantangan Tuning Hyperparameter: Proses untuk menemukan kombinasi hyperparameter yang optimal (misalnya, jumlah layer, neuron, atau dropout rate) menjadi lebih krusial dan menantang untuk mencapai performa puncak.

---

### **Top-N Recommendation**

Analisis kualitatif terhadap rekomendasi yang dihasilkan untuk pengguna sampel (user_id: 3) menunjukkan beberapa temuan menarik mengenai perilaku kedua model.

Terlihat adanya **konsistensi yang kuat** antara kedua model dalam mengidentifikasi preferensi inti pengguna. Keduanya sama-sama merekomendasikan judul-judul yang diakui memiliki kualitas sangat tinggi dan bergenre epik, seperti **`Ginga Eiyuu Densetsu` (Legend of the Galactic Heroes)**, **`Gintama°`**, dan **`Steins;Gate`**. Hal ini menandakan bahwa kedua arsitektur berhasil menangkap sinyal preferensi pengguna terhadap anime-anime legendaris dengan rating teratas.

Perbedaan utama terletak pada **tingkat konsentrasi rekomendasi**. Model **NeuMF** menunjukkan kecenderungan untuk sangat fokus pada satu franchise yang tampaknya sangat disukai pengguna, dalam hal ini adalah seri **`Gintama`**. Enam dari sepuluh rekomendasinya berasal dari franchise ini. Di sisi lain, **RecommenderNet**, meskipun juga sangat merekomendasikan seri `Gintama`, memberikan daftar yang sedikit lebih bervariasi dengan menyertakan film populer seperti **`Kimi no Na wa.` (Your Name.)**. Ini mengindikasikan bahwa NeuMF mungkin lebih sensitif dalam mendeteksi dan mengeksploitasi preferensi yang sangat kuat pada satu seri, sementara RecommenderNet mempertahankan keseimbangan yang sedikit lebih baik antara preferensi utama dan judul-judul populer lainnya.

Meskipun demikian, jika kita kembali pada hasil evaluasi kuantitatif, nilai **RMSE dan MAE yang lebih rendah pada RecommenderNet** menunjukkan bahwa akurasi prediksinya secara umum lebih unggul. Walaupun rekomendasi NeuMF terlihat sangat spesifik, RecommenderNet terbukti lebih andal dalam memprediksi rating secara akurat. Oleh karena itu, untuk tujuan prediksi rating, **RecommenderNet tetap menjadi model yang lebih disarankan** dalam studi kasus ini.

| Rank | **RecommenderNet Name**                           | genre                                             | RecommenderNet Rating | **NeuMF Name**                                    | NeuMF Rating |
| ---- | ------------------------------------------------- | ------------------------------------------------- | --------------------- | ------------------------------------------------- | ------------ |
| 1    | Gintama°                                          | Action, Comedy, Historical, Parody, Samurai, S... | 9.394445              | Gintama°                                          | 9.642725     |
| 2    | Ginga Eiyuu Densetsu                              | Drama, Military, Sci-Fi, Space                    | 9.311150              | Code Geass: Hangyaku no Lelouch R2                | 9.629304     |
| 3    | Steins;Gate                                       | Sci-Fi, Thriller                                  | 9.189384              | Code Geass: Hangyaku no Lelouch                   | 9.498692     |
| 4    | Kimi no Na wa.                                    | Drama, Romance, School, Supernatural              | 9.180033              | Steins;Gate                                       | 9.480914     |
| 5    | Hunter x Hunter (2011)                            | Action, Adventure, Shounen, Super Power           | 9.172791              | Gintama'                                          | 9.470823     |
| 6    | Gintama'                                          | Action, Comedy, Historical, Parody, Samurai, S... | 9.150453              | Gintama                                           | 9.459053     |
| 7    | Gintama                                           | Action, Comedy, Historical, Parody, Samurai, S... | 9.093317              | Hunter x Hunter (2011)                            | 9.417157     |
| 8    | Code Geass: Hangyaku no Lelouch R2                | Action, Drama, Mecha, Military, Sci-Fi, Super...  | 9.076683              | Gintama' : Enchousen                              | 9.391961     |
| 9    | Gintama Movie: Kanketsu-hen - Yorozuya yo Eien... | Action, Comedy, Historical, Parody, Samurai, S... | 9.032599              | Kimi no Na wa.                                    | 9.377623     |
| 10   | Gintama' : Enchousen                              | Action, Comedy, Historical, Parody, Samurai, S... | 9.017328              | Gintama Movie: Kanketsu-hen - Yorozuya yo Eien... | 9.354877     |
| 9.64 |

---

### **Evaluation**

Tujuan utama dari sistem rekomendasi yang kita bangun adalah untuk memprediksi **rating** yang akan diberikan pengguna terhadap sebuah **anime** seakurat mungkin. Oleh karena itu, performa model dievaluasi menggunakan metrik standar untuk tugas regresi, yang mengukur seberapa dekat nilai prediksi dengan nilai rating sebenarnya.

#### Metrik Evaluasi yang Digunakan

1.  **Root Mean Squared Error (RMSE)**: Mengukur akar dari rata-rata selisih kuadrat antara nilai rating aktual ($y_i$) dan nilai prediksi ($\hat{y}_i$). Metrik ini sangat sensitif terhadap kesalahan besar. Nilai RMSE yang lebih rendah menandakan model yang lebih baik.
    **Rumus**:

$$
RMSE = \sqrt{ \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 }
$$

2.  **Mean Absolute Error (MAE)**: Menghitung rata-rata dari nilai absolut selisih antara rating aktual dan prediksi. MAE memberikan gambaran intuitif mengenai rata-rata kesalahan prediksi. Nilai MAE yang lebih rendah adalah lebih baik.
    **Rumus**:

$$
MAE = \frac{1}{n} \sum_{i=1}^{n} \left| y_i - \hat{y}_i \right|
$$

---

### Hasil dan Analisis

Berikut adalah hasil perbandingan performa kedua model pada data validasi berdasarkan metrik evaluasi yang didapat:

| Metrik   | RecommenderNet (Baseline) | **NeuMF (Deep Learning)** |
| :------- | :------------------------ | :------------------------ |
| **RMSE** | 1.146903                  | 1.152114                  |
| **MAE**  | 0.874188                  | 0.875410                  |

#### Scatterplot : Actual Rating vs Predicted Rating

![Scatterplot](/Image/Scatterplot.png)

Kedua scatter plot ini menyajikan perbandingan visual secara langsung antara akurasi model RecommenderNet dan NeuMF. Sumbu-x merepresentasikan rating aktual yang diberikan pengguna, sementara sumbu-y adalah nilai yang diprediksi oleh model. Garis diagonal merah berfungsi sebagai acuan prediksi yang sempurna; semakin rapat sebaran titik-titik data di sekitar garis ini, semakin baik performa model. Pola vertikal yang terlihat pada plot juga menunjukkan bahwa untuk setiap tingkatan rating asli, model memberikan rentang prediksi yang terkonsentrasi di sekitarnya, yang merupakan perilaku yang diharapkan dari sebuah model regresi.

#### Interpretasi Hasil:

1.  **Keunggulan Model Deep Learning**: Berdasarkan tabel di atas, model **NeuMF** secara konsisten menunjukkan performa yang **lebih unggul** dibandingkan RecommenderNet. Ini terlihat dari nilai RMSE dan MAE yang lebih rendah, yang mengindikasikan bahwa secara rata-rata, prediksi rating dari NeuMF lebih akurat dan lebih dekat ke nilai rating yang sebenarnya.

2.  **Justifikasi Kompleksitas Model**: Hasil ini menunjukkan bahwa untuk dataset ini, **penambahan kompleksitas pada arsitektur model memberikan keuntungan performa yang nyata**. Arsitektur NeuMF yang menggabungkan jalur linear (GMF) dan non-linear (MLP) terbukti mampu menangkap pola interaksi antara pengguna dan anime yang lebih rumit. Kemampuan non-linear dari komponen MLP kemungkinan besar berhasil memodelkan nuansa preferensi yang tidak dapat dijangkau oleh model faktorisasi matriks yang lebih sederhana.

3.  **Implikasi Praktis**: Terdapat _trade-off_ antara performa dan sumber daya. Meskipun NeuMF membutuhkan waktu training yang lebih lama dan sumber daya komputasi yang lebih besar, **peningkatan akurasi yang dihasilkannya dapat membenarkan investasi tersebut**. Jika tujuan utama sistem adalah memberikan prediksi seakurat mungkin, maka NeuMF adalah pilihan yang lebih superior.

---

### **Conclusion and Future Work**

#### Kesimpulan

Proyek ini berhasil mengimplementasikan dan membandingkan dua arsitektur _collaborative filtering_: sebuah model klasik berbasis _matrix factorization_ (RecommenderNet) dan sebuah model _deep learning_ (NeuMF). Temuan utamanya adalah bahwa model **NeuMF yang lebih kompleks secara konsisten memberikan akurasi prediksi rating yang lebih tinggi** (RMSE dan MAE lebih rendah) dibandingkan dengan model RecommenderNet yang lebih sederhana.

Ini memberikan pelajaran berharga bahwa investasi pada arsitektur yang lebih canggih seperti _neural network_ dapat memberikan hasil yang signifikan pada dataset yang kaya akan interaksi. Kemampuan NeuMF untuk memodelkan hubungan non-linear terbukti menjadi kunci untuk mencapai performa yang lebih baik dalam memprediksi selera pengguna anime pada studi kasus ini.

#### Pengembangan di Masa Depan (Future Work)

Untuk menyempurnakan dan memperluas sistem rekomendasi ini, beberapa langkah strategis dapat diambil di masa depan:

1.  **Evaluasi Berbasis Peringkat (Ranking)**: Saat ini evaluasi hanya fokus pada akurasi prediksi rating. Langkah berikutnya adalah mengimplementasikan metrik yang berfokus pada kualitas daftar rekomendasi, seperti **Precision@k, Recall@k, dan NDCG@k**. Metrik ini mengukur seberapa relevan item yang muncul di posisi teratas rekomendasi.

2.  **Membangun Model Hibrida**: Menggabungkan pendekatan _collaborative filtering_ saat ini dengan **Content-Based Filtering**. Dengan memanfaatkan metadata anime (seperti **genre, sinopsis, studio, tema**), kita dapat secara signifikan meningkatkan rekomendasi untuk pengguna baru dan merekomendasikan anime yang baru rilis (_cold-start problem_), serta meningkatkan diversitas rekomendasi.

3.  **Eksplorasi Arsitektur Deep Learning Lanjutan**: Jika data yang lebih besar tersedia, kita dapat bereksperimen dengan arsitektur yang lebih canggih seperti **Wide & Deep Learning** (yang secara formal menggabungkan kekuatan model linear dan deep learning) atau model berbasis **Autoencoder** untuk pembelajaran fitur yang lebih kaya.

4.  **Implementasi Online dan A/B Testing**: Langkah paling krusial adalah membawa sistem ini ke lingkungan produksi. Melakukan **A/B testing** akan memungkinkan kita untuk mengukur dampak nyata model terhadap perilaku pengguna, menggunakan metrik bisnis seperti **tingkat klik (CTR)**, **durasi tonton (watch time)**, dan **tingkat retensi pengguna**. Ini adalah cara terbaik untuk memvalidasi efektivitas sistem di dunia nyata.
