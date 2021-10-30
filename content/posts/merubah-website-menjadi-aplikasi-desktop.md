---
title: Merubah Website menjadi aplikasi Desktop
date: 2020-10-10T09:57:25.013Z
description: Cara Merubah Website menjadi aplikasi Desktop
featured_image: /img/screenshot-from-2020-10-08-17-27-01.png
youtube_embed: 9mjJDaoZ6g8
---
Bagaimana caranya merubah website menjadi aplikasi desktop?.

Caranya cukup mudah, bahkan dengan waktu kurang dari 10 menit. yang perlu kita persiapkan adalah sebagai berikut:

1. NodeJS
2. ElectronJS
3. Nativefier

Pertama install terlebih dahulu [NodeJS](https://nodejs.org). ketika menginstal NodeJS untuk OS Windows akan otomatis terinstall NPM (Node Package Manager), untuk linuk mungkin harus install terpisah.

Setelah NodeJS sudah terinstall lanjut untuk menginstall [ElectronJS](https://www.electronjs.org/) dengan cara menjalankan perintah "npm i -g electron" di terminal atau CMD

Setelah Electron sudah terinstall yang terakhir install [Nativefier](https://github.com/jiahaog/nativefier) dengan cara menjalankan perintah "npm i -g nativefier" di terminal atau CMD

Proses instalasi toolsnya sudah selesai, saatnya kita membuat aplikasi desktop dari website. saya akan menjadikan website saya menjadi aplikasi desktop dengan melakukan perintah `nativefier --name AgikWeb "https://www.agiksetiawan.com"` dimana `AgikWeb adalah nama Folder/Aplikasi yang akan kita buat`