# Cara Menjalankan Dashboard Analisis Data Bike Sharing

Dashboard ini dibuat untuk menampilkan analisis data penyewaan sepeda secara interaktif menggunakan Streamlit.

## Prasyarat
Pastikan Anda sudah menginstal:
- Python (versi 3.7 atau lebih baru)
- Streamlit
- Pandas
- Matplotlib
- Seaborn

## Langkah-Langkah Menjalankan Dashboard

1. **Clone Repositori**  
   Clone repositori proyek ini atau unduh file `app.py` ke dalam direktori lokal Anda:
   ```bash
   git clone https://github.com/Naufalfarros21/dashboard-bike.git
   cd repository-name
   ```

2. **Instal Dependensi**  
   Pastikan semua paket yang diperlukan telah diinstal. Anda bisa menggunakan `pip` untuk menginstal dependensi:
   ```bash
   pip install streamlit pandas matplotlib seaborn
   ```

3. **Jalankan Dashboard**  
   Jalankan aplikasi Streamlit dengan perintah berikut:
   ```bash
   streamlit run dashboard.py
   ```

4. **Akses Dashboard**  
   Buka browser Anda dan akses URL berikut:
   ```
   http://localhost:8501
   ```

## Penjelasan File Data
Pastikan Anda memiliki file data yang sesuai:
- `hour.csv`: Data penyewaan sepeda per jam.
- `day.csv`: Data penyewaan sepeda per hari.

Letakkan file CSV di dalam direktori proyek atau ubah path di dalam `dashboard.py` agar sesuai dengan lokasi file.

## Insight yang Disajikan
Dashboard ini menampilkan:
- Rata-rata penyewaan sepeda per jam.
- Hubungan antara suhu dalam Celsius dan jumlah penyewaan.
- Tren penyewaan sepeda berdasarkan musim.
- Perbandingan pola penyewaan antara hari kerja dan akhir pekan.

## Contoh Perintah Jalankan
Jika Anda memiliki file `hour.csv` dan `day.csv` di folder yang sama dengan `dashboard.py`, cukup jalankan:
```bash
streamlit run app.py
```

## Kontribusi
Jika Anda ingin berkontribusi, silakan buat pull request atau ajukan issue di repositori ini.

## Lisensi
Proyek ini dilisensikan di bawah [Naufalfrrs21].
