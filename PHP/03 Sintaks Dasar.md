# Sintaks Dasar PHP  

## Basic PHP Sintaks :

Setiap file di `.php` harus diawali dengan `<?php...?>` contoh :

```php 
<?php 
    // your code
?>
```

contoh dalam kode :
```php
<!DOCTYPE html>
<html>
<body>

<h1>Page pertama saya</h1>

<?php
echo "Hello World!";
?>

</body>
</html>
```
> Note : Baris di PHP diakhiri dengan semi-kolon / titik koma (`;`)  

dan apabila tidak diharuskan untuk menggunakan bahasa lain seperti :  

- HTML
- CSS
- JS  

maka kamu bisa menggunakan `<?php` saja tanpa penutup tag, contoh :  

```php 
<?php
 //code kamu
 //sampai ke bawah

```
## Case sensitive 

Dalam PHP semua _keyword_ (`if`, `else`, `for`, `in`), variable,class dan function dll, contoh:

```php
$a = 10;
$A = 12;

echo $a; //output: 10
```

| [sebelumnya: Introduction](03%20Sintaks%20Dasar.md)  | [berikutnya: komentar](04%20komentar.md) |