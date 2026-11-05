# BlueTrack - Sistem Operasional Laundry Pickup & Delivery

BlueTrack adalah aplikasi web modern berbasis web statis dan Supabase PostgreSQL untuk mencatat aktivitas operasional *Pickup* dan *Delivery* pelanggan laundry secara efisien, responsif di HP Android, serta dilengkapi fitur rekapitulasi dan berbagi link publik yang aman.

---

## 🚀 Panduan Pemasangan Supabase

### Tahap 1: Membuat Proyek Supabase
1. Buka [https://supabase.com/](https://supabase.com/)
2. Login atau buat akun baru.
3. Buat proyek baru (misal: `bluetrack`), tentukan password database, dan pilih region terdekat.

### Tahap 2: Menyiapkan Database & Tabel
1. Masuk ke menu **SQL Editor** di dashboard Supabase Anda.
2. Buat query baru, salin seluruh isi file `supabase_setup.sql`, lalu klik **Run**.
3. Pastikan tabel, kebijakan RLS, dan fungsi RPC berhasil dibuat.

### Tahap 3: Membuat Akun Administrator
1. Masuk ke menu **Authentication** > **Users**.
2. Klik **Add User** > **Create User**, masukkan email dan password administrator Anda.

### Tahap 4: Menghubungkan Frontend dengan Supabase
1. Masuk ke **Project Settings** > **API**.
2. Salin **Project URL** dan **Anon / Public Key**.
3. Buka file `index.html`, lalu ganti teks `'YOUR_SUPABASE_URL'` dan `'YOUR_SUPABASE_ANON_KEY'` dengan data asli Anda.

---

## 🌐 Panduan Hosting Menggunakan GitHub Pages

1. Buat repository publik baru di GitHub dengan nama `bluetrack`.
2. Upload file `index.html` dan `404.html` ke direktori root repository tersebut.
3. Buka **Settings** > **Pages**, pilih *Deploy from a branch* ke branch `main` dan folder `/ (root)`, lalu simpan.
4. Akses alamat website yang diberikan oleh GitHub Pages!
5. 
