<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil CSO - Ega Prasetyo</title>
    <style>
        /* Reset CSS */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 50px auto;
            padding: 0 20px;
        }
        
        .profile-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            display: flex;
            flex-direction: column;
        }
        
        .profile-header {
            background: linear-gradient(135deg, #2c3e50, #34495e);
            color: white;
            padding: 40px;
            text-align: center;
            position: relative;
        }
        
        .profile-header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .profile-header .position {
            font-size: 1.2rem;
            color: #ecf0f1;
            font-weight: 300;
            margin-bottom: 20px;
        }
        
        .profile-badge {
            position: absolute;
            top: 20px;
            right: 20px;
            background: #e74c3c;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
        }
        
        .profile-content {
            display: flex;
            flex-wrap: wrap;
        }
        
        .profile-about, .profile-experience {
            padding: 40px;
            flex: 1;
            min-width: 300px;
        }
        
        .profile-about {
            border-right: 1px solid #eee;
        }
        
        .section-title {
            font-size: 1.5rem;
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #3498db;
        }
        
        .info-item {
            margin-bottom: 15px;
        }
        
        .info-label {
            font-weight: bold;
            color: #7f8c8d;
            display: block;
            margin-bottom: 5px;
        }
        
        .info-value {
            font-size: 1.1rem;
        }
        
        .experience-item {
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 1px dashed #eee;
        }
        
        .experience-item:last-child {
            border-bottom: none;
        }
        
        .company {
            font-weight: bold;
            font-size: 1.2rem;
            color: #2c3e50;
        }
        
        .duration {
            color: #7f8c8d;
            font-style: italic;
            margin: 5px 0;
        }
        
        .profile-footer {
            background: #ecf0f1;
            padding: 20px;
            text-align: center;
            font-size: 0.9rem;
            color: #7f8c8d;
        }
        
        @media (max-width: 768px) {
            .profile-about {
                border-right: none;
                border-bottom: 1px solid #eee;
            }
            
            .profile-header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-card">
            <div class="profile-header">
                <span class="profile-badge">CSO</span>
                <h1>Ega Prasetyo</h1>
                <div class="position">Chief Security Officer</div>
            </div>
            
            <div class="profile-content">
                <div class="profile-about">
                    <h2 class="section-title">Tentang</h2>
                    <div class="info-item">
                        <span class="info-label">Nama Lengkap</span>
                        <span class="info-value">Ega Prasetyo</span>
                    </div>
                    <div class="info-item">
                        <span class="info-label">Posisi</span>
                        <span class="info-value">Chief Security Officer</span>
                    </div>
                    <div class="info-item">
                        <span class="info-label">Spesialisasi</span>
                        <span class="info-value">Keamanan Siber, Manajemen Risiko, Keamanan Finansial</span>
                    </div>
                </div>
                
                <div class="profile-experience">
                    <h2 class="section-title">Pengalaman Kerja</h2>
                    <div class="experience-item">
                        <div class="company">Bank Central Asia Tbk (BCA)</div>
                        <div class="duration">4 Tahun (2019 - Sekarang)</div>
                        <div class="info-value">
                            <p>Bertanggung jawab atas keamanan sistem informasi dan perlindungan data finansial perusahaan. Memimpin tim keamanan siber dan mengimplementasikan protokol keamanan terbaru.</p>
                        </div>
                    </div>
                    
                    <div class="experience-item">
                        <div class="company">PT. SecureNet Indonesia</div>
                        <div class="duration">2 Tahun (2017 - 2019)</div>
                        <div class="info-value">
                            <p>Konsultan Keamanan Siber, membantu berbagai perusahaan dalam mengaudit dan meningkatkan sistem keamanan jaringan mereka.</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="profile-footer">
                &copy; 2023 Profil CSO - Ega Prasetyo | All Rights Reserved
            </div>
        </div>
    </div>
</body>
</html>
