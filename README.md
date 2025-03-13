# Nama : Syai Dean Putri
#  Nim :09030282327044
# Kelas :TK4C
# Mata Kuliah : Sistem operasi

## TUGAS 1 : EKSEKUSI PROFILE
## A. Edit file/etc/profile
1. Tahap pertama buka terminal
   
2. lalu jalankan perintah berikut untuk membuka file dengan editor : sudo nano / etc/profile
    -   setelah itu tambahkan perintah ini dibagian paling akhir file: echo "profile dari /etc/profile"
    -    simpan file tersebut, dengan cara menekan ctrl+o kemudian enter dan ctrl + x untuk keluar

3. Verifikasi perubahan:
   -  jika ingin melihat apakah perubahan yg kita buat sudah berhasil,  jalankan perintah:
source /etc/profile
  -  Anda akan melihat pesan: Profile dari /etc/profile.

## B. Edit file profile pengguna
1. Edit file .bash_profile
-   jalankan perintah : nano ~/.bash_profile
-   Tambahkan kata berikut: echo "Profile dari .bash_profile" lalu simpan
2. Edit   file .bash_login
-   Buka file .bash_login dengan menjalankaan perintah : nano ~/.bash_login
- kemudian Tambahkan kalimat  berikut:  echo "Profile dari .bash_login" setelah itu simpan
3. Edit file .profile
-   Buka file .profile dengan menjalan perintah : nano ~/.profile
-   kumudian Tambahkan baris berikut: echo "Profile dari .profile" Simpan dan keluar dari editor.
4. Edit file .bashrc
-    Buka file .bashrc dengan menjalankan perintah: nano ~/.bashrc
- Lalu Tambahkan baris berikut:echo "Profile dari .bashrc" kumudian simpan
  
![VirtualBox_MASTER_13_03_2025_13_41_51](https://github.com/user-attachments/assets/e905daf1-2d95-47f9-ab0e-d3d42af972d2)

5. Verifikasi perubahan:
-   Logout dan login kembali, atau buka terminal baru.
-   Anda akan melihat pesan dari masing-masing file profile yang dieksekusi.
  ![VirtualBox_MASTER_13_03_2025_13_44_00](https://github.com/user-attachments/assets/b20be019-3179-48fb-8b5b-79db33afaf6d)
