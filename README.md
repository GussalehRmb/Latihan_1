# NAMA  : AGUS SALEH RUMBOUW
# NIM   : 312510465
# KELAS : TI.25.A.2
# MATKUL: PENGANTAR PEMROGRAMAN

## Latihan1
## menentukan bilangan terbesar dari 4 bilangan menggunakan statement if
## Tujuan
<pre>Membuat program Python sederhana yang meminta input 4 bilangan, kemudian menentukan bilangan yang paling besar menggunakan statement if.</pre>

## Lankah Lankah Pembuatanya
<pre>1. Buka VS Code di laptop jika sudah terinstall dan python 
   Buatkan folder project baru dengan nama misalkan 'latihan1.py'
2. buat file pyton dan didalam nama file itu misalkan nama filenya "latihan1.py"
3. Tuliskan kode berikut ke dalam file "latihan1.py"
4. setelah itu jalankan proramnya di bagian terminal, tekan titik tiga masuk ke terminal dan jalankan terminal baru.
5. terakhir tentukan bilangan besar dari ke 4 bilangan yang di masukan

## Menentukan nilai besar dari bilangan yang di inputkan

<pre>a = int(input("Masukkan bilangan pertama: "))
b = int(input("Masukkan bilangan kedua: "))
c = int(input("Masukkan bilangan ketiga: "))
d = int(input("Masukkan bilangan keempat: "))

terbesar = a

if b > terbesar:
    terbesar = b
if c > terbesar:
    terbesar = c
if d > terbesar:
    terbesar = d

print("Bilangan terbesar adalah:", terbesar)</pre>

Jalankan di terminal "Contoh" :
<pre>masukan bilangan pertama : 15
masukan bilangan kedua : 10
masukan bilangan ketiga : 25
masukan bilangan keempat : 20
  Bilangan terbesar adalah : 25</pre>
# Selesai