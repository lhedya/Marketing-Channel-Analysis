# 📊 Marketing Channel Analysis
**RFM Analysis & Customer Segmentation | Dibimbing.id Bootcamp**

**Author:** Lhedya Monica Ismon

---

## 🎯 Objective
Menganalisis performa channel marketing menggunakan teknik 
clustering dan RFM Analysis untuk menghasilkan insight 
segmentasi pelanggan yang actionable.

---

## 🗃️ Dataset
| Dataset | Kegunaan |
|---------|----------|
| Sample-Superstore.csv | Analisis profitabilitas & perilaku pelanggan |
| Attribution_Datasets.xlsx | RFM Analysis & segmentasi pelanggan |

---

## ❓ Business Questions
1. Negara mana yang paling profit dan berapa jumlah user-nya?
2. Kota mana yang paling banyak melakukan pembelian?
3. Kategori produk apa yang paling banyak dibeli?
4. Jenis pengiriman apa yang paling sering digunakan?
5. Bagaimana distribusi pelanggan dalam 9 segmen RFM?

---

## 👥 9 Segmen RFM

| Segmen | Karakteristik | Rekomendasi |
|--------|--------------|-------------|
| Champions | Beli baru-baru ini, sering, nilai tinggi | Reward & loyalty program |
| Loyal Customers | Beli sering, nilai tinggi | Upsell produk premium |
| Potential Loyalist | Beli baru-baru ini, frekuensi sedang | Nurture dengan email |
| New Customers | Baru pertama beli | Onboarding & welcome offer |
| Promising | Baru beli, belum sering | Edukasi produk |
| Need Attention | Di atas rata-rata, mulai jarang | Re-engagement campaign |
| About to Sleep | Jarang beli, nilai rendah | Discount atau reminder |
| At Risk | Dulu aktif, sekarang menghilang | Win-back campaign |
| Lost | Sudah lama tidak beli | Survei alasan churn |

---

## 🔧 Tools & Libraries
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Sklearn
- **Dashboard:** Microsoft Power BI
- **Notebook:** Google Colab

---

## 📋 Langkah Analisis
1. Data Understanding & Cleaning
2. Analisis Profitabilitas per Negara
3. Analisis Perilaku Pembelian Pelanggan
4. Perhitungan RFM Score
5. Segmentasi 9 Cluster RFM
6. Dashboard Power BI
7. Insight & Rekomendasi

---

## 📸 Dashboard Preview
[RFM Dashboard](dashboard/Marketing Channel Analysis.pbix)

---

## 💡 Key Insights & Rekomendasi

### 📌 Overview Metrics
- Total **793 Customers** dengan total profit **Rp67.06bn**
- Periode data: Januari 2014 – Desember 2017

---

### 1️⃣ Ship Mode
- **Standard Class** mendominasi pengiriman dengan **59.72%** 
  dari total transaksi
- Same Day hanya **5.43%** → pelanggan cenderung tidak 
  terburu-buru dalam pengiriman

**Rekomendasi:**
Optimalkan layanan Standard Class karena paling banyak digunakan.
Berikan insentif (diskon ongkir) untuk mendorong penggunaan 
First Class guna meningkatkan margin pengiriman.

---

### 2️⃣ Marketing Channel
- Semua channel (Facebook, Instagram, Online Ads, Paid Search) 
  memiliki distribusi **merata ~20%** masing-masing
- Tidak ada channel yang secara signifikan mendominasi

**Rekomendasi:**
Lakukan A/B testing untuk mengidentifikasi channel dengan 
konversi tertinggi. Alokasikan budget lebih besar ke channel 
dengan ROI terbaik daripada menyebar rata.

---

### 3️⃣ Product Category
- **Office Supplies** adalah kategori terlaris (~6.0K transaksi)
- Diikuti **Furniture** (~2.1K) dan **Technology** (~1.8K)

**Rekomendasi:**
Fokuskan promosi pada Office Supplies sebagai produk andalan.
Tingkatkan kampanye untuk Technology karena potensi margin 
lebih tinggi meski volume lebih rendah.

---

### 4️⃣ RFM Segmentation - Number of Users per Segment
| Segmen | Jumlah User | Rekomendasi |
|--------|-------------|-------------|
| About to Sleep | 26K | Re-engagement campaign & reminder |
| Average | 19K | Dorong frekuensi pembelian dengan promo |
| Lost Customer | 14K | Win-back campaign / survei churn |
| Loyal | 13K | Pertahankan dengan loyalty program |
| Potential Loyalist | 8K | Nurture menuju Champions |
| Champion | 8K | Reward eksklusif & jadikan brand ambassador |
| Other | 2K | Analisis lebih lanjut |
| Cannot Lose Them | 2K | Prioritas tinggi - personal outreach |

**Rekomendasi:**
Segmen **About to Sleep (26K)** adalah yang terbesar dan perlu 
perhatian segera dengan kampanye reaktivasi.
Segmen **Cannot Lose Them** meski kecil (2K) namun bernilai 
tinggi — lakukan pendekatan personal.

---

### 5️⃣ Country with Highest Profit
- **California** memimpin dengan profit **Rp18.6bn**
- Diikuti New York (Rp13.8bn) dan Washington (Rp5.3bn)
- Virginia dan Michigan relatif rendah (~Rp3-4bn)

**Rekomendasi:**
Perkuat distribusi dan kampanye di California & New York 
sebagai pasar utama. Investigasi potensi ekspansi di 
Washington yang menunjukkan pertumbuhan signifikan.

---

### 6️⃣ Total Transaksi by City
- **New York City** transaksi tertinggi (384)
- Diikuti **Los Angeles** (265) dan **Philadelphia** (265)
- **Seattle** (212) menunjukkan potensi yang perlu dikembangkan

**Rekomendasi:**
Fokuskan event marketing dan promosi lokal di NYC dan LA 
sebagai kota dengan volume transaksi tertinggi.

---

## 📁 File Structure
- `notebook/` → Google Colab (.ipynb)
- `dashboard/` → Power BI file (.pbix)
- `data/` → Raw data