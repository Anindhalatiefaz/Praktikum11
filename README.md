# Praktikum 11
# Nama : Anindha Latiefa Zahra 
# NIM : 312210323
# Kelas : TI.22.A.3
# Pertemuan 15

1. !pip install pandas digunakan untuk menginstall package pandas di python. Package pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis. Fungsi dari package pandas sangat luas, seperti melakukan operasi pada data, mengimport dan mengeksport data dari berbagai format, dan lainnya. !pip install requests digunakan untuk menginstall package requests di python. Package requests digunakan untuk melakukan HTTP request dari python.

2. !pip install BeautifulSoup4 digunakan untuk menginstall package BeautifulSoup4 di python. Package BeautifulSoup4 digunakan untuk parsing dan mengelola data dari HTML atau XML.

3. import pandas as pd digunakan untuk mengimport library pandas dan menyebutnya sebagai pd. Library pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis.

4. from bs4 import BeautifulSoup digunakan untuk mengimport class BeautifulSoup dari package BeautifulSoup4. Class BeautifulSoup digunakan untuk mengelola dan mengolah data dari HTML atau XML.

![image](https://user-images.githubusercontent.com/115516800/213156946-c6588b1d-3309-47c6-9e5f-c0f8c3c5ac46.png)

# Penjelasan 

1. Mengambil data lowongan kerja dari situs web Glints. Dengan menggunakan library Python 'requests', Codingan mengirim permintaan GET ke URL "https://glints.com/id/lowongan-kerja" yang merupakan halaman web yang berisi informasi lowongan kerja. Kemudian, dengan menggunakan library 'BeautifulSoup', Codingan menganalisis konten halaman web yang didapat dari permintaan GET tersebut dengan menggunakan parser HTML.

2. Selanjutnya, Codingan mencari semua elemen HTML dengan atribut 'div' dan 'id' yang sesuai, yaitu '__next'. Kemudian, dari elemen-elemen tersebut, Codingan mengekstrak informasi pekerjaan, lokasi, dan nama perusahaan dengan mencari elemen yang memiliki atribut 'class' yang sesuai. Informasi yang diambil kemudian disimpan dalam sebuah list yang sesuai.

3. Setelah itu, Codingan menggunakan library pandas untuk membuat dataframe dari list yang didapat dan menyimpannya dalam variabel 'df'. Kemudian Codingan mencetak dataframe tersebut, sehingga kita dapat melihat informasi lowongan kerja yang diambil dari situs web Glints.

![image](https://user-images.githubusercontent.com/115516800/213157861-87893484-6665-476f-a074-c4c084e9680f.png)

# SELESAI
