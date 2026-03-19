# 🎤 K-Pop Idols Data Analysis: Physical Traits & Industry Trends

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444444?style=for-the-badge&logo=python&logoColor=white)

Repositori ini berisi proyek analisis data eksploratif (EDA) terhadap dataset idol K-Pop. Fokus utama proyek ini adalah memahami karakteristik fisik, distribusi demografis, dan struktur grup dalam industri musik Korea.

---

## 📌 Ringkasan Proyek
Industri K-Pop telah berkembang menjadi fenomena global. Proyek ini mencoba menjawab beberapa pertanyaan kunci melalui pendekatan data:
* Bagaimana standar fisik (tinggi & berat) bervariasi antar gender?
* Sejauh mana keberagaman negara asal idol dalam industri ini?
* Bagaimana tren tahun lahir mencerminkan pergantian generasi (Gen 2 ke Gen 4)?

## 📊 Dataset
Dataset yang digunakan adalah `kpop idols.csv` yang berisi informasi detail tentang:
* **Identitas:** Stage Name, Full Name, Korean Name.
* **Biodata:** Date of Birth, Gender, Country, Birthplace.
* **Fisik:** Height (cm), Weight (kg).
* **Afiliasi:** Group Name.

## 🛠️ Metodologi & Tahapan Analisis

### 1. Data Cleaning
Sebelum analisis, dilakukan pembersihan data untuk menjamin validitas hasil:
* **Handling Zero Values:** Mengubah nilai `0` pada kolom `Height` dan `Weight` menjadi `NaN` agar tidak merusak perhitungan rata-rata.
* **Formatting:** Mengubah kolom `Date of Birth` menjadi tipe data `datetime`.
* **Feature Engineering:** Mengekstrak `Birth Year` (Tahun Lahir) dari data tanggal lahir.

### 2. Analisis Statistik
Berikut adalah cuplikan temuan dari analisis deskriptif:

| Karakteristik | Gender | Rata-rata (Mean) |
| :--- | :--- | :--- |
| **Tinggi Badan** | Laki-laki (M) | ~177.6 cm |
| | Perempuan (F) | ~164.7 cm |
| **Berat Badan** | Laki-laki (M) | ~61.6 kg |
| | Perempuan (F) | ~51.3 kg |

---

## 📈 Visualisasi & Insights

### 1. Karakteristik Fisik (Boxplot)
Analisis menunjukkan distribusi tinggi badan idol laki-laki lebih bervariasi dibandingkan idol perempuan, namun keduanya memiliki standar yang cukup konsisten di seluruh agensi.

### 2. Persebaran Negara Asal (Bar Chart)
Meskipun didominasi oleh Korea Selatan, terdapat konsentrasi talenta yang signifikan dari **Jepang, China, dan Thailand**, menunjukkan keberhasilan strategi *global casting*.

### 3. Distribusi Tahun Lahir (Histogram)
Puncak populasi idol dalam dataset berada pada tahun kelahiran **1995-2005**, yang merupakan tulang punggung dari K-Pop Generasi ke-3 dan ke-4.

---

## 💻 Cara Penggunaan
1.  **Clone Repositori:**
    ```bash
    git clone [https://github.com/username-kamu/analisis-kpop-idol.git](https://github.com/username-kamu/analisis-kpop-idol.git)
    ```
2.  **Instalasi Library:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Jalankan Notebook:**
    Buka `analytic.ipynb` menggunakan Jupyter Notebook atau Google Colab.

## 📂 Struktur File
* `analytic.ipynb`: Notebook utama berisi kode analisis dan visualisasi.
* `kpop idols.csv`: Dataset mentah yang digunakan.
* `README.md`: Dokumentasi proyek.

---

## 👤 Kontak
**Jihan Fauziah** - jihanian2017@gmail.com

*Project Link: [https://github.com/jeje-ui/analisis-kpop-idol](https://github.com/jeje-ui/analisis-kpop-idol)*
