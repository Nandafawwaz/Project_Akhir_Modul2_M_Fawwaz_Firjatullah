📊 Project Akhir Modul 2 – SaaS Sales Analysis

📌 Project Overview

Proyek ini merupakan bagian dari Capstone Project Modul 2 (Data Analysis).
Tujuannya adalah menganalisis dataset penjualan dari sebuah perusahaan SaaS untuk mengidentifikasi faktor pendorong profit dan kerugian, serta memberikan rekomendasi yang dapat ditindaklanjuti untuk meningkatkan profitabilitas.

Sebagai seorang data analyst, saya memposisikan diri seolah bekerja di sebuah perusahaan nyata, di mana insight dari analisis dipresentasikan kepada stakeholder untuk mendukung pengambilan keputusan bisnis.

🎯 Business Problem
Meskipun penjualan terlihat tinggi, perusahaan mengalami kerugian pada beberapa pelanggan dan produk.
Pertanyaan bisnis utama:

Bagaimana cara meningkatkan tingkat profit pada produk berdasarkan Sales, Segment customer, dan Industri perusahaan?

🗂 Dataset
Saas-Sales
Jumlah data: 9994 baris, 19 kolom.
Kolom utama:
- Sales, Profit, Discount
- Region, Country, City
- Industry, Segment
- Product, Customer, Order Date

🔧 Data Cleaning
- Pengecekan missing values → tidak ditemukan.
- Pengecekan data duplicate → tidak ditemukan.
- Format tanggal diubah ke tipe datetime.
- Identifikasi outlier pada Profit/Discount:
  Outlier merupakan pelanggan nyata dengan kerugian/profit ekstrem, bukan error.
  Sehingga tetap dipertahankan bukan dihapus (karena penting untuk insight bisnis).

📈 Analysis
Statistik Deskriptif

- KPI keseluruhan: Total Sales, Total Profit, Margin Profit, Rata-rata Discount.
- Breakdown profit berdasarkan Product, Region, Segment, Industry, Customer.
- Top 10 customer/product dengan profit negatif.
- Distribusi diskon dan dampaknya terhadap profit margin.

Statistik Inferensial

- Korelasi antara Discount % dan Profit Margin.
  Hasil: Semakin tinggi diskon, semakin rendah margin profit secara signifikan.

💡 Insight

- Product: Big Ol Database dan ContactMatcher sering menyebabkan kerugian.
- Region: Jepang & Swedia sering menjadi pasar yang merugi.
- Segment: SMB (Small & Medium Business) lebih berisiko dan profit margin lebih rendah.
- Discount: Diskon di atas 15% → profit margin berubah menjadi negatif.
- Customer: Beberapa pelanggan dengan penjualan tinggi tetap tidak menguntungkan karena diskon terlalu besar dan produk berbiaya tinggi.

✅ Recommendation

- Batasi diskon SMB maksimal ≤15%.
- Repricing produk yang membuat loss.
- Terapkan penyesuaian harga regional di APJ & Swedia.
- Negosiasi ulang kontrak dengan 20 pelanggan terburuk.
- Pantau margin dalam proses penjualan.

Tableau Public Link :
https://public.tableau.com/app/profile/fawwaz.firjatullah/viz/capstone_17557684845910/Dash_Overview?publish=yes
  
