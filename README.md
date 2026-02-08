# Sistem Manajemen Pembayaran SPP (Financial Module)
Oleh: **Raffli Islami Fashya (NIM: 24360003)**

[cite_start]Proyek ini adalah implementasi sistem manajemen keuangan kampus yang mencakup siklus penagihan, pembayaran via webhook, dan pelaporan keuangan berbasis AI sesuai dengan standar Modul Keuangan SPP[cite: 1, 3].

## Fitur Utama
- [cite_start]**Billing Service**: Generate tagihan otomatis tiap semester (Teknik: 5jt, Ekonomi: 4jt)[cite: 14, 30].
- [cite_start]**Payment Webhook**: Menangani notifikasi sukses dari payment gateway untuk update status `paid`[cite: 22, 23].
- [cite_start]**KRS Blocking**: Validasi otomatis status tunggakan untuk membatasi akses akademik.
- [cite_start]**AI Financial Report**: Analisis revenue dan collection rate untuk dashboard dashboard pimpinan[cite: 51, 52].

## Tech Stack
- **Framework**: FastAPI (Python)
- **Validation**: Pydantic
- **Documentation**: Swagger UI & Mermaid UML

## Database Schema
[cite_start]Mengacu pada Deliverables proyek[cite: 10, 11]:
- `billing`: Menyimpan detail tagihan per mahasiswa.
- `payment`: Mencatat riwayat transaksi.
- `payment_method`: Integrasi metode pembayaran (simulasi).

## Cara Menjalankan
1. Clone repository:
   ```bash
   git clone [https://github.com/username/spp-billing-system-ai.git](https://github.com/username/spp-billing-system-ai.git)
