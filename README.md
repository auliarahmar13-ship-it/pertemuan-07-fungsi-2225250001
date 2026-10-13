# Pertemuan 07 Fungsi Python

Nama: Aulia Rahma Ramadhani  
NIM: 2225250001  
Kelas: 3A

## Tujuan

Menggunakan fungsi, parameter, return value, dan scope untuk membuat program modular.

## Cara Menjalankan

```bash
python praktik/utilitas_matematika.py
```

## Struktur Fungsi

- `luas_persegi_panjang(p, l)`: menghitung luas persegi panjang dan mengembalikan hasil perkalian panjang dan lebar.
- `luas_segitiga(a, t)`: menghitung luas segitiga dan mengembalikan hasil perhitungan alas dikali tinggi dibagi dua.
- `jumlah_n(n)`: menghitung jumlah bilangan dari 1 sampai n menggunakan perulangan.
- `faktorial(n)`: menghitung faktorial menggunakan perulangan.
- `tampilkan_menu()`: menampilkan pilihan operasi matematika kepada pengguna.

## Hasil Pengujian

| Operasi | Input | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---:|---:|---|
| Luas persegi panjang | p = 8, l = 5 | 40 | 40.0 | Berhasil |
| Luas segitiga | a = 10, t = 6 | 30.0 | 30.0 | Berhasil |
| Jumlah 1 sampai n | n = 10 | 55 | 55 | Berhasil |
| Faktorial | n = 5 | 120 | 120 | Berhasil |
| Faktorial | n = 0 | 1 | 1 | Berhasil |

## Refleksi

Program menjadi lebih terstruktur karena setiap operasi matematika dipisahkan menjadi fungsi tersendiri. Parameter digunakan untuk menerima masukan, sedangkan return value digunakan untuk mengembalikan hasil perhitungan. Perulangan digunakan dalam fungsi jumlah bilangan dan faktorial. Fungsi tampilkan_menu() membantu menampilkan pilihan operasi kepada pengguna.