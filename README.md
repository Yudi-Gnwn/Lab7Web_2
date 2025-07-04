# Tugas Praktikum Pemrograman Web 2
```
Yudi Gunawan
312310179
```
## Praktikum 1
- download codeigniter dari website, kemudian ekstrak file ke direktori baru
  htdocs/lab11_ci, kemudian ubah nama file menjadi ci4
- kemudian cek ```http://localhost/lab11_ci/ci4/public```
  
  ![Screenshot 2025-03-19 112837](https://github.com/user-attachments/assets/5fc81915-ec3a-4c8f-ab46-39f80f405570)

- buka cmd kemudian masuk ke direktori project

  ![Screenshot 2025-03-19 113715](https://github.com/user-attachments/assets/f9b999d1-78ae-479c-b2b1-fe99bc260f60)

- kemudian jalankan codeigniter dengan perintah```php spark```

  ![Screenshot 2025-03-19 115600](https://github.com/user-attachments/assets/66a4c97d-22aa-4713-b622-f84d69dbc613)

- masuk ke file ```.env``` kemudian rubah variabel menjadi ```CI_ENVIRONMENT = development```

  ![Screenshot 2025-03-19 115804](https://github.com/user-attachments/assets/edbea406-2c10-4897-b25c-8f4df027bb3e)

- jika terjadi error, maka akan terbaca oleh codeigniter

  ![Screenshot 2025-03-20 090736](https://github.com/user-attachments/assets/80acd4b2-2a46-49e1-a933-4d3d783296d7)

- kemudian membuat konfigurasi di ```app/Config/Routes.php```

  ![Screenshot 2025-03-20 090057](https://github.com/user-attachments/assets/9b9ff089-79fe-463b-b343-554d8f1067dd)

- buka cmd dan lakukan ```php spark route``` untuk mengecek route yang telah dibuat

  ![Screenshot 2025-03-20 090113](https://github.com/user-attachments/assets/02738ed4-bbc8-4ca7-8c94-c3e15bcd147f)

- lakukan pengecekan dengan ```http/localhost:8080/about```

  ![Screenshot 2025-03-20 093610](https://github.com/user-attachments/assets/02b2b0d6-22d0-42fd-bf70-2fa78fcda5d9)

- membuat controller agar halaman ```About```  bisa terkoneksi
- buat file baru ```Page.php``` pada direktori ```app/Controller```, kemudian masukan code berikut:

  ![Screenshot 2025-07-04 165920](https://github.com/user-attachments/assets/6a9cad8b-28a6-4105-8c83-345581ed5440)

- Refresh dan cek kembali web browser, maka halaman about sudah terkoneksi
- kemudian sesuaikan halaman about sesuai dengan struktur pada modul Praktikum

  ![Screenshot 2025-03-20 093623](https://github.com/user-attachments/assets/5385558a-b416-47b6-b0ab-affb08da59a9)
 
- Setelah menyesuaikan struktur web, kemudian tambahkan CSS
- buat file pada direktori ```public``` dengan nama ```stye.css``` mengikuti dari praktikum sebelumnya (lab4_layout)

  ![Screenshot 2025-07-04 171449](https://github.com/user-attachments/assets/c4239f70-2ae6-4219-983b-a8d259c34045)

- pada direktori ```views``` buat folder ```template```, disana kita mengisikan file ```header.php``` dan ```footer.php``` untuk meringkas code pada ```app/views/about.php```
- akses kembali ```http://localhost:8080/lab11_ci/ci4/public```

  ![Screenshot 2025-03-20 101438](https://github.com/user-attachments/assets/58238671-b451-4aa2-8408-e200381ea575)
