
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#075985">
  <meta name="description" content="Independent guide to Kenyan national and county public services.">
  <title>Kenya Public Services</title>

  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f1f5f9;
      color: #172033;
    }

    header {
      background: #075985;
      color: white;
      padding: 25px 18px;
      text-align: center;
    }

    header h1 { margin: 5px 0; }
    header p { color: #e0f2fe; }

    main {
      max-width: 850px;
      margin: auto;
      padding: 18px;
    }

    .search {
      width: 100%;
      padding: 14px;
      border: 1px solid #cbd5e1;
      border-radius: 10px;
      font-size: 16px;
      margin-bottom: 18px;
    }

    h2 { color: #075985; }

    .grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
    }

    .tile {
      background: white;
      padding: 20px 12px;
      border-radius: 12px;
      text-align: center;
      border: 1px solid #dbe4ee;
      font-weight: bold;
    }

    .tile span {
      display: block;
      font-size: 27px;
      margin-bottom: 9px;
    }

    .service {
      background: white;
      padding: 16px;
      margin: 12px 0;
      border-radius: 10px;
      border-left: 4px solid #d4af37;
    }

    .service h3 { margin-top: 0; }

    a { color: #075985; font-weight: bold; }

    .notice {
      background: #fff7ed;
      border: 1px solid #fed7aa;
      padding: 14px;
      border-radius: 10px;
      font-size: 14px;
      margin-top: 20px;
    }

    footer {
      background: #082f49;
      color: white;
      padding: 22px;
      text-align: center;
      margin-top: 30px;
    }

    @media(max-width: 400px) {
      .grid { grid-template-columns: 1fr 1fr; }
    }
  </style>
</head>

<body>

<header>
  <h1>🇰🇪 Kenya Public Services</h1>
  <p>Your guide to national and county government services</p>
</header>

<main>

  <input
    class="search"
    id="search"
    type="search"
    placeholder="Search for a public service..."
    aria-label="Search services"
  >

  <h2>Explore Services</h2>

  <div class="grid">
    <div class="tile"><span>🏛️</span>National Services</div>
    <div class="tile"><span>📍</span>47 Counties</div>
    <div class="tile"><span>📋</span>Requirements</div>
    <div class="tile"><span>📴</span>Offline Access</div>
  </div>

  <h2>National Government Services</h2>

  <div id="services">

    <article class="service">
      <h3>eCitizen</h3>
      <p>Government digital services and applications.</p>
      <a href="https://www.ecitizen.go.ke/">Official website</a>
    </article>

    <article class="service">
      <h3>Immigration Services</h3>
      <p>Passport, visa and immigration information.</p>
      <a href="https://immigration.go.ke/">Official website</a>
    </article>

    <article class="service">
      <h3>Kenya Revenue Authority</h3>
      <p>Tax, customs and taxpayer information.</p>
      <a href="https://www.kra.go.ke/">Official website</a>
    </article>

    <article class="service">
      <h3>Huduma Kenya</h3>
      <p>Public service assistance and service centres.</p>
      <a href="https://www.hudumakenya.go.ke/">Official website</a>
    </article>

    <article class="service">
      <h3>NTSA</h3>
      <p>Transport and road safety services.</p>
      <a href="https://www.ntsa.go.ke/">Official website</a>
    </article>

    <article class="service">
      <h3>County Governments</h3>
      <p>Find information about services provided by Kenya's 47 counties.</p>
      <a href="https://cog.go.ke/">Council of Governors</a>
    </article>

  </div>

  <div class="notice">
    <strong>Important:</strong> This is an independent public
    information prototype, not an official government website.
    Always verify requirements, fees and procedures with the
    relevant government agency before taking action.
  </div>

</main>

<footer>
  <p>Kenya Public Services PWA</p>
  <p>Independent project · Version 1.0</p>
  <p>Learn. Access. Connect.</p>
</footer>

<script>
  const search = document.getElementById("search");
  const services = document.querySelectorAll(".service");

  search.addEventListener("input", function () {
    const term = search.value.toLowerCase();

    services.forEach(function (service) {
      service.style.display =
        service.textContent.toLowerCase().includes(term)
          ? "block"
          : "none";
    });
  });
</script>

</body>
</html>

Independent offline-first public service information prototype
