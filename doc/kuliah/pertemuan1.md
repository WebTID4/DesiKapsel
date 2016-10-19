<h2 align="center">TUTORIAL GITHUB</h2> 
<p align="justify">
<strong>Membuat SSH KEYS</strong>
<br>
1. Buka github masuk ke setting, buka sub <strong><i>ssh and gpg keys</i></strong>.
<br>
2. Buka tab baru <strong><i>generating ssh keys</i></strong> dan <strong><i>new ssh keys</i></strong>.
<br>
3. Kemudian klik kanan dimana saja, => <strong>Git bash here</strong>.
<br>
4. Buka generating a new ssh key and ... lalu salin perintah
	<strong>ssh-keygen -t rsa -b 4096 -C "<i>your_email@example.com</i>"</strong>
	ganti email diatas dengan alamat email github anda.
<br>
5. Kemudian enter terus masukkan perintah
<strong>cat ~/.ssh/id_rsa.pub</strong>
<br>
6. Setelah itu, salin hasilnya ke kolom key lalu beri judul dan tekan tombol add ssh key.
<br>
<br>
Membuat Folder Kerja yang bernama <strong>Kapita Selekta</strong>
<br>
1. Masukkan perintah <strong>git init</strong> untuk menginisialisasi.
<br>
2. Lalu masukkan perintah <strong>git remote add origin (link repository by ssh)</strong> (pada repository di github)
<br>
3. Masukkan <strong>git pull origin master</strong> untuk mengunduh file-file yang ada pada repository.

<br>4. Di dalam folder Kapita Selekta buat folder bernama doc.
   Kemudian di dalam folder doc buat kembali folder yang bernama kuliah.
   Selanjutnya buat file dengan nama pertemuan1.md
   5. Ketikkan <status>git status</status> untuk mengetahui perubahan yang ada.
<br>
6. Kemudian ketikkan <strong>git add doc/</strong>
<br>
7. Ketikkan kembali <strong>git status</strong> untuk mengetahui folder yang ada di dalam folder doc.
<br>
8. Kemudian ketikkan <strong>git add doc/kuliah/pertemuan1.md</strong>.
<br>
9. Laku ketikkan <strong>git status</strong> (jika muncul:On branch master Changes to be committed) langsung ketikkan perintah selanjutnya.
<br>
10. Lalu <strong>git commit -m "menambahkan pertemuan1"</strong> -m disini untuk menambahkan message.
<br>
11.Kemudian<strong>git status</strong> kembali, (jika muncul:nothing to commit, working tree clean) langsung ketikkan perintah di bawah ini.
<br>
12.Terakhir, ketikkan <strong>git push origin master</strong> untuk mensinkronisasi file yang sudah ditambahkan.
<br>
<br>
<strong>Create Organization</strong>
<br>
1. Klik tanda plus=> <i><strong>Create Organization</strong></i>
<br>
2. Masukan Judul Organisasi dan email kemudian enter.
<br>
3. Masukkan anggota kelompok beserta koordinator proyek 2.
<br>
4. Untuk merubah profil dari organization masuk ke setting.
<br>
5. Anggota yang di invite harus terlebih dahulu menyetujuinya.
</p>