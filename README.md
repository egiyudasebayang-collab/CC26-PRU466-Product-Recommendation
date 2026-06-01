# CC26-PRU466-Product-Recommendation
Capstone Project Dicoding CC26-PRU466: Sistem Rekomendasi Produk E-commerce menggunakan Neural Collaborative Filtering

## Business Questions

1. Bagaimana memprediksi tingkat preferensi pengguna terhadap suatu produk berdasarkan riwayat interaksi yang tersedia?

2. Bagaimana menghasilkan rekomendasi produk yang relevan dan dipersonalisasi untuk setiap pengguna?

3. Produk apa saja yang memiliki nilai prediksi tertinggi untuk direkomendasikan kepada pengguna tertentu?

## Data Understanding

Dataset yang digunakan merupakan data interaksi pengguna dan produk yang telah dibersihkan sehingga siap digunakan dalam proses pemodelan.

### Data Dictionary

| Variabel | Deskripsi |
|-----------|-----------|
| user_id | Identitas unik pengguna |
| product_id | Identitas unik produk |
| rating | Nilai preferensi atau rating pengguna terhadap produk |
| timestamp | Waktu terjadinya interaksi pengguna dengan produk |

Jumlah data setelah preprocessing:
- Total observasi: 155.938
- Total pengguna unik: 13.345
- Total produk unik: 27.447
