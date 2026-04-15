# 📊 Retail Sales Data: Analysis & Exploration

## 📝 Project Overview
Bu layihə, pərakəndə satış dataseti üzərində ilkin məlumat təhlili (EDA) və təmizlənməsi prosesini əhatə edir. Məqsəd, xam datanı analizə hazır hala gətirmək və ilk biznes insaytlarını çıxarmaqdır.

## 🛠️ Key Technical Steps
* **Data Loading:** `sales_data_sample.xls` yükləndi.
* **Data Cleaning:** `ORDERDATE` datetime formatına çevrildi, boşluqlar `Unknown` ilə dolduruldu və `ADDRESSLINE2` silindi.
* **Exploratory Data Analysis (EDA):** `describe()` və `value_counts()` metodları ilə ilkin statistika çıxarıldı.
* **Data Visualization:** Satış trendləri (Line Chart) və kateqoriya paylanmaları (Bar Chart) vizuallaşdırıldı.

## 💡 Key Business Insights
* **Lider Kateqoriya:** Satışların əsas hissəsi `Classic Cars` kateqoriyasına məxsusdur.
* **Logistika:** Sifarişlərin çoxu uğurla `Shipped` edilib.
* **Qiymət:** Mağaza həm kütləvi, həm də premium məhsul seqmentlərinə sahibdir.

## 🧰 Tech Stack
* Python, Pandas, Matplotlib, Seaborn
