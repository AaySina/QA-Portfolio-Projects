# 🌐 Proyek 02: Compatibility Testing - Dibimbing.com

## Tipe Pengujian
Compatibility Testing (Web) dan Responsive Design Testing.

## Tujuan Proyek
Menguji fungsionalitas dan tampilan antarmuka pengguna (UI/UX) pada website Dibimbing.com di berbagai lingkungan (peramban dan resolusi perangkat) untuk memastikan pengalaman pengguna yang konsisten.

## 🛠️ Tools & Teknologi
| Kategori | Tools yang Digunakan |
|---|---|
| Peramban Desktop | Google Chrome, Microsoft Edge |
| Perangkat Mobile (Simulasi) | Chrome DevTools (Simulasi: iPhone, Pixel, iPad) |
| Dokumentasi | Spreadsheet (CSV/Excel) |

## 📊 Ringkasan Test Case
* **Fokus Utama:** Fitur Login, Add to Chart, dan tampilan *Course Detail Page*.
* **Lingkungan Uji:** Desktop vs. Mobile (Responsiveness), Chrome vs. Edge.
* **Temuan Kunci (Key Findings):**
    * Ditemukan isu kritis pada Mobile View (DevTools) di mana bagian UI/UX tertentu (misal: "About LMS") tidak muncul pada simulasi Pixel 7.
    * Terdapat isu *thumbnail overlap* pada halaman detail kursus yang terjadi di hampir semua lingkungan uji, mengganggu keterbacaan deskripsi kursus.

## 📄 File Test Case & Hasil
| Nama File | Fokus Uji | Keterangan |
| :--- | :--- | :--- |
| **[Main Feature Manual Testing.csv](Compability%20Testing%20-%20dibimbing.com.xlsx%20-%20Main%20Feature%20Manual%20Testing.csv)** | Skenario Uji Fungsional | Daftar skenario dan kasus uji utama yang digunakan. |
| **[Result Compatibility Testing.csv](Compability%20Testing%20-%20dibimbing.com.xlsx%20-%20Result%20Compatibility%20Testing.csv)** | Matriks Hasil Kompatibilitas | Matriks hasil pengujian di Chrome, Edge, dan Mobile View. |