# Analisa Aplikasi Klinik

Workbook ini berisi matriks perbandingan fitur beberapa jenis aplikasi klinik/rumah sakit, dengan fokus utama pada penawaran `PRIVATA`, `CLINICA`, `Klinik Satu`, dan `HOSPITA`.

## Struktur Workbook
- File: `Analisa Aplikasi Klinik.xlsx`
- Jumlah sheet: 1
- Sheet utama: `Sheet1` (15 baris x 9 kolom)

## Inti Isi
- Lima baris pertama membandingkan modul inti: pendaftaran, rawat jalan, rekam medis, kasir, dan laporan.
- Bagian bawah menambahkan fitur lanjutan seperti farmasi, payroll, integrasi Satu Sehat, BPJS, audit log, MFA, hak akses, dan dukungan operasional.
- Struktur sheet tampak seperti bahan analisis/penjualan yang memetakan kemampuan solusi untuk praktik mandiri, klinik multi cabang, klinik tunggal, dan rumah sakit.

## Tabel Perbandingan Utama

| No | PRIVATA | Modul PRIVATA | Deskripsi | CLINICA | Modul CLINICA | Catatan CLINICA | Klinik Satu | HOSPITA |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Pendaftaran Pasien | Modul Pendaftaran | registrasi, kunjungan ulang. mengurangi antrean & mempercepat pelayanan | Pendaftaran & Antrian Pasien | Modul Pendaftaran |  | Manajemen Kunjungan<br>AI Chat Pasien | Display Antrian UGD Pasien<br>Display Antrian Apotek Pasien<br> |
| 2 | Rawat Jalan Pasen | Modul Rawat Jalan | pencatatan keluhan, pemeriksaan, tindak lanjut. | Rawat Jalan Pasen | Modul Rawat Jalan |  | Eskalasi ke Nakes |  |
| 3 | Rekan Medis Elektronik | Modul Rekam Medis | catat riwayat medis, diagnosis, tindakan, dan resep obat standar kemenkes. data aman dan integrasi dgn satu sehat. kepatuhan aman. | RME Terintergasi | Modul Rekam Medis | terintegrasi multicabang | Rekam Medis Pasien<br>Diagnosis ICD-10<br>Resep Obat & Master Data<br> | Input Triase pada pasien UGD<br>Rekam Medis Radiologi |
| 4 | Kasir | Modul Kasir | sederhana, akurat, transparan dan terintegrasi | Kasir & Keuangan Klinik | Modul Kasir | fitur tutup buku, paket prosedur, & integrasi akreditasi | Tarif & Penerimaan<br>Invoice Otomatis<br>Pembayaran Online | Deposit Pasien<br>Struk Pembayaran<br>Cek Tagihan Sementara Pasien Rawat Inap<br>Info metode pembayaran pasien pd antrean apotek<br>Simpan transaksi kasir<br>Mengatur tutup buku sesuai shift di kasir |
| 5 | Laporan | Modul Laporan | analisis kinerja praktik: jumlah pasien, pendapatan, laporan medis | Laporan Manajemen & Akreditasi | Modul Laporan |  | Laporan & Analitik |  |

## Fitur Tambahan yang Muncul di Sheet
- Instalasi Farmasi & Bahan Habis Pakai | Modul Instalasi Farmasi | kelola obat, stok, dan distribusi farmasi. connect dengan RME & kasir | Manajemen Stok Obat | Notifikasi order lab
- Payroll & Komisi Tenaga Medis | Modul Bahan Habis Pakai | hitung honor, komisi, dan payroll otomoatis
- Alokasi Ruangan Rawat Inap; Rujuk Pasien Rawat Inap dari Front Office
- Integrasi Satu Sehat | Integrasi Satu Sehat | Integrasi Satu Sehat | Integrasi Satu Sehat
- Bridging BPJS P-Care | Audit Log (ISO 27001) | BPJS Vclaim
- Unlimited Data Pasien | Unlimited Data Pasien | MFA (TOTP)
- Unlimited Rekam Medis | Unlimited Rekam Medis | Hak Akses (RBAC)
- Support After Sales | Unlimited Transaksi
- Unlimited Jumlah Obat
