# 🚀 Proyek 01: API & Database Testing - Sport Activity CRUD

## Tipe Pengujian
**API Testing (Postman)** dan **Database Verification (PostgreSQL)**

## Tujuan Proyek
Memastikan fungsionalitas **CRUD** (Create, Read, Update, Delete) pada API aktivitas olahraga berjalan dengan benar, termasuk verifikasi token autentikasi (Login) dan konsistensi data di database.

## 🛠️ Tools & Teknologi
| Kategori | Tools yang Digunakan |
|---|---|
| API Client | Postman |
| Database | PostgreSQL (Verifikasi via SQL Query) |
| Dokumentasi | Spreadsheet (CSV/Excel) |

## 📊 Ringkasan Test Case
* **Fokus Utama:** Operasi CRUD pada entitas `sport-activities`, dan fungsionalitas `Login` (Autentikasi).
* **Temuan Kunci (Key Findings):** Ditemukan ketidakkonsistenan status code pada skenario Negatif.

## 📄 File Test Case & Hasil
| Nama File | Fokus Uji | Keterangan |
| :--- | :--- | :--- |
| **[Login - API Testing]**(API_DATABASE_TESTING.xlsx%20-%20Login.csv) | Autentikasi | Menguji skenario positif dan negatif. |
| **[POST Create Activity]**(API_DATABASE_TESTING.xlsx%20-%20POSTCREATE_SPORT_ACTIVITY.csv) | POST (Create) | Pengujian pembuatan data dan verifikasi database. |
| **[POST Update Activity]**(API_DATABASE_TESTING.xlsx%20-%20POSTUPDATE_SPORT_ACTIVITY.csv) | POST (Update) | Pengujian pembaruan data dan verifikasi data terbaru di database. |
| **[GET All Activities]**(API_DATABASE_TESTING.xlsx%20-%20GETSPORT%20ACTIVITIES.csv) | GET (All) | Menguji *pagination* dan akses data keseluruhan. |
| **[GET By ID]**(API_DATABASE_TESTING.xlsx%20-%20GETSPORT_ACTIVITIES_BY_ID.csv) | GET (By ID) | Menguji akses dengan ID valid dan invalid. |
| **[DELETE Activity]**(API_DATABASE_TESTING.xlsx%20-%20DELETESPORT_ACTIVITY.csv) | DELETE | Menguji penghapusan data dan verifikasi data hilang dari database. |