# UTS Communication Protocol

## Identitas Mahasiswa

- Nama : Galih Agung Nurfadhilah
- NIM : 25110500026
- Case : Case 3 - Order/Transaction API

---

## Deskripsi

Repository ini dibuat untuk memenuhi tugas UTS mata kuliah Communication Protocol.

Pengujian dilakukan menggunakan Postman Collection yang disediakan dosen dengan fokus pada Case 3 yaitu Order dan Transaction API.

---

## Endpoint yang Diuji

### GET

1. GET /api/orders
2. GET /api/transactions

### POST

1. POST /api/orders
2. POST /api/transactions

---

## Struktur Repository

```text
.
├── README.md
├── analysis/
│   └── encoding-analysis.md
├── evidence/
│   ├── Get-1-Order.png
│   ├── Get-2-Transaction.png
│   ├── Post-1-CreateOrder.png
│   └── Post-2-CreateTransaction.png
└── requests/
    └── curl-commands.md
```

---

## Evidence

Folder `evidence` berisi screenshot hasil pengujian API menggunakan Postman.

---

## Analisis

Folder `analysis` berisi analisis encoding, endpoint, response, dan format data JSON.

---

## Kesimpulan

Pengujian berhasil dilakukan menggunakan metode GET dan POST pada REST API. Seluruh endpoint memberikan response yang sesuai dengan status code HTTP yang diharapkan. Format data yang digunakan adalah JSON sehingga mudah dibaca dan diproses oleh aplikasi client maupun server.
