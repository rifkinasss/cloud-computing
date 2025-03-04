# Cloud Computing Project

Selamat datang di repositori proyek Cloud Computing! Dokumentasi ini mencakup langkah-langkah yang dilakukan selama pengembangan proyek, terorganisasi berdasarkan minggu.

---

## Pekan 1: Membuat Struktur Folder Proyek

Pada pekan pertama, kami memulai proyek dengan membuat struktur folder dasar untuk mengorganisasi file proyek. Berikut adalah struktur folder yang dibuat:
```
Project/
   │
   ├── backend/ # Folder untuk menyimpan file backend (API, logika server, dll.)
   ├── db/ # Folder untuk menyimpan file database atau skrip terkait database
   └── frontend/ # Folder untuk menyimpan file frontend (UI, halaman web, dll.)
```
### Penjelasan Struktur Folder:
1. **Backend**
   - Folder ini digunakan untuk menyimpan semua file terkait backend, seperti file Python untuk API Flask, konfigurasi server, dan logika bisnis aplikasi.
   
2. **DB (Database)**
   - Folder ini digunakan untuk menyimpan file terkait database, seperti skrip SQL, file migrasi, atau konfigurasi koneksi database.

3. **Frontend**
   - Folder ini digunakan untuk menyimpan semua file terkait frontend. Dalam hal ini menggunakan framework React.js dengan instalasi menggunakan vite

---

## Pekan 2: Membuat API Sederhana dengan Flask (Backend)

Pada pekan kedua, kami membuat API sederhana menggunakan Flask. Berikut adalah langkah-langkah yang dilakukan:

1. **Membuat Virtual Environment**
   - Buat Virtual Environment menggunakan perintah:
     ```bash
     python -m venv venv
     ```
   - Aktifkan Virtual Environment:
     - Untuk Windows:
       ```bash
       venv\Scripts\activate
       ```
     - Untuk macOS/Linux:
       ```bash
       source venv/bin/activate
       ```

2. **Menginstall Flask**
   - Install Flask menggunakan pip:
     ```bash
     pip install Flask
     ```

3. **Struktur Dasar Flask**
   - Tidak ada struktur dasar Flask yang dibuat pada tahap ini.

4. **Menjalankan Flask**
   - Jalankan aplikasi Flask menggunakan perintah:
     ```bash
     python app.py
     ```

---

## Pekan 3: Instalasi React + Vite (Frontend)

Pada pekan ketiga, kami menginstal React menggunakan Vite sebagai alat pengembangan frontend. Vite adalah build tool modern yang cepat dan efisien untuk proyek JavaScript/React. Berikut adalah langkah-langkah instalasi:

1. **Masuk ke Folder Frontend**
   - Buka terminal dan navigasikan ke folder `frontend`:
     ```bash
     cd frontend
     ```

2. **Inisialisasi Proyek React dengan Vite**
   - Gunakan perintah berikut untuk membuat proyek React baru dengan Vite:
     ```bash
     npm create vite@latest
     ```
     - Anda akan diminta untuk memasukkan nama proyek (misalnya `my-react-app`) dan memilih framework. Pilih `React` sebagai framework dan `JavaScript` sebagai bahasa.

3. **Masuk ke Folder Proyek React**
   - Setelah proyek dibuat, masuk ke folder proyek React:
     ```bash
     cd my-react-app
     ```

4. **Install Dependensi**
   - Install semua dependensi yang diperlukan menggunakan npm:
     ```bash
     npm install
     ```
     5. **Menjalankan Aplikasi React**
   - Jalankan aplikasi React dalam mode development:
     ```bash
     npm run dev
     ```
   - Aplikasi React akan berjalan di `http://localhost:5173` (atau port lain jika port tersebut sudah digunakan).

6. **Struktur Folder React + Vite**
   - Setelah instalasi selesai, berikut adalah struktur folder dasar yang dihasilkan oleh Vite:
     ```
     my-react-app/
     ├── node_modules/      # Folder untuk dependensi npm
     ├── public/            # Folder untuk file statis (misalnya gambar, favicon)
     ├── src/               # Folder untuk kode sumber aplikasi
     │   ├── App.jsx        # Komponen utama aplikasi
     │   ├── main.jsx       # Entry point aplikasi
     │   └── assets/        # Folder untuk aset seperti gambar atau font
     ├── index.html         # File HTML utama
     ├── package.json       # File konfigurasi npm
     ├── vite.config.js     # Konfigurasi Vite
     └── README.md          # Dokumentasi proyek (opsional)
     ```

---

## Pekan 4

(Tambahkan deskripsi tugas atau aktivitas yang dilakukan pada pekan keempat.)

---

## Catatan Tambahan

- Pastikan semua dependensi telah diinstal sebelum menjalankan aplikasi.
- Jika ada pertanyaan atau masalah, silakan buat issue di repositori ini.

Terima kasih!
