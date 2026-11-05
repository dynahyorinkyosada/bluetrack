# BlueTrack — Panduan Singkat

## Setup
1. Buat proyek di https://supabase.com/dashboard
2. SQL Editor → paste `supabase_setup.sql` → **Run**
3. Authentication → Users → **Add user** (centang Auto Confirm)
4. Project Settings → API → catat **Project URL** & **anon key**

## Konfigurasi
Edit `index.html`, ganti dua baris:
```js
const SUPABASE_URL='https://dggsarhrtmthlxyuwptu.supabase.co';
const SUPABASE_ANON_KEY='vQOzRxyK6kbaC8ZnJvjy5A_5sEswodQ';
