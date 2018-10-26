# Belajar Membuat PR (Pull Request)

## Apa itu Pull Request?
_Pull Request_ adalah cara untuk berkontribusi pada suatu proyek _open source_. Dengan membuat _pull request_ ke suatu proyek, kita meminta pemilik / pengelola proyek untuk memeriksa perubahan yang telah kita buat pada _source code_ di repo kita dan menggabungkannya pada repo resmi proyek tersebut.

Ikuti langkah-langkah berikut untuk mulai membuat *PR*. Pada tutorial ini, kita akan belajar membuat _pull request_ dari _fork_.

## _Fork_ repositori
_Fork_ repositori ini dengan menekan tombol _fork_ yang ada di kanan atas.

## _Clone_ repositori di lokal komputer
Setelah _fork_ selesai, kemudian _clone_ ke lokal komputer masing-masing untuk membuat perubahan
```
git clone https://github.com/YOUR-GITHUB-USERNAME/GresikFunPR.git
```
## Tambahkan repo utama sebagai git remote "upstream"
Masuk ke folder hasil `clone`. Kemudian masukkan
```
git remote add upstream git://github.com/GresikDev/GresikFunPR.git
```
## Dapatkan perubahan terakhir dari repo utama
```
git pull upstream
```
## Tambahkan nama di _CONTRIBUTOR.md_
Melakukan perubahan adalah wajib untuk membuat *PR*, jadi lakukan perubahan dengan menambahkan nama di berkas *CONTRIBUTOR.md*. Jika sudah _commit_ dan _push_ perubahan yang telah dilakukan.
```
git add CONTRIBUTOR.md
git commit –m 'tambah nama'
git push origin
```
## Membuat PR
Setelah berhasil, sekarang saatnya membuat *PR*. Masuk ke halaman asli repositori yang tadi di _fork_. Kemudian klik _Pull requests_ yang ada diatas menu setelah judul repositori. Setelah masuk ke halaman *PR*, klik "_New pul request_", akan masuk ke halaman _compare changes_. Karena *PR* yang akan dibuat berbasis _fork_ maka, carilah tautan/teks _compare across forks_. Lalu kemudian pilih _branch_ mana yang akan di _merge_. 

Duduk diam dan sabar menanti *PR* untuk disetujui

Selesai.
