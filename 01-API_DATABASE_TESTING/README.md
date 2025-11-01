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
| Dokumentasi | Spreadsheet (Excel) |

## 📊 Ringkasan Test Case
Berdasarkan data yang diuji:
* **Fokus Utama:** Operasi CRUD pada entitas `sport-activities`, dan fungsionalitas `Login` (Autentikasi).
* **Temuan Kunci (Key Findings):**
    1.  Ditemukan ketidakkonsistenan status code pada skenario Negatif (Misal: TC-DELETE-003, ekspektasi `401 Unauthorized` namun aktual `500 Internal Server Error`).
    2.  Pengujian Database berhasil memverifikasi bahwa operasi API telah memengaruhi data di PostgreSQL sesuai harapan.

## 📄 File Test Case & Hasil
| Nama File | Fokus Uji | Hasil Kritis (Contoh) |
| :--- | :--- | :--- |
| **[Login.csv](Login.csv)** | Autentikasi | Menguji skenario positif dan negatif (kosong/invalid credential). |
| **[POSTCREATE_SPORT_ACTIVITY.csv](POSTCREATE_SPORT_ACTIVITY.csv)** | POST (Create) | Pengujian pembuatan data, termasuk verifikasi database (`INSERT`). |
| **[POSTUPDATE_SPORT_ACTIVITY.csv](POSTUPDATE_SPORT_ACTIVITY.csv)** | POST (Update) | Pengujian pembaruan data dan verifikasi data terbaru di database (`UPDATE`). |
| **[GETSPORT ACTIVITIES.csv](GETSPORT ACTIVITIES.csv)** | GET (All) | Menguji *pagination* dan akses data keseluruhan. |
| **[GETSPORT_ACTIVITIES_BY_ID.csv](GETSPORT_ACTIVITIES_BY_ID.csv)** | GET (By ID) | Menguji akses dengan ID valid dan invalid. |
| **[DELETESPORT_ACTIVITY.csv](DELETESPORT_ACTIVITY.csv)** | DELETE | Menguji penghapusan data dan verifikasi data hilang dari database (`DELETE`). |