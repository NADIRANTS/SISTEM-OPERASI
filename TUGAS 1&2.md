# LAPORAN PRAKTIKUM SISTEM OPERASI
---
### NAMA : NADIRA NATASYA
### NIM : 09011182328096
### JUDUL PRAKTIKUM : Instalasi Linux dengan VM / V-Box
---
Jurusan Sistem Komputer
Fakultas Ilmu Komputer 
Universitas Sriwijaya 

2024
---

# TUGAS 1
1. BUKA VIRTUAL BOX LALU PILIH NEW
   
   ![Screenshot (205)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364189511-30256a0c-de75-461d-b982-8740a6bba135.png)
  

2. LALU KETIK SETTINGS
 
   ![Screenshot (207)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364189653-d231600d-8e2e-403f-acfa-a01789ee3489.png)


3. LANGKAH SELANJUTNYA BASE MEMORY BUAT MENJADI 4906 DAN 
PROCESSORS MENJADI 2 LALU NEXT

   ![Screenshot (208)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364189865-54c0a9cd-569b-4f56-8932-5eed69249031.png)

   
4. KEMUDIAN BUAT DISK SIZE MENJADI 25,00 GB DAN TEKAN NEXT

    ![Screenshot (209)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364190160-c99239eb-8531-4aad-96b2-2fdc988bbea2.png)


5. TEKAN SETTINGS DAN TEKAN DISPLAY LALU VIDEO MEMORY MENJADI 128 MB, MONTOR COUNT 1 LALU SCALE FACTOR 100% DAN KETIK OKE, LALU TEKAN INSTALL LINUX MINT

    ![Screenshot (210)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364191202-54d2bc76-7c7b-41d9-b6a7-f122869888e1.png)


6. TAMPILAN AWAL INSTALL LINUX, PENGGUNA DIMINTA UNTUK MEMILIH LAYOUT KEYBOARD SESUAI KOMPUTER YANG DIGUNAKAN, LALU TEKAN ERASE DISK AND STILL LINUX MINT DAN TEKAN INSTALL NOW

    ![Screenshot (211)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364191910-016081b6-53bd-4310-b90c-573650fcefa0.png)


7. SETELAH MENDAPATKAN TAMPILAN INI TEKAN CONTINUE

   ![Screenshot (212)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364192249-1e2e0ac9-fdd0-4535-acee-9cb578e4e6ec.png)


8. TAMPILAN SELANJUTNYA SETELAH MENGKONFIRMASI KONFIGURASI PARTISI, PENGGUNA DIMINTA UNTUK MEMILH LOKASI YANG AKAN DIJADIKAN ZONA WAKTU

   ![Screenshot (213)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364192370-584f345e-47db-4126-a7ba-e1010d91a1cb.png)


9. KEMUDIAN, PENGGUNA DIMINTA UNTUK MEMBUAT USERNAME, NAMA HOST, DAN PASSWORD YANG AKAN DIGUNAKAN, PENGGUNA BISA MEMILIH UNTUK MENGENKRIPSI DRIVE, DIKASUS INI, HAL TERSEBUT TIDAK PERLU DILAKUKAN DAN TUNGGU PROSES INSTALASI LINUX SAMPAI SELESAI

    ![Screenshot (214)](https://github.com/NADIRANTS/SISTEM-OPERASI/blob/main/File/364192596-edb51c40-2399-45c0-84ab-1a9da690feea.png)


10. SELANJUTNYA TEKAN RESTART NOW

    ![Screenshot (215)](


11. JIKA INSTALASI DILAKUKAN MELALUI MESIN SCR LANGSUNG MENGGUNAKAN CD/DVD/FLASHDRIVE, SILAKAN COPOT FLASHDRIVE LALU KLIK ENTER DAN INSTALASI TELAH SELESAI DILAKUKAN

    ![image](https://github.com/user-attachments/assets/f3c03e7e-ab90-4446-aca4-62672b2f197d)

---

# TUGAS 2
2. Pada saat menginstal linux, partisi yang di-mount ke (/) atau dikenal sebagai 
root, merupakan direktori utama yang berisi file-file esensial linux. Partisi ini 
menyimpan file sistem yang sangat penting untuk menjalankan sistem operasi, 
termasuk kernel, program inti, library, dan konfigurasi sistem.

---

3. Penjelasan tentang ext4, ext3, swap, ntfs, fat32, btrfs

1.) Ext4 (fourth extended filesystem)
Penjelasan: ext4 adalah versi terbaru dari seri sistem berkas `ext` yang banyak 
digunakan di linux.
Sistem berkas ini adalah peningkatan dari ext3 dan menawarkan fitur seperti 
pengelolaan ruang disk yang
Lebih efisien, waktu akses yang lebih cepat, dan peningkatan kapasitas 
penyimpanan.
- fitur utama:
- dukungan untuk volume hingga 1 exabyte.
- fragmentasi berkas yang lebih sedikit.
- waktu boot yang lebih cepat.
- mendukung jumlah maksimum file yang lebih besar dibandingkan ext3.
  
2.) Ext3 (third extended filesystem)
Penjelasan: ext3 adalah versi sebelumnya dari sistem berkas ext4 dan juga 
banyak digunakan di linux.
Ini adalah peningkatan dari ext2 dengan menambahkan fitur journaling, yang 
membantu mencegah
Kerusakan data saat sistem tidak ditutup dengan benar.
- fitur utama:
- journaling untuk meningkatkan integritas data.
- mudah diupgrade ke ext4 tanpa memformat ulang partisi.
- tidak seefisien ext4 dalam hal manajemen ruang dan kecepatan akses.
  
3.) Swap
Penjelasan: Swap bukanlah sistem berkas, melainkan partisi atau file khusus yang 
digunakan untuk
menyimpan data sementara ketika RAM penuh. Ini adalah semacam "memori 
virtual" yang membantu
sistem tetap berjalan lancar ketika beban memori tinggi.
- Fitur Utama:
- Meningkatkan performa sistem ketika RAM hampir habis.
- Membantu dalam hibernasi sistem, di mana isi RAM dapat disimpan ke swap.
- Kecepatan akses lebih lambat dibandingkan RAM, jadi sebaiknya digunakan 
hanya ketika
diperlukan.

4.) NTFS (New Technology File System)
Penjelasan: NTFS adalah sistem berkas yang digunakan secara default oleh sistem 
operasi Windows.
NTFS menawarkan dukungan untuk file dan volume yang lebih besar, fitur 
keamanan, dan kemampuan
pemulihan kesalahan.
- Fitur Utama:
- Mendukung file dengan ukuran lebih dari 4 GB dan volume hingga 256 TB.
- Fitur journaling dan keamanan tingkat file.
- Dukungan untuk kompresi berkas dan enkripsi.
  
5.) FAT32 (File Allocation Table 32)
Penjelasan: FAT32 adalah sistem berkas yang lebih lama, digunakan di berbagai 
sistem operasi,
terutama Windows dan perangkat penyimpanan seperti USB drive. Meskipun 
memiliki kompatibilitas
yang luas, FAT32 memiliki keterbatasan dalam ukuran file dan volume.
- Fitur Utama:
- Kompatibilitas yang sangat baik di berbagai perangkat dan sistem operasi.
- Batas ukuran file maksimal 4 GB dan batas volume 2 TB.
- Tidak mendukung fitur keamanan tingkat file atau journaling.
  
6.) Btrfs (B-tree File System)
Penjelasan: Btrfs adalah sistem berkas modern yang dikembangkan untuk Linux, 
menawarkan fiturfitur canggih seperti snapshot, kompresi transparan, dan 
kemampuan manajemen volume yang lebih baik.
- Fitur Utama:
- Snapshot dan rollback, yang memungkinkan pengguna untuk memulihkan 
keadaan sebelumnya dari
sistem berkas.
- Manajemen volume dan disk yang lebih fleksibel.
- Fitur pemeriksaan integritas data untuk mencegah kerusakan berkas.

