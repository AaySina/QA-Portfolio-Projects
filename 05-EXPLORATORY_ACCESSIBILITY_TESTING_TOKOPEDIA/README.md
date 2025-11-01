# ♿ Proyek 05: Exploratory & Accessibility Testing - Tokopedia

## Tipe Pengujian
Exploratory Testing dan Accessibility Testing (WCAG Compliance).

## Tujuan Proyek
Mengidentifikasi potensi isu kritis pada fungsionalitas dan UI/UX (Exploratory Testing) serta mengevaluasi tingkat kepatuhan website Tokopedia terhadap standar aksesibilitas (Accessibility Testing), terutama untuk pengguna *screen reader* dan keyboard.

## 🛠️ Tools & Teknologi
| Kategori | Tools yang Digunakan |
|---|---|
| Exploratory | User Flows, Heuristic Evaluation |
| Accessibility | Chrome DevTools, Keyboard Navigation, Screen Reader Simulation |
| Dokumentasi | Microsoft Word / DOCX (berisi bukti dan laporan) |

## 📊 Ringkasan Temuan Kunci
* **Exploratory Findings:** Ditemukan isu *critical failure* pada rendering halaman ketika JavaScript di-disable (fallback content yang tidak memadai) dan isu *major* pada visibilitas elemen navigasi saat scrolling.
* **Accessibility Findings:** Ditemukan *critical* isu pada **icon-only buttons** (tombol ikon tanpa teks) yang tidak memiliki `aria-label` yang deskriptif, melanggar prinsip **WCAG Success Criterion 2.4.4 (Link Purpose) / 4.1.2 (Name, Role, Value)**, sehingga sulit digunakan oleh *screen reader*.

## 📄 File Laporan
| Nama File | Fokus Laporan | Keterangan |
| :--- | :--- | :--- |
| **[Exploratory & Accessibility Report](Exploratory-Accresbility%20Testing%20-%20Tokopedia.com.docx)** | Dokumentasi Komprehensif | Berisi Test Case, *Steps to Reproduce*, *Actual vs Expected Result*, *Severity*, dan *Evidence* (termasuk *screenshots*). |