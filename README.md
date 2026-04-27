# 🚐 Singgalang Travel System

---

## 📌 Deskripsi

**Singgalang Travel System** adalah aplikasi berbasis web yang dikembangkan untuk membantu digitalisasi operasional _Singgalang Jaya Travel_.
Sistem ini bertujuan untuk mempermudah pengelolaan trip, penumpang, dan perhitungan setoran driver secara lebih efisien dan terstruktur.

---

## 🎯 Tujuan

- Mengurangi proses manual dalam pencatatan data
- Meningkatkan efisiensi operasional travel
- Menyediakan laporan yang lebih akurat

---

## ⚙️ Fitur Utama

- 🔐 Authentication (Login & Register)
- 👥 Multi Role (Admin & Driver)
- 🚐 Manajemen Trip
- 🧾 Input Data Penumpang
- 💰 Perhitungan Setoran Driver
- 📊 Report / Laporan

---

## 🛠️ Teknologi

- Laravel 13
- MySQL
- Tailwind CSS
- Vite

---

## 📂 Struktur Project

```bash
singgalang-travel-system/
│
├── app/
├── resources/
├── routes/
├── database/
├── public/
├── docs/
└── README.md
```

---

## ⚙️ Cara Menjalankan Project

### 1. Clone Repository

```bash
git clone https://github.com/username/singgalang-travel-system.git
cd singgalang-travel-system
```

### 2. Install Dependency Backend

```bash
composer install
```

### 3. Setup Environment

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Setup Database

- Buat database dengan nama:

```
singgalang
```

- Edit file `.env`:

```
DB_DATABASE=singgalang
DB_USERNAME=root
DB_PASSWORD=
```

### 5. Jalankan Migration

```bash
php artisan migrate
```

### 6. Install Frontend

```bash
npm install
npm run dev
```

### 7. Jalankan Server

```bash
php artisan serve
```

Akses di browser:

```
http://127.0.0.1:8000
```

## 👨‍💻 Tim Pengembang

- Rayhan Ramadhan
- Rayfo Huda
- Kevin Maulana
- Nayasha Ananda Risdi

---

## 📌 Catatan

Project ini dibuat untuk memenuhi tugas **Project Based Learning (PBL)**.

---

## 🚀 Status Project

🟡 On Development
