# 📊 Regional Sales Analysis

### Mengubah Data Penjualan Menjadi Wawasan Bisnis yang Dapat Ditindaklanjuti

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Manipulation-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/EDA-Exploratory%20Analysis-orange?style=for-the-badge" />
</p>

<p align="center">
  <b>Proyek Data Analytics End-to-End</b><br>
  Python • Pandas • NumPy • Matplotlib • Seaborn • Power BI
</p>

---

## 📌 Ringkasan Proyek

**Regional Sales Analysis** merupakan proyek **data analytics end-to-end** yang berfokus pada transformasi **data historis penjualan selama lima tahun** menjadi wawasan bisnis yang dapat ditindaklanjuti.

Proyek ini menganalisis kinerja penjualan berdasarkan beberapa dimensi utama:

* 🌎 **Wilayah & Negara Bagian**
* 📦 **Produk & SKU**
* 🛒 **Saluran Penjualan**
* 👥 **Pelanggan**
* 📅 **Waktu & Musiman**
* 💰 **Pendapatan & Profitabilitas**

Proses analisis dimulai dari **konsolidasi dan preprocessing data**, dilanjutkan dengan **Exploratory Data Analysis (EDA)**, kemudian menghasilkan **dashboard Power BI interaktif dan rekomendasi bisnis strategis**.

> **Tujuan:** Mengidentifikasi peluang pertumbuhan, memahami faktor yang memengaruhi profitabilitas, serta memberikan rekomendasi berbasis data untuk mendukung keputusan penjualan dan operasional.

---

# 🎯 Permasalahan Bisnis

Tim penjualan memiliki keterbatasan visibilitas terhadap kinerja regional dan komersial, sehingga sulit untuk mengidentifikasi:

* Wilayah dengan kinerja tinggi dan rendah
* Fluktuasi pendapatan berdasarkan musim
* Produk dan SKU dengan performa terbaik
* Kontribusi masing-masing saluran penjualan
* Konsentrasi pendapatan berdasarkan pelanggan
* Faktor yang memengaruhi profitabilitas
* Peluang untuk meningkatkan pendapatan dan margin keuntungan

### Tujuan Bisnis

Mengembangkan solusi analitik berbasis data yang dapat menjawab pertanyaan:

> **Apa yang mendorong kinerja penjualan, di mana peluang terbesar berada, dan tindakan apa yang seharusnya menjadi prioritas bisnis?**

---

# 🔍 Pertanyaan Bisnis

Analisis dirancang untuk menjawab beberapa pertanyaan bisnis berikut:

| #  | Pertanyaan Bisnis                                                      |
| -- | ---------------------------------------------------------------------- |
| 01 | Negara bagian dan wilayah mana yang menghasilkan pendapatan tertinggi? |
| 02 | Bagaimana perubahan pendapatan dari waktu ke waktu?                    |
| 03 | Apakah terdapat pola musiman yang signifikan?                          |
| 04 | Produk mana yang memberikan kontribusi pendapatan terbesar?            |
| 05 | Produk mana yang menghasilkan margin keuntungan terbaik?               |
| 06 | Saluran penjualan mana yang memberikan kontribusi pendapatan terbesar? |
| 07 | Pelanggan mana yang menghasilkan pendapatan tertinggi?                 |
| 08 | Apakah pendapatan terkonsentrasi pada sejumlah kecil pelanggan?        |
| 09 | Faktor apa yang memiliki hubungan paling kuat dengan profit?           |
| 10 | Strategi apa yang dapat meningkatkan penjualan dan profitabilitas?     |

---

# 🧠 Pendekatan Analisis

Proyek ini mengikuti alur **data analytics end-to-end** yang terstruktur:

```text
                 PERMASALAHAN BISNIS
                       │
                       ▼
                 PENGUMPULAN DATA
                       │
                       ▼
              KONSOLIDASI DATA
                       │
                       ▼
          PEMBERSIHAN & PERSIAPAN DATA
                       │
                       ▼
              FEATURE ENGINEERING
                       │
                       ▼
       EXPLORATORY DATA ANALYSIS (EDA)
                       │
                       ▼
                WAWASAN BISNIS
                       │
                       ▼
              POWER BI DASHBOARD
                       │
                       ▼
           REKOMENDASI BISNIS
```

Alur ini memastikan bahwa dashboard akhir bukan hanya sekadar kumpulan visualisasi, tetapi merupakan hasil dari proses analisis yang terstruktur.

---

# 🛠️ Teknologi yang Digunakan

### Programming & Data Analysis

| Teknologi     | Penggunaan                      |
| ------------- | ------------------------------- |
| 🐍 Python     | Analisis dan preprocessing data |
| 🐼 Pandas     | Manipulasi data                 |
| 🔢 NumPy      | Perhitungan numerik             |
| 📊 Matplotlib | Visualisasi data                |
| 📈 Seaborn    | Visualisasi statistik           |

### Business Intelligence

| Teknologi           | Penggunaan                    |
| ------------------- | ----------------------------- |
| 🟨 Power BI         | Dashboard interaktif          |
| 🔄 Power Query      | Transformasi data             |
| 📊 Power BI Visuals | Reporting & data storytelling |

### Tools Pendukung

```text
Google Colab
Microsoft Excel
PowerPoint
GitHub
```

---

# 📂 Struktur Dataset

Data mentah terdiri dari beberapa tabel yang mencakup:

```text
Sales
├── Orders
├── Customers
├── Products
├── States
├── Regions
├── Channels
└── Budget
```

Dataset akhir kemudian disusun berdasarkan beberapa dimensi analisis.

### Informasi Order & Pelanggan

```text
order_number
order_date
customer_name
channel
product_name
```

### Informasi Keuangan

```text
quantity
unit_price
revenue
cost
profit
profit_margin_pct
```

### Informasi Waktu

```text
order_month
order_month_num
order_month_name
```

### Informasi Geografis

```text
state
state_name
us_region
lat
lon
```

### Perencanaan

```text
budget_2017
```

---

# 🧹 Persiapan & Pembersihan Data

Tahap preprocessing dilakukan untuk menghasilkan dataset yang siap digunakan dalam analisis.

### Proses yang Dilakukan

* Restrukturisasi header
* Konsolidasi data
* Penggabungan tabel
* Menghapus kolom redundan
* Standardisasi nama kolom
* Mengubah nama kolom
* Penyesuaian tipe data
* Pemilihan kolom kunci
* Validasi data

### Feature Engineering

Beberapa metrik bisnis penting dibuat selama proses analisis:

```text
Profit
Profit Margin %
```

Selain itu, fitur kalender juga dibuat untuk mendukung analisis time-series.

Berdasarkan dokumentasi proyek, **tidak ditemukan missing values maupun baris duplikat setelah proses preprocessing**.

---

# 📊 Exploratory Data Analysis

Tahap EDA berfokus pada pemahaman:

```text
WHAT  → Apa yang sedang terjadi?
WHERE → Di mana hal tersebut terjadi?
WHY   → Apa yang mungkin menjadi penyebabnya?
```

Analisis mencakup:

* Tren penjualan
* Performa produk
* Profitabilitas
* Saluran penjualan
* Performa geografis
* Konsentrasi pelanggan
* Distribusi AOV
* Segmentasi pelanggan
* Korelasi antar fitur

---

# 📈 Temuan Utama

## 01 — Pola Musiman yang Kuat

Penjualan bulanan menunjukkan pola yang relatif konsisten.

### Temuan Utama

* **Mei–Juni:** periode puncak penjualan
* **Januari:** titik terendah tahunan
* **Awal 2017:** terjadi penurunan pendapatan yang cukup signifikan

Temuan ini menunjukkan bahwa perencanaan penjualan dan operasional perlu mempertimbangkan pola musiman yang berulang.

---

## 02 — Konsentrasi Produk

Produk **26 dan 25** muncul sebagai produk dengan kontribusi pendapatan terbesar.

Secara gabungan, kedua produk tersebut menyumbang sekitar:

> **~25% dari total penjualan**

Hal ini menciptakan dua sisi:

**Peluang** → Memprioritaskan produk dengan performa tinggi.

**Risiko** → Ketergantungan yang terlalu besar pada sejumlah SKU tertentu.

---

## 03 — Wholesale Menjadi Mesin Utama Pendapatan

Kontribusi pendapatan berdasarkan channel:

| Channel        | Kontribusi |
| -------------- | ---------: |
| 🥇 Wholesale   |  **54,1%** |
| 🥈 Distributor |  **31,3%** |
| 🥉 Export      |  **14,6%** |

Wholesale menjadi kontributor pendapatan terbesar, sementara Export memberikan peluang untuk mengeksplorasi pertumbuhan dengan margin yang lebih tinggi.

---

## 04 — California Memimpin Pasar

California menjadi negara bagian dengan performa terkuat berdasarkan pendapatan dan jumlah order.

### Performa

```text
Revenue     ≈ $230M
Orders      ≈ 7,6K
```

Negara bagian lain yang juga menunjukkan kontribusi signifikan:

* Texas
* Florida
* Illinois

---

## 05 — Wilayah West Memimpin Penjualan

Performa berdasarkan wilayah:

| Wilayah    | Performa          |
| ---------- | ----------------- |
| 🥇 West    | Tertinggi         |
| 🥈 South   | Kontributor utama |
| 🥉 Midwest | Stabil            |
| Northeast  | Terendah          |

Wilayah **West** menunjukkan performa pasar yang kuat, sedangkan Northeast dapat menjadi peluang untuk dilakukan investigasi pasar lebih lanjut.

---

## 06 — Konsentrasi Pendapatan Pelanggan

Analisis pelanggan menunjukkan perbedaan yang signifikan antara pelanggan dengan performa tertinggi dan terendah.

**Aibox Company** menjadi pelanggan dengan kontribusi pendapatan terbesar.

Hal ini menunjukkan pentingnya:

* Customer retention
* Key-account management
* Upselling
* Cross-selling
* Diversifikasi pendapatan

---

## 07 — Pricing Merupakan Faktor Penting dalam Profitabilitas

Analisis korelasi menunjukkan hubungan yang kuat antara **unit price** dan metrik keuangan.

| Hubungan             | Korelasi |
| -------------------- | -------: |
| Unit Price ↔ Cost    | **0,94** |
| Unit Price ↔ Revenue | **0,91** |
| Revenue ↔ Profit     | **0,87** |
| Unit Price ↔ Profit  | **0,79** |
| Cost ↔ Profit        | **0,58** |

Quantity menunjukkan hubungan yang relatif lebih lemah dengan metrik keuangan.

### Interpretasi Bisnis

Temuan ini menunjukkan bahwa **pengelolaan harga dan biaya berpotensi menjadi tuas yang lebih kuat untuk meningkatkan profitabilitas dibandingkan hanya meningkatkan volume penjualan**.

---

# 💡 Insight Strategis

Hasil analisis dapat dirangkum menjadi lima fokus utama:

```text
SEASONALITY
    ↓
Rencanakan inventory & campaign berdasarkan pola permintaan

PRODUCT
    ↓
Pertahankan SKU unggulan & optimalkan produk dengan performa rendah

CHANNEL
    ↓
Pertahankan skala Wholesale & kembangkan Export

REGION
    ↓
Replikasi strategi dari wilayah dengan performa tinggi

CUSTOMER
    ↓
Prioritaskan pelanggan dengan revenue & margin tinggi
```

---

# 🚀 Rekomendasi Bisnis

## 01. Strategi Penjualan Musiman

Meluncurkan campaign yang lebih terarah pada periode dengan performa rendah serta memperkuat persiapan sebelum periode puncak penjualan.

## 02. Optimasi SKU

Memprioritaskan Produk 26 dan 25 sekaligus mengevaluasi SKU dengan performa rendah berdasarkan demand dan profitabilitas.

## 03. Ekspansi Channel

Mempertahankan Wholesale sebagai mesin utama pendapatan sekaligus mengembangkan peluang Export pada area dengan margin yang menarik.

## 04. Pertumbuhan Regional

Menggunakan California dan wilayah West sebagai benchmark untuk mengidentifikasi strategi yang dapat diterapkan pada wilayah dengan performa lebih rendah.

## 05. Customer Value Management

Melakukan segmentasi pelanggan berdasarkan:

```text
Revenue
+
Profit Margin
```

Kemudian memprioritaskan strategi:

* Retention
* Upselling
* Cross-selling
* Pricing optimization

## 06. Monitoring Margin

Memantau akun dengan margin rendah serta menganalisis faktor biaya dan harga yang menyebabkan penurunan profitabilitas.

---

# 📊 Power BI Dashboard

Hasil analisis kemudian diterjemahkan menjadi **dashboard Power BI interaktif** yang terdiri dari tiga halaman utama.

### 01 — Performance Summary

Menampilkan:

* Performa pendapatan
* Tren penjualan
* Performa produk
* Performa channel
* Performa regional

### 02 — Customer Segmentation

Berfokus pada:

* Pendapatan pelanggan
* Profitabilitas pelanggan
* Ranking pelanggan
* Revenue vs. Margin

### 03 — Revenue Scenario

Menyediakan tampilan interaktif untuk mengeksplorasi skenario dan performa yang berkaitan dengan pendapatan.

---

# 🖼️ Dashboard Preview

> Ganti path di bawah dengan nama file screenshot Power BI Anda.

### Performance Summary

<p align="center">
  <img src="screenshots/dashboard-overview.png" width="90%">
</p>

### Customer Segmentation

<p align="center">
  <img src="screenshots/customer-segmentation.png" width="90%">
</p>

### Revenue Scenario

<p align="center">
  <img src="screenshots/revenue-scenario.png" width="90%">
</p>

---

# 📁 Struktur Repository

```text
Regional-Sales-Analysis/
│
├── 📄 README.md
│
├── 📂 data/
│   └── README.md
│
├── 📂 notebooks/
│   └── Regional_Sales_Analysis.ipynb
│
├── 📂 powerbi/
│   └── Regional_Sales_Analysis.pbix
│
├── 📂 screenshots/
│   ├── dashboard-overview.png
│   ├── customer-segmentation.png
│   └── revenue-scenario.png
│
└── 📂 presentation/
    └── Regional_Sales_Analysis.pptx
```

---

# 🎯 Kompetensi yang Ditunjukkan

### Data Analytics

```text
✓ Exploratory Data Analysis
✓ Trend Analysis
✓ Product Analysis
✓ Customer Analysis
✓ Regional Analysis
✓ Profitability Analysis
✓ Correlation Analysis
```

### Data Preparation

```text
✓ Data Cleaning
✓ Data Transformation
✓ Data Integration
✓ Feature Engineering
✓ Data Validation
```

### Business Intelligence

```text
✓ Power BI Dashboard Development
✓ KPI Analysis
✓ Interactive Data Visualization
✓ Business Storytelling
✓ Dashboard Design
```

### Business & Analytical Thinking

```text
✓ Problem Solving
✓ Perumusan Business Question
✓ Insight Generation
✓ Strategic Recommendation
✓ Data-Driven Decision Making
```

---

# 🏆 Dampak Proyek

Proyek ini menunjukkan kemampuan untuk bergerak lebih jauh dari sekadar:

> **"Apa yang dikatakan oleh data?"**

menjadi:

> **"Apa yang harus dilakukan bisnis berdasarkan data tersebut?"**

Workflow analisis akhir menghubungkan:

**Raw Data → Clean Data → EDA → Insights → Dashboard → Business Recommendations**

Pendekatan ini memungkinkan stakeholder untuk mengeksplorasi performa penjualan secara mandiri dan menggunakan hasil analisis untuk mendukung:

* Sales planning
* Customer strategy
* Product optimization
* Regional expansion
* Profitability management

---

# 👨‍💻 Tentang Saya

### Faris Fatur Rohman

**Lulusan Matematika | Aspiring Data Analyst**

Saya merupakan lulusan Matematika dengan ketertarikan kuat pada **Data Analytics dan Data Science**, khususnya dalam mengubah data mentah menjadi insight yang dapat mendukung pengambilan keputusan bisnis.

### Kompetensi Utama

```text
Python
SQL
Microsoft Excel
Power BI
Pandas
NumPy
Data Cleaning
EDA
Data Visualization
Business Intelligence
```

Saya tertarik pada peluang yang memungkinkan saya menggabungkan **kemampuan berpikir matematis, analytical skills, dan business understanding** untuk menyelesaikan permasalahan nyata menggunakan data.

---

# 💼 Minat Karier

Saya terbuka terhadap peluang pada bidang:

* Data Analyst
* Junior Data Analyst
* Business Intelligence Analyst
* BI Developer
* Data Science
* Analytics Internship

---

# ⭐ Let's Connect

Jika Anda merupakan recruiter, hiring manager, atau profesional data yang tertarik untuk berdiskusi mengenai proyek ini, jangan ragu untuk terhubung.

**Saya terbuka untuk terus belajar, berkolaborasi, dan menyelesaikan permasalahan menarik menggunakan data.**

---

## 📌 Disclaimer

Proyek ini dibuat untuk **keperluan portfolio dan edukasi**.

Tujuan utama proyek adalah menunjukkan kemampuan dalam menjalankan proses **Data Analytics end-to-end**, mulai dari persiapan data, exploratory analysis, menghasilkan business insights, membangun dashboard, hingga menyusun strategic recommendations.
