# <h1 align="center">LAPORAN PRAKTIKUM ALGORITMA PEMROGRAMAN</h1>
# <h2 align="center">MODUL 1 </h2>
<p align="center">Fatimah Az Zahra</p>

## Guided 

### 1. Guided 1

```C++
#include <iostream>
//Fatimah Az Zahra/2211102160/IF-10-D
using namespace std;
int main()
{
cout << "Hello world!" << endl;
return 0;
}
```
Deskripsi program
 Baris pertama #include <iostream>
Pernyataan yang diawali dengan menggunakan tanda pagar # disebut sebagai
Preprocessor Directive, Pada contoh diatas tertulis #include <iostream>
yang berarti program tersebut akan menggunakan fitur dari pustaka (Library) yang
bernama iostream.
 Baris kedua //File-header
//File-header adalah komentar, semua karakter setelah tanda // akan
menjadi komentar dan tidak akan mempengaruhi jalannya program. Komentar

digunakan untuk mempermudah programmer dalam mempelajari program dengan
memberi tanda atau keterangan pada program. Ada dua cara dalam menggunakan
komentar yang pertama adalah dengan tanda // dan kedua dengan menaruh
komentar di antara tanda /* dan */.
 Baris ketiga : baris kosong
Terdapat baris kosong, hal itu tidak akan mempengaruhi jalannya program karena
hanya digunakan untuk mempermudah pembacaan kode program oleh manusia.
 Baris keempat : Using namespace std;
Using namespace std; berarti gunakan semua yang ada dalam namespace
std(standard), seperti con, cout, end1, vector, string, pair, map, queue, deque, dan
lain-lain yang merupakan fitur-fitur C++ standard Library. Dalam kasus ini kita
menggunakan namespace yang bernama cout.
 Baris keenam : int main()
Int main() merupakan fungsi utama, fungsi yang akan dibaca oleh kompilator
pertama kali secara otomatis, tidak aka nada function yang otomatis dibaca oleh
kompilator kecuali fungsi utama, fungsi utama bagaikan sebuah kepala dari sebuah
program yang mengatur arah kompilator.
Int dalam fungsi utama adalah sebuah return type integer. Dalam peraturan C++
fungsi utama memang harus menggunakan return type integer. dan tepat detelah
identifier (identitas) main terdapat sepasang tanda kurung (), itu merupakan tempat
dimana kita dapat mengisi parameter untuk function, tetapi dalam fungsi utama, hal
itu tidak dibutuhkan dan dibiarkan dalam keadaan kosong.
 Baris ketujuh : tanda {
Merupakan sebuah blok pembuka, blok pembuka memiliki sebuah pasangan yang
disebut blok penutup, di dalam contoh program diatas penulis menaruh blok penutup
di baris paling akhir dengan tanda }. Kedua blok tersebut menyatakan bahwa kode
yang diapit oleh mereka adalah satu ruang lingkup (scope) dan menyatakan bahwa
semua kode di dalam blok tersebut merupakan definisi dai fungsi utama.
 Baris kedelapan : cout<<”Hello World!”<< ,adlah sebuah baris pernyataan
dan merupakan definisi dar fungsi utama. Cout merupakan bagian dari librry
<iostream>. Berfungsi untuk mencetak sebuah kalimat Hello World! Saat program
di eksekusi.
 Baris kedelapan : end1 setelah cout <<”Hello World!<< merupakan
anggota dari iostream dan masuk sebagai anggota namespace std yang digunakan
untuk mengakhiri baris/pindah baris pada hasil layer program.

 Baris kesembilan : return 0;

Merupakan pernyataan pengembalian, untuk memberitahu kepada system operas
bahwa program telah berakhir secara normal dengan nilai 0 dan berarti tanpa
kesalahan.
Dalam Pemrograman C++ sebenarnya tidak jauh beda dengan Bahasa Pemrograman

lainnya, setiap program diberbagai Bahasa Pemrograman biasana berisi dari baris-
baris pernyataan (statements), ada statement bersifat mengatur jalannya alur

program dan ada yang bersifat sebagai perintah, dan setiao baris dari pernyataan
akan diakhiri dengan tanda titik koma atau semicolon ;

```C++
#include <iostream>
//Fatimah Az Zahra/2211102160/IF-10-D
using namespace std;
int addem(int, int);
int addem(int a, int b){
int c;
c= a+b;
return c;
}
int main()
{
int x=5, y=2, z;
z=addem(x,y);
cout << z << endl;
return 0;
}
```

