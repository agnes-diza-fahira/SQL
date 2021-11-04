# OPERATOR

> **Operator** adalah karakter/simbol yang digunakan untuk memberikan instruksi pada program untuk melakukan seusatu

> **Operator** terdiri dari Operator Aritmatika, _Bitwise_, Perbandingan (_Comparison_), Penggabungan (_Compound_), dan _Logical_.

Berikut adalah jenis-jenis operator dalam SQL beserta penggunaannya:

## Operator Aritmatika
> Berfungsi untuk menjalankan operasi aritmatik atau perhitungan matematika.

- `+` | **Tambah**
- `-` | **Kurang**
- `*` | **Kali**
- `/` | **Bagi**
- `%` | **Modulo** atau sisa pembagian

## Operator Bitwise
> Berfungsi untuk menangani operasi logika bilangan biner dalam bentuk bit.

- `&` | **AND**
- `|` | **OR**
- `^` | **OR Eksklusif**

## Operator Perbandingan (_Comparison_)
> Berfungsi untuk melakukan perbandingan antara dua nilai.

- `=`  | **Sama dengan**
- `>`  | **Lebih dari**
- `<`  | **Kurang dari**
- `>=` | **Lebih dari sama dengan**
- `<=` | **Kurang dari sama dengan**
- `<>` | **Tidak sama dengan**

## Operator Penggabungan (_Compound_)
> Berfungsi untuk melakukan operasi aritmatika dan hasilnya dimasukkan ke nilai asli. contoh:`a = a+b` menjadi `a+=b`

- `+=` | Nilai asli **ditambah** variable baru
- `-=` | Nilai asli **dikurang** variable baru
- `*=` | Nilai asli **dikali** variable baru
- `/=` | Nilai asli **dibagi** variable baru
- `%=` | Milai asli **dimodulo** variable baru

## Operator Logical
> Berfungsi untuk membandingkan 2 kondisi logika benar (TRUE) dan logika salah (FALSE).

- `ALL`     | **TRUE** jika semua nilai subqueri sesuai dengan kondisi
- `AND`     | **TRUE** jika dua kondisi yang dipisahkan **AND** bernilai **TRUE**
- `ANY`     | **TRUE** jika salah satu nilai subquery memenuhi kondisi
- `BETWEEN` | **TRUE** jika berada dalam kisaran perbandingan
- `EXIST`   | **TRUE** jika subqueri mengembalikan satu atau lebih rekaman
- `IN`      | **TRUE** jika sama dengan salah satu daftar ekpresi
- `LIKE`    | **TRUE** jika cocok dengan suatu pola
- `NOT`     | Menampilkan rekaman jika kondisi tidak sesuai
- `OR`      | **TRUE** jika salah satu kondisi yang dipisahkan oleh **OR** adalah **TRUE**
- `SOME`    | **TRUE** jika salah satu nilai subqueri memenuhi kondisi
