# Instalasi PHP

## Apa saja yang harus kita butuhkan?  

1. PHP
1. Composer
1. Web Server.

### Install menggunakan XAMPP 

XAMPP adalah software untuk menginstall satu paket pengembangan dalam satu instalasi, jadi kamu ngga perlu menginstall satu satu secara manual.  

Kamu bisa mendapatkannya di web official [**XAMPP**] (https://www.apachefriends.org/download.html) disini.

Adapun untuk windows pihak XAMPP menyediakan versi khusus yaitu WAMPP, dan MAMPP untuk MacOS meskipun secara fungsi masih sama dengan XAMPP

### Install menggunakan Laragon

Untuk Laragon sendiri memiliki fungsi yang hampir sama dengan XAMPP, dan kamu bisa dapatkan [**Laragon**] (https://laragon.org/download/) disini.

### Install PHP

Jika kamu menggunakan linux debian dan turunannya:

```shell
sudo apt install php
```
untuk mengecek versi yang terinstall bisa menggunakan perintah:

```shell
php -v
```
### Install Composer 

Untuk Debian dan turunanya :

```shell
sudo apt install composer
````

dan untuk mengecek versi yang sudah terinstall 

```shell
composer --version
```
### Install servel lokal

Ada banyak pilihan untuk menjalankan server di lokal, salat satunya menggunakan apache2 atau ngnix:

install apache2

```script sudo apt install apache2