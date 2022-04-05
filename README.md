<h1>Step by Step Tutorial Cara Memasang Express.</h1>

1.  Kita download & Install Node.js dulu sebelum memasang npm install package.

2.  Ketika kita sudah melakukan install Node.js di laptop kita.<br>
    (Oh iya, jangan lupa klik centang yang ada keterangan 'pop up' untuk wajib install node.js.<br>
    Jika kita tidak centang 'pop up' maka tidak wajib install karena npm tidak bisa panggilan<br>
    kode perintah di terminal cmd kita.)

3.  Setelah itu, kita tekan klik logo 'WINDOWS'+ 'R' untuk memanggil kode 'cmd' secara langsung<br>
    atau dimana yang berada logo 'SEARCH' untuk melakukan cari terminal 'Command'/'cmd' di laptop kita.<br>

4.  Selanjutnya, kita melakukan ketik perintah kode:<br>
    'npm install node'<br>
    lalu tekan 'ENTER'. (TEMAN-TEMAN TIDAK PERLU KETIK '' (TANDA PETIK SATU) INGAT YA!!!)

5.  Kemudian agak beberapa menit, kita ketik perintah kode:<br>
    'node -v'<br>
    di Command/cmd/bash/powershell terus tekan 'ENTER' yang telah muncul package version kita.

6.  Lalu disarankan kita pakai Visual Studio Code untuk melakukan buat terminal baru cmd/bash/powershell dll<br>
    dengan perintah kode 'npm install "package"'. Tujuan kita kebutuhan program senjata untuk membuat<br>
    website mini project/portofolio.

7.  Kemudian lalu kita membuat direktori 'list-app' dan file 'app.js' di Visual Studio atau boleh<br>
    perintah kode:<br>
    'mkdir list-app'<br>
    dan<br>
    'touch app.js'<br>
    di terminal cmd/bash/powershell kita.

8.  Lalu kita mengecek file package.json yang ada nama variabel dengan version sudah diinstall dan<br>
    ketik perintah kode:<br>
    'npm init --yes' -> untuk mengecek file package.json di terminal nya.<br>
    Lalu kita mengecek file package.json yang telah muncul variabel nya.

9.  Selanjutnya, kita sudah membuat direktori list-app, file app.js dan dibuat npm lagi untuk melakukan perintah kode:<br>
    'npm install express ejs'<br>
    sehingga selesai dan jangan lupa ditambahkan direktori perintah kode:<br>
    'mkdir views' -> untuk membuat nama folder dan<br>
    'touch hello.ejs' -> untuk membuat nama file di dalam direktori views.

10. lalu kita mengecek file hello.ejs isi script kosong ya kan.<br>
    Jadi kita copy-paste untuk menampilkan script hello.ejs di halaman.<br>
    <h1>Hello World</h1>

11. Kemudian, kita cek file app.js isi kosong juga. Jadi kita copy-paste untuk menaruh script di file app.js.<br>
    const express = require('express');<br>

    const app = express();<br>

    app.get('/', (req, res) => {<br>
    res.render('hello.ejs');<br>
    });<br>

    app.listen(3000);

12. Ketika kita sudah meng-copas script di file app.js lalu kita ketik perintah kode server 'node app.js' di terminal<br>
    bash melalui Visual Studio Code.

13. Jika kita ketik 'localhost:3000' melalui browser untuk "Hello World" ditampilkan sebagai berikut maka kita berhasil<br>
    menyelesaikan langkah ini.

14. Kamu bisa me-restart server dengan mematikan, lalu memulai server lagi.<br>
    Untuk menerapkan perubahan dalam file, pertama-tama hentikan server dengan<br>
    'Ctrl + C'<br>
    lalu restart server dengan<br>
    'node app.js'.

15. Kita sudah berhasil menampilkan halaman tapi setiap ada perubahan di situ, kita harus me-restart server untuk menerapkannya.<br>
    Agar tidak me-restart secara manual, mari kita ketik kode perintah posisi dalam direktori list-app dengan<br>
    'npm install nodemon'<br>
    di terminal cmd/bash/powershell melalui VS Code.

16. Berikutnya, mari kita coba memulai server menggunakan nodemon. Untuk menjalankan nodemon, jalankan command berikut.<br>
    (Kamu bisa salin lalu tempelkan command ini dengan Ctrl + V atau Ctrl + Shift + V).<br>
    version windows:<br>
    .\\node_modules\\.bin\\nodemon app.js

    version macOS:<br>
    ./node_modules/.bin/nodemon app.js

    Jika layar ditampilkan berikut maka kamu berhasil sudah mulai server menggunakan nodemon.

17. Menulis .\\node_modules\\.bin\\nodemon app.js setiap kali ingin menjalankan server terkesan agak repot.<br>
    Ketika kita bisa melihat tulisan file package.json yang telah muncul variabel.<br>
    "scripts": {<br>
    "test": "echo \"Error: no test specified\" && exit 1"<br>
    }

18. Di sini kita akan menghapus tugas bernama "test" yang sudah ditulis dalam scripts, dan sebagai gantinya
    kita akan mendaftarkan tugas bernama start.<br>
    Hapus baris `"test": 〜 dan masukkan command berikut.<br>
    version windows:<br>
    "script": {<br>
    "start": ".\\node_modules\\.bin\\nodemon app.js"<br>
    }

    version macOS:<br>
    "script": {<br>
    "start": "./node_modules/.bin/nodemon app.js"<br>
    }

19. Mari jalankan tugas "start" yang baru kita daftarkan. Syntax yang digunakan untuk ini adalah npm run 'taskname'.<br>
    Jalankan command berikut dan periksa apakah kamu bisa memulai server menggunakan nodemon di terminal powershell melalui VS Code.<br>

20. Sekarang kamu bisa memulai server dengan cepat!<br>

<h1>Selamat mencoba teman-teman ya~</h1>

Jika ada kamu bingung poin-poin maka silahkan ditanya ke dm ig @tara_id97.exe<br>

<h1>Coming soon 'public static' dengan Express dan 'npm install mysql' ya~</h1>
