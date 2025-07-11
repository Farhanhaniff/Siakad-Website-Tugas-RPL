## Fitur apa saja yang tersedia di Sistem Informasi Akademik Kampus?

- Multi User
- CRUD : Dosen, Mahasiswa, Fakultas, Gedung, Kelas, Matkul, Prodi, Ruangan, Jadwal, dan Tahun Akademik
- otomatis pengisian data user berdasarkan data mahasiswa dan dosen
- Pengelompokan kelas mahasiswa
- KRS mahasiswa
- Jadwal Dosen
- Nilai
- KHS Mahasiswa

## Default Account for testing

Admin Default Account
username:farhan@gmail.com
password:11111111

Mahasiswa Default Account
username:123456
password:123456

Dosen Default Account
username:1102220
password:Admin123

## How to Install

1. **Clone Repository**

```bash
git clone https://github.com/Farhanhaniff/Siakad-Website-Tugas-RPL
go to folder
composer install
npm install
cp .env.example .env
```

2. **Buka `.env` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**

```bash
DB_PORT=3306
DB_DATABASE=siakd
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**

```bash
php artisan key:generate
php artisan migrate --seed
```

4. **Jalankan website**

```bash
php artisan serve
```
