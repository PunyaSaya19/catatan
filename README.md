# MENU
- [Ganti Versi PHP](#ganti-versi-php)
- [Import File SQL berukuran besar](#import-sql-berukuran-besar)
---

## Ganti Versi PHP 
1.  Buka Terminal dan ketik
    ```sh
    sudo update-alternatives --config php
    ```
2. Akan Muncul list seperti ini. lalu pilih saja sesuai nomer nya
    ![Gambar](img/ganti-versi-php/1.png)
3. Restart server Apache
    ```sh
    sudo systemctl restart apache2
    ```
