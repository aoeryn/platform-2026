# Business Requirement Document (BRD)
## Sistem Informasi Manajemen Akademik Terintegrasi (SIMAK-TK/SD/SMP/SMA)

| | |
|---|---|
| **Nama Proyek** | Sistem Informasi Manajemen Akademik Terintegrasi (SIMAK) |
| **Rumpun Ilmu** | Ilmu Komputer |
| **Tujuan Bisnis** | Meningkatkan efisiensi pengelolaan akademik sekolah melalui platform web |

---

## 1. Latar Belakang

Proses pengelolaan akademik secara manual (buku, spreadsheet) rentan terhadap kesalahan, lambat, dan menyulitkan koordinasi antara guru, siswa, orang tua, dan akademik sekolah. Dibutuhkan sistem terpusat berbasis web untuk mengatasi permasalahan tersebut.

---

## 2. Tujuan Bisnis (Business Objectives)

- Memudahkan pengelolaan nilai, absensi, jadwal, dan rapor.
- Meningkatkan transparansi informasi akademik antara sekolah dan orang tua.
- Mengurangi beban administrasi guru hingga **40%**.
- Menyediakan laporan akademik real-time untuk kepala sekolah/pengawas.

---

## 3. Stakeholders

| Peran | Kebutuhan |
|---|---|
| **Guru** | Input nilai, absensi, melihat jadwal |
| **Siswa** | Lihat jadwal, nilai, tugas |
| **Akademik (Admin Sekolah)** | Kelola data master (kelas, mapel, tahun ajaran) |
| **Orang Tua** | Pantau progres anak, komunikasi dengan wali kelas |
| **Kepala Sekolah** | Lihat laporan agregat, monitoring kinerja guru |

---

## 4. Lingkup Bisnis

| Jenjang | Lingkup |
|---|---|
| **TK** | Sederhana: absensi, catatan pertumbuhan, notifikasi orang tua |
| **SD** | Nilai tema, rapor per kompetensi |
| **SMP / SMA** | Nilai per mata pelajaran, KKM, remedial, jadwal ujian |

---

## 5. Key Performance Indicators (KPI)

- Waktu input nilai per kelas turun dari **2 jam** menjadi **20 menit**.
- **90%** orang tua aktif login minimal 1x per minggu.
- Tidak ada duplikasi data siswa.
- **100%** data akademik tersedia online setiap saat.

---

## 6. Batasan & Asumsi

### Batasan
- Sistem hanya mencakup jenjang **TK – SMA**.
- Tidak mengelola keuangan (SPP) pada fase awal pengembangan.

### Asumsi
- Sekolah memiliki koneksi internet yang stabil.
- Guru memahami dasar penggunaan aplikasi berbasis web.
