# Project-filter-Target-data-python
This project about learning filtering and targeting data in python (In Indonesia)

Kini saatnya kita membahas untuk melakukan filter untuk sebuah nilai dengan menggunakan perintah where() dalam pernyataan query tersebut.
Where Clause:
Sebagai contoh misalkan ingin menampilkan data untuk kolom state dan kolom age dimana dengan kondisi ketika state == California.
Dimulai dengan pernyataan select lalu kita tambahkan klausa where untuk kolom state == California. Kemudian execute pernyataan dan kita gunakan perulangan for untuk menampilkan data di kolom state dan age.
Klausa where juga dapat kita gunakan untuk membandingkan nilai kolom dengan nilai kolom lainnya. Kita juga dapat menggunakan operator perbandingan seperti sama dengan (=), kurang dari sama dengan (<=), lebih dari sama dengan (>=) atau tidak sama dengan (!=).
Expressions,
selain operator perbandingan, terdapat juga SQL Expressions untuk kondisi yang lebih kompleks seperti:
- in_() untuk pencocokan nilai dari sebuah list
- like() untuk pencocokan nilai kolom dengan nilai parsial dengan simbol wildcards
- dan between() untuk mengecek apakah nilai kolom tersebut diantara 2 nilai.

Disini menampilkan kolom state dan kolom pop2008 dimana kondisinya adalah untuk state yang diawali dengan string ‘New’.
Conjunctions:
- Digunakan untuk multiple kriteria di dalam klause where
- Contohnya: and_(), not_(), or_()

Misalkan kita ingin menampilkan data dari kolom state dan kolom sex dengan kondisi dimana kolom state = California atau state = New York
