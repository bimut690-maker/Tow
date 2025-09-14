# Tow
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Edukasi Perang Dunia II</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: #f3f4f6;
      color: #1f2937;
      line-height: 1.6;
    }
    header {
      background: url('https://upload.wikimedia.org/wikipedia/commons/5/5c/NormandySupply_edit.jpg') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 5rem 1rem;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute;
      inset: 0;
      background: rgba(0,0,0,0.5);
    }
    header h1, header p {
      position: relative;
      z-index: 1;
    }
    header h1 {
      font-size: 2.5rem;
      margin-bottom: .5rem;
      text-shadow: 0 2px 5px rgba(0,0,0,0.6);
    }
    header p {
      font-size: 1.2rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      flex-wrap: wrap;
      background: #1e3a8a;
      padding: .7rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: .5rem 1rem;
      border-radius: 20px;
      transition: background .3s;
    }
    nav a:hover {
      background: #2563eb;
    }
    main {
      max-width: 1000px;
      margin: auto;
      padding: 2rem 1rem;
    }
    section {
      background: white;
      margin-bottom: 2rem;
      padding: 1.5rem;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      animation: fadeIn 1s ease;
    }
    h2 {
      border-left: 6px solid #2563eb;
      padding-left: .5rem;
      margin-bottom: 1rem;
      color: #1e3a8a;
    }
    .timeline {
      position: relative;
      padding-left: 2rem;
    }
    .timeline::before {
      content: "";
      position: absolute;
      left: 12px;
      top: 0;
      bottom: 0;
      width: 4px;
      background: #2563eb;
      border-radius: 2px;
    }
    .event {
      margin-bottom: 1.5rem;
      position: relative;
    }
    .event::before {
      content: "⚔️";
      position: absolute;
      left: -1.8rem;
      background: white;
      border: 2px solid #2563eb;
      border-radius: 50%;
      padding: .3rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
      gap: 1rem;
    }
    .card {
      border: 1px solid #ddd;
      border-radius: 12px;
      padding: 1rem;
      transition: transform .3s, box-shadow .3s;
    }
    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    img {
      width: 100%;
      border-radius: 10px;
      margin-top: .5rem;
    }
    footer {
      background: #1e3a8a;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>
  <header>
    <h1>Sejarah Perang Dunia II</h1>
    <p>Konflik terbesar abad ke-20 yang mengubah dunia</p>
  </header>
  <nav>
    <a href="#overview">Overview</a>
    <a href="#causes">Penyebab</a>
    <a href="#timeline">Timeline</a>
    <a href="#battles">Pertempuran</a>
    <a href="#leaders">Tokoh</a>
    <a href="#impact">Dampak</a>
  </nav>
  <main>
    <section id="overview">
      <h2>Overview</h2>
      <p>Perang Dunia II berlangsung dari tahun 1939 hingga 1945, melibatkan lebih dari 100 juta orang dari 30 negara. Pertempuran terjadi di Eropa, Asia, Afrika, dan lautan. Konflik ini berakhir dengan kekalahan Jerman dan Jepang, serta menjadi awal Perang Dingin.</p>
    </section>

    <section id="causes">
      <h2>Penyebab</h2>
      <ul>
        <li>Ketidakpuasan atas Perjanjian Versailles</li>
        <li>Krisis Ekonomi Besar (Great Depression)</li>
        <li>Kebangkitan Nazi Jerman, Fasis Italia, dan Militeris Jepang</li>
      </ul>
    </section>

    <section id="timeline">
      <h2>Timeline</h2>
      <div class="timeline">
        <div class="event"><strong>1939:</strong> Jerman menyerang Polandia, perang dimulai.</div>
        <div class="event"><strong>1941:</strong> Jepang menyerang Pearl Harbor, AS masuk perang.</div>
        <div class="event"><strong>1942:</strong> Pertempuran Stalingrad & Midway jadi titik balik.</div>
        <div class="event"><strong>1944:</strong> D-Day, Sekutu mendarat di Normandia.</div>
        <div class="event"><strong>1945:</strong> Bom atom di Hiroshima & Nagasaki, Jepang menyerah.</div>
      </div>
    </section>

    <section id="battles">
      <h2>Pertempuran Penting</h2>
      <div class="grid">
        <div class="card">
          <h3>Stalingrad</h3>
          <p>Pertempuran brutal di Front Timur, titik balik melawan Jerman.</p>
          <img src="https://upload.wikimedia.org/wikipedia/commons/7/74/Bundesarchiv_Bild_183-R70516%2C_Schlacht_um_Stalingrad%2C_Soldaten_im_Kampf.jpg">
        </div>
        <div class="card">
          <h3>Midway</h3>
          <p>Pertempuran laut besar antara AS dan Jepang di Pasifik.</p>
          <img src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Battle_of_Midway_USS_Yorktown.jpg">
        </div>
        <div class="card">
          <h3>Normandia (D-Day)</h3>
          <p>Pendaratan Sekutu di Prancis, awal pembebasan Eropa Barat.</p>
          <img src="https://upload.wikimedia.org/wikipedia/commons/a/a3/NormandySupply_edit.jpg">
        </div>
      </div>
    </section>

    <section id="leaders">
      <h2>Tokoh Penting</h2>
      <div class="grid">
        <div class="card">
          <h3>Winston Churchill</h3>
          <p>Perdana Menteri Inggris, simbol perlawanan melawan Nazi.</p>
        </div>
        <div class="card">
          <h3>Adolf Hitler</h3>
          <p>Pemimpin Nazi Jerman, penyebab utama perang & Holocaust.</p>
        </div>
        <div class="card">
          <h3>Franklin D. Roosevelt</h3>
          <p>Presiden AS, memimpin negaranya masuk perang.</p>
        </div>
        <div class="card">
          <h3>Joseph Stalin</h3>
          <p>Pemimpin Uni Soviet, terlibat dalam pertempuran di Front Timur.</p>
        </div>
      </div>
    </section>

    <section id="impact">
      <h2>Dampak</h2>
      <ul>
        <li>Lebih dari 70 juta korban jiwa.</li>
        <li>Lahirnya Perserikatan Bangsa-Bangsa (PBB).</li>
        <li>Awal Perang Dingin antara AS dan Uni Soviet.</li>
        <li>Dekolonisasi besar-besaran di Asia & Afrika.</li>
      </ul>
    </section>
  </main>
  <footer>
    © 2025 Website Edukasi Perang Dunia II | Dibuat untuk pembelajaran
  </footer>
</body>
</html>
