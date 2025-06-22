<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BEM FIS UM</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #f8f9fa;
        }

        header {
            background: linear-gradient(to right, #026873, #03a9f4);
            color: white;
            padding: 30px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
        }

        .logo span {
            color: #ffde59;
        }

        .header-img {
            max-width: 200px;
            border-radius: 10px;
        }

        nav {
            background-color: #212121;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav a {
            padding: 14px 20px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #03a9f4;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h1 {
            color: #026873;
        }

        .highlight {
            color: #03a9f4;
            font-weight: bold;
        }

        footer {
            background-color: #026873;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        .icon {
            margin-right: 5px;
        }
    </style>
</head>
<body>

    <header>
        <div>
            <div class="logo">BEM <span>FIS UM</span></div>
            <p>Fakultas Ilmu Sosial - Universitas Negeri Malang</p>
        </div>
        <img class="header-img" src="https://via.placeholder.com/200x150.png?text=LOGO+BEM" alt="Logo BEM FIS UM">
    </header>

    <nav>
        <a href="#">BERANDA</a>
        <a href="#">PROFIL</a>
        <a href="#">BERITA</a>
        <a href="#">ZEFIR (MAJALAH)</a>
        <a href="#">ARTIKEL</a>
        <a href="#">MEDPART</a>
        <a href="#">KONTAK</a>
    </nav>

    <section>
        <h1>Selamat Datang di Website Resmi <span class="highlight">BEM FIS UM</span></h1>
        <p>Badan Eksekutif Mahasiswa Fakultas Ilmu Sosial Universitas Negeri Malang adalah lembaga eksekutif mahasiswa yang berperan sebagai representasi dan wadah aspirasi seluruh mahasiswa FIS UM.</p>

        <h2>Informasi & Menu Utama</h2>
        <ul>
            <li><strong>Profil:</strong> Sejarah, Visi Misi, Struktur Organisasi</li>
            <li><strong>Berita:</strong> Update kegiatan, agenda, dan pengumuman terbaru</li>
            <li><strong>Majalah ZEFIR:</strong> Wadah publikasi kreatif mahasiswa</li>
            <li><strong>Artikel:</strong> Press Release, Kajian Isu, Surat Edaran</li>
            <li><strong>Medpart:</strong> Media Partner dan pengajuan kolaborasi</li>
        </ul>
    </section>

    <footer>
        &copy; 2025 BEM FIS UM. All rights reserved.
    </footer>

</body>
</html>
