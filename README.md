# Belajar Versio Control System
## Menggunakan Github 

### Tutorial Membuat Repository Github

1. Langkah pertama Klik Creat Repository di pojok kiri atas.
! [Gambar1](sstutorial/ss1.png)
2. Lalu Masukan nama repository yang ingin anda buat. Lalu pilih Public dan centang Add a README.md. 
! [Gambar1](sstutorial/ss2.png)
3. Selanjutnya klik CODE lalu pilih HTTPS, link tersebut kita salin untuk di tambahkan di aplikasi Git Bash. Untuk aplikasi Git Bash Bisa kita download di link https://git-scm.com/ .
! [Gambar1](sstutorial/ss3.png)
4. Jika Git Bash sudah terinstal, kita buka aplikasinya
! [Gambar1](sstutorial/ss4.png)
5. Lalu kita masuk kedirectory pc/laptop yang akan kita upload ke github. Disini nama directory saya belajargit, maka perintahnya cd /d/belajargit
! [Gambar1](sstutorial/ss5.png)
6. Setelah masuk directory kita paste link telah kita salin tadi, kita ketikan git clone https://github.com/ImamSolehudin1/BelajarVCS.git. Perintah tersebut berfunsi untuk membaca file README.md yang ada di akun github kita.
! [Gambar1](sstutorial/ss6.png)
7.	Masuk ke repository github kita, disini repository kita Bernama belajarvcs  jadi perintahnya cd belajarvcs/.
! [Gambar1](sstutorial/ss7.png)
8.	Jika sudah masuk ke repository, kita akan mengupload file yang Bernama Daftar_Akun_Github.pdf ke repository github. Ketikan perintah git add Daftar_Akun_Github.pdf
! [Gambar1](sstutorial/ss8.png)
9.	Setelah menambahkan file kita cek dulu statusnya menggunakan perintah git status.
! [Gambar1](sstutorial/ss9.png)
10.	 Ketikan perintah git commit -m “Menambahkan file Daftar_Akun_Github.pdf”. perintah tersebut berfungsi untuk memberi komentar pada setiap pendambahan/perubahan file.
! [Gambar1](sstutorial/ss10.png)
11.	Ketikan perintah git push -u origin main.  Untuk mengirim file ke repository, biasanya jika baru menggunakan github akan disuruh login ke akun github untuk verifikasi pengguna.
! [Gambar1](sstutorial/ss11.png)
12.	Selanjutnya kita akan menampilkan screenshot file yang kita buat pada repository. Kita buka file README.md tersebut menggunakan VS Code(bisa menggunakan software lain). Lalu kita masukan file screenshotnya pada file README.md. contohnya pada gambar dibawah ini 

13. Jika sudah kita simpan Kembali file README.md nya.selanjutnya kita buka Kembali git bash nya untuk menambahkan file screenshot dan menyimpan file README.md yang telah diubah tadi. Pertama kita ketik perintah git add screenshot/pict1.png

14.	Ketikan perintah git status, kita lihat ada perubahan di file README.md. sekarang kita simpan perubahan tersebut.

15.	Cara menyimpannya ketikan git add README.md

16. Lalu kita ketikan perintah git commit -m “perubahan Gambar”

17. Dan untuk Langkah terakhir kita push, ketikan perintah git push -u origin main

18.	 Berikut adalah tampilan yang berada di website Github