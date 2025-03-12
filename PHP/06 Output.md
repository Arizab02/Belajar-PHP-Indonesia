## Input / Output 

## Input 

Tidak terdapat fungsi input secara baaan di php, akan tetapi jika ingin melakukan input anda bisa melakukannya dengan variabel global `$_GET` dan `$_POST`.

contoh :
```php 
// Mengambil data menggunakan $_GET
if (isset($_GET['nama'])) {
    $nama = $_GET['nama'];
    echo "Nama yang diambil menggunakan GET: " . htmlspecialchars($nama);
}

// Mengambil data menggunakan $_POST
if (isset($_POST['nama'])) {
    $nama = $_POST['nama'];
    echo "Nama yang diambil menggunakan POST: " . htmlspecialchars($nama);
}
```

> Pembahasan ini akan dibahas lebih lanjut di global variabel / variabel global.

atau kamu bisa menggunakan `STDIN` :

```php
// Mengambil data menggunakan STDIN
echo "Masukkan nama: ";
$nama = trim(fgets(STDIN));
echo "Nama yang diambil menggunakan STDIN: " . htmlspecialchars($nama);
```
## Output

PHP menyediakan setidakya dua cara untuk menampilkan data ke view, yaitu dengan :

1. echo (paling umum digunakan)
1. print 
1. printf

contoh :

```php

$nama = "PHP";
echo "hello world ".$nama; 
print "hello world $nama";
printf("hello world %s",$nama);
// Output : hello world PHP