# ✍️ Proyek 04: Test Case & Scenario Design - DemoQA

## Tipe Pengujian
Test Case Design, Scenario Mapping, dan Functional Testing.

## Tujuan Proyek
Mendemonstrasikan kemampuan dalam merancang Test Case dan Skenario Uji yang komprehensif (positif, negatif, batasan) untuk berbagai jenis komponen web interaktif, seperti Forms, Widgets, dan Alert.

## 🛠️ Tools & Teknologi
| Kategori | Tools yang Digunakan |
|---|---|
| Platform Uji | DemoQA (Practice Website) |
| Metodologi | Boundary Value Analysis, Equivalence Partitioning (diterapkan dalam desain skenario) |
| Dokumentasi | Spreadsheet (CSV/Excel) |

## 📊 Ringkasan Desain Test Case
* **Fokus Utama:** Pengujian komponen dasar dan kompleks. Penekanan pada validasi input (contoh: email, nomor HP) dan interaksi browser (contoh: new tab/window, alert).
* **Cakupan:** Meliputi 6 fitur utama pada DemoQA: Elements, Forms, Alert/Frame/Windows, Widgets, Interactions, dan Book Store Application.
* **Tujuan Desain:** Menciptakan Test Case yang:
    1.  Mencakup **Positif** (Happy Path) dan **Negatif** (Error Handling).
    2.  Spesifik pada **Langkah-Langkah Reproduksi** dan **Hasil yang Diharapkan**.

## 📄 File Test Case & Skenario
| Nama File | Fokus Uji | Keterangan |
| :--- | :--- | :--- |
| **[Form.csv](Test%20Case%20&%20Scenario%20demoqa.xlsx%20-%20Form.csv)** | Formulir Pendaftaran | Desain kasus uji untuk validasi data wajib/opsional, email, dan nomor HP. |
| **[Element.csv](Test%20Case%20&%20Scenario%20demoqa.xlsx%20-%20Element.csv)** | Text Box, Check Box, Radio Button | Kasus uji untuk interaksi dasar UI dan output hasil. |
| **[Element 2.csv](Test%20Case%20&%20Scenario%20demoqa.xlsx%20-%20Element%202.csv)** | Validasi Input Lanjutan | Fokus pada pengujian input non-karakter pada field nama. |
| **[Widgets.csv](Test%20Case%20&%20Scenario%20demoqa.xlsx%20-%20Widgets.csv)** | Accordian, Tooltip, Menu | Kasus uji fungsionalitas komponen interaktif yang kompleks. |
| **[Alert, Frame & Windows.csv](Test%20Case%20&%20Scenario%20demoqa.xlsx%20-%20Alert,%20Frame%20&%20Windows.csv)** | Pop-up & Browser Interaksi | Kasus uji untuk Alert (Prompt/Confirm) dan pembukaan New Tab/Window. |
| **[Book Store.csv](Test%20Case%20&%20Scenario%20demoqa.xlsx%20-%20Book%20Store.csv)** | Login, Register, Search | Kasus uji fungsionalitas Book Store (API-like features). |

---

**Apakah Anda sudah menyelesaikan Proyek 04 di folder lokal Anda? Jika sudah, kita bisa langsung lanjutkan ke Proyek 05.** (Untuk *upload*, kita akan gabungkan Proyek 04 dan 05 di akhir).