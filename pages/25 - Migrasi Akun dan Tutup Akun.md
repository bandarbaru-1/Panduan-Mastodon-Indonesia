# Migrasi Akun dan Tutup Akun
Adakalanya sebuah peladen Mastodon mengumumkan untuk berhenti beroperasi, sedangkan kalian sudah membangun suatu basis pengikut yang cukup lumayan.

Jika terjadi demikian, mungkin kalian bisa berpikir untuk **pindah dan buat akun ke peladen Mastodon lain yang masih aktif dan kembali membangun basis pengikut di sana**. Dan cara ini adalah **cara yang termudah**.

**Ini juga mengapa saya masih merekomendasikan untuk bergabung di peladen utama yang besar, terutama yang langsung dikelola oleh lembaga utama seperti mastodon.social**, karena adanya jaminan keberlangsungan keberadaan peladen oleh lembaga utama tsb.

Peladen yang dikelola oleh komunitas misalnya, pada satu titik jika terjadi kendala (misal kendala teknis, pembiayaan, krisis moderator, dsb.), seringkali mereka memutuskan untuk menutup peladen yang mereka kelola.

Namun ini juga bukan berarti bahwa peladen mastodon.social juga tidak akan mengalami hal yang sama juga di masa mendatang.

Kembali ke pembahasan migrasi akun, tetapi ada cara lain. Alih-alih membangun basis pengikut lagi di peladen baru, mengapa tidak basis pengikut kalian yang sudah ada juga ikut pindah ke peladen baru?

Mastodon memiliki fitur migrasi akun untuk memindahkan akun kalian dari peladen sebelumnya ke peladen yang baru yang kalian telah pilih.

Mari kita coba buat akun di peladen lain. Untuk contoh di sini, saya memilih peladen **mstdn.party**, dengan nama pengguna `@bandarbaru01@mstdn.party`.

<div align="center">
  <div>
    <img src="../assets/25pic-01.jpg" width="30%" />
  </div>
</div>

Di peladen mstdn.party, kita ke *Preferences* -> klik *Account* -> scroll ke bawah, ke bagian *Moving from a different account*, klik ***create an account alias***.

<div align="center">
  <div>
    <img src="../assets/25pic-02.jpg" width="30%" />
    <img src="../assets/25pic-03.jpg" width="30%" />
    <img src="../assets/25pic-04.jpg" width="30%" />
    <img src="../assets/25pic-05.jpg" width="30%" />
    <img src="../assets/25pic-06.jpg" width="30%" />
  </div>
</div>

Dari sini, kita masukkan nama pengguna lama kita, yakni contoh di sini adalah: `@bandarbaru01@mastodon.social`.

<div align="center">
  <div>
    <img src="../assets/25pic-07.jpg" width="30%" />
  </div>
</div>

Setelah berhasil, sekarang kita kembali ke halaman akun kita di peladen mastodon.social.

<div align="center">
  <div>
    <img src="../assets/25pic-08.jpg" width="30%" />
  </div>
</div>

Di peladen mastodon.social, kita ke *Preferences* ->klik *Account* -> scroll ke bawah, ke bagian *Pindah ke akun berbeda (Move to  a different account)*, klik ***mengaturnya di sini (configure it here)***.

<div align="center">
  <div>
    <img src="../assets/25pic-09.jpg" width="30%" />
    <img src="../assets/25pic-10.jpg" width="30%" />
    <img src="../assets/25pic-11.jpg" width="30%" />
    <img src="../assets/25pic-12.jpg" width="30%" />
    <img src="../assets/25pic-13.jpg" width="30%" />
  </div>
</div>

Di sini, kita bisa masukkan alamat nama pengguna baru kita di peladen yang baru kita pilih, serta kata sandi akun kita di peladen yang lama. Klik ***Pindahkan pengikut (Move followers)*** untuk memulai proses.

<div align="center">
  <div>
    <img src="../assets/25pic-14.jpg" width="30%" />
  </div>
</div>

Proses migrasi akun selesai. Sekarang pengikut kita secara otomatis akan dipindahkan untuk mengikuti akun kita yang baru di peladen yang baru.

<div align="center">
  <div>
    <img src="../assets/25pic-15.jpg" width="30%" />
  </div>
</div>

Jika seseorang mengakses akun kita di peladen yang lama, maka akan memunculkan pesan bahwa akun tersebut sudah pindah ke akun yang baru.

<div align="center">
  <div>
    <img src="../assets/25pic-16.jpg" width="30%" />
  </div>
</div>

Setelah kita memindahkan akun, perlu diperhatikan bahwa ada grace period selama 30 hari. Yakni, kita tidak bisa melakukan proses pemindahan akun lagi hingga 30 hari.

<div align="center">
  <div>
    <img src="../assets/25pic-17.jpg" width="30%" />
  </div>
</div>

Sebagian data, seperti:
- daftar orang yang kita ikuti
- postingan yang kita markahi
- sebuah daftar yang berisi akun-akun
- daftar orang yang kita bisukan
- daftar orang yang kita blokir
- peladen yang kita blokir

ini tidak dipindahkan secara otomatis. Untuk itu kalian bisa melakukan proses impor-ekspor.

Baik, setelah kita memindahkan akun kita, di menu pengaturan ->  klik *Impor dan Ekspor (Import and Export)*

<div align="center">
  <div>
    <img src="../assets/25pic-18.jpg" width="30%" />
  </div>
</div>

Di sini, kita bisa menngunduh file CSV dari beberapa bagian data yang akan kita pindahkan ke peladen yang baru.

<div align="center">
  <div>
    <img src="../assets/25pic-19.jpg" width="30%" />
  </div>
</div>

Setelah kita mengunduh file CSV tersebut, kita ke peladen yang baru, kita ke pengaturan -> klik *Import and Export* -> klik *Import*

<div align="center">
  <div>
    <img src="../assets/25pic-20.jpg" width="30%" />
  </div>
</div>

Di sini, kita bisa memilih file CSV yang akan kita unggah, lalu pilih data apa yang akan kita pindahkan ke akun baru, lalu pilih apakah datanya di-*merge* (digabungkan) atau di-*overwrite* (diganti, disesuaikan dengan arsip data tersebut). Klik ***Upload*** untuk memulai prosesnya.

<div align="center">
  <div>
    <img src="../assets/25pic-21.jpg" width="30%" />
  </div>
</div>

Proses migrasi akun selesai, dan sekarang kita sudah berada di akun yang baru.

## Menghapus Akun

Apakah kalian berpikir untuk hapus akun? Mungkin kalian merasa ada defiensi dan mempertimbangkan hal-hal lain untuk meninggalkan dan berhenti menggunakan Mastodon. Daripada meninggalkan Mastodon dengan masih meninggalkan postingan atau gambar yang dapat menjadi masalah privasi bagi kalian di masa mendatang, lebih baik kalian menghapus akun sebelum meninggalkan dan berhenti menggunakan Mastodon.

Baik, di beranda, klik panel menu -> klik *Pengaturan (Preferences)* -> di halaman berikutnya, klik panel menu -> klik *Akun (Account)* -> scroll ke bawah, di bagian *Hapus akun (Delete account)*, klik ***memproses ini (proceed here)***.

<div align="center">
  <div>
    <img src="../assets/25pic-22.jpg" style="display:inline-block; width:30%; margin:15px;"/>
    <img src="../assets/25pic-23.jpg" style="display:inline-block; width:30%; margin:15px;"/>
    <img src="../assets/25pic-24.jpg" style="display:inline-block; width:30%; margin:15px;"/>
    <img src="../assets/25pic-25.jpg" style="display:inline-block; width:30%; margin:15px;"/>
    <img src="../assets/25pic-26.jpg" style="display:inline-block; width:30%; margin:15px;"/>
  </div>
</div>


Perhatikan catatannya: **akun yang telah dihapus tidak dapat diaktifkan kembali**, **nama pengguna yang telah dihapus tidak dapat lagi digunakan ketika kalian mencoba mendaftar kembali**, seluruh data kalian di Mastodon terhapus, namun data kalian mungkin masih tersimpan di peladen lain (terutama jika peladen itu menggunakan sistem yang berbeda dari Mastodon).

<div align="center">
  <div>
    <img src="../assets/25pic-27.jpg" width="30%" />
  </div>
</div>

Jika sudah, masukkan kata sandi, dan klik ***Hapus akun (Delete account)***.

Selesai. Semoga bisa bertemu lagi di lain waktu dan di lain kesempatan.





