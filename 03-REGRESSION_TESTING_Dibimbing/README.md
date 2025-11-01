# 🔄 Proyek 03 Regression Testing - Dibimbing.com

## Tipe Pengujian
Regression Testing (Manual & Skenario Otomasi) pada fitur yang ada dan fitur baru (Add-Feature Testing).

## Tujuan Proyek
Memastikan pembaruan atau penambahan fitur (seperti Login SSO, mekanisme promo, dan pembaruan profil pengguna) tidak menyebabkan kerusakan pada fungsionalitas utama yang sudah ada pada Dibimbing.com.

## 🛠️ Tools & Teknologi
 Kategori  Tools yang Digunakan 
------
 Metodologi  Regression Testing, Acceptance Testing 
 Dokumentasi  Spreadsheet (CSVExcel) 
 Tools Lain  Browser DevTools (untuk verifikasi elemen) 

## 📊 Ringkasan Test Case
 Fokus Utama Login (SSO, limit percobaan), Fungsionalitas Keranjang (Promo), dan Fitur Utama LMS.
 Temuan Kunci (Key Findings)
    1.  Ditemukan isu Data Inconsistency pada fitur Add Promo, di mana potongan harga tidak ditampilkan secara benar pada pop-up (`BUG-PR-002`), menyebabkan skenario pembayaran terblokir.
    2.  Ditemukan beberapa Bug UIUX minor, seperti menu Internship yang tidak disorot pada halaman yang sesuai dan isu logout yang tidak berhasil tanpa refresh.

## 📄 File Test Case & Hasil
 Nama File  Fokus Uji  Keterangan 
 ---  ---  --- 
 [Add Feature - Login.csv](Regression%20Testing%20-%20dibimbing.com.xlsx%20-%20Add%20Feature%20-%20Login.csv)  Login SSO & Security  Mencakup Login via GoogleLinkedIn dan percobaan 5x gagal login. 
 [Add Promo on Chart.csv](Regression%20Testing%20-%20dibimbing.com.xlsx%20-%20Add%20Promo%20on%20Chart.csv)  Fitur Keranjang  Pengujian mekanisme promo (aplikasi, kedaluwarsa, error data). 
 [Manual Testing - Main Feature.csv](Regression%20Testing%20-%20dibimbing.com.xlsx%20-%20Manual%20Testing%20-%20Main%20Feature.csv)  Core Functionality  Pengujian manual fitur utama (Login, Course, Cart, Logout). 
 [User - Feature.csv](Regression%20Testing%20-%20dibimbing.com.xlsx%20-%20User%20-%20Feature.csv)  Fitur Profil  Pengujian pengeditan data profil dan pengaturan bahasa. 
 [Automation.csv](Regression%20Testing%20-%20dibimbing.com.xlsx%20-%20Automation.csv)  Skenario Login (Automasi)  Skenario login positif dan negatif (sebagai dasar automasi). 