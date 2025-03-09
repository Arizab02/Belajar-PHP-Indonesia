# Variabel 

Variabel adalah sebuah wadah yang menyimpan nilai nilai tertentu, 

contoh : 

```php
$s = 3;  // ini berarti a menyimpan nilai 3. 
$nama = 'Anton'; // ini berarti variabel nama menyimpan nilai Anton .
```

## Aturan dalam penamaan

- Variabel harus diawali dengan tanda dolar(`$`).
- Variabel tidak boleh diawali dengan angka 0-9.
- Variabel harus diawali dengan huruf atau underscore `_`.
- Variabel hanya bisa diisi oleh numeric (0-9, A-Z, a-z).
- Variabel merupakan case-sensitive ( yang berarti $nama dan $NAMA adalah variabel yang berbeda).

## Scope

Scope atau jangkauan adalah istilah untuk menyebutkan apakah variabel tersebut bisa dijangkau darimana sahaja?

Setidaknya ada dua jenis scope di variabel, yaitu *local scope* dan *global scope* .

### Local Scope

adalah variabel yang hanya bisa digunakan di jangkauan tertutup / tertentu saja, seperti pada fungsi, iterasi, dan juga pengondisian.

### Global Scope

adalah variabel yang bisa digunakan dimana saja tidak terbatas oleh blok kode tertentu.
contoh :

```php
$x = 12;

function berapaX(){
    $x = 15;
    echo $x; 
}

berapaX() // Output : 15
echo $x; // Output : 12
```

