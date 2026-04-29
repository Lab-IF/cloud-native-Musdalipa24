# 📝 Jawaban — 01. React vs Next.js

| Info | Detail |
|------|--------|
| **Nama** | Musdalipa |
| **NIM** | 105841121623 |
| **Halaman** | 01. React vs Next.js |
| **Tanggal** | 29 April 2026, 16.27 |

---

## 📝 Kuis Singkat

### 1. Next.js adalah...

**Jawaban:** Next.js adalah framework yang membungkus React. Dibuat oleh Vercel. Dia menambahkan semua yang React tidak punya.

### 2. Mana yang TIDAK perlu di-install manual di Next.js?

**Jawaban:** React (dan React DOM). Karena saat install Next.js (create-next-app), React sudah otomatis terpasang.

### 3. Saat install Next.js, agar menggunakan JavaScript (bukan TypeScript), kita harus pilih...

**Jawaban:** TypeScript = No

### 4. Apakah komponen React bisa dipakai di Next.js?

**Jawaban:** Ya, bisa. Karena Next.js memang menggunakan React sebagai dasar, jadi semua komponen React tetap bisa digunakan.

### 5. Sebutkan minimal 3 fitur yang Next.js berikan di atas React biasa!

**Jawaban:** 
a. Routing otomatis — buat file = buat halaman
b. API backend — bisa buat endpoint langsung
c. Build system — next build langsung jalan
d. SSR & SSG — rendering di server, SEO lebih bagus
e. Deployment mudah — deploy ke Vercel dengan 1 klik
---

## ✏️ Jawaban Latihan

### Latihan 1 — Halaman Utama

export default function Home() {
  return (
    <main>
      <h1>Selamat Datang di Website Saya</h1>
      <p>Ini adalah halaman utama (Home Page)</p>
    </main>
  );
}

### Latihan 2 — Halaman About

export default function About() {
  return <h1>Tentang Kami</h1>;
}

### Latihan 3 — Tantangan: Bandingkan Routing
perbandingan routing :

Tanpa Next.js (React Biasa)
- Install banyak package tambahan
- konfigurasi routing manual
- Backend terpisah
- Satup build rumit

Dengan Next.js
- Minimal package-sudah lengkap
- Routing 
- Backend build-in
- Build 1 perintah
---

## 📊 Ringkasan

| Metrik | Nilai |
|--------|-------|
| Total dijawab | 0 / 8 |
| Skor kuis | 0 / 4 (0%) |
| Latihan terisi | 0 / 3 |

---

_Dibuat otomatis oleh Sistem Kuis Pertemuan 00_
