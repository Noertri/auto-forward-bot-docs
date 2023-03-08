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

    <img src="images/img2.png" style="display: block; margin: auto auto; max-height:250px; max-width: 200px;"/>

## Cara penggunaan
### Android

1. Sebelum menggunakan program, termux harus diberi izin untuk mengakses media penyimpanan, caranya ketik perintah `termux-setup-storage`. Kemudian jika muncul popup pilih allow app (proses ini cukup dilakukan sekali).

2. Program ini butuh api id dan api hash dari telegram, untuk mendapatkannya buat [disini](https://my.telegram.org/auth), untuk tutorialnya bisa lihat [video](https://youtu.be/8naENmP3rg4).

3. Simpan file `auto-forward-bot.zip` di tempat yang mudah diakses (disarankan di folder download di penyimpanan internal).

<img src="images/img3.png" style="display: block; margin: auto auto; max-height: 250px; max-width: 200px"/>

4. Ekstrak file `auto-forward-bot.zip` tersebut.

<img src="images/img4.png" style="display: block; margin: auto auto; max-height: 250px; max-width: 200px"/>

5. 