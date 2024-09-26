# TUGAS 6 
PRAKTIKUM 5 SISTEM OPERASI
---
### NAMA : NADIRA NATASYA
### NIM : 09011182328096
### KELAS : SK3C
---
Jurusan Sistem Komputer
Fakultas Ilmu Komputer 
Universitas Sriwijaya

2024
---


## Hasil Tugas
  
1.Eksekusi seluruh profile yang ada :

a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : 
echo “Profile dari /etc/profile”
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_07_48_42.png)

b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu : 

/home/stD02001/.bash_profile 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_08_11_42.png)

/home/. stD02001/.bash_login
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_08_24_49.png)

/home/mahasiswa/.profile 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_08_32_58.png)

/home/mahasiswa/.bashrc 
![Screenshot](

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap 
file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : 
echo “Profile dari .bash_profile” 
Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang 
bersangkutan. 
c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: 
$ su mahasiswa 
$ exit 
kemudian gunakan opsi – sebagai berikut : 
$ su – mahasiswa 
$ exit 
Jelaskan perbedaan kedua utilitas tersebut. 
2. Prompt String (PS) 
a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan 
parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell 
PS1=‟> „ 
export PS1 
b. Eksperimen hasil PS1 :
