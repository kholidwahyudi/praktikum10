# Praktikum 10
* Nama : Kholid Wahyudi
* Kelas : TI.22.B2
* NIM : 312210345

## Latihan String Python

<p> String dalam bahasa pemrograman Python disebut sebagai kumpulan karakter yang dikelilingi oleh tanda kutip tunggal, tanda kutip ganda bahkan tanda kutip tiga. Komputer tidak memahami karakter. Secara internal, tipe string ini menyimpan karakter yang dimanipulasi sebagai kombinasi dari 0 dan 1. </p>

* Sebagai latihan dibawah ini sebagai contoh :
### Latihan 1
[img 1](project14/l1)
### source code
[img 2](project14/1)

Berikut source code yang sudah saya buat :
```Python
txt = 'Hello World'

print()
print("===================================")
print("1.   jumlah karakternya adalah : ", len (txt))
print("-----------------------------------")
print("2.   " + txt[6:12])
print("-----------------------------------")
print(txt[2:5])
print("-----------------------------------")
x = txt.replace(" ","")
print(x)
print("-----------------------------------")
print(txt.upper())
print("-----------------------------------")
print(txt.lower())
print("-----------------------------------")
new_txt = 'J' + txt[1:]
print(new_txt)
print("===================================")
```
### output
[img 3](project14/hs1)
### Penjelasan

* Fungsi len() digunakan untuk mengidentifikasi dan mengetahui seberapa panjang jumlah item atau anggota pada suatu objek.
* Fungsi [ : ] Memberikan karakter dari kisaran yang diberikan.
* Fungsi replace( , ) Menggantikan karakter lama dalam string dengan karakter baru yang dipisahkan oleh tanda koma(,).
* Fungsi upper() Mengonversi huruf kecil dalam bentuk string ke huruf besar.
* Fungsi lower() Mengonversi semua huruf besar dalam bentuk string menjadi huruf kecil.

### Latihan 2
[img 4](project14/l2)
### source code
[img 5](project14/2)

Berikut source code yang sudah saya buat :

umur = 20
txt = "Hello nama saya Kholid, dan umur saya %d tahun" % (20)
print(txt.format(umur))

### output
[img 6](project14/hs2)
### Penjelasan

jadi sintax tambahannya adalah %d, %d ini berfungsi sebagai bilangan bulat desimal.

### Cukup Sekian Terimakasih 