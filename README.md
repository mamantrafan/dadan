<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Website Sederhana</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('Foto latar Web.jpg');
            background-position: center center;
            background-size: cover;
            color: white;
            font-family: Arial, sans-serif;
        }
        .header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        .main {
            padding: 10px;
            color: rgb(255, 255, 255);
        }
        .footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>SMK NEGERI 1 PANGKALAN KERINCI</h1>
    </div>
    <div class="main">
        <h2>Selamat Datang</h2>
        <p>Selamat Datang di Website Kurikulm SMK Negeri 1 Pangkalan Kerinci untuk Absend Guru berikut fitur yang digunakan :</p>
        <h3>Fitur</h3>
        <ul>
            <li><button onclick="absendGuru()">Absend Guru</button></li>
            <li><button onclick="izinGuru()">Izin Guru</button></li>
        </ul>
           </div>
    <div class="footer">
        <p>Copyright © 2024 made by Aufa Cahyo Ramadhan, S.Pd</p>
    </div>

    <script>
        function absendGuru() {
            // Mengarahkan pengguna ke halaman lain
            location.href = 'APK ABSEN.html';
        }

        function izinGuru() {
            // Mengarahkan pengguna ke halaman lain
            location.href = 'izin-guru.html';
        }
    </script>
</body>
</html>
