# Tugas-ke-6--SISTEM-OPERASI-SK3B

Nama: Satrio Joronggur Mahendra 

Kelas : SK3B

NIM : 09011282328092

menghubungkan server linux ke perangkat lain dgn menggunakan command ssh

Pertama-tama kita ubah dulu settingan network nya di virtual box ke Bridged Adapter. Caranya buka dulu aplikasi virtual box, lalu ke setting, kemudian pilih ke network, dan di bagian Attached to nya ubah ke Bridged Adapter

![image](https://github.com/user-attachments/assets/be313d44-f3de-4625-a791-9ab4b61a41d4)

sambungkan dulu perangkat kita dan perangkat orang lain ke jaringan/wifi yang sama agar bisa terhubung ke server 


disini saya mencoba menghubungkan dengan server saya sendiri
 pergi ke terminal linux, lalu kita gunakan command ifconfig untuk mengecek ip addres kita, jika ingin masuk perangkat yang berbeda maka ifconfig di perangkat tersebut untuk mengetahui ip perangkat tersebut. 
![Screenshot 2024-10-01 210433](https://github.com/user-attachments/assets/f55b07bc-f728-440d-8e41-d742526c222f)
Bisa dilihat di gambar kalau ip addres nya adalah 192.168.43.246 (dibawah tulisan flags=4163)

Kemudian kita menggunakan command ssh yang digunakan untuk melakukan koneksi aman ke sistem lain melalui jaringan. Caranya adalah kita ketik ssh, kemudian nama user, terus @, dan kita masukkan ip addres nya. Contoh : ssh satriojr@192.168.43.246. lalu setelahnya masukkan password saat di mintai password
kalo ingin mencoba di beda perangkat. masukkan nama user dan ip mereka serta masukkan juga pasword mereka agar bisa masuk ke perangkat mereka
![Screenshot 2024-10-01 210453](https://github.com/user-attachments/assets/f799657f-d3b8-48f7-b77f-ed6362854e34)
![Screenshot 2024-10-01 210524](https://github.com/user-attachments/assets/35a0d379-33f4-4573-9763-2c7b6ab6629b)\


 dan kita bisa mengubah, menambahkan dan apapun di perangkat tersebut. jika sudah selesai maka ketik exit untuk keluar
