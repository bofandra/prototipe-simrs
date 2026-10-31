# Arsip Diskusi Desain SIMRS (30–31 Oktober 2026)

## Tujuan
Inventaris hasil diskusi desain **SIMRS baru** berbasis prinsip *FHIR-first*, **tanpa kewajiban menjalankan FHIR Server**. Diskusi meliputi rancangan modul, database transaksional yang memetakan resource FHIR, studi struktur database HIS/EHR global, benchmarking fitur, dan mockup interaktif.

**Catatan keterbatasan arsip:** berkas asli (DOCX/XLSX/PNG/PDF) ditemukan di Library percakapan, tetapi koneksi arsip ini belum memperoleh akses baca *byte* untuk mengunggah aslinya. Karena itu, file berakhiran `.txt` di folder ini adalah **ekstraksi teks**, bukan file asli atau rekonstruksi format/rumus workbook. Gambar belum berhasil disalin. Jangan anggap file ekstraksi sebagai pengganti master.

## Inventaris berkas asli yang teridentifikasi

| Kategori | Nama file asli | Status pengarsipan |
|---|---|---|
| Rencana arsitektur | `Rencana_Induk_SIMRS_FHIR_First_Tanpa_FHIR_Server_v1.docx` | Ekstraksi teks |
| Model database | `Desain_Database_SIMRS_FHIR_First_Tanpa_FHIR_Server_v1.xlsx` | Ekstraksi teks, bukan workbook |
| Studi database global | `master_studi_database_simrs_global_20261031.xlsx` | Ekstraksi teks, bukan workbook |
| Benchmark fitur detail | `Benchmark_Detail_Fitur_SIMRS_Global_Indonesia_20261031.docx` | Ekstraksi teks |
| Benchmark fitur matriks | `benchmark_fitur_simrs_global_indonesia_20261031.xlsx` | Ekstraksi teks, bukan workbook |
| Referensi rancangan awal | `new simrs.pdf` | Ekstraksi teks |
| Infografis | `Cetak Biru Database SIMRS Modular.png` | Berkas PNG belum tersalin |
| Infografis | `Infografis Desain Database SIMRS.png` | Berkas PNG belum tersalin |
| Infografis | `Infografik ERD Database SIMRS Modular.png` | Berkas PNG belum tersalin |
| Infografis | `Global SIMRS Database Architecture Infographic.png` | Berkas PNG belum tersalin |
| Infografis | `Comparing Database Structures for Hospital EHR Systems.png` | Berkas PNG belum tersalin |
| Infografis | `Global vs Indonesia SIMRS Feature Benchmark.png` | Berkas PNG belum tersalin |

`Benchmark_Detail_Fitur_SIMRS_Global_Indonesia_20261031(1).docx` teridentifikasi sebagai duplikat dengan ukuran sama dan tidak diinventaris sebagai artefak terpisah.

## Pokok keputusan desain
- Desain **FHIR-first**, bukan seluruh data internal wajib disimpan dalam format JSON FHIR.
- **FHIR Server tidak wajib**; gateway/adapter melakukan validasi dan transformasi FHIR untuk interoperabilitas SATUSEHAT.
- Modularisasi meliputi front office, RME, LIS, RIS/PACS, farmasi, billing/klaim, rawat inap/IGD, dan back office/ERP.
- Data klinis perlu desain versi, provenance/audit, master data, episode pelayanan, dan terminologi untuk menjaga interoperabilitas tanpa mengorbankan proses operasional SIMRS.
- Benchmark membedakan fitur **terdokumentasi**, fitur dengan **bukti implementasi**, fitur **parsial/draft**, dan yang **belum dapat diverifikasi**; bukan penilaian kualitas vendor.

## Mockup yang terkait
- Repository prototipe UI sebelumnya: https://github.com/bofandra/simrs
- GitHub Pages: https://bofandra.github.io/simrs/
- Kode mockup berada pada repo tersebut, **belum disalin** ke folder arsip ini.

## Tindak lanjut
1. Unggah berkas asli DOCX, XLSX, PDF, dan PNG setelah akses byte tersedia.
2. Validasi struktur dan formula pada file XLSX asli.
3. Kaitkan roadmap fitur dengan matriks benchmarking dan implementasi kode mockup.
4. Pisahkan artefak desain dari produk SIMRS-Sensi yang sudah berjalan.

_Dibuat 31 Oktober 2026. Folder ini tidak mengubah SOP/peraturan yang sudah tersedia di root repository._
