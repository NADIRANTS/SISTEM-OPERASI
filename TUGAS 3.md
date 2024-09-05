# 50 Command Line beserta penjelasannya
---
1. ls
   ![Screenshot (218)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.57.34.jpeg)
Menampilkan daftar file dan folder dalam direktori saat ini.

---
2. cd [direktori]
   ![Screenshot (219)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.58.28.jpeg)
Berpindah ke direktori tertentu.

---
3. mkdir [nama folder]
   ![Screenshot (220)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.58.29%20(1).jpeg)
Membuat folder baru dengan nama tertentu.

---
4. pwd
    ![Screenshot (221)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.58.29.jpeg)
Menampilkan path lengkap dari direktori saat ini.

---
5. rmdir [nama_folder]
   ![Screenshot (222)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.59.13.jpeg)
Menghapus folder kosong.

---
6. rm -r [nama_folder]
   ![Screenshot (223)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.59.14%20(1).jpeg)
Menghapus folder beserta isinya.

---
7. rm [nama_file]
   ![Screenshot (224)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.59.14.jpeg)
Menghapus file tertentu.

---
8. mv [sumber] [tujuan]
   ![Screenshot (225)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.59.49%20(1).jpeg)
Memindahkan atau mengganti nama file atau folder.

---
9. touch [nama_file]
    ![Screenshot (226)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.59.49%20(2).jpeg)
Membuat file kosong baru.

---
10. cp [sumber] [tujuan]
     ![Screenshot (227)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2008.59.49.jpeg)
Menyalin file dari lokasi sumber ke tujuan.

---
11. cat [nama_file]
    ![Screenshot (228)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/WhatsApp%20Image%202024-09-05%20at%2009.29.28.jpeg)
Menampilkan isi file ke terminal.

---
12. nano [nama_file]
     ![Screenshot (229)]
Membuka editor teks nano untuk mengedit file.

---
13. vim [nama_file]
     ![Screenshot (230)]
Membuka editor teks vim untuk mengedit file.

---
head [nama_file]
Menampilkan 10 baris pertama dari file.

tail [nama_file]
Menampilkan 10 baris terakhir dari file.

grep [teks] [nama_file]
Mencari teks tertentu dalam file.

find [direktori] -name [nama_file]
Mencari file berdasarkan nama dalam direktori.

chmod [izin] [nama_file]
Mengubah izin akses file atau folder.

chown [user]:[group] [nama_file]
Mengubah kepemilikan file atau folder.

df -h
Menampilkan penggunaan disk dalam format yang mudah dibaca.

du -sh [direktori]
Menampilkan ukuran direktori atau file.

ps aux
Menampilkan semua proses yang berjalan.

kill [PID]
Menghentikan proses berdasarkan PID (Process ID).

top
Menampilkan proses yang menggunakan sumber daya paling banyak.

htop
Versi interaktif dari top dengan tampilan lebih baik (jika terpasang).

history
Menampilkan daftar perintah yang telah digunakan sebelumnya.

clear
Membersihkan layar terminal.

echo [teks]
Menampilkan teks ke layar.

man [perintah]
Menampilkan manual atau panduan penggunaan untuk perintah tertentu.

ssh [user]@[host]
Mengakses server atau komputer lain melalui SSH.

scp [sumber] [user]@[host]:[tujuan]
Menyalin file ke komputer lain melalui SSH.

wget [URL]
Mengunduh file dari internet menggunakan URL.

curl [URL]
Mengambil atau mengirim data ke/ dari URL.

tar -cvf [arsip.tar] [file/direktori]
Membuat arsip tar dari file atau direktori.

tar -xvf [arsip.tar]
Mengekstrak arsip tar.

zip [arsip.zip] [file/direktori]
Membuat arsip zip dari file atau direktori.

unzip [arsip.zip]
Mengekstrak arsip zip.

sudo [perintah]
Menjalankan perintah sebagai administrator atau root.

apt-get update
Memperbarui daftar paket pada sistem berbasis Debian.

apt-get upgrade
Memperbarui semua paket yang diinstal ke versi terbaru.

apt-get install [nama_paket]
Menginstal paket atau program baru.

ping [alamat_ip/domain]
Menguji koneksi jaringan ke IP atau domain tertentu.

ifconfig
Menampilkan konfigurasi jaringan.

netstat -tuln
Menampilkan semua port jaringan yang sedang aktif.

iptables -L
Menampilkan aturan firewall yang sedang diterapkan.

hostname
Menampilkan atau mengatur nama host komputer.

uname -a
Menampilkan informasi detail tentang sistem operasi.

whoami
Menampilkan nama user yang sedang login.

date
Menampilkan atau mengatur tanggal dan waktu sistem.

reboot
Merestart sistem operasi.
