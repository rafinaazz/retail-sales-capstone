Capstone Project - Retail Sales Analysis with Seasonal Trends and Marketing

- Project Overview
Proyek ini bertujuan untuk menganalisis data penjualan retail yang mengandung tren musiman dan pengaruh marketing. Analisis dilakukan menggunakan Google Colab dengan bantuan Python dan visualisasi data, serta dukungan AI insight generation bila diperlukan.

- Dataset
Dataset digunakan dari KaggleHub:

Judul: retail-sales-data-with-seasonal-trends-and-marketing

Link: KaggleHub - abdullah0a

Fitur data mencakup:

Tahun dan bulan penjualan

Supplier, item code dan deskripsi barang

Jenis item (beer, wine, dll.)

Retail Sales, Retail Transfers, dan Warehouse Sales

- Insight & Findings
Dominasi Produk Wine
Produk kategori Wine jauh lebih dominan dibanding Beer, baik dari sisi jumlah maupun frekuensi penjualannya.

Tren Musiman
Terlihat peningkatan penjualan signifikan di bulan tertentu (visualisasi menunjukkan lonjakan besar di bulan tertentu, kemungkinan karena promosi atau libur akhir tahun).

Warehouse Sales > Retail Sales
Penjualan dari warehouse (gudang) secara umum lebih tinggi daripada retail. Ini menunjukkan bahwa distribusi skala besar lebih dominan dibanding penjualan ke end-user.

- Conclusion & Recommendation
Fokus marketing dan persediaan perlu diarahkan ke produk Wine.

Bulan dengan puncak penjualan dapat digunakan untuk kampanye promosi besar berikutnya.

Retail Sales bisa ditingkatkan dengan strategi diskon atau promosi lokal karena saat ini jauh lebih kecil dari Warehouse Sales.

- AI Support Explanation
Proyek ini menggunakan Google Colab sebagai platform eksplorasi dan analitik data. Tools AI tambahan seperti WatsonX dapat digunakan untuk:

Generasi insight otomatis

Pembuatan prediksi tren penjualan berikutnya

Deteksi anomali dari outlier (misalnya: nilai negatif atau ekstrem seperti -3999 warehouse sales)

