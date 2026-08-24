# Introduction to Data Science for Economists

Materi terbuka mata kuliah **B10B.2110**, Program Sarjana Ilmu Ekonomi,
Fakultas Ekonomi dan Bisnis, Universitas Padjadjaran.
Semester Ganjil 2026/2027 · Mikro Kredensial Luhung.

Koordinator: Prof. Mohamad Fahmi
Tim pengajar: Dr. Ahmad Komarulzaman · Herlina Napitupulu, Ph.D. · Prof. I Gede Nyoman Mindra Jaya

---

## Sesi 1 — Pengenalan Data Science & Ekonomi

**Lab: Sinyal hari ini, angka resmi berbulan-bulan lagi**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FEB-Unpad/ds-econ/blob/main/sesi01/Lab_Sesi1_PHK_vs_Angka_Resmi.ipynb)

Notebook ini membandingkan minat pencarian Google untuk kata `PHK` dan `lowongan kerja`
dengan rilis Tingkat Pengangguran Terbuka BPS. Tidak perlu memasang apa pun dan tidak
perlu bisa Python.

Klik lencana di atas, lalu pilih `File → Save a copy in Drive` sebelum mengubah apa pun.

---

## Struktur repositori

```
sesi01/
  Lab_Sesi1_PHK_vs_Angka_Resmi.ipynb    notebook lab
data/
  trends_phk_lowongan.csv                salinan cadangan ekspor Google Trends
                                         (dipakai kalau Google menolak permintaan otomatis)
```

## Sumber data

| Berkas | Sumber | Tanggal unduh |
|---|---|---|
| `trends_phk_lowongan.csv` | trends.google.com, kata kunci `PHK` dan `lowongan kerja`, wilayah Indonesia, Januari 2019 sampai Agustus 2026 | 23 Agustus 2026 |

Angka Tingkat Pengangguran Terbuka ditulis langsung di dalam notebook, satu baris satu
rilis, lengkap dengan tanggal terbit dan tautan Berita Resmi Statistik BPS.

## Catatan untuk mahasiswa

Repositori ini hanya berisi materi kelas dan bersifat publik. Repositori kelompok kamu
dibuat pada Sesi 3, bersifat **privat**, dengan dosen pengampu dan asisten sebagai
kolaborator.

## Lisensi materi

Materi kuliah ini boleh dipakai ulang untuk keperluan pendidikan dengan mencantumkan sumber.
Artikel dan data pihak ketiga tunduk pada lisensi masing-masing pemiliknya.
