# 📊 TikTok Affiliate Data & Revenue Performance Analysis

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

## 📌 Ringkasan Eksekutif
Proyek ini menganalisis performa kampanye **TikTok Affiliate** berdasarkan kombinasi data postingan (`tiktok_posts.csv`) dan data pemesanan (`orders.csv`). Fokus utama analisis adalah mengidentifikasi kreator berkinerja terbaik dari sisi pendapatan (*revenue*) dan *engagement*, mengukur tingkat konversi (*conversion rate*), serta memberikan rekomendasi strategis untuk kampanye berikutnya.

---

## 🎯 Tujuan Analisis
1. Menentukan kreator dengan **Revenue tertinggi**.
2. Menentukan kreator dengan **Engagement Rate tertinggi**.
3. Mengetahui apakah *Engagement Rate* yang tinggi selalu berbanding lurus dengan *Revenue*.
4. Mengidentifikasi kreator strategis yang perlu diprioritaskan pada kampanye mendatang.

---

## 📈 Metrik Utama (Key Performance Metrics)

| Metrik | Nilai Total | Deskripsi / Formula |
| :--- | :--- | :--- |
| **Total Clicks** | **953.919** | Total klik tautan produk dari seluruh postingan |
| **Total Views** | **27.186.281** | Total tayangan video |
| **Total Orders** | **350** | Total pesanan terkonfirmasi |
| **Total Revenue** | **Rp 96.840.744** | Pendapatan kotor dari penjualan affiliate |
| **Overall Conversion Rate** | **0.04%** | `(Total Orders / Total Clicks) * 100%` |
| **Revenue per Click (RPC)**| **Rp 101.52** | `Total Revenue / Total Clicks` |

---

## 🔍 Temuan Utama (Key Insights)

### 1. Performa Kreator Terbaik
* 🏆 **Revenue Tertinggi**: **Creator A07** menghasilkan pendapatan sebesar **Rp 13.542.060** (48 pesanan). Menunjukkan kemampuan monetisasi dan persuasi audiens yang sangat kuat.
* 🔥 **Engagement Rate Tertinggi**: **Creator A05** mencatatkan tingkat keterikatan audiens sebesar **11.68%** (Views: 2.72M, Engagement: 278.4K).

### 2. Korelasi Engagement vs Revenue
> **Ekspektasi vs Realita**: *Engagement Rate* yang tinggi **tidak selalu** menghasilkan *Revenue* tertinggi.
* **Creator A07** unggul dalam konversi transaksi meskipun *engagement rate*-nya berada di tingkat sedang.
* **Creator A05** sangat efektif membangkitkan interaksi audiens (*awareness*).
* **Kesimpulan**: Kedua kreator ini adalah aset strategis. A07 difokuskan untuk kampanye berorientasi penjualan (*sales conversion*), sedangkan A05 untuk penguatan kesadaran merek (*brand awareness*).

---

## 🛠️ Kerangka Diagnosa Bisnis

| Permasalahan | Kemungkinan Penyebab | Tindakan / Solusi |
| :--- | :--- | :--- |
| **High Views, Low Revenue** | • CTR tautan rendah<br>• Audien konten viral tidak sesuai *target market* | Perjelas *Call to Action* (CTA) dalam video dan sesuaikan gaya konten dengan segmen pembeli. |
| **High Clicks, Low Revenue** | • *Conversion Rate* halaman produk rendah<br>• Harga produk kurang kompetitif / Ongkir mahal | Evaluasi *landing page* produk, berikan promo potongan harga/ongkir, serta tingkatkan ulasan produk. |

---

## 💡 Rekomendasi Data Tambahan (Data Expansion)
Untuk meningkatkan akurasi keputusan di masa mendatang, disarankan bagi tim *marketing* untuk mengumpulkan variabel data berikut:
1. **Data Campaign**: `campaign_name`, `campaign_type`, `traffic_source`.
2. **Data Content**: `content_type` (Video/Carousel), `content_category`, `posting_time`, `hashtags`.
3. **Data Produk**: `product_id`, `product_category`, `price`, `discount`.
4. **Data Audiens**: `age_group`, `gender`, `location`, `device_type`.

---

## 📁 File & Laporan Lanjutan
* 🌐 **Live Web Portfolio**: [portofoliocharlie.odoo.com](https://portofoliocharlie.odoo.com)

---

## 👤 Kontak
* **Nama**: Charlie Da Vinci Ranggi
* **Email**: charliedavinciranggi@gmail.com
