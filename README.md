# Pertemuan 11 - Dictionary/Map

**Nama:** Kesya Nur Aprilliani  
**NIM:** 2225250219  
**Kelas:** 3E  
**Mata Kuliah:** Algoritma dan Pemrograman

## 1. Tujuan

Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value, mengakses data berdasarkan NIM, memanipulasi data, melakukan iterasi, serta menghitung rata-rata nilai mahasiswa.

## 2. Struktur Data

Program menggunakan dictionary bernama `data_mahasiswa`.

- **Key utama:** NIM mahasiswa.
- **Value:** Dictionary yang berisi nama, kelas, dan nilai mahasiswa.
- **Fungsi `cari_mahasiswa()`:** Mencari mahasiswa berdasarkan NIM.
- **Fungsi `rata_rata_nilai()`:** Menghitung rata-rata nilai seluruh mahasiswa.

Dictionary bersarang digunakan agar setiap NIM terhubung dengan informasi mahasiswa yang sesuai.

## 3. Struktur Folder

```text
pertemuan-11-dictionary-2225250219/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_dasar_dictionary.py
│   ├── 02_akses_get.py
│   ├── 03_manipulasi_dictionary.py
│   ├── 04_iterasi_dictionary.py
│   ├── 05_dictionary_bersarang.py
│   └── 06_fungsi_dictionary.py
└── praktik/
    └── data_mahasiswa.py
```

## 4. Cara Menjalankan

Pastikan Python sudah terpasang dan terminal berada di folder utama proyek.

Jalankan perintah berikut:

```bash
python praktik/data_mahasiswa.py
```

Jika diperlukan, gunakan `python3` sebagai pengganti `python`.

## 5. Test Case

| Input/Aksi | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|
| Mencari A003 | Data Citra ditampilkan | Data Citra ditemukan | Berhasil |
| Mencari A999 | Data tidak ditemukan | Data tidak ditemukan | Berhasil |
| Mengubah A002 menjadi 82 | Nilai menjadi 82 | Nilai Budi menjadi 82 | Berhasil |
| Menambah A006 | Data Fajar tersimpan | Data Fajar ditambahkan | Berhasil |
| Menampilkan `items()` | Seluruh 6 data mahasiswa ditampilkan | Seluruh 6 data ditampilkan | Berhasil |
| Menghitung rata-rata | 83.50 | Rata-rata nilai = 83.50 | Berhasil |

## 6. Refleksi

Kesalahan yang perlu dihindari adalah mengakses key yang tidak tersedia menggunakan tanda kurung siku karena dapat menimbulkan KeyError. Perbaikan dilakukan dengan menggunakan `get()` atau memeriksa keberadaan key menggunakan operator `in`.

## 7. Kesimpulan

Dictionary memudahkan penyimpanan dan pencarian data berdasarkan key. Melalui praktik ini, dictionary dapat digunakan untuk menambah, mengubah, mencari, dan menampilkan data mahasiswa serta menghitung rata-rata nilai dengan fungsi Python.
