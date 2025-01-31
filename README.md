# GPIO LED Indikator untuk STB B860H 📺💡

![GitHub repo size](https://img.shields.io/github/repo-size/bayusegara27/gpio-led-indikator-stb-b860h?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/bayusegara27/gpio-led-indikator-stb-b860h?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/bayusegara27/gpio-led-indikator-stb-b860h?style=for-the-badge)

Proyek ini menyediakan skrip yang telah dimodifikasi untuk mengontrol LED pada STB B860H menggunakan GPIO. 🎛️

## Fitur Utama 🚀

- **Kontrol LED**: Menghidupkan dan mematikan LED dengan mudah.
- **Skrip yang Dimodifikasi**: Skrip telah disesuaikan untuk kinerja optimal pada STB B860H.

## Daftar GPIO pada B860H v1/v2 📋

Berikut adalah daftar GPIO dan fungsinya pada STB B860H versi 1 dan 2:

| GPIO | Fungsi       |
|------|--------------|
| 415  | LED LAN1     |
| 416  | LED LAN2     |
| 474  | LED Merah    |
| 476  | LED Hijau    |
| 505  | USB          |

## Langkah Instalasi 🛠️

1. **Kloning repositori**:

    ```bash
    git clone https://github.com/bayusegara27/gpio-led-indikator-stb-b860h.git
    ```

2. **Masuk ke direktori repositori**:

    ```bash
    cd gpio-led-indikator-stb-b860h
    ```

3. **Pindahkan skrip ke `/usr/bin/`**:

    ```bash
    sudo mv bled bledon /usr/bin/
    ```

4. **Ubah izin file**:

    ```bash
    sudo chmod 755 /usr/bin/bled /usr/bin/bledon
    ```

5. **Jalankan skrip**:

    ```bash
    bled -r
    ```

## Kontribusi 🤝

Kontribusi sangat diterima! Anda dapat memulai dengan:

- Melakukan fork repositori ini.
- Membuat branch fitur (`git checkout -b fitur-baru`).
- Melakukan commit perubahan (`git commit -m 'Menambahkan fitur baru'`).
- Melakukan push ke branch (`git push origin fitur-baru`).
- Membuat Pull Request.

---

*Catatan*: Proyek ini merupakan modifikasi dan bukan karya asli saya.
