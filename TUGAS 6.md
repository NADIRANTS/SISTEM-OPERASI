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
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_08_47_31.png)

/home/mahasiswa/.bashrc 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_08_40_13.png)

Ganti nama /home/mahasiswa dengan nama anda sendiri. 
Pada setiap file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : 

echo “Profile dari .bash_profile” 

Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang 
bersangkutan. 

c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: 
$ su mahasiswa 

$ exit 

kemudian gunakan opsi – sebagai berikut : 

$ su – mahasiswa 

$ exit 

![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_09_07_05.png)

Jelaskan perbedaan kedua utilitas tersebut.

1. su mahasiswa:

Perintah ini menjalankan su untuk beralih ke user mahasiswa. Saat menggunakan perintah ini tanpa opsi -, lingkungan (environment) dari user saat ini tetap dipertahankan. Artinya, hanya identitas pengguna yang berubah, tetapi variabel lingkungan seperti PATH tidak akan berubah. Jadi, variabel lingkungan dan direktori kerja yang sedang aktif tetap sama seperti sebelumnya.
        
2. su - mahasiswa:

Perintah ini menggunakan opsi - yang dikenal sebagai login shell. Opsi ini melakukan login penuh sebagai user mahasiswa, sehingga environment yang dimuat adalah environment milik mahasiswa secara lengkap. Ini termasuk mengubah direktori kerja ke home directory user mahasiswa dan memuat variabel lingkungan seperti yang didefinisikan dalam shell milik mahasiswa. Jadi, ini seperti memulai sesi baru sebagai user mahasiswa.
   
2.Prompt String (PS) 

a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan  parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell

PS1=‟> „ 

export PS1 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_09_12_03.png)

b. Eksperimen hasil PS1 :
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_09_38_45.png)

3.Logout 

Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout 
Echo “Terima kasih atas sesi yang diberikan”
Sleep 5 
clear
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_09_45_26.png)

4.Bash script 
a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing : 

p1.sh 

#! /bin/bash 

echo “Program p1” 

ls –l 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_09_51_37.png)

p2.sh 

#! /bin/bash 

echo “Program p2” 

who 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_09_52_56.png)
p3.sh 

#! /bin/bash 

echo “Program p3” 

ps x
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_09_53_51.png)

b. Jalankan script tersebut sebagai berikut : 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_27_09_2024_20_11_34.png)
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_27_09_2024_20_11_55.png)
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_27_09_2024_20_12_45.png)
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_27_09_2024_20_32_58.png)
![Screenshot](

5.Jobs 

a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, 
setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_04_26.png)

b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di background 
sebagai berikut : 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_11_23.png)

c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke 
background 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_14_36.png)

d. Stop program background dengan utilitas kil 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_19_26.png)
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_19_35.png)
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_19_43.png)

6.History 

a. Ganti nilai HISTSIZE dari 1000 menjadi 20 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_33_57.png)

b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang terakhir
dilakukan 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_34_32.png)

c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_35_11.png)

d. Ulangi instruksi pada history bufer nomor 150 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_37_31.png)

e. Ulangi instruksi dengan prefix “ls” 
![Screenshot](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File%20Tugas%206/VirtualBox_NADIRA%20NATASYA_26_09_2024_11_39_26.png)


