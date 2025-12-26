# wfc.ajadulu

**Temukan kafe terbaik untuk bekerja dan produktif di sekitarmu.**

`wfc.ajadulu.com` adalah sebuah platform yang didedikasikan untuk para pekerja remote, freelancer, dan mahasiswa yang gemar bekerja dari kafe (Work From Cafe). Kami membantu Anda menemukan tempat yang tidak hanya nyaman untuk bersantai, tetapi juga mendukung produktivitas dengan fasilitas yang memadai.

## 🎯 Latar Belakang

Seiring dengan meningkatnya tren kerja remote, banyak orang mencari alternatif tempat kerja selain rumah atau kantor. Kafe menjadi pilihan populer, namun tidak semua kafe ideal untuk bekerja. Seringkali kita kesulitan menemukan informasi tentang ketersediaan Wi-Fi yang stabil, jumlah colokan listrik, tingkat kebisingan, atau bahkan jam operasional yang sesuai. `wfc.ajadulu` hadir untuk menjawab tantangan tersebut.

## ✨ Fitur Utama (Direncanakan)

*   **Pencarian Kafe:** Cari kafe berdasarkan nama atau lokasi.
*   **Filter Cerdas:** Saring pencarian berdasarkan fasilitas krusial seperti:
    *   Kualitas Wi-Fi
    *   Ketersediaan Colokan Listrik
    *   Tingkat Kebisingan
    *   Jam Buka
    *   Area Merokok
*   **Ulasan Spesifik:** Baca dan berikan ulasan yang berfokus pada pengalaman kerja di kafe tersebut.
*   **Galeri Foto:** Lihat suasana kafe dari foto yang diunggah oleh komunitas.
*   **Simpan Favorit:** Tandai dan simpan daftar kafe idamanmu.

## 📍 Wilayah Jangkauan

Untuk tahap awal, platform ini akan berfokus pada area **Jabodetabek** (Jakarta, Bogor, Depok, Tangerang, Bekasi). Kami memiliki rencana untuk terus memperluas jangkauan ke kota-kota besar lainnya di seluruh Indonesia.

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun dengan arsitektur monorepo yang terdiri dari dua bagian utama:

*   **Frontend:** Dibangun dengan [Next.js](httpshttps://nextjs.org/) (React) dan TypeScript.
*   **Backend:** Dibangun dengan [NestJS](https://nestjs.com/) (Node.js) dan TypeScript.
*   **Package Manager:** Menggunakan [pnpm](https://pnpm.io/) untuk manajemen dependensi yang efisien.

## 📂 Struktur Proyek

```
/
├── backend/     # Kode sumber untuk server (NestJS)
└── frontend/    # Kode sumber untuk klien (Next.js)
```

## 🚀 Memulai Proyek

Untuk menjalankan proyek ini secara lokal, ikuti langkah-langkah di masing-masing direktori:

### Backend

```bash
cd backend
pnpm install
pnpm run start:dev
```

### Frontend

```bash
cd frontend
pnpm install
pnpm run dev
```

## 🤝 Kontribusi

Kontribusi sangat kami harapkan! Jika Anda memiliki ide, saran, atau ingin melaporkan bug, silakan buat *issue* atau *pull request*.

---

Terima kasih telah menjadi bagian dari perjalanan `wfc.ajadulu`!
