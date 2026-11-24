
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#075985">
  <meta name="description" content="Independent guide to Kenya's national and county public services.">
  <meta name="apple-mobile-web-app-capable" content="yes">

  <title>Kenya Public Services</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f1f5f9;
      color: #172033;
      line-height: 1.6;
    }

    header {
      background: #075985;
      color: white;
      text-align: center;
      padding: 28px 16px;
    }

    header h1 {
      margin: 0;
      font-size: 27px;
    }

    header p {
      color: #e0f2fe;
      margin-bottom: 0;
    }

    nav {
      background: #082f49;
      padding: 12px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 9px;
      font-size: 14px;
    }

    main {
      max-width: 950px;
      margin: auto;
      padding: 18px;
    }

    .search {
      width: 100%;
      padding: 15px;
      border: 1px solid #cbd5e1;
      border-radius: 10px;
      font-size: 16px;
      margin: 12px 0 20px;
    }

    h2 {
      color: #075985;
      margin-top: 28px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
    }

    .tile {
      background: white;
      padding: 18px 10px;
      border-radius: 12px;
      text-align: center;
      border: 1px solid #dbe4ee;
    }

    .tile span {
      display: block;
      font-size: 28px;
    }

    .tile strong {
      display: block;
    }

    .service {
      background: white;
      padding: 16px;
      margin: 12px 0;
      border-radius: 10px;
      border-left: 4px solid #d4af37;
    }

    .service h3 {
      margin-top: 0;
      color: #075985;
    }

    a {
      color: #075985;
      font-weight: bold;
    }

    .county-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 9px;
    }

    .county {
      background: white;
      padding: 11px;
      border-radius: 8px;
      border: 1px solid #dbe4ee;
      font-size: 14px;
    }

    .notice {
      background: #fff7ed;
      border: 1px solid #fed7aa;
      padding: 15px;
      border-radius: 10px;
      margin-top: 25px;
      font-size: 14px;
    }

    .offline {
      background: #ecfdf5;
      border: 1px solid #a7f3d0;
      padding: 14px;
      border-radius: 10px;
      margin-top: 18px;
    }

    button {
      background: #075985;
      color: white;
      border: none;
      padding: 11px 15px;
      border-radius: 8px;
      font-size: 14px;
      cursor: pointer;
    }

    footer {
      background: #082f49;
      color: white;
      text-align: center;
      padding: 22px;
      margin-top: 30px;
      font-size: 14px;
    }

    footer p {
      margin: 5px;
    }

    @media (min-width: 650px) {
      .grid {
        grid-template-columns: repeat(4, 1fr);
      }

      .county-grid {
        grid-template-columns: repeat(4, 1fr);
      }
    }
  </style>
</head>

<body>

<header>
  <h1>🇰🇪 Kenya Public Services</h1>
  <p>Your independent guide to national and county government services</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#national">National Services</a>
  <a href="#counties">Counties</a>
  <a href="#about">About</a>
</nav>

<main id="home">

  <input
    class="search"
    id="search"
    type="search"
    placeholder="Search services or counties..."
    aria-label="Search services and counties"
  >

  <h2>Explore the Directory</h2>

  <div class="grid">
    <div class="tile">
      <span>🏛️</span>
      <strong>National Services</strong>
      <small>Government agencies</small>
    </div>

    <div class="tile">
      <span>📍</span>
      <strong>47 Counties</strong>
      <small>County information</small>
    </div>

    <div class="tile">
      <span>📋</span>
      <strong>Requirements</strong>
      <small>Service preparation</small>
    </div>

    <div class="tile">
      <span>📴</span>
      <strong>Offline Access</strong>
      <small>Offline-ready design</small>
    </div>
  </div>

  <section id="national">
    <h2>National Government Services</h2>

    <div id="services">

      <article class="service">
        <h3>eCitizen</h3>
        <p>Access digital government services and applications.</p>
        <a href="https://www.ecitizen.go.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

      <article class="service">
        <h3>Immigration Services</h3>
        <p>Passport, visa and immigration information.</p>
        <a href="https://immigration.go.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

      <article class="service">
        <h3>Kenya Revenue Authority</h3>
        <p>Tax, customs and taxpayer information.</p>
        <a href="https://www.kra.go.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

      <article class="service">
        <h3>Huduma Kenya</h3>
        <p>Public service assistance and service centres.</p>
        <a href="https://www.hudumakenya.go.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

      <article class="service">
        <h3>National Transport and Safety Authority</h3>
        <p>Transport, driving licences and road safety information.</p>
        <a href="https://www.ntsa.go.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

      <article class="service">
        <h3>National Social Security Fund</h3>
        <p>Social security and member information.</p>
        <a href="https://www.nssf.or.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

      <article class="service">
        <h3>National Health Insurance Fund / SHA</h3>
        <p>Find information about Kenya's Social Health Authority.</p>
        <a href="https://sha.go.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

      <article class="service">
        <h3>Office of the Data Protection Commissioner</h3>
        <p>Personal data protection information and guidance.</p>
        <a href="https://www.odpc.go.ke/" target="_blank" rel="noopener noreferrer">Official website</a>
      </article>

    </div>
  </section>

  <section id="counties">
    <h2>Kenya's 47 Counties</h2>
    <p>Select a county to find its official government information.</p>

    <div id="countyList" class="county-grid">

      <div class="county">001 — Mombasa</div>
      <div class="county">002 — Kwale</div>
      <div class="county">003 — Kilifi</div>
      <div class="county">004 — Tana River</div>
      <div class="county">005 — Lamu</div>
      <div class="county">006 — Taita Taveta</div>
      <div class="county">007 — Garissa</div>
      <div class="county">008 — Wajir</div>
      <div class="county">009 — Mandera</div>
      <div class="county">010 — Marsabit</div>
      <div class="county">011 — Isiolo</div>
      <div class="county">012 — Meru</div>
      <div class="county">013 — Tharaka Nithi</div>
      <div class="county">014 — Embu</div>
      <div class="county">015 — Kitui</div>
      <div class="county">016 — Machakos</div>
      <div class="county">017 — Makueni</div>
      <div class="county">018 — Nyandarua</div>
      <div class="county">019 — Nyeri</div>
      <div class="county">020 — Kirinyaga</div>
      <div class="county">021 — Murang'a</div>
      <div class="county">022 — Kiambu</div>
      <div class="county">023 — Turkana</div>
      <div class="county">024 — West Pokot</div>
      <div class="county">025 — Samburu</div>
      <div class="county">026 — Trans Nzoia</div>
      <div class="county">027 — Uasin Gishu</div>
      <div class="county">028 — Elgeyo Marakwet</div>
      <div class="county">029 — Nandi</div>
      <div class="county">030 — Baringo</div>
      <div class="county">031 — Laikipia</div>
      <div class="county">032 — Nakuru</div>
      <div class="county">033 — Narok</div>
      <div class="county">034 — Kajiado</div>
      <div class="county">035 — Kericho</div>
      <div class="county">036 — Bomet</div>
      <div class="county">037 — Kakamega</div>
      <div class="county">038 — Vihiga</div>
      <div class="county">039 — Bungoma</div>
      <div class="county">040 — Busia</div>
      <div class="county">041 — Siaya</div>
      <div class="county">042 — Kisumu</div>
      <div class="county">043 — Homa Bay</div>
      <div class="county">044 — Migori</div>
      <div class="county">045 — Kisii</div>
      <div class="county">046 — Nyamira</div>
      <div class="county">047 — Nairobi City</div>

    </div>

    <p>
      <a href="https://cog.go.ke/" target="_blank" rel="noopener noreferrer">
        Council of Governors — official information
      </a>
    </p>
  </section>

  <section id="requirements">
    <h2>Preparing for a Public Service</h2>

    <article class="service">
      <h3>Before applying</h3>
      <ul>
        <li>Identify the government agency responsible.</li>
        <li>Check the official application procedure.</li>
        <li>Confirm the required identification documents.</li>
        <li>Verify current fees and payment methods.</li>
        <li>Check whether an appointment is necessary.</li>
        <li>Keep your official application reference safely.</li>
      </ul>
      <p>Requirements vary by service. This is a general preparation checklist, not an official application requirement.</p>
    </article>
  </section>

  <section class="offline">
    <h2>Offline Access</h2>
    <p>
      This website is designed for future offline support.
      Offline caching will be activated after the web app
      manifest and service worker are installed.
    </p>
    <p id="connectionStatus">Checking connection...</p>
  </section>

  <section id="about" class="notice">
    <strong>Important notice:</strong>
    Kenya Public Services is an independent public information
    prototype. It is not a government website, government agency,
    or official service portal. Always verify requirements,
    fees, contacts and procedures directly with the relevant
    government institution.
  </section>

</main>

<footer>
  <p><strong>Kenya Public Services PWA</strong></p>
  <p>Independent public information initiative</p>
  <p>Learn. Access. Connect.</p>
  <p>Version 1.0</p>
</footer>

<script>
  const search = document.getElementById("search");

  search.addEventListener("input", function () {
    const term = search.value.toLowerCase().trim();

    document.querySelectorAll(".service, .county").forEach(function (item) {
      item.style.display =
        item.textContent.toLowerCase().includes(term)
          ? ""
          : "none";
    });
  });

  function updateConnectionStatus() {
    const status = document.getElementById("connectionStatus");

    status.textContent = navigator.onLine
      ? "Connection status: Online"
      : "Connection status: Offline";
  }

  window.addEventListener("online", updateConnectionStatus);
  window.addEventListener("offline", updateConnectionStatus);

  updateConnectionStatus();
</script>

</body>
</html>
