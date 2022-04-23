# uploading-project-using-termux
tutorial uploading files using termux

langkah pertama yang harus dilakukan adalah menjalankan aplikasi termux terlebih dahulu

ketika sudah didalam aplikasi termux, langkah selanjutnya adalah menginstall git lebih dahulu

```bash
pkg install git
```

ketika sudah menginstall git, langkah selanjutnya adalah menuju lokasi file yang ingin diupload

```bash
cd lokasi-files
```

ketika sudah berada didalam folder tujuan, lakukan langkah dibawah ini

```bash 
git init
```

jika kalian ingin mengupload 1 file saja, maka lakukan cara dibawah ini

```bash
git add nama-file
```

jika kalian ingin mengupload semua file yang ada didalam folder tersebut, lakukan cara dibawah ini

```bash
git add .
```

setelah itu, lakukan commit seperti dibawah ini

```bash
git commit -m "isi sesuka kalian"
```

setelah itu, lakukan git branch dengan nama branch default milik github kalian

```bash
git branch -M nama-branch-kalian
```

default branch github adalah : **master**

lalu, lakukan remote dengan url repo project kalian

```bash
git remote add origin https://github.com/username-github-kalian/nama-repository-project-kalian.git
```

lalu, push file kalian

```bash
git push -u origin nama-branch-repo-kalian
```

setelah itu, kalian akan disuruh memasukkan sebuah username github kalian. 
kalian tinggal isi dengan username github kalian.

setelah itu, kalian akan disuruh memasukkan sebuah password github kalian.

### catatan

ketika kalian disuruh untuk memasukkan sebuah password github kalian, kalian harus memasukkan code **personal access token** github milik kalian.

jika kalian belum punya sebuah **personal access token** github milik kalian sendiri. kalian bisa membuatnya terlebih dahulu di bagian

**Settings** -> **Developer settings** -> **Personal access tokens** -> lalu buat access token.

kalian akan disuruh menulis note / judul access token milik kalian sesuai keinginan kalian

jika kalian menemukan checkbox bertuliskan **repo**, kalian bisa centang checkbox tersebut dan kalian bisa menentukan waktu / expired token milik kalian.

setelah semua itu selesai, kalian akan mendapatkan **personal access token** milik kalian sendiri dan disarankan dari pihak **github** untuk menyalin token tersebut. karena, kalian hanya bisa melihat token itu satu kali di **github**.

kalian bisa menyimpan token tersebut ke aplikasi catatan dengan diberikan sebuah password yang aman sebelum menggunakan atau melihat token itu lagi.

tinggal kalian **paste** token tersebut di aplikasi termux. setelah itu files kalian akan sukses terupload

semoga kalian paham dengan penjelasan saya ini. jika kalian masih kebingungan dengan penjelasan saya, silahkan kirimkan keluhan anda ke platform saya di bawah ini

* ....
> ... **   **
