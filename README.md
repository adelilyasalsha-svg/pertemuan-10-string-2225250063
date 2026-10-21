# Pertemuan 10 - String dan Pengolahan Teks

**Nama:** Adelilya Salsha  
**NIM:** 2225250063  
**Kelas:** 3B

## Tujuan

Mengolah dan menormalisasi data teks menggunakan string Python.

## Cara Menjalankan

Jalankan file latihan melalui VS Code atau terminal.

Untuk menjalankan tugas utama:

```bash
python tugas/normalisasi_data_mahasiswa.py
```

## Algoritma

1. Menerima input nama mahasiswa dan kode kelas.
2. Menghapus spasi berlebih dan menyeragamkan penulisan nama.
3. Mengubah kode kelas menjadi huruf kapital dan mengganti pemisah spasi dengan tanda hubung.
4. Menghitung jumlah kata dan membuat inisial nama.
5. Menampilkan hasil normalisasi.

## Test Case

| Input nama | Input kode | Hasil utama |
|---|---|---|
| aan hendrayana | pmat a 2026 | Aan Hendrayana, PMAT-A-2026, AH |
| fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah, KELAS-B, FM |
| BUDI | pmtk 01 | Budi, PMTK-01, B |
| siti nur aisyah | kelas c | Siti Nur Aisyah, KELAS-C, SNA |

**Status:** Isi setelah seluruh pengujian dilakukan.

## Refleksi

Saya mempelajari penggunaan string untuk membersihkan dan mengolah teks. Saya memahami fungsi `strip()`, `title()`, `upper()`, `split()`, dan `join()`. Kesulitan yang ditemukan adalah menangani spasi berlebih dan huruf yang tidak konsisten. Masalah tersebut dapat diatasi dengan normalisasi teks sebelum data ditampilkan.

## Sumber Bantuan

Bahan Ajar Pertemuan 10: String dan Pengolahan Teks dalam Python.
