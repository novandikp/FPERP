# Modul HR Odoo Docker Container
Ini adalah container Docker untuk modul HR Odoo, platform open source ERP dan CRM. Container ini menggunakan Docker Compose untuk memudahkan instalasi dan konfigurasi modul HR Odoo.


## Persyaratan
Untuk menggunakan container ini, Anda perlu memiliki Docker terpasang pada sistem Anda. Anda juga perlu memiliki modul HR Odoo yang terinstal pada sistem Anda. Anda dapat mengikuti petunjuk ini untuk menginstal Odoo.


## Instalasi
Clone repositori ini pada sistem Anda menggunakan perintah 
```bash
git clone https://github.com/novandikp/FPERP.git
```
Masuk ke direktori FPERP yang baru saja Anda clone menggunakan perintah 
```bash
cd FPERP
```
Jalankan perintah 
```bash
docker compose up
```
untuk menjalankan container modul HR Odoo.



## Konfigurasi
Password admin terdapat dalam file config/odoo.conf pada atribut admin_passwd. Anda juga dapat mengubah file .env untuk menyesuaikan parameter konfigurasi container Docker.