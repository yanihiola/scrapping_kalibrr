# 🕸️ Proyek

<p align="center" width="80%">
    <img width="60%" src="https://static.kalibrr.com/public/kalibrr-og-image.png">
</p>

<div align="center">
  
</p>

</div>

Proyek ini bertujuan untuk mengambil (scraping) data lowongan pekerjaan yang masih aktif atau sedang dibuka dari situs Kalibrr. Proses scraping dilakukan secara otomatis untuk mengumpulkan informasi penting seperti:

+ 📝 **Lowongan Pekerjaan**
  
  Informasi mengenai jenis pekerjaan yang sedang dibuka oleh perusahaan.

+ 🏢 **Nama Perusahaan**
  
  Nama organisasi atau instansi yang membuka lowongan kerja.

+ 📍 **Kota/Lokasi Penempatan**

  Lokasi geografis di mana posisi kerja akan ditempatkan.

+ 💰 **Gaji**

  Estimasi atau rentang penghasilan yang ditawarkan untuk posisi tersebut.

+ ⏳ **Status Kerja**

  Jenis ikatan kerja seperti penuh waktu, paruh waktu, kontrak, atau magang.
  
+ 👔 **Posisi/Jabatan**

  Nama jabatan atau peran yang ditawarkan dalam lowongan kerja.

+ ⏰ **Batas Akhir Pengiriman Lamaran**

  Tanggal terakhir pelamar dapat mengajukan lamaran untuk posisi tersebut.

Scraping data dilakukan pada website https://www.kalibrr.id/id-ID/home dengan menggunakan Data Miner

# 📌 Tujuan
Data yang dikumpulkan digunakan untuk analisis lebih lanjut, yaitu untuk mengetahui:

+ **Jumlah lowongan kerja berdasarkan posisi/jabatan.**
+ **Jumlah lowongan kerja berdasarkan status kerja.**
+ **Jumlah lowongan kerja berdasarkan posisi dan status.**
+ **Tren jumlah lowongan kerja per bulan.**
+ **10 perusahaan dengan jumlah lowongan kerja terbanyak.**
+ **10 perusahaan dengan jumlah lowongan kerja terbanyak berdasarkan posisi.**
+ **Jumlah lowongan kerja berdasarkan kota/lokasi penempatan.**
+ **Jumlah lowongan kerja per status di 10 kota teratas.**
+ **Jumlah lowongan kerja berdasarkan posisi dan status.**
+ **Proporsi jumlah lowongan kerja berdasarkan info gaji (diumumkan vs tidak diumumkan).**
+ **Distribusi posisi dengan gaji tidak diumumkan.**
+ **Boxplot sebaran gaji.**
+ **Rata-rata gaji minimum per tingkat posisi.**
+ **Distribusi posisi pada perusahaan dengan jumlah lowongan kerja terbanyak.**

# 🔧 Teknologi yang Digunakan
+ **Data Miner** : Melakukan scraping.
+ **MongoDB** : Tempat penyimpanan data hasil scraping.
+ **R** : Agregasi MongoDB dan visualisasi di R untuk analisis data.

# 📔 Dokumen
Berikut adalah salah satu contoh dokumen di MongoDB:
```mongodb
{
"_id":{"$oid":"68381022b6b2dc150057f7cb"},
"Pekerjaan":"Loyalty Marketing Associate Manager",
"Nama Perusahaan":"Traveloka",
"Kota":"Tangerang, Indonesia",
"Gaji":"Gaji Tidak Diumumkan",
"Status":"Full Time",
"Posisi":"Mid-Senior Level Manager",
"Deadline":"06 July 2025",
"Bulan":"Juli"
}
```

# 📚 File Proyek
+ Berikut adalah file yang berisi link agregasi dan visualisasi data di R:
https://drive.google.com/drive/folders/1Ournc1xKMBfmz0cSJHyeOd8CvF9NXHDq?usp=sharing
+ Berikut adalah link yang berisi materi presentasi scraping:
(link canva)

# ⚠️ Catatan
Data yang diambil bersifat sementara dan dinamis, mengikuti perubahan yang terjadi di situs Kalibrr. Scraping dilakukan dengan tetap memperhatikan etika dan batasan penggunaan situs web.

# 👩‍💻 Pengembang
Hazelita Dwi Rahmasari (M05012410)

Mahda Al Maida (M05012410)

Nabila Syukri (M05012410)

Yani Prihantini Hiola (M0501241026)
