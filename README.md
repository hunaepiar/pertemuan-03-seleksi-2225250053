# Pertemuan 03 Seleksi Python

Nama: Khunaepi
NIM: 2225250053
Kelas: 3B

## Tujuan

Menulis program seleksi if, if-else, kondisi majemuk, dan nested if.

## Cara Menjalankan

Program dijalankan melalui Terminal pada VS Code.

Untuk menjalankan latihan:

python latihan/01_genap_ganjil.py

python latihan/02_bandingkan_dua_bilangan.py

python latihan/03_kelulusan_bersyarat.py

python latihan/04_jenis_segitiga.py

Untuk menjalankan tugas utama:

python tugas/analisis_persamaan_kuadrat.py

## Algoritma Tugas

1. Membaca nilai a, b, dan c.
2. Memeriksa apakah a sama dengan 0.
3. Jika a sama dengan 0, program menampilkan bahwa input bukan persamaan kuadrat.
4. Jika a tidak sama dengan 0, program menghitung diskriminan dengan rumus D = b² - 4ac.
5. Jika D > 0, program menghitung dan menampilkan dua akar real.
6. Jika D = 0, program menghitung dan menampilkan satu akar real kembar.
7. Jika D < 0, program menampilkan bahwa tidak ada akar real.

## Hasil Pengujian

| Test Case | a | b | c | Hasil Pengujian |
|---|---:|---:|---:|---|
| 1 | 1 | -5 | 6 | Dua akar real: x1 = 3.00, x2 = 2.00 |
| 2 | 1 | 2 | 1 | Akar real kembar: x = -1.00 |
| 3 | 1 | 0 | 1 | Tidak ada akar real |
| 4 | 0 | 2 | 3 | Bukan persamaan kuadrat |

## Kuis

1. Tipe data hasil perbandingan di Python adalah Boolean (True/False).
2. Operator untuk membandingkan kesamaan adalah `==`.
3. `=` digunakan untuk penugasan, sedangkan `==` digunakan untuk membandingkan kesamaan.
4. Pernyataan "nilai harus minimal 75" berarti kondisi yang tepat adalah `nilai >= 75`, karena nilai 75 tetap memenuhi syarat.
5. Blok `else` dijalankan saat kondisi pada `if` bernilai False.
6. 14 % 2 = 0, sehingga 14 adalah bilangan genap.
7. Operator logika untuk memastikan dua kondisi sama-sama benar adalah `and`.
8. Nested if digunakan ketika keputusan kedua hanya relevan jika syarat pertama sudah terpenuhi.
9. Nilai yang memenuhi kondisi `nilai >= 60` adalah 59, 60, dan 61? Jawaban: 60 dan 61.
10. Perintah Git untuk mengirim commit lokal ke repository GitHub adalah `git push`.

## Refleksi

Melalui tugas ini, saya memahami penggunaan percabangan if, if-else, kondisi majemuk, dan nested if dalam Python. Saya juga memahami penggunaan diskriminan untuk menentukan jenis akar pada persamaan kuadrat.
