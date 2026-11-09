<!DOCTYPE html>
<html lang="fi">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Clear Pages – Nettisivut pienyrityksille Vantaalla</title>
<meta name="description" content="Clear Pages tekee selkeät, nopeat ja puhelimella toimivat nettisivut pienyrityksille Vantaalla ja lähialueilla. Valmis 1–3 päivässä.">
<meta property="og:title" content="Clear Pages – Nettisivut pienyrityksille">
<meta property="og:description" content="Selkeät nettisivut, jotka toimivat puhelimella. Valmis 1–3 päivässä.">
<meta property="og:type" content="website">
<meta name="theme-color" content="#0b0b0a">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='20' fill='%230b0b0a'/%3E%3Cpath d='M28 18h30l16 16v48H28z' fill='%23d4af66'/%3E%3C/svg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Lora:wght@500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0b0b0a; --panel:#141413; --line:#2a2825;
  --text:#f4f1ea; --muted:#b9b3a6;
  --gold:#d4af66; --gold-2:#f0d995; --gold-3:#a8803a;
  --serif:'Lora',Georgia,'Times New Roman',serif;
  --sans:'Inter',system-ui,-apple-system,'Segoe UI',Roboto,Arial,sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--text);font-family:var(--sans);line-height:1.6;font-size:17px;-webkit-font-smoothing:antialiased}
a{color:inherit;text-decoration:none}
.wrap{max-width:1000px;margin:0 auto;padding:0 22px}
.gold-text{background:linear-gradient(135deg,var(--gold-2),var(--gold) 50%,var(--gold-3));-webkit-background-clip:text;background-clip:text;color:transparent}

header{position:sticky;top:0;z-index:10;background:rgba(11,11,10,.92);backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
.nav{display:flex;align-items:center;justify-content:space-between;height:64px}
.brand{display:flex;align-items:center;gap:10px;font-family:var(--serif);font-weight:600;font-size:21px}
.brand svg{width:28px;height:28px}
.nav-cta{font-size:14px;font-weight:600;color:#14110a;background:linear-gradient(135deg,var(--gold-2),var(--gold));padding:9px 16px;border-radius:999px}

.hero{padding:72px 0 60px;text-align:center}
.eyebrow{font-size:12px;letter-spacing:.28em;text-transform:uppercase;color:var(--gold);font-weight:500}
h1{font-family:var(--serif);font-weight:600;font-size:clamp(34px,8vw,58px);line-height:1.12;margin:18px auto 18px;max-width:760px}
.lead{color:var(--muted);max-width:560px;margin:0 auto 32px;font-size:18px}
.btns{display:flex;flex-wrap:wrap;gap:12px;justify-content:center}
.btn{display:inline-block;padding:15px 26px;border-radius:999px;font-weight:600;font-size:16px;border:1px solid var(--gold)}
.btn.primary{background:linear-gradient(135deg,var(--gold-2),var(--gold) 55%,var(--gold-3));color:#14110a;border-color:transparent}
.btn.ghost{color:var(--gold-2)}
.proof{display:flex;flex-wrap:wrap;gap:10px 22px;justify-content:center;margin-top:34px;color:var(--muted);font-size:14px}
.proof span::before{content:"✓ ";color:var(--gold)}

section{padding:64px 0;border-top:1px solid var(--line)}
h2{font-family:var(--serif);font-weight:600;font-size:clamp(26px,6vw,38px);line-height:1.2;margin-bottom:10px}
.sub{color:var(--muted);margin-bottom:32px;max-width:560px}
.grid{display:grid;gap:16px}
@media(min-width:760px){.grid.three{grid-template-columns:repeat(3,1fr)}}
.card{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:26px}
.card h3{font-family:var(--serif);font-size:20px;margin-bottom:8px;color:var(--gold-2)}
.card p{color:var(--muted);font-size:16px}
.num{display:inline-flex;width:36px;height:36px;border-radius:50%;border:1px solid var(--gold);color:var(--gold);align-items:center;justify-content:center;font-weight:600;margin-bottom:14px}

.price{background:linear-gradient(160deg,#1a1814,#0f0e0c);border:1px solid var(--gold-3);border-radius:20px;padding:36px 26px;text-align:center}
.price .amount{font-family:var(--serif);font-size:54px;font-weight:600;line-height:1.1;margin:6px 0}
.price ul{list-style:none;max-width:420px;margin:22px auto 28px;text-align:left}
.price li{padding:9px 0;border-bottom:1px solid var(--line);color:var(--muted)}
.price li::before{content:"✓ ";color:var(--gold)}
.note{color:var(--muted);font-size:14px;margin-top:16px}

.contact{text-align:center}
.contact .btns{margin-top:24px}

footer{border-top:1px solid var(--line);padding:30px 0;text-align:center;color:var(--muted);font-size:14px}
</style>
</head>
<body>

<header>
  <div class="wrap nav">
    <a class="brand" href="#top" aria-label="Clear Pages">
      <svg viewBox="0 0 100 100" aria-hidden="true"><path d="M24 10h36l18 18v62H24z" fill="#d4af66"/><path d="M60 10v18h18z" fill="#a8803a"/><path d="M38 62l11 11 21-22" fill="none" stroke="#0b0b0a" stroke-width="9" stroke-linecap="round" stroke-linejoin="round"/></svg>
      <span class="gold-text">Clear Pages</span>
    </a>
    <a class="nav-cta" href="#yhteys">Ota yhteyttä</a>
  </div>
</header>

<main id="top">
  <div class="wrap hero">
    <p class="eyebrow">Nettisivut pienyrityksille</p>
    <h1>Selkeät nettisivut, jotka <span class="gold-text">tuovat asiakkaat luoksesi</span></h1>
    <p class="lead">Teen yrityksellesi nopean ja ammattimaisen sivun, joka toimii puhelimella ja kertoo asiakkaille heti oleellisen: mitä teet, paljonko se maksaa ja miten sinut tavoittaa.</p>
    <div class="btns">
      <a class="btn primary" href="#yhteys">Pyydä ilmainen esimerkkisivu</a>
      <a class="btn ghost" href="#hinta">Katso hinta</a>
    </div>
    <div class="proof">
      <span>Valmis 1–3 päivässä</span>
      <span>Toimii puhelimella</span>
      <span>Ei kuukausimaksua</span>
    </div>
  </div>

  <section id="palvelut">
    <div class="wrap">
      <h2>Mitä saat</h2>
      <p class="sub">Kaikki, mitä pieni yritys tarvitsee verkossa – ei turhaa.</p>
      <div class="grid three">
        <div class="card"><h3>Selkeä rakenne</h3><p>Palvelut, hinnat, aukioloajat ja yhteystiedot löytyvät yhdeltä sivulta ilman etsimistä.</p></div>
        <div class="card"><h3>Puhelimella ensin</h3><p>Useimmat asiakkaat katsovat sivun puhelimelta, joten sivu on tehty ensin sitä varten. Iso soittopainike on aina käsillä.</p></div>
        <div class="card"><h3>Löydettävyys</h3><p>Yrityksen nimi, paikkakunta ja palvelut kirjoitetaan sivulle niin, että hakukoneen on helppo ymmärtää ne. Autan myös Google-yritysprofiilin kanssa.</p></div>
      </div>
    </div>
  </section>

  <section id="miten">
    <div class="wrap">
      <h2>Näin se toimii</h2>
      <p class="sub">Kolme vaihetta, ei byrokratiaa.</p>
      <div class="grid three">
        <div class="card"><div class="num">1</div><h3>Kerrot yrityksestäsi</h3><p>Lähetät palvelut, hinnat ja yhteystiedot esimerkiksi WhatsAppilla.</p></div>
        <div class="card"><div class="num">2</div><h3>Näet esimerkkisivun</h3><p>Teen sivun valmiiksi, ja voit pyytää muutoksia, kunnes se on juuri sinun näköisesi.</p></div>
        <div class="card"><div class="num">3</div><h3>Sivu julkaistaan</h3><p>Liitän sivun omaan verkkotunnukseesi, ja sivu on valmis asiakkaille.</p></div>
      </div>
    </div>
  </section>

  <section id="hinta">
    <div class="wrap">
      <div class="price">
        <p class="eyebrow">Selkeä hinta</p>
        <p class="amount gold-text">alkaen 300 €</p>
        <p style="color:var(--muted)">kertamaksu</p>
        <ul>
          <li>Yhden sivun ammattimainen sivusto</li>
          <li>Toimii puhelimella ja tietokoneella</li>
          <li>Kaksi muutoskierrosta hintaan sisältyen</li>
          <li>Apu verkkotunnuksen käyttöönotossa</li>
          <li>Valmis 1–3 päivässä</li>
        </ul>
        <a class="btn primary" href="#yhteys">Pyydä tarjous</a>
        <p class="note">Verkkotunnus (noin 10–20 €/vuosi) maksetaan erikseen ja jää sinun omistukseesi. Ylläpito ja myöhemmät muutokset sovitaan erikseen.</p>
      </div>
    </div>
  </section>

  <section id="yhteys" class="contact">
    <div class="wrap">
      <h2>Aloitetaan <span class="gold-text">ilmaisella esimerkillä</span></h2>
      <p class="sub" style="margin-left:auto;margin-right:auto">Kerro yrityksesi nimi, niin teen sinulle esimerkkisivun, josta näet miltä lopputulos näyttäisi. Se ei velvoita mihinkään.</p>
      <div class="btns">
        <a class="btn primary" href="tel:[PUHELINNUMERO]">Soita: [PUHELINNUMERO]</a>
        <a class="btn ghost" href="mailto:[SÄHKÖPOSTI]">[SÄHKÖPOSTI]</a>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">© 2026 Clear Pages · Vantaa</div>
</footer>

</body>
</html>