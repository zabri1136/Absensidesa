# 🏛️ SIAP Desa Lando — Sistem Informasi Absensi Perangkat Desa

Aplikasi website sistem informasi absensi dan presensi perangkat **Desa Lando, Kecamatan Terara, Kabupaten Lombok Timur, Nusa Tenggara Barat (NTB)** yang modern, responsif, menggunakan **Bootstrap 5**, dan mudah digunakan (mobile-friendly).

---

## ✨ Fitur Utama

### 🔐 Hak Akses (Roles)
| Role | Akun Default | Hak Akses |
|------|-------------|-----------|
| **ADMIN** | Kepala Desa, Sekdes, Operator | Kelola semua data, persetujuan izin, kelola perangkat desa, ekspor laporan SPJ |
| **PEGAWAI** | Kasi, Kaur, Kadus, Staf | Presensi masuk/pulang berbasis GPS, pengajuan izin/sakit, lihat riwayat pribadi |

### 📲 Fitur Pegawai (Perangkat Desa Lando)
- ✅ **Presensi Cepat Masuk & Pulang** — **Tanpa perlu foto/selfie**, proses absensi instan dan praktis
- 📍 **Deteksi GPS & Geofencing Otomatis** — Memastikan perangkat desa berada dalam radius wilayah Kantor Desa Lando (250m)
- ⏰ **Status Otomatis** — Hadir tepat waktu, Terlambat (jika lewat jam 08.00 WITA), Izin, Sakit, atau Dinas Luar
- 📋 **Pengajuan Izin / Sakit / Dinas** disertai keterangan terperinci
- 📅 **Riwayat Presensi** harian dan rekap bulanan pribadi
- 👤 **Profil Lengkap** dengan informasi NIK, NIP, alamat dusun, dan kontak

### 🛠️ Fitur Admin (Kepala Desa & Sekdes)
- 📊 **Dashboard Statistik Real-time** — Jumlah hadir, terlambat, izin, sakit, dan belum presensi
- 🔴 **Rasio Kehadiran Live** dengan progress bar berwarna
- 📋 **Tabel Presensi Real-time** seluruh perangkat desa
- 👥 **Manajemen Perangkat Desa** — Tambah, Edit, Hapus data (Nama, NIK, NIP, Jabatan, Role, Alamat, No HP)
- ✅ **Validasi & Persetujuan** pengajuan izin dan sakit
- ⏰ **Pengaturan Jam Kerja** & toleransi keterlambatan (WITA)
- 📍 **Pengaturan Geofencing** — Koordinat Kantor Desa Lando (-8.629524, 116.425128) & batas radius
- 📥 **Ekspor CSV/Excel** untuk pengarsipan
- 🖨️ **Cetak Dokumen Resmi SPJ (PDF)** dengan format kop resmi Pemerintah Desa Lando, Kec. Terara, Kab. Lombok Timur

---

## 🎨 Teknologi & Desain
- **Framework CSS**: Bootstrap 5.3.3 + Bootstrap Icons
- **Font**: Inter (Google Fonts)
- **Tema Warna**: Hijau Instansi Desa (`#0f5132` / `#157347`) dipadu Biru Formal
- **Tanpa Dependency Server**: Single-file HTML mandiri (`index.html`) yang langsung jalan di browser

---

## 🚀 Cara Menjalankan

### Cara Paling Mudah (Langsung Buka)
1. **Double-click** file `index.html` untuk membuka di browser (Chrome, Edge, Firefox, Safari)
2. Aplikasi langsung berjalan tanpa memerlukan instalasi Node.js atau web server tambahan!

---

## 🔑 Akun Uji Coba (Demo)

### Admin
| Nama | Jabatan | NIK / NIP | Password | PIN |
|------|---------|-----------|----------|-----|
| BUDI SANTOSO, S.IP | Kepala Desa Lando | `123456789` | `admin123` | `1234` |
| SRI WAHYUNI, S.E | Sekretaris Desa | `198003202008012015` | `admin123` | `2345` |
| LESTARI INDAH, S.Pd | Operator Desa | `199601252020012002` | `admin123` | `0123` |

### Pegawai
| Nama | Jabatan | NIP / NIK | Password | PIN |
|------|---------|-----------|----------|-----|
| AHMAD FAUZI | Kasi Pemerintahan | `199001152015031005` | `pegawai123` | `3456` |
| DEWI RAHAYU, A.Md | Kaur Keuangan | `198506102010012020` | `pegawai123` | `4567` |
| JOKO WIDODO | Kepala Dusun Lando Daya | `198708202012031010` | `pegawai123` | `7890` |

---

## 📱 Cara Presensi Pegawai
1. Masuk menggunakan NIK/NIP dan Password atau PIN Cepat.
2. Di dashboard, klik tombol **"Absen Masuk Sekarang"** atau **"Absen Pulang Sekarang"**.
3. Sistem secara otomatis mendeteksi GPS lokasi Anda dan menghitung jarak ke Kantor Desa Lando.
4. Klik **"Simpan Presensi Sekarang"** — selesai tanpa repot foto/selfie!

---

## 📍 Koordinat Kantor Desa Lando
- **Lokasi**: Jl. Jurusan Terara - Montong Gading, Desa Lando, Kec. Terara, Kab. Lombok Timur, NTB (83663)
- **Latitude**: `-8.629524`
- **Longitude**: `116.425128`
- **Radius**: `250 Meter`

---

© 2026 Pemerintah Desa Lando — Kecamatan Terara, Kabupaten Lombok Timur
