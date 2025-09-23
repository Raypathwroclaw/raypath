<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Raypath — Oddział Wrocław | Pokazy i produkty bez chemii</title>
  <meta name="robots" content="index,follow" />
  <link rel="canonical" href="https://wroclaw.raypath.info/" />
  <meta property="og:url" content="https://wroclaw.raypath.info/" />
  <meta property="og:image" content="tlo.jpg" />
  <meta property="og:locale" content="pl_PL" />
  <meta name="twitter:card" content="summary_large_image" />
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Raypath — Oddział Wrocław",
    "url": "https://wroclaw.raypath.info/",
    "logo": "https://raypath.eu/assets/images/logo-b.svg",
    "sameAs": ["https://raypath.eu/"]
  }
  </script>
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "Raypath — Wrocław (Przedstawiciel regionalny)",
    "image": "tlo.jpg",
    "telephone": "+48 794 566 404",
    "email": "raypathwroclaw@gmail.com",
    "url": "https://wroclaw.raypath.info/",
    "address": {
      "@type": "PostalAddress",
      "streetAddress": "ul. Kiełczowska 138A",
      "addressLocality": "Wrocław",
      "addressCountry": "PL"
    },
    "areaServed": "Wrocław, Polska"
  }
  </script>
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "FAQPage",
    "mainEntity": [
      {
        "@type": "Question",
        "name": "Czy naprawdę nie używacie chemii?",
        "acceptedAnswer": {"@type": "Answer", "text": "Standardowe mycie odbywa się wyłącznie przy użyciu wody i odpowiednio dobranych czyścików z mikrowłókna."}
      },
      {
        "@type": "Question",
        "name": "Czym jest technologia NanoSilver?",
        "acceptedAnswer": {"@type": "Answer", "text": "To dodatek nanosrebra we włóknach, który ogranicza namnażanie bakterii w materiale. Produkt nie jest środkiem dezynfekującym."}
      },
      {
        "@type": "Question",
        "name": "Jak zamówić pokaz?",
        "acceptedAnswer": {"@type": "Answer", "text": "Wypełnij formularz na stronie lub zadzwoń – oddzwonimy i ustalimy dogodny termin."}
      }
    ]
  }
  </script>
  <style>
    :root{
      --bg:#fafafa; --card:#ffffff; --ink:#0a0a0a; --muted:#6b7280; --ring:#e5e7eb;
    }
    *{box-sizing:border-box}
    html,body{margin:0; padding:0; font-family:system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial,sans-serif; color:var(--ink); background:var(--bg);}
    img{max-width:100%; display:block}
    a{color:inherit; text-decoration:none}
    .container{max-width:1200px; margin:0 auto; padding:0 16px}
    .btn{display:inline-block; padding:12px 18px; border-radius:16px; background:#0a0a0a; color:#fff; transition:transform .08s ease, box-shadow .2s ease; box-shadow:0 6px 16px rgba(0,0,0,.08)}
    .btn:hover{transform:translateY(-1px); box-shadow:0 10px 22px rgba(0,0,0,.12)}
    .btn.alt{background:#e5e7eb; color:#0a0a0a}
    .shadow{box-shadow:0 8px 24px rgba(0,0,0,.06)}
    header{position:sticky; top:0; z-index:40; backdrop-filter:saturate(180%) blur(8px); background:rgba(255,255,255,.85); border-bottom:1px solid var(--ring)}
    nav a{font-size:14px; opacity:.9}
    .nav{display:none; gap:20px}
    .nav.show{display:flex}
    @media(min-width:768px){.nav{display:flex}}
    .logo{display:flex; align-items:center; gap:12px}
    .logo-badge{width:44px; height:44px; border-radius:14px; background:#e5e7eb; display:grid; place-items:center; font-weight:800}
    section{padding:64px 0}
    .grid{display:grid; gap:24px}
    @media(min-width:768px){.grid-2{grid-template-columns:1fr 1fr}}
    @media(min-width:1024px){.grid-3{grid-template-columns:repeat(3,1fr)} .grid-4{grid-template-columns:repeat(4,1fr)}}
    .card{background:var(--card); border:1px solid var(--ring); border-radius:22px; padding:18px}
    .muted{color:var(--muted)}
    .hero h1{font-size:40px; line-height:1.1; margin:0}
    @media(min-width:768px){.hero h1{font-size:56px}}
    .kafel img{height:176px; width:100%; object-fit:cover; border-radius:16px}
    details{border-radius:16px}
    details summary{cursor:pointer; font-weight:600}
    footer{background:#fff; border-top:1px solid var(--ring)}
    .tag{display:inline-block; padding:6px 10px; border-radius:999px; background:#f3f4f6; font-size:12px}
    .divider{height:1px; background:var(--ring); margin:10px 0}
    .mobile-toggle{border:1px solid var(--ring); padding:8px 12px; border-radius:14px; background:#fff}
    .sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);border:0}
    .calendar{display:grid; gap:10px}
    .cal-head{display:flex; align-items:center; justify-content:space-between}
    .cal-grid{display:grid; grid-template-columns:repeat(7,1fr); gap:6px}
    .cal-cell{background:#fff; border:1px solid var(--ring); border-radius:12px; padding:10px; text-align:center; font-size:14px}
    .cal-cell.muted{color:var(--muted); background:#f9fafb}
    .cal-cell.slot{cursor:pointer; border-color:#c7eed8; box-shadow:inset 0 0 0 2px #c7eed8}
    .cal-cell.selected{outline:2px solid #0a0a0a}
    .slots{display:flex; flex-wrap:wrap; gap:8px}
    .chip{padding:8px 12px; border-radius:999px; border:1px solid var(--ring); background:#fff; cursor:pointer}
    .chip.active{background:#0a0a0a; color:#fff}
    .form-grid{display:grid; gap:10px; grid-template-columns:1fr}
    @media(min-width:768px){.form-grid{grid-template-columns:1fr 1fr}}
    .lb-backdrop{position:fixed; inset:0; background:rgba(0,0,0,.75); display:none; align-items:center; justify-content:center; z-index:1000}
    .lb-backdrop.show{display:flex}
    .lb-box{max-width:90vw; max-height:90vh}
    .lb-img{max-width:90vw; max-height:85vh; border-radius:16px; box-shadow:0 20px 60px rgba(0,0,0,.35)}
    .lb-close{position:absolute; top:18px; right:18px; background:#fff; border-radius:12px; padding:8px 12px; cursor:pointer; border:1px solid var(--ring)}
  </style>
</head>
<body>
  <!-- HEADER -->
  <header>
    <div class="container" style="display:flex; align-items:center; justify-content:space-between; padding:12px 0; gap:12px">
      <div class="logo">
        <img src="https://raypath.eu/assets/images/logo-sm.svg" alt="Raypath logo" style="width:44px;height:44px;border-radius:12px"/>
        <div>
          <div style="font-weight:800; letter-spacing:.3px">RAYPATH INTERNATIONAL</div>
          <div class="muted" style="font-size:12px">Przedstawiciel regionalny — Wrocław</div>
        </div>
      </div>
      
      <button class="mobile-toggle" id="navToggle" aria-expanded="false" aria-controls="primaryNav">
        <span class="sr-only">Otwórz menu</span>☰
      </button>
      <nav id="primaryNav" class="nav">
        <a href="#produkty">Produkty</a>
        <a href="#materialy">Materiały</a>
        <a href="#ecobody">ECOBody</a>
        <a href="#branze">Branże</a>
        <a href="#wspolpraca">Współpraca</a>
        <a href="#pokazy">Rezerwacje</a>
        <a href="#o-nas">O nas</a>
        <a href="#opinie">Opinie</a>
        <a href="#galeria">Galeria</a>
        <a href="#faq">FAQ</a>
        <a href="#kontakt" class="btn" style="padding:10px 14px">Kontakt</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="hero">
    <div class="container grid grid-2" style="align-items:center">
      <div>
        <h1>Czysty dom i auto <span class="tag">bez chemii</span></h1>
        <p class="muted" style="font-size:18px; margin-top:12px">
          Oryginalne produkty Raypath® z mikrowłóknem i technologią NanoSilver. Pokazy na żywo w domu, na targach i eventach.
        </p>
        <div style="display:flex; gap:12px; flex-wrap:wrap; margin-top:18px">
          <a class="btn" href="#produkty">Zobacz produkty</a>
          <a class="btn alt" href="#pokazy">Zamów pokaz</a>
        </div>
        <p class="muted" style="font-size:12px; margin-top:8px">Znaki towarowe użyte za pisemną zgodą. Dodaj własne logo/dopisek „Oddział {miasto}”.</p>
      </div>
      <div>
        <!-- HERO IMAGE: zapisz swoje zdjęcie jako tlo.jpg obok pliku index.html -->
        <img class="shadow" src="tlo.jpg" loading="eager" alt="Produkty Raypath i akcesoria" style="border-radius:24px">
      </div>
    </div>
  </section>

  <!-- USP -->
  <section style="background:#fff; border-top:1px solid var(--ring); border-bottom:1px solid var(--ring)">
    <div class="container grid grid-4">
      <div class="card">
        <div style="font-weight:600">Tylko woda</div>
        <p class="muted">Czyściki działają z użyciem samej wody — bez detergentów.</p>
      </div>
      <div class="card">
        <div style="font-weight:600">NanoSilver</div>
        <p class="muted">Dodatek nanosrebra we włóknach ogranicza namnażanie bakterii w materiale.*</p>
      </div>
      <div class="card">
        <div style="font-weight:600">Ekonomia</div>
        <p class="muted">Mniej środków czystości i dłuższa żywotność produktów.</p>
      </div>
      <div class="card">
        <div style="font-weight:600">Recykling</div>
        <p class="muted">Zużyte czyściki możesz odesłać — otrzymasz nowe z rabatem.</p>
      </div>
    </div>
  </section>

  <!-- KATEGORIE -->
  <section id="produkty">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Produkty Raypath — kategorie</h2>
      <p class="muted">Czyściki z mikrowłóknem i NanoSilver, kosmetyki, suplementy oraz ECOBody Care.</p>
      <div class="grid grid-4" style="margin-top:18px">
        <article class="card kafel shadow">
          <img loading="lazy" src="https://images.unsplash.com/photo-1600585154526-990dced4db0d?q=80&w=1600&auto=format&fit=crop" alt="Czyściki i rękawice Raypath" />
          <h3>Czyściki i rękawice</h3>
          <p class="muted">Biały, Beżowy, Różowy, Sunbeam – dobierz zestaw do powierzchni.</p>
          <a class="btn" href="https://wroclaw.raypath.info" style="margin-top:8px">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="https://images.unsplash.com/photo-1501045661006-fcebe0257c3f?q=80&w=1600&auto=format&fit=crop" alt="Mopy i podłogi Raypath" />
          <h3>Mopy i podłogi</h3>
          <p class="muted">Szybkie mycie, polerowanie i pielęgnacja podłóg.</p>
          <a class="btn" href="https://wroclaw.raypath.info" style="margin-top:8px">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?q=80&w=1600&auto=format&fit=crop" alt="Kosmetyki Raypath The Ritual" />
          <h3>The Ritual</h3>
          <p class="muted">Kosmetyki pielęgnacyjne na co dzień.</p>
          <a class="btn" href="https://wroclaw.raypath.info" style="margin-top:8px">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="https://images.unsplash.com/photo-1573883431205-98b5f10be20b?q=80&w=1600&auto=format&fit=crop" alt="Suplementy diety Raypath" />
          <h3>Naturalne suplementy</h3>
          <p class="muted">Wsparcie codziennej rutyny.</p>
          <a class="btn" href="https://wroclaw.raypath.info" style="margin-top:8px">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="https://images.unsplash.com/photo-1629198735668-67b83674c4ed?q=80&w=1600&auto=format&fit=crop" alt="ECOBody Care Raypath" />
          <h3>ECOBody Care</h3>
          <p class="muted">Rękawice Face/Body, naturalne mydła i pielęgnacja.</p>
          <a class="btn" href="https://wroclaw.raypath.info" style="margin-top:8px">Kup teraz</a>
        </article>
      </div>
    </div>
  </section>

  <!-- MATERIAŁY RAYPATH -->
  <section id="materialy" style="background:#fff; border-top:1px solid var(--ring); border-bottom:1px solid var(--ring)">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Materiały Raypath</h2>
      <p class="muted">Dobierz materiał do zadania: na mokro, wilgotno lub na sucho.</p>
      <div class="grid grid-4" style="margin-top:18px">
        <article class="card kafel shadow">
          <img loading="lazy" src="material-bialy.png" alt="Biały materiał — czyszczenie na mokro" />
          <h3>Biały materiał</h3>
          <p class="muted">Najwyższa siła czyszcząca. Do powierzchni dobrze znoszących wodę: okna, armatura, szkło, drzwi, twarde podłogi.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="Rękawica Pielęgnacyjna.jpg" alt="Beżowy materiał — czyszczenie na wilgotno" />
          <h3>Beżowy / Biały Nova</h3>
          <p class="muted">Do powierzchni, które nie lubią nadmiaru wody: drewno, meble, parkiety, elektronika, biżuteria, rośliny.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="material-rozowy.jpg" alt="Różowy materiał — czyszczenie na sucho" />
          <h3>Różowy materiał</h3>
          <p class="muted">Usuwanie kurzu na sucho. Ładunek antystatyczny spowalnia ponowne osadzanie pyłu. Idealny do polerowania.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="Czyścik Sunbeam DUO.jpg" alt="Sunbeam — czyszczenie na sucho i mokro" />
          <h3>Sunbeam</h3>
          <p class="muted">Bardzo chłonny. Do zbierania resztek wody, emulsji i finalnego polerowania: okna, lustra, lampy, ceramika, optyka, naczynia.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
      </div>
      <p class="muted" style="font-size:12px; margin-top:10px">Opisy zostały zredagowane pod SEO i nie stanowią deklaracji właściwości leczniczych.</p>
    </div>
  </section>

  <!-- ECOBODY CARE -->
  <section id="ecobody">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">ECOBody Care</h2>
      <p class="muted">Domowe SPA: rękawice do twarzy i ciała oraz naturalne mydła.</p>
      <div class="grid grid-4" style="margin-top:18px">
        <article class="card kafel shadow">
          <img loading="lazy" src="img/ecobody-faceglove.jpg" alt="Face Glove — rękawiczka do demakijażu" />
          <h3>Face Glove</h3>
          <p class="muted">Delikatne oczyszczanie i demakijaż tylko z wodą — miękki materiał przyjazny dla skóry.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="img/ecobody-bodyglove.jpg" alt="Body Glove — rękawica do mycia ciała" />
          <h3>Body Glove</h3>
          <p class="muted">Codzienna pielęgnacja pod prysznicem — pobudza mikrokrążenie i odświeża skórę.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="img/ecobody-facecleaner.jpg" alt="Face Cleaner — rękawiczka do peelingu" />
          <h3>Face Cleaner</h3>
          <p class="muted">Bezpieczny peeling twarzy. Wygładza i rozświetla cerę — idealny przed makijażem.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
        <article class="card kafel shadow">
          <img loading="lazy" src="img/ecobody-bodycleaner.jpg" alt="Body Cleaner — rękawica do peelingu i masażu" />
          <h3>Body Cleaner</h3>
          <p class="muted">Peeling i masaż ciała na sucho lub na mokro. Wspiera gładkość i jędrność skóry.</p>
          <a class="btn" href="https://wroclaw.raypath.info">Kup teraz</a>
        </article>
      </div>
    </div>
  </section>

  <!-- BRANŻE I ZASTOSOWANIA -->
  <section id="branze" style="background:#fff; border-top:1px solid var(--ring); border-bottom:1px solid var(--ring)">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Branże i zastosowania</h2>
      <p class="muted">Wybierz obszar, a przygotujemy dedykowaną prezentację i zestaw produktów.</p>
      <div class="grid grid-3" style="margin-top:18px">
        <article class="card shadow"><h3>Dom i mieszkanie</h3><p class="muted">Okna, łazienka, kuchnia, podłogi, lustra, AGD.</p></article>
        <article class="card shadow"><h3>Auto & detailing</h3><p class="muted">Karoseria, wnętrze, szyby, ekoskóra, multimedia.</p></article>
        <article class="card shadow"><h3>Biuro i usługi</h3><p class="muted">Biurka, sprzęt elektroniczny, sale konferencyjne.</p></article>
        <article class="card shadow"><h3>Beauty & SPA</h3><p class="muted">Rękawice do twarzy i ciała, naturalne mydła.</p></article>
        <article class="card shadow"><h3>Gastro</h3><p class="muted">Stal, szkło, ceramika, blaty robocze, polerowanie.</p></article>
        <article class="card shadow"><h3>Hotel</h3><p class="muted">Szybkie utrzymanie czystości pokoi i stref wspólnych.</p></article>
      </div>
    </div>
  </section>

  <!-- WSPÓŁPRACA -->
  <section id="wspolpraca">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Współpraca — dołącz do zespołu</h2>
      <p class="muted">Szukasz elastycznego zajęcia w sprzedaży bezpośredniej? Pokażemy Ci, jak prowadzić pokazy i budować własną sieć klientów.</p>
      <div class="grid grid-3" style="margin-top:18px">
        <article class="card shadow"><h3>Szkolenia i materiały</h3><p class="muted">Gotowe scenariusze pokazów, grafiki, filmy i wsparcie mentora.</p></article>
        <article class="card shadow"><h3>Elastyczny czas pracy</h3><p class="muted">Pokazy domowe, eventy firmowe, targi, social media.</p></article>
        <article class="card shadow"><h3>Prosty start</h3><p class="muted">Zestaw startowy i ścieżka wdrożenia — krok po kroku.</p></article>
      </div>
      <div style="margin-top:16px; display:flex; gap:12px; flex-wrap:wrap">
        <a class="btn" href="mailto:raypathwroclaw@gmail.com?subject=Dołączam%20do%20zespołu%20Raypath%20Wrocław&body=Imię%20i%20nazwisko:%0ATelefon:%0ADlaczego%20chcę%20współpracować:%0A">Zgłoś chęć współpracy</a>
        <a class="btn alt" href="#pokazy">Zobacz jak wygląda pokaz</a>
      </div>
    </div>
  </section>

  <!-- WYDARZENIA / POKAZY -->
  <section id="pokazy" style="background:#fff; border-top:1px solid var(--ring); border-bottom:1px solid var(--ring)">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Zarezerwuj pokaz</h2>
      <p class="muted">Wybierz termin, produkt i zostaw kontakt. Potwierdzimy rezerwację telefonicznie.</p>
      <div class="grid grid-2" style="margin-top:18px; align-items:start">
        <!-- KALENDARZ -->
        <div class="card">
          <div class="cal-head">
            <button class="mobile-toggle" id="prevMonth">◀</button>
            <div><strong id="calTitle">Kalendarz</strong></div>
            <button class="mobile-toggle" id="nextMonth">▶</button>
          </div>
          <div class="cal-grid" style="margin-top:10px" id="calGrid" aria-label="Kalendarz rezerwacji"></div>
          <p class="muted" style="font-size:12px; margin-top:10px">Dni zaznaczone na zielono mają wolne terminy.</p>
        </div>
        <!-- FORMULARZ REZERWACJI -->
        <div class="card">
          <form id="bookingForm" class="form-grid">
            <div>
              <label class="muted" for="productSelect">Wybierz produkt/pokaz</label>
              <select id="productSelect" class="card" required>
                <option value="Czyściki i rękawice">Czyściki i rękawice</option>
                <option value="Mopy i podłogi">Mopy i podłogi</option>
                <option value="ECOBody Care">ECOBody Care</option>
                <option value="The Ritual — kosmetyki">The Ritual — kosmetyki</option>
                <option value="Suplementy">Naturalne suplementy</option>
                <option value="Detailing auta">Detailing auta</option>
              </select>
            </div>
            <div>
              <label class="muted" for="custName">Imię i nazwisko</label>
              <input id="custName" class="card" placeholder="Jan Kowalski" required>
            </div>
            <div>
              <label class="muted" for="custPhone">Telefon</label>
              <input id="custPhone" class="card" placeholder="794 566 404" pattern="[0-9 +()-]{7,}" required>
            </div>
            <div>
              <label class="muted" for="custEmail">E-mail (opcjonalnie)</label>
              <input id="custEmail" type="email" class="card" placeholder="jan@przyklad.pl">
            </div>
            <div class="md:col-span-2">
              <div class="muted">Wybierz godzinę</div>
              <div id="timeSlots" class="slots" role="listbox" aria-label="Dostępne godziny"></div>
            </div>
            <div class="md:col-span-2">
              <label class="muted" for="notes">Dodatkowe informacje</label>
              <textarea id="notes" class="card" rows="3" placeholder="Adres pokazu / preferencje"></textarea>
            </div>
            <label class="md:col-span-2" style="display:flex; gap:8px; align-items:flex-start">
              <input type="checkbox" required style="margin-top:6px">
              <span class="muted" style="font-size:14px">Wyrażam zgodę na kontakt w sprawie rezerwacji pokazu.</span>
            </label>
            <div class="md:col-span-2" style="display:flex; gap:10px; flex-wrap:wrap">
              <button class="btn" type="submit">Zarezerwuj</button>
              <a class="btn alt" href="https://wroclaw.raypath.info" target="_blank" rel="noopener">Kup teraz</a>
            </div>
            <p id="bookingMsg" class="muted" style="font-size:12px"></p>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- O NAS -->
  <section id="o-nas">
    <div class="container grid grid-2" style="align-items:center">
      <img class="shadow" src="https://images.unsplash.com/photo-1504805572947-34fad45aed93?q=80&w=1600&auto=format&fit=crop" alt="Zespół konsultantów" style="border-radius:24px">
      <div>
        <h2 style="font-size:28px; margin:0 0 6px 0">Raypath — Wrocław</h2>
        <p class="muted">Lokalny zespół konsultantów. Prowadzimy pokazy i dobieramy zestawy pod Twoje potrzeby: dom, samochód, biuro.</p>
        <ul style="margin-top:10px">
          <li>Legalne użycie znaków towarowych Raypath® (pisemna zgoda).</li>
          <li>Sprzedaż online i offline: pokazy, targi, social media.</li>
          <li>Wsparcie posprzedażowe i instruktaże wideo.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- OPINIE -->
  <section id="opinie" style="background:#fff; border-top:1px solid var(--ring); border-bottom:1px solid var(--ring)">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Opinie klientów</h2>
      <div class="grid grid-3" style="margin-top:18px">
        <figure class="card shadow"><blockquote>“Świetna demonstracja, sprzątanie szybciej i bez zapachu chemii.”</blockquote><div class="divider"></div><figcaption class="muted" style="font-size:14px">Anna, Wrocław</figcaption></figure>
        <figure class="card shadow"><blockquote>“Mopy do podłóg — petarda. Okna zrobiłam w 15 minut.”</blockquote><div class="divider"></div><figcaption class="muted" style="font-size:14px">Kasia</figcaption></figure>
        <figure class="card shadow"><blockquote>“Do auta najlepszy zestaw, kokpit i szyby lśnią.”</blockquote><div class="divider"></div><figcaption class="muted" style="font-size:14px">Michał</figcaption></figure>
      </div>
    </div>
  </section>

  <!-- GALERIA -->
  <section id="galeria" style="background:#fff; border-top:1px solid var(--ring); border-bottom:1px solid var(--ring)">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Galeria pokazów</h2>
      <p class="muted">Zdjęcia z prezentacji domowych i eventów. Kliknij, aby powiększyć.</p>
      <div class="grid grid-3" style="margin-top:18px">
        <img class="shadow" src="img/real-life/pokaz-01.jpg" alt="Pokaz w domu — kuchnia" data-lightbox>
        <img class="shadow" src="img/real-life/pokaz-02.jpg" alt="Prezentacja materiałów — łazienka" data-lightbox>
        <img class="shadow" src="img/real-life/pokaz-03.jpg" alt="Czyszczenie szyb — demo" data-lightbox>
        <img class="shadow" src="img/real-life/pokaz-04.jpg" alt="Stoisko na targach" data-lightbox>
        <img class="shadow" src="img/real-life/pokaz-05.jpg" alt="Zestaw do auta — kokpit" data-lightbox>
        <img class="shadow" src="img/real-life/pokaz-06.jpg" alt="ECOBody Care — demo SPA" data-lightbox>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Najczęstsze pytania</h2>
      <div class="grid" style="margin-top:10px">
        <details class="card">
          <summary>Czy naprawdę nie używacie chemii?</summary>
          <p class="muted">Tak. Standardowe mycie odbywa się wyłącznie przy użyciu wody i odpowiednio dobranych czyścików z mikrowłókna.</p>
        </details>
        <details class="card">
          <summary>Czym jest technologia NanoSilver?</summary>
          <p class="muted">To dodatek nanosrebra we włóknach, który ogranicza namnażanie bakterii w materiale.* Produkt nie jest środkiem dezynfekującym.</p>
        </details>
        <details class="card">
          <summary>Jak zamówić pokaz?</summary>
          <p class="muted">Wypełnij formularz poniżej lub zadzwoń — oddzwonimy i ustalimy dogodny termin.</p>
        </details>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section style="background:#0a0a0a; color:#fff">
    <div class="container" style="display:flex; gap:16px; align-items:center; justify-content:space-between; flex-wrap:wrap">
      <div>
        <h3 style="margin:0">Chcesz zobaczyć produkty na żywo?</h3>
        <p class="muted" style="color:#cbd5e1">Zorganizujemy pokaz w domu lub spotkajmy się na evencie.</p>
      </div>
      <a class="btn" href="#pokazy" style="background:#fff; color:#0a0a0a">Umów termin</a>
    </div>
  </section>

  <!-- KONTAKT -->
  <section id="kontakt">
    <div class="container">
      <h2 style="font-size:28px; margin:0 0 6px 0">Kontakt</h2>
      <p class="muted">Oddział Wrocław • <a href="https://maps.google.com/?q=Kie%C5%82czowska+138A,+Wroc%C5%82aw" target="_blank" rel="noopener">ul. Kiełczowska 138A, Wrocław</a> • tel. <a href="tel:+48794566404">794 566 404</a> • <a href="mailto:raypathwroclaw@gmail.com">raypathwroclaw@gmail.com</a></p>
      <form class="grid grid-2" style="margin-top:16px; gap:12px" onsubmit="event.preventDefault(); alert('Dziękujemy! Skontaktujemy się wkrótce.');">
        <input class="card" placeholder="Imię i nazwisko" required>
        <input class="card" type="email" placeholder="E-mail" required>
        <input class="card" placeholder="Telefon" pattern="[0-9 +()-]{7,}">
        <textarea class="card" rows="4" placeholder="Wiadomość / preferowany termin"></textarea>
        <label class="card" style="display:flex; align-items:flex-start; gap:8px">
          <input type="checkbox" required style="margin-top:6px">
          <span class="muted" style="font-size:14px">Wyrażam zgodę na kontakt w celu przedstawienia oferty i umówienia pokazu. Administratorem danych jest Oddział Wrocław.</span>
        </label>
        <button class="btn" type="submit">Wyślij</button>
      </form>
      <p class="muted" style="font-size:12px; margin-top:10px">* Informacyjnie: treści marketingowe nie stanowią obietnicy efektu; kosmetyki i suplementy nie leczą chorób.</p>
    </div>
  </section>

  <footer>
    <div class="container" style="display:flex; flex-wrap:wrap; align-items:center; justify-content:space-between; gap:12px; padding:22px 0">
      <p style="font-size:14px">© <span id="year"></span> Raypath — Oddział Wrocław. Wszelkie prawa zastrzeżone.</p>
      <p class="muted" style="font-size:12px">Znaki towarowe Raypath® użyte za pisemną zgodą. Strona informacyjno‑sprzedażowa.</p>
    </div>
  </footer>

  <script>
    // Rok w stopce
    document.getElementById('year').textContent = new Date().getFullYear();

    // Smooth scroll dla linków nawigacji
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        const id=a.getAttribute('href').slice(1);
        const el=document.getElementById(id);
        if(el){ e.preventDefault(); el.scrollIntoView({behavior:'smooth'}); }
      });
    });

    // Mobile nav toggle
    const toggle=document.getElementById('navToggle');
    const nav=document.getElementById('primaryNav');
    const mq=window.matchMedia('(min-width:768px)');
    const setDesktop=()=>{ if(mq.matches){ nav.classList.add('show'); toggle.setAttribute('aria-expanded','true'); } else { nav.classList.remove('show'); toggle.setAttribute('aria-expanded','false'); } };
    setDesktop(); mq.addEventListener('change', setDesktop);
    toggle.addEventListener('click', ()=>{ nav.classList.toggle('show'); const ex=toggle.getAttribute('aria-expanded')==='true'; toggle.setAttribute('aria-expanded', String(!ex)); });
    // === REZERWACJE — PROSTY KALENDARZ ===
    const slots = {};
    function addRecurringSlots(days, times, weeks){
      const today = new Date();
      const end = new Date(today.getTime() + weeks*7*24*60*60*1000);
      for(let d = new Date(today); d <= end; d.setDate(d.getDate()+1)){
        if(days.includes(d.getDay())){
          const key = `${d.getFullYear()}-${String(d.getMonth()+1).padStart(2,'0')}-${String(d.getDate()).padStart(2,'0')}`;
          slots[key] = (slots[key]||[]).concat(times);
        }
      }
    }
    // wtorek (2), czwartek (4), sobota (6) — godziny 10:00 i 17:00, na 8 tygodni
    addRecurringSlots([2,4,6],["10:00","17:00"],8);

    const calGrid = document.getElementById('calGrid');
    const calTitle = document.getElementById('calTitle');
    const prevBtn = document.getElementById('prevMonth');
    const nextBtn = document.getElementById('nextMonth');
    const timeSlots = document.getElementById('timeSlots');
    const bookingForm = document.getElementById('bookingForm');
    const bookingMsg = document.getElementById('bookingMsg');

    let current = new Date();
    current.setDate(1);
    let selectedDate = null;
    let selectedTime = null;

    function fmt(y,m,d){ return `${y}-${String(m+1).padStart(2,'0')}-${String(d).padStart(2,'0')}`; }

    function renderCalendar(){
      calGrid.innerHTML='';
      const y = current.getFullYear();
      const m = current.getMonth();
      calTitle.textContent = current.toLocaleDateString('pl-PL', { month: 'long', year:'numeric'});

      const firstDay = new Date(y,m,1).getDay(); // 0 nd
      const daysInMonth = new Date(y,m+1,0).getDate();
      const startPad = (firstDay+6)%7; // pon=0

      // dni nagłówków
      ['Pn','Wt','Śr','Cz','Pt','So','Nd'].forEach(d=>{
        const el=document.createElement('div'); el.textContent=d; el.className='cal-cell muted'; calGrid.appendChild(el);
      });

      // puste komórki
      for(let i=0;i<startPad;i++){ const el=document.createElement('div'); el.className='cal-cell muted'; el.textContent=''; calGrid.appendChild(el); }

      // dni miesiąca
      for(let d=1; d<=daysInMonth; d++){
        const key = fmt(y,m,d);
        const has = !!slots[key];
        const el = document.createElement('button');
        el.type='button';
        el.className = 'cal-cell' + (has ? ' slot' : '');
        el.textContent = d;
        el.setAttribute('aria-label', has?`Dzień ${d} — dostępne terminy`:`Dzień ${d}`);
        el.addEventListener('click', ()=>{
          // zaznacz
          calGrid.querySelectorAll('.cal-cell').forEach(c=>c.classList.remove('selected'));
          el.classList.add('selected');
          selectedDate = key; selectedTime = null; renderTimes();
        });
        calGrid.appendChild(el);
      }
    }

    function renderTimes(){
      timeSlots.innerHTML='';
      const arr = slots[selectedDate]||[];
      if(arr.length===0){ timeSlots.innerHTML = '<span class="muted">Wybierz dzień z wolnymi terminami.</span>'; return; }
      arr.forEach(t=>{
        const b=document.createElement('button'); b.type='button'; b.className='chip'; b.textContent=t;
        b.addEventListener('click', ()=>{
          timeSlots.querySelectorAll('.chip').forEach(x=>x.classList.remove('active'));
          b.classList.add('active'); selectedTime=t;
        });
        timeSlots.appendChild(b);
      });
    }

    prevBtn?.addEventListener('click', ()=>{ current.setMonth(current.getMonth()-1); renderCalendar(); });
    nextBtn?.addEventListener('click', ()=>{ current.setMonth(current.getMonth()+1); renderCalendar(); });

    bookingForm?.addEventListener('submit', (e)=>{
      e.preventDefault();
      const prod = document.getElementById('productSelect').value;
      const name = document.getElementById('custName').value;
      const phone = document.getElementById('custPhone').value;
      const email = document.getElementById('custEmail').value;
      const notes = document.getElementById('notes').value;

      if(!selectedDate || !selectedTime){ bookingMsg.textContent='Wybierz dzień i godzinę.'; return; }

      const subject = encodeURIComponent(`Rezerwacja pokazu — ${prod} — ${selectedDate} ${selectedTime}`);
      const body = encodeURIComponent(`Imię i nazwisko: ${name}
Telefon: ${phone}
E-mail: ${email}
Termin: ${selectedDate} ${selectedTime}
Produkt: ${prod}
Notatki: ${notes}`);
      const mailto = `mailto:raypathwroclaw@gmail.com?subject=${subject}&body=${body}`;
      window.location.href = mailto;
      bookingMsg.textContent = 'Dziękujemy! Otrzymaliśmy Twoją rezerwację e-mailem.';
    });

    if(calGrid){ renderCalendar(); }
  </script>
  // === LIGHTBOX ===
    const lb = document.createElement('div');
    lb.className='lb-backdrop';
    lb.innerHTML = '<button class="lb-close" aria-label="Zamknij">Zamknij ✕</button><img class="lb-img" alt="Podgląd" />';
    document.body.appendChild(lb);
    const lbImg = lb.querySelector('.lb-img');
    const lbClose = lb.querySelector('.lb-close');
    function openLb(src, alt){ lbImg.src = src; lbImg.alt = alt||''; lb.classList.add('show'); }
    function closeLb(){ lb.classList.remove('show'); lbImg.src=''; }
    lb.addEventListener('click', (e)=>{ if(e.target===lb){ closeLb(); }});
    lbClose.addEventListener('click', closeLb);
    document.addEventListener('keydown', (e)=>{ if(e.key==='Escape') closeLb(); });
    document.querySelectorAll('[data-lightbox]').forEach(el=>{
      el.style.cursor='zoom-in';
      el.addEventListener('click', ()=> openLb(el.src, el.alt));
    });
  </script>
</body>
</html>
