<!DOCTYPE html>
<title>STAINU - KPM Jatirejo</title>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dokumentasi KPM STAINU Madiun</title>

        <link rel="shorcut icon" href="logokpm.jpeg" type="image/x-icon"/>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body{
            background-image: url('logokpm.JPEG');
        }
        
        header {
            background: linear-gradient(135deg, hsla(103, 88%, 25%, 0.788) 0%, #008040 100%);
            color: white;
            padding: 30px 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        
        header h1 {
            font-size: 28px;
            margin-bottom: 5px;
        }
        
        header p {
            opacity: 0.9;
        }
        
        .container {
            max-width: 1000px;
            margin: 30px auto;
            padding: 0 20px;
        }
        
        .hari {
            background: white;
            border-radius: 12px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 3px 15px rgba(0,0,0,0.08);
            border-left: 5px solid #008040;
        }
        
        .hari-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
            flex-wrap: wrap;
        }
        
        .hari-header h2 {
            color: #008040;
            font-size: 20px;
        }
        
        .tanggal {
            background: #e8f5e9;
            color: #008040;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: bold;
        }
        
        .kegiatan-desc {
            margin-bottom: 15px;
            text-align: justify;
        }
        
        .media-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }
        
        .media-item img, .media-item video {
            width: 100%;
            border-radius: 8px;
            display: block;
        }
        
        .caption {
            font-size: 13px;
            color: #666;
            margin-top: 8px;
            text-align: center;
        }
        
        .placeholder {
            height: 180px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #999;
            font-size: 14px;
            background: #eee;
            border-radius: 8px;
        }
        
        .statistik {
            background: white;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 25px;
            text-align: center;
            box-shadow: 0 3px 15px rgba(0,0,0,0.08);
        }
        
        .statistik h3 {
            color: #008040;
            margin-bottom: 10px;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            color: #777;
            font-size: 14px;
        }
        
        @media (max-width: 600px) {
            header h1 { font-size: 22px; }
            .hari { padding: 15px; }
        }
    </style>
</head>
<body>
    <header>
        <h1>📍 DOKUMENTASI KPM</h1>
        <h1>DESA JATIREJO</h1>
        <p>[Juli - Agustus 2026] | Kelompok [KPM Jatirejo] | Kampus [STAINU Madiun]</p>
    </header>

    <div class="container">
        
        <div class="statistik">
            <h3>Ringkasan Kegiatan</h3>
            <p>Total Hari: 30 Hari | Sinergi Aswaja & Digitalisasi : Membangun Peradaban Desa yang Religius, Inovativ dan Mandiri</p>
        </div>

        <!-- COPY BLOCK INI UNTUK TIAP HARI -->
        <div class="hari">
            <div class="hari-header">
                <h2>Hari ke-1</h2>
                <span class="tanggal">Senin, 1 Agustus 2026</span>
            </div>
            <div class="kegiatan-desc">
                <strong>Kegiatan:</strong> Observasi Desa & Perkenalan dengan Perangkat Desa Jatirejo
                <br><br>
                <strong>Uraian:</strong> Hari pertama kami melakukan survei lokasi, bertemu dengan Kepala Desa, dan pemetaan potensi desa. Diskusi program kerja yang akan dilaksanakan selama 1 bulan.
            </div>
            <div class="media-grid">
                <div class="media-item">
                    <div class="placeholder"><img src="Sowankades.jpeg" width="200px" height="200"></div>
                    <!-- Ganti dengan: <img src="foto1.jpg" alt="Deskripsi"> -->
                    <div class="caption">Foto: Pertemuan dengan perangkat desa</div>
                </div>
                <div class="media-item">
                    <div class="placeholder">📷 Tempat Gambar 2</div>
                    <!-- Ganti dengan: <img src="foto2.jpg" alt="Deskripsi"> -->
                    <div class="caption">Foto: Observasi lingkungan desa</div>
                </div>
                <div class="media-item">
                    <div class="placeholder">🎥 Tempat Video</div>
                    <!-- Ganti dengan: <video controls src="video1.mp4"></video> -->
                    <div class="caption">Video: Sambutan Kepala Desa</div>
                </div>
            </div>
        </div>
