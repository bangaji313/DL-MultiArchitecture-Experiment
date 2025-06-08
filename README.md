# 🧠 Tugas Besar Deep Learning – Eksperimen Multi-Arsitektur

Repositori ini berisi implementasi Tugas Besar untuk mata kuliah **IFB-454 Deep Learning**.  
Tujuan dari proyek ini adalah melakukan eksperimen serta membandingkan performa dari tiga arsitektur deep learning berbeda pada tiga dataset publik yang memiliki karakteristik yang bervariasi (teks dan time series).

## 🎯 Tujuan Proyek

Melakukan eksperimen mendalam dan perbandingan performa terhadap arsitektur berikut:
- Transformer
- BiLSTM dengan Attention
- Self-Organizing Map (SOM)

Setiap arsitektur diuji pada tiga dataset berikut:
1. **BBC News** – Klasifikasi teks topik berita
2. **Sentiment140** – Klasifikasi sentimen tweet
3. **FordA** – Klasifikasi time series (data sensor mobil)

---

## 🔗 Download Dataset

Karena keterbatasan ukuran file di GitHub, folder `Dataset` tidak diunggah langsung ke repositori ini.  
Silakan unduh seluruh dataset yang dibutuhkan melalui tautan Google Drive berikut:

👉 [Klik di sini untuk download folder Dataset (BBCNews, FordA, Sentiment140)](https://drive.google.com/drive/folders/1m90935ogflKjd09EW52Ix1BasP6bmL3Q?usp=sharing)

Setelah diunduh, pastikan folder `Dataset` diletakkan di direktori utama proyek ini agar notebook dapat berjalan dengan lancar.

---

## 👥 Anggota Kelompok

| Nama                           | NRP         | Arsitektur yang Dikerjakan             |
|--------------------------------|-------------|----------------------------------------|
| Muhammad Figo Razzan Fadillah  | 152022064   | Self-Organizing Map (Time Series)      |
| Maulana Seno Aji Yudhantara    | 152022065   | Transformer (Teks & Time Series)       |
| Naizirun De Jesus Da Silva     | 152022077   | BiLSTM + Attention (Teks)              |

> Mata Kuliah: **IFB-454 Deep Learning**  
> Semester: Genap 2024/2025  
> Dosen Pengampu: *Dr. Jasman Pardede, S.Si., M.T.*
