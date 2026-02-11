# AGDAL
SISWA SMKN I RANGKASBITUNG 
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Online - [AGDAL]</title>
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
            <h1>[AGDAL]</h1>
            <div class="contact-info">
                <span>📧 [agdalagdal01@gmail.com]</span>
                <span>📱 [089516397991]</span>
                <span>📍 [Kota, Rangkasbitung]</span>
                <span>🔗 <a href="[link LinkedIn/GitHub]">Profil Online</a></span>
            </div>
        </header>

        <!-- Tentang Saya -->
        <section>
            <h2>TENTANG SAYA</h2>
            <p>
                [Siswa SMKN 1 RANGKASBITUNG jurusan Teknik Komputer dan Jaringan yang memiliki minat di bidang IT dan jaringan komputer. Terbiasa bekerja dengan rapi, disiplin, dan bertanggung jawab.]
            </p>
        </section>

        <!-- Pengalaman Kerja -->
        <section>
            <h2>PENGALAMAN KERJA</h2>
            <div class="item">
                <h3>[PKL dinas komunikasi informatika statistik dan persandian provinsi banten]</h3>
                <div class="sub-info">[
                <p>
                    - [
Mendukung kegiatan operasional lapangan.]<br>
                    - [Konfigurasi jaringan dasar menggunakan Cisco Packet Tracer]
                </p>
            </div>
            <div class="item">
            
                </p>
            </div>
        </section>

        <!-- Pendidikan -->
        <section>
            <h2>PENDIDIKAN</h2>
            <div class="item">
                <h3>[SMKN1 RANGKASBITUNG]</h3>
                <div class="sub-info">[TEKNIK KOMPUTER JARINGAN] | [2023 -2026] | [IPK/Nilai]</div>
                <p>[Ringkasan prestasi jika ada, misal: Juara lomba teknologi, organisasi yang diikuti]</p>
            </div>
        </section>

        <!-- kemampuan -->
        <section>
            <h2>kemampuan</h2>
            <div class="skills-list">
                <span>[Dasar-dasar Jaringan]</span>
                <span>[Dasar HTML & CSS]</span>
                <span>[Microsoft Office]</span>
                <span>[Administrasi]</span>
            </div>
        </section>
    </div>
</body>
</html>
