# Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning

Problem Statement : 
- Sebuah perusahaan dapat berkembang dengan pesat saat mengetahui perilaku customer personality nya, sehingga dapat memberikan layanan serta manfaat lebih baik kepada customers yang berpotensi menjadi loyal customers. Dengan mengolah data historical marketing campaign guna menaikkan performa dan menyasar customers yang tepat agar dapat bertransaksi di platform perusahaan, dari insight data tersebut fokus kita adalah membuat sebuah model prediksi kluster sehingga memudahkan perusahaan dalam membuat keputusan

Goals :
- Membuat Cluster menggunakan KMeans, cluster optimal dipilih berdasarkan Elbow Method dan Silhoutte Score

Business Insight : \
**Tipe 1 (Cluster 1)**

- Konsumen tipe 1 merupakan tipe konsumen dengan rata-rata income tinggi dimana rata-ratanya 61.227k atau 2x lipat dari income konsumen tipe 2
- Total spending konsumen konsumen tipe 1 lebih tinggi dibandingkan tipe lain, meskipun jumlah konsumen setengah dari tipe 2. 
- Total transaksi konsumen 1 merupakan yang tertinggi dimana rata-ratanya adalah 21 transaksi dengan minimal transaksi adalah 10. 
- Konsumen tipe 1 selalu melakukan pembelian di website minimal 2 pembelian
- Sedangkan pembelian di store minimal 3x dan setiap bulannya selalu mengunjungi website minimal 1x. 
- Konsumen tipe 1 mayoritas didominasi konsumen yang memiliki satu orang anak 
- Konsumen tipe 1 didominasi dari background pendidikan S1 
- Mayoritas konsumen tipe 1 merupakan konsumen dengan usia 45-54 atau Pra Pensiun 
- Konsumen tipe 1 mayoritas memiliki income dengan Kategori IV
- Konsumen tipe 1 merupakan konsumen yang mayoritas melakukan pembelian terakhir sejak >60 hari terakhir
- Mayoritas konsumen tipe 1 belum menikah 
- Minimal pembelian dengan menggunakan diskon masih 0
- Minimal pembelian dengan menggunakan diskon dan katalog masih 0 \

**Tipe 2 (Cluster 2)**
- Rata-rata Total spending konsumen tipe 2 adalah seperdelapan dari konsumen tipe 1, dimana minimal total spending adalah 5000
- Tidak semua konsumen tipe 2 melakukan transaksi, hal ini terlihat dari minimal total transaksi yaitu 0 
- Semua konsumen tipe 2 melakukan kunjungan website dimana minimal 1 kunjungan 
- Mayoritas konsumen tipe 2 memiliki 1 orang anak
- Background pendidikan konsumen tipe 2 adalah S1 
- Mayoritas konsumen tipe 2 berusia 45-54 atau Pra Pensiun 
- Sebagian besar konsumen tipe 2 memiliki pendapatan kategori III atau pendapatan >20 juta hingga 40 juta 
- Konsumen tipe 2 melakukan pembelian terakhir adalah >60 hari terakhir 
- Sebagian besar konsumen tipe 2 belum menikah 
- Minimal pembelian dengan menggunakan diskon dan katalog masih 0

Business Recommendation : \
- Mempertahankan konsumen tipe 1 agar supaya tidak churn
- Mengoptimalkan konsumen tipe 2 untuk melakukan transaksi karena terlihat minimal transaksinya masih 0 
- Mengoptimalkan pembelian dengan diskon karena pada kedua tipe konsumen minimal pembelian masih 0, hal ini mengindikasikan bahwa tidak semua konsumen baik dari kedua tipe memanfaatkan diskon yang ada 
- Jumlah konsumen tipe 2 memang lebih banyak, namun secara jumlah spending dan total transaksi lebih sedikit dibandingkan tipe 1. Perlu dilihat kembali faktor-faktor yang mempengaruhi, misal seperti diskon yang dirasa kurang (terlihat dari pembelian dengan diskon)
- Mengoptimalkan pembelian dengan Deals/Diskon dan Catalog, karena minimal pembelian dengan Deals/Diskon dan Catalog pada kedua tipe konsumen masih 0
