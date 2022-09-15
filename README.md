<div align = "center">
  <h1> CATETAN LINUX UBUNTU </h1>
</div>

<br><br>

## PENJELASAN SINGKAT TENTANG UBUNTU

Ubuntu merupakan salah satu distribusi Linux yang berbasis Debian dan didistribusikan sebagai perangkat lunak bebas. Ubuntu ditawarkan dalam tiga edisi resmi: Ubuntu Desktop untuk komputer pribadi, Ubuntu Server untuk server dan komputasi awan, dan Ubuntu Core untuk "Internet untuk Segala", perangkat kecil dan robot. Untuk lebih detail [Disini](https://id.wikipedia.org/wiki/Ubuntu)

<br><br>

## CARA DOWNLOAD FLUTTER DI UBUNTU!

download flutter make snap. paan snap? Snap merupakan manajer paket yang bersifat universal sama seperti flatpak, artinya ia dapat digunakan dipelbagai distribusi Linux. Hal ini tidak seperti manajer paket linux lain seperti apt atau pacman yang memang hanya diperuntukkan untuk distribusi linux tertentu.
[sumber](https://kopiding.in/mengenal-snap/)

Ubuntu versi 16.04 LTS (Xenial Xerus) sudah keinstall snap 

kalo mau ngecek snap langsung tinggal ketik 
```snap```
kalo hasilnya kayak gini
```
The snap command lets you install, configure, refresh and remove snaps.
Snaps are packages that work across many different Linux distributions,
enabling secure delivery and operation of the latest apps and utilities.

Usage: snap <command> [<options>...]

Commonly used commands can be classified as follows:

         Basics: find, info, install, remove, list
        ...more: refresh, revert, switch, disable, enable, create-cohort
        History: changes, tasks, abort, watch
        Daemons: services, start, stop, restart, logs
    Permissions: connections, interface, connect, disconnect
  Configuration: get, set, unset, wait
    App Aliases: alias, aliases, unalias, prefer
        Account: login, logout, whoami
      Snapshots: saved, save, check-snapshot, restore, forget
         Device: model, reboot, recovery
      ... Other: warnings, okay, known, ack, version
    Development: download, pack, run, try

For more information about a command, run 'snap help <command>'.
For a short summary of all commands, run 'snap help --all'.

```
maka sudah keinstall

#### cara cek versi ubuntu di terminal 
```lsb_release -a```
```No LSB modules are available.
Distributor ID:	Ubuntu
Description:	Ubuntu 20.04.5 LTS
Release:	20.04
Codename:	focal
```

<br><br>

## CARA CEK TASK MANAGER DI TERMINAL

tinggal buka aplikasi "System Monitor"

![Screenshot from 2022-09-13 23-01-29](https://user-images.githubusercontent.com/92344349/189950627-108034ac-c354-4c64-a810-c82351b122bb.png)

<br><br>

## Software Bawaan Linux

### Rythmbox

Rhythmbox adalah aplikasi pemutar musik (atau audio) yang dapat berjalan di lingkungan desktop GNOME. Di Ubuntu, Debian, dan Linux Mint, Rhythmbox menjadi aplikasi pemutar musik bawaan. Penjelasan lengkap [Disini](https://www.breedie.com/rhythmbox-aplikasi-ubuntu/)


![Screenshot from 2022-09-13 23-03-22](https://user-images.githubusercontent.com/92344349/189951261-26c50801-eae0-42e0-a982-4d26d9095a14.png)

### Ubuntu Software

Intinya ini buat download aplikasi di ubuntu gitu aja se

![Screenshot from 2022-09-13 23-08-02](https://user-images.githubusercontent.com/92344349/189952079-14665757-d1c9-46bd-980c-58d1b03813ff.png)

### thunderbird mail

![Screenshot from 2022-09-13 23-37-31](https://user-images.githubusercontent.com/92344349/189958054-be2feeed-7111-4e1f-921d-152f2752eae5.png)

Thunderbird adalah aplikasi mail client (MUA – Mail User Agent) yang fungsinya sama dengan Outlook Express, Eudora Mail, Evolution, Sylpheed, dan sejenisnya. Thunderbird ini adalah salah satu produk turunan dari Mozilla. Pada awalnya Mozilla selalu mengemas aplikasinya dengan Browser dan Mail Client.
Pengertian Email client adalah software yang digunakan untuk organisasi email, baik untuk akun email berbayar maupun yang gratis. Syaratnya, harus ada akun POP3-nya. Email Client biasa disebut juga sebagai Oulook Express.
Email client ini sangat sering digunakan sebab ia sudah tersedia langsung dalam Windows. Konfigurasi dan penggunaannya pun cukup mudah, cukup lewat control panel atau Internet Explorer. Bisa dibilang Outlook Express ini adalah format standar e-mail client. File extension-nya adalah EML. Dilengkapi dengan menu export dan import membuatnya mudah untuk dipindahkan ke email client lainnya.Namun, jika digunakan untuk urusan bisnis, Outlook Express ini dirasa kurang sekali. Ia tidak terintegrasi dengan software-software lain seperti messenger contohnya Skype, pdf reader and creator seperti Nitro PDF maupun antivirus seperti AVG Error handlingnya-pun kadang msih suka naik turun, utamanya jika berurusan dengan delivery status message. Jika berpindah sistem operasi seperti Linux, harus di-convert dulu.

Sumber: 

[Disini](https://lovelyristin.com/perbedaan-thunderbird-dan-gmail)

[Disini](https://faqdesk.net/id/klien-email-mana-yang-lebih-baik-mozilla-thunderbird-atau-microsoft-outlook)

<br><br>

## INSTALASI SOFTWARE

### VISUAL STUDIO CODE

Pertama masuk link [Disini](https://code.visualstudio.com/)

![Screenshot from 2022-09-13 23-45-39](https://user-images.githubusercontent.com/92344349/189959828-9d6784d4-4dc8-4e60-a05c-bc65c0faace6.png)

Terus klik yang ```.deb``` udh gitu aja langsung keinstall

kalo sekarang mau nginstall gampang tinggal klik 2 kali, nanti muncul windows baru terus bisa langsung install.

tapi kalo mau make cara lain make terminal juga bisa. kayak gini pertama masuk ke direktori filenya dulu. terus abis itu dpkg filenya dengan cara mengertik

```sudo dpkg -i namaFileYangDiDownload.deb```

```dpkg``` apaan? 

dpkg (debian package manager) : adalah dasar manajemen paket dari sistem operasi debian dan merupakan program dasar untuk menginstal dan memanipulasi paket biner debian dengan ekstensi file “.deb“). lebih detail [Disini](https://glosarium.org/arti-dpkg-di-komputer/)

abis itu kita disuruh masukin passwordnya karena kita make file root alias sudo

terus sekarang udah keinstal ya masehh
