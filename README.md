# latihan2

## Operator Pada Python
1. Operator adalah simbol khusus pada python yang di gunakan untuk perhitungan aritmatika atau logika. Dan nilai yang dihasilkan oleh operator disebut operand.

### Contoh Symbol Operator Aritmatika 
1. Penjumlahan (+)
2. Pengurangan (-)
3. Perkalian (*)
4. Pembagian (/)
5. Sisa bagi (%)
6. Pangkat   (**)
7. Pebagian bulat (//)

#### Berikut Tampilan Syntax yang Benar 
- a=input("masukan nilai a:")
- b=input("masukan nilai b:")
- print("variable a=" ,a)
- print("variable b=" ,b)
- print("hasil penggabungan {0}&{1}=%s" .format(a,b) %(a+b))
- a=int(a)
- b=int(b)
- print("hasil penjumlahan {0}+{1}=%d" .format(a,b) %(a+b))
- print("hasil pembagian {0}/{1}=%d" .format(a,b) %(a/b))

##### Penjelasan Operator Format String Python
1. %d dianggap sebagai bilangan bulat desimal 
2. %s konfersi string melalui str () sebelum memformat
3. %f yaitu bilangan real floating point 

###### Langkah - langkah Mengoperasikannya 
1. a=input("masukan nilai a:")

2. b=input("masukan nilai b:") urutan pertama dan kedua ini untuk, meminta kita memasukan angka ke variable a dan b

3. print("variable a=" ,a)

4. print("variable b=" ,b) setelah itu kita menuliskan ulang nilai yanng telah dimasukan di langkah yang pertama tadi.

5. print("hasil penggabungan {1}&{0}=%d" .format(a,b) %(a+b)) Syntax ini akan menggabungkan variable a dan b, namun pada tahap ini akan terjadi error karena tipe data pada variable adalah string sedangkan yang diminta adalah nomor(integer), maka kita harus mengubah '%d' menjadi '%s' agar sistem membacanya sebagai string bukan integer. Lalu karena {1} adalah variable b dan {0} adalah variable a (b,a), maka di ubah menjadi {0}&{1} agar tidak terbalik dan sesuai dengan format yang akan digabungkan.

6. a=int(a)

7. b=int(b) Lalu urutan 6 dan 7 akan mengkonversikan tipe data variable a dan b, dari bilangan yang sebelumnya 'str' menjadi 'int'.

8. print("hasil penjumlahan {1}+{0}=%d .format(a,b) %(a+b)) Pada langkah ini akan menjumlahkan nilai angka variable a dan b, namun sebaiknya {1}+{0} diubah menjadi {0}+{1} agar variable tidak terbalik.

9. print("hasil pembagian {1}+{0}=%d .format(a,b) %(a/b)) Dan yang terakhir, melakukan pembagian nilai variable a dan b, tetapi ubah {1}/{0} menjadi {0}/{1} agar nilai yang dibagi sesuai dengan hasilnya. Gunakan '%d' atau '%s' apabila hasilnya angka desimal. 
  

 
