# auto-forwards-bot
Bot telegram untuk meneruskan pesan dari user ke grup secara otomatis.

**Gunakan program ini secara bijak jika anda tidak ingin akun anda dibn oleh telegram**

## Instalasi termux dan python di android
1. Download dan install apk termux terbaru dari [sini](https://f-droid.org/en/packages/com.termux/). Pilih link seperti yang ada di gambar


    ![image1](images/img1.png)


2. Update dan upgrade repositori termux, ketik perintah berikut:

    ```
    pkg update && pkg upgrade
    ```
3. Install python, ketik perintah berikut:
    ```
    pkg install python
    ```
4. Cek instalasi python dengan perintah:
    ```
    python --version
    ```
    atau
    ```
    python3 --version
    ```
5. Jika berhasil maka akan keluar tulisan yang menunjukkan versi python yang terinstal. Seperti gambar dibawah

    <img src="images/img2.png" height="250" style="display: block; margin: auto auto;"/>

## Cara penggunaan
### Beri izin termux
Sebelum menggunakan program termux harus diberi izin untuk mengakses media penyimpanan, caranya ketik perintah `termux-setup-storage`. Kemudian jika muncul popup pilih allow app.