# 🚀 Addon DigiposAja

**Addon DigiposAja** adalah aplikasi integrasi dan otomasi transaksi **Digipos** untuk membantu server pulsa mengelola transaksi Digipos secara terintegrasi.

Addon DigiposAja tersedia dalam bentuk **Windows Installer (.exe)** dan dirancang untuk digunakan pada sistem **Windows 64-bit**.

---

## ✨ Features

### 📊 Web Dashboard

* Saldo LinkAja
* Saldo Finpay
* Bintang
* Redeem Bintang
* Riwayat Redeem Bintang
* Riwayat Perolehan Bintang
* Riwayat Transaksi

### 📦 Produk Digipos

* Pulsa
* Paket Data
* Telepon & SMS
* Roaming
* Injek Voucher
* Perdana Internet
* Produk lainnya

### 🔄 Integrasi Server Pulsa

* IRS
* Otomax
* Single Product Transaction
* Transaksi 23Loop
* Callback transaksi
* Monitoring status transaksi

### 💳 Payment Method

Mendukung metode pembayaran transaksi Digipos:

* LinkAja
* Finpay

### 🛠️ Tools

* Cek Voucher
* Cek Nomor Pelanggan
* Cek Nama E-Wallet
* Informasi produk

### 🎁 Dealing Program

* Riwayat pencapaian dealing
* Download data dealing program

---

## 💻 System Requirements

| Requirement         | Support                 |
| ------------------- | ----------------------- |
| Operating System    | Windows 10 / Windows 11 |
| Architecture        | 64-bit (x64)            |
| Node.js             | Included                |
| Internet Connection | Required                |

> Runtime Node.js sudah termasuk di dalam aplikasi, sehingga pengguna tidak perlu melakukan instalasi Node.js secara terpisah.

---
## 📥 Installation

## 1. 📥 Download

[![Download](https://img.shields.io/github/v/release/USERNAME/REPOSITORY?label=Download&style=for-the-badge)](../../releases/latest)

### 2. Jalankan Installer

Klik dua kali file installer:

```text
Addon-DigiposAja-Setup.exe
```

Ikuti proses instalasi hingga selesai.

### 3. Jalankan Addon

Setelah instalasi selesai, jalankan **Addon DigiposAja** melalui:

* Desktop Shortcut, atau
* Start Menu

### 4. Aktivasi

Pada penggunaan pertama, aplikasi akan meminta proses aktivasi.

Ikuti instruksi aktivasi yang ditampilkan pada aplikasi.

### 5. Akses Dashboard

Setelah addon berhasil dijalankan, buka browser dan akses:

```text
http://localhost:3000
```

---

## 🔌 Architecture

```text
┌──────────────┐
│  Server Pulsa│
└──────┬───────┘
       │
       ▼
┌──────────────────┐
│ Addon DigiposAja │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│     Digipos      │
└────────┬─────────┘
         │
         ▼
   Status Transaksi
         │
         ▼
┌──────────────┐
│   Callback   │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ Server Pulsa │
└──────────────┘
```

---

## 🌐 Web Dashboard

Addon menyediakan Web Dashboard untuk memonitor dan mengelola berbagai aktivitas Digipos.

Dashboard dapat diakses melalui:

```text
http://localhost:3000
```

---

## 🔐 License & Activation

Addon DigiposAja menggunakan sistem **License & Activation**.

Aktivasi diperlukan agar aplikasi dapat digunakan pada perangkat yang terdaftar.

Informasi lisensi diberikan sesuai dengan akses atau paket penggunaan yang dimiliki.

---

## 📦 Release

Installer tersedia pada halaman **GitHub Releases**.

Contoh nama file:

```text
Addon-DigiposAja-Setup.exe
```

Target:

```text
Windows x64
```

---

## 📝 Changelog

### v4.1.0

* Initial release
* Web Dashboard
* Integrasi Digipos
* Support IRS
* Support Otomax
* Support LinkAja
* Support Finpay
* Transaction monitoring
* License & activation system

---

## ⚠️ Disclaimer

Addon DigiposAja ditujukan untuk kebutuhan integrasi dan otomasi sistem bagi pengguna yang memiliki hak akses terhadap layanan terkait.

Pengguna bertanggung jawab untuk memastikan penggunaan aplikasi sesuai dengan ketentuan dan kebijakan layanan Digipos serta layanan pihak ketiga yang digunakan.

---

## 👨‍💻 Developer

**Baiduri Addon**

Software & Integration Development

---

⭐ **Addon DigiposAja — Integrate, Automate, Monitor.**

