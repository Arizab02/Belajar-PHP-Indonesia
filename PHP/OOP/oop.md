# OOP (PHP)

## Apa itu OOP 

OOP merupakan singkatan dari Object Oriented Programming atau dalam bahasa indonesia adalah Pemrograman berorientasi objek, kenapa dinamakan begitu ? karena  kita menggunakan konsep objek yang terbawa dari dunia nyata.

## Apa itu Class

Kelas adalah semacam suatu template (blueprint) yang memudahkan kita untuk menginisiasi(membuat) sebuah objek sebelum dibuat.

Untuk membuat kelas bisa dengan keyword `class <nama kelas>`.

## Apa itu Objek 

Objek adalah istilah yang digunakan di jenis pemrograman berbasis objek, yaitu:

> Benda (dalam dunia nyata), baik yang berwujud atau nyata maupun yang tidak nyata (seperti sistem).

Contoh : Komputer, manusia, motor, mobil, basis data, report, dan lainya.

> **Untuk lebih mudahnya lagi _`Objek`_ adalah kelas yang dimasukkan ke suatu variable.**

![Gambar Ilustrasi OOP](image.png)

### Objek mempunyai dua karakteristik :
 - Ciri-ciri (atribut/state/properti).
 - Perilaku (Method/behavior)


Misalnya objek manusia memiliki *atribut* atau *properti* (nama, tinggi, warna, usia, berat), *method* (menangis, tertawa, tersenyum, belajar, berlari, dll).

contoh kode : 

```php 
class Mobil{

    // Property
    public $warna;
    public $merk;

    // Method
    function setWarna($warna){
        $this->warna = $warna;
    }
    function setMerk($merk){
        $this->merk = $merk;
    }

    function getMerk(){
        echo "Merk Mobil : ".$this->merk."\n";
    }
    function getWarna(){
        echo "Warna Mobil : ".$this->warna."\n";
    }
}

$toyota = new Mobil; // Objek1 dari kelas Mobil.
$yamaha = new Mobil; // Objek2 dari kelas Mobil.
```


### Penjelasan Kode 

Kode di ataas adalah contoh dari pengimplementasian (pewujudan) dari kelas dan objek:  

 - `public` merupakan acess modifier, dan akan kita bahas nanti.
   - `public $warna` merupakan contoh properti.
 - `function setMerk()` adalah contoh method.
 - `$this` artinya dia memanggil kelas itu sendiri agar bisa mengakses properti atau method yang ada di kelas tersebut.
 
---
[sebelumnya :  ](3) | [ berikutnya : constructor dan destructor](consturctor-destructor.md)