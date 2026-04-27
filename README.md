# Docker Fullstack Project

## 📌 Deskripsi
Project ini merupakan implementasi Docker Compose untuk menjalankan aplikasi fullstack yang terdiri dari beberapa service, yaitu:
- Nginx sebagai reverse proxy
- Node.js sebagai backend API
- MongoDB sebagai database

---

## ⚙️ Teknologi yang Digunakan
- Docker
- Docker Compose
- Node.js (Express)
- MongoDB
- Nginx

---

## 📁 Struktur Project

.
├── api
│ ├── app.js
│ ├── Dockerfile
│ └── package.json
├── nginx
│ └── nginx.conf
└── docker-compose.yml


---

## 🚀 Cara Menjalankan

1. Clone repository:

git clone https://github.com/USERNAME/fullstack-docker.git

cd fullstack-docker


2. Jalankan Docker Compose:

docker-compose up -d


3. Akses aplikasi:

http://localhost:8080


---

## 🧪 Testing

Cek melalui terminal:

curl http://localhost:8080


Untuk API:

curl http://localhost:8080/api/


---

## 📊 Hasil
- Nginx berhasil berjalan sebagai reverse proxy  
- API Node.js berjalan dengan baik  
- MongoDB terhubung dalam satu network  
- Semua service berjalan menggunakan Docker Compose  

---

## 📝 Kesimpulan
Docker Compose mempermudah pengelolaan aplikasi multi-container dengan konfigurasi yang terpusat. Dengan menggunakan Docker, aplikasi dapat dijalankan secara konsisten di berbagai environment.

---
