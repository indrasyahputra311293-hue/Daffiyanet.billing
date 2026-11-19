<div align="center">🌐 DAFFIYANET BILLING

Smart ISP Billing & Network Automation System

Integrated with Winme Digital Products & MikroTik RouterOS

"Daffiyanet" (https://img.shields.io/badge/DAFFIYANET-ISP%20SOLUTIONS-blue?style=for-the-badge)
"Python" (https://img.shields.io/badge/Python-FastAPI-yellow?style=for-the-badge&logo=python)
"MikroTik" (https://img.shields.io/badge/MikroTik-RouterOS-red?style=for-the-badge)
"Integration" (https://img.shields.io/badge/Winme-Integration-green?style=for-the-badge)

📍 Lampung, Indonesia 🇮🇩

</div>---

📖 About Project

Daffiyanet Billing adalah sistem manajemen billing RT/RW Net yang dirancang untuk mengotomatisasi pengelolaan pelanggan internet, pembayaran, invoice, dan manajemen jaringan.

Sistem ini dikembangkan dengan integrasi Winme sebagai platform produk digital dan MikroTik RouterOS sebagai pengelola jaringan internet.

Tujuan utama proyek ini adalah menciptakan ekosistem billing ISP yang otomatis, efisien, aman, dan mudah digunakan.

🚀 Main Features

1. Customer Management

- Manajemen data pelanggan.
- Manajemen paket internet.
- Pengelolaan akun PPPoE.
- Portal pelanggan.
- Riwayat pembayaran.

2. Winme Integration

- Integrasi akun Winme.
- Sinkronisasi produk digital.
- Integrasi pembelian produk.
- Penerimaan notifikasi transaksi.
- Webhook untuk pemrosesan transaksi.
- Pemetaan produk Winme dengan pelanggan billing.

3. MikroTik Integration

- MikroTik RouterOS API.
- Manajemen PPPoE Secrets.
- Monitoring PPPoE Active.
- Automatic Isolation.
- Automatic Reactivation.
- Sinkronisasi status pelanggan.
- Monitoring bandwidth.

4. Payment System

- QRIS Payment.
- Payment Link.
- Invoice Management.
- Payment Verification.
- Payment Notifications.

5. Automation System

- Otomatisasi isolir pelanggan.
- Otomatisasi pembukaan isolir.
- Pemrosesan pembayaran.
- Notifikasi WhatsApp pelanggan.
- Notifikasi email administrator.

🔄 Integration Workflow

CUSTOMER
   |
   v
DAFFIYANET BILLING
   |
   v
WINME DIGITAL PRODUCTS
   |
   v
CUSTOMER PURCHASES PRODUCT
   |
   v
WINME WEBHOOK / API
   |
   v
PAYMENT VERIFICATION
   |
   v
BILLING SYSTEM
   |
   v
MIKROTIK ROUTEROS
   |
   v
AUTOMATIC REACTIVATION

🛠️ Technology Stack

Technology| Function
Python| Backend
FastAPI| REST API
SQLite| Database
MikroTik RouterOS| Network Management
Winme API| Digital Product Integration
Webhook| Transaction Notifications
Docker| Deployment
Linux / Armbian| Server Infrastructure

🔐 Security

- API Key disimpan dalam environment variables.
- Validasi webhook.
- Proteksi kredensial MikroTik.
- Validasi transaksi sebelum membuka isolir.
- Logging aktivitas administrator.
- Proteksi data pelanggan.

📂 Project Structure

daffiyanet-billing/
│
├── app/
│   ├── main.py
│   ├── api/
│   ├── models/
│   ├── services/
│   └── integrations/
│
├── database/
├── config/
├── tests/
├── docs/
├── .env.example
├── .gitignore
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── README.md

Struktur di atas merupakan rancangan struktur proyek.

🎯 Project Goals

1. Mengintegrasikan Winme dengan sistem billing RT/RW Net.
2. Mengotomatisasi pembayaran pelanggan.
3. Menghubungkan transaksi dengan status pelanggan MikroTik.
4. Mengurangi pekerjaan administrasi manual.
5. Membangun sistem billing ISP yang scalable.

👨‍💻 Developer

DAFFIYANET

Internet & Network Solutions
Lampung, Indonesia 🇮🇩

Website: https://winme.id/daffiyanet

---

<div align="center">DAFFIYANET BILLING

Connecting Digital Payments with Network Automation.

Made with ❤️ in Indonesia.

</div>
