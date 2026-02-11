# AGDAL-
SISWA SMKN I RANGKASBITUNG 
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Online - [Nama Kamu]</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f0f2f5;
            padding: 20px;
        }

        .cv-container {
            max-width: 900px;
            margin: 0 auto;
            background-color: white;
            padding: 30px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 20px;
        }

        header h1 {
            color: #2c3e50;
            font-size: 2.2rem;
        }

        header p {
            color: #7f8c8d;
            font-size: 1.1rem;
            margin-top: 5px;
        }

        .contact-info {
            margin-top: 10px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            font-size: 0.9rem;
        }

        .contact-info a {
            color: #3498db;
            text-decoration: none;
        }

        section {
            margin-bottom: 25px;
        }

        section h2 {
            color: #2c3e50;
            font-size: 1.5rem;
            margin-bottom: 15px;
            border-left: 4px solid #3498db;
            padding-left: 10px;
        }

        .item {
            margin-bottom: 15px;
        }

        .item h3 {
            color: #34495e;
            font-size: 1.2rem;
        }

        .item .sub-info {
            color: #7f8c8d;
            font-size: 0.9rem;
            margin: 3px 0;
        }

        .item p {
            font-size: 1rem;
            line-height: 1.5;
        }

        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skills-list span {
            background-color: #ecf0f1;
            padding: 5px 10px;
            border-radius: 5px;
            color: #2c3e50;
        }

        /* Responsif untuk hp */
        @media (max-width: 600px) {
            .cv-container {
                padding: 20px;
            }

            header h1 {
                font-size: 1.8rem;
            }

            .contact-info {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <!-- Header -->
        <header>
            <h1>[NAMA LENGKAP KAMU]</h1>
            <p>[JABATAN YANG DIINGINKAN, MISAL: WEB DEVELOPER]</p>
            <div class="contact-info">
                <span>📧 [email@contoh.com]</span>
                <span>📱 [Nomor HP (tanpa detail privasi)]</span>
                <span>📍 [Kota, Indonesia]</span>
                <span>🔗 <a href="[link LinkedIn/GitHub]">Profil Online</a></span>
            </div>
        </header>

        <!-- Tentang Saya -->
        <section>
            <h2>TENTANG SAYA</h2>
            <p>
                [Tuliskan ringkasan diri singkat, pengalaman utama, dan tujuan karir. Misal: Pengembang web dengan pengalaman 2 tahun dalam membuat situs responsif menggunakan HTML, CSS, dan JavaScript. Berkomitmen untuk menghasilkan karya berkualitas tinggi dan mendukung pertumbuhan perusahaan.]
            </p>
        </section>

        <!-- Pengalaman Kerja -->
        <section>
            <h2>PENGALAMAN KERJA</h2>
            <div class="item">
                <h3>[Nama Perusahaan]</h3>
                <div class="sub-info">[Jabatan] | [Bulan Tahun - Bulan Tahun]</div>
                <p>
                    - [Deskripsi tugas/hasil kerja 1]<br>
                    - [Deskripsi tugas/hasil kerja 2]
                </p>
            </div>
            <div class="item">
                <h3>[Nama Perusahaan Lain]</h3>
                <div class="sub-info">[Jabatan] | [Bulan Tahun - Bulan Tahun]</div>
                <p>
                    - [Deskripsi tugas/hasil kerja 1]<br>
                    - [Deskripsi tugas/hasil kerja 2]
                </p>
            </div>
        </section>

        <!-- Pendidikan -->
        <section>
            <h2>PENDIDIKAN</h2>
            <div class="item">
                <h3>[Nama Universitas/Sekolah]</h3>
                <div class="sub-info">[Jurusan] | [Tahun Masuk - Tahun Lulus] | [IPK/Nilai]</div>
                <p>[Ringkasan prestasi jika ada, misal: Juara lomba teknologi, organisasi yang diikuti]</p>
            </div>
        </section>

        <!-- Keterampilan -->
        <section>
            <h2>KETERAMPILAN</h2>
            <div class="skills-list">
                <span>[Keterampilan 1, misal: HTML]</span>
                <span>[Keterampilan 2, misal: CSS]</span>
                <span>[Keterampilan 3, misal: JavaScript]</span>
                <span>[Keterampilan 4, misal: Bootstrap]</span>
                <span>[Keterampilan 5, misal: Git]</span>
            </div>
        </section>
    </div>
</body>
</html>
