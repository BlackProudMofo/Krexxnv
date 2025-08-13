<!-- index.html — N.V’sion • Executive EPK (deal-ready) -->
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>N.V’sion — Executive EPK</title>
  <meta name="description" content="N.V’sion (Krexx Nv) — visuals, key releases, press, profiles, and contacts for bookings, press, and sync." />
  <meta name="theme-color" content="#0b0b0b" />

  <!-- Open Graph / Twitter -->
  <meta property="og:title" content="N.V’sion — Executive EPK" />
  <meta property="og:description" content="Visuals, releases, press and direct contacts." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="images/header.jpg" />
  <meta name="twitter:card" content="summary_large_image" />

  <!-- Fonts + Tailwind -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;900&family=Space+Grotesk:wght@700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    :root{
      --bg:#0b0b0b; --surface:#121212; --ink:#e6e6e6; --muted:#a3a3a3; --line:#252525;
      --chip:#151515; --accent1:#00e0e0; --accent2:#f59e0b; --vignette:#1a120e;
    }
    html,body{background:var(--bg); color:var(--ink); font-family:Inter,system-ui,sans-serif}
    /* subtle dark-brown vignette */
    body::before{content:""; position:fixed; inset:0; pointer-events:none;
      background:radial-gradient(80% 80% at 50% 50%, rgba(26,18,14,0) 60%, rgba(26,18,14,.45) 100%);}

    header{background:rgba(0,0,0,.85); backdrop-filter:saturate(160%) blur(8px); border-bottom:1px solid var(--line)}
    .brand-title{
      font-family:"Space Grotesk",Inter,sans-serif; font-weight:800; letter-spacing:-.01em;
      background:linear-gradient(90deg,var(--accent1),var(--accent2));
      -webkit-background-clip:text; background-clip:text; color:transparent;
    }
    .section-title{font-family:"Space Grotesk",Inter,sans-serif; font-weight:800; font-size:clamp(1.75rem,3.2vw,2.25rem)}
    .btn{border:1px solid var(--line); background:var(--surface); padding:.6rem .95rem; border-radius:.7rem}
    .pill{display:inline-flex; align-items:center; gap:.4rem; padding:.45rem .8rem; border-radius:999px; background:var(--chip); border:1px solid var(--line); font-size:.9rem}
    .card{background:var(--surface); border:1px solid var(--line)}
    .accent-underline{position:relative; display:inline-block}
    .accent-underline::after{content:""; position:absolute; left:0; right:0; bottom:-4px; height:3px;
      background:linear-gradient(90deg,var(--accent1),var(--accent2)); border-radius:2px; opacity:.7}

    /* NON-CROPPED header image: show full image via object-fit:contain */
    .hero-photo{width:100%; height:clamp(260px,36vw,440px); object-fit:contain; display:block; background:#0a0a0a}
    section{scroll-margin-top:76px} /* sticky header offset */

    /* Print = one-sheet */
    @media print{
      @page{margin:12mm}
      header,#videos,#press,#links,footer{display:none!important}
      body{background:#fff;color:#111}
      .brand-title,.section-title{color:#000!important; background:none!important; -webkit-text-fill-color:#000!important}
      .card,.pill{border-color:#ddd; background:#fff}
      a{color:#111; text-decoration:underline}
    }
  </style>
</head>
<body class="antialiased">

  <!-- Sticky Nav -->
  <header class="sticky top-0 z-40">
    <nav class="container mx-auto px-6 py-3 flex items-center justify-between">
      <a href="#hero" class="text-lg md:text-xl brand-title">N.V’sion</a>
      <div class="hidden md:flex items-center gap-6 text-[var(--muted)] text-sm">
        <a href="#bio">Bio</a><a href="#videos">Visuals</a><a href="#music">Music</a>
        <a href="#press">Press</a><a href="#links">Profiles & Lyrics</a><a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <!-- Hero -->
  <section id="hero" class="border-b border-[var(--line)]">
    <div class="container mx-auto px-6 py-8 md:py-12">
      <div class="flex flex-col md:flex-row md:items-end md:justify-between gap-6">
        <div>
          <h1 class="text-3xl md:text-5xl brand-title">N.V’sion</h1>
          <p class="mt-1 text-[var(--muted)]">When it whispers we synchronize</p>
        </div>
        <div class="flex gap-3 overflow-x-auto snap-x">
          <a href="#videos" class="btn snap-start">Get latest visuals here</a>
          <a href="#music" class="btn snap-start">New collections</a>
          <button onclick="window.print()" class="btn snap-start">Download one-sheet (PDF)</button>
        </div>
      </div>
    </div>

    <!-- Use your new header photo as /images/header.jpg; a remote fallback is provided -->
    <img class="hero-photo"
         src="images/header.jpg"
         onerror="this.src='https://cdn.pmnewsnigeria.com/wp-content/uploads/2024/09/e010352f-41ff-4b24-95e8-6813e40efd94.jpeg';"
         alt="N.V’sion portrait banner">
  </section>

  <!-- BIO -->
  <section id="bio" class="py-12 md:py-16">
    <div class="container mx-auto px-6">
      <h2 class="section-title mb-6"><span class="accent-underline">WANNA KNOW MORE? FOLLOW ME!</span></h2>
      <div class="max-w-3xl text-[var(--ink)]/90 leading-relaxed space-y-4">
        <p>Krexx Nv (Honest Ornan Okoawo) is a Nigerian singer and songwriter born on July 9, 1996, in Benin City, Nigeria. Renowned for his introspective lyrics and genre-blending sound, he combines Afrobeat, R&amp;B, and rap to craft music that resonates both locally and internationally.</p>
        <p>He began his musical journey in 2012, experimenting with freestyles and cover recordings. In 2024, he gained widespread recognition with the release of his EP <em>INTEL (Inside The Eko Life)</em>, a project that captures the vibrancy and complexity of urban life in Lagos.</p>
        <p>Influenced by artists such as Kendrick Lamar, Damian Marley, and 6LACK, Krexx explores themes of resilience, love, personal growth, and cultural identity, appealing to a broad and diverse audience.</p>
      </div>
    </div>
  </section>

  <!-- VISUALS -->
  <section id="videos" class="py-12 md:py-16">
    <div class="container mx-auto px-6">
      <h2 class="section-title text-center mb-10"><span class="accent-underline">Visuals</span></h2>
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto">
        <!-- No overlay glyphs; clean embedded players (autoplay muted loop) -->
        <figure class="rounded-lg overflow-hidden border border-[var(--line)] bg-[var(--surface)] shadow-sm">
          <div class="relative w-full" style="aspect-ratio:16/9">
            <iframe class="absolute inset-0 w-full h-full"
              src="https://www.youtube.com/embed/LX9GEuXQVcA?autoplay=1&mute=1&controls=1&rel=0&playsinline=1&loop=1&playlist=LX9GEuXQVcA"
              title="The Invite" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen loading="lazy"></iframe>
          </div>
          <figcaption class="px-3 py-2 text-[var(--muted)] text-sm">The Invite</figcaption>
        </figure>

        <figure class="rounded-lg overflow-hidden border border-[var(--line)] bg-[var(--surface)] shadow-sm">
          <div class="relative w-full" style="aspect-ratio:16/9">
            <iframe class="absolute inset-0 w-full h-full"
              src="https://www.youtube.com/embed/rxT8jT0QZGM?autoplay=1&mute=1&controls=1&rel=0&playsinline=1&loop=1&playlist=rxT8jT0QZGM"
              title="Reason (feat. Shi Boi)" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen loading="lazy"></iframe>
          </div>
          <figcaption class="px-3 py-2 text-[var(--muted)] text-sm">Reason (feat. Shi Boi)</figcaption>
        </figure>

        <figure class="rounded-lg overflow-hidden border border-[var(--line)] bg-[var(--surface)] shadow-sm">
          <div class="relative w-full" style="aspect-ratio:16/9">
            <iframe class="absolute inset-0 w-full h-full"
              src="https://www.youtube.com/embed/n3Bb4QynU2g?autoplay=1&mute=1&controls=1&rel=0&playsinline=1&loop=1&playlist=n3Bb4QynU2g"
              title="My Belle" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen loading="lazy"></iframe>
          </div>
          <figcaption class="px-3 py-2 text-[var(--muted)] text-sm">My Belle</figcaption>
        </figure>

        <figure class="rounded-lg overflow-hidden border border-[var(--line)] bg-[var(--surface)] shadow-sm">
          <div class="relative w-full" style="aspect-ratio:16/9">
            <iframe class="absolute inset-0 w-full h-full"
              src="https://www.youtube.com/embed/sGDYGEA4Kmk?autoplay=1&mute=1&controls=1&rel=0&playsinline=1&loop=1&playlist=sGDYGEA4Kmk"
              title="Close to Me" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen loading="lazy"></iframe>
          </div>
          <figcaption class="px-3 py-2 text-[var(--muted)] text-sm">Close to Me</figcaption>
        </figure>

        <figure class="rounded-lg overflow-hidden border border-[var(--line)] bg-[var(--surface)] shadow-sm">
          <div class="relative w-full" style="aspect-ratio:16/9">
            <iframe class="absolute inset-0 w-full h-full"
              src="https://www.youtube.com/embed/MEe63F72XvY?autoplay=1&mute=1&controls=1&rel=0&playsinline=1&loop=1&playlist=MEe63F72XvY"
              title="Better or Worse" allow="autoplay; encrypted-media; picture-in-picture" allowfullscreen loading="lazy"></iframe>
          </div>
          <figcaption class="px-3 py-2 text-[var(--muted)] text-sm">Better or Worse</figcaption>
        </figure>
      </div>
    </div>
  </section>

  <!-- MUSIC -->
  <section id="music" class="py-12 md:py-16">
    <div class="container mx-auto px-6">
      <h2 class="section-title text-center mb-10"><span class="accent-underline">Selected Releases</span></h2>

      <!-- VENUS (2025) -->
      <div class="grid md:grid-cols-3 gap-8 items-center mb-12">
        <div class="rounded-lg overflow-hidden shadow-sm card">
          <!-- swap this image if you prefer the provided Venus cover -->
          <img src="images/venus.jpg" alt="VENUS cover" onerror="this.src='https://i.imgur.com/4Qy7lVQ.png';" class="w-full h-full object-cover">
        </div>
        <div class="md:col-span-2">
          <h3 class="text-2xl font-semibold">VENUS <span class="text-sm text-[var(--muted)]">(2025)</span></h3>
          <div class="mt-3 flex flex-wrap gap-2">
            <a class="pill" target="_blank" href="https://ditto.fm/venus_krexx_nv_d2">Pre-save / Pre-add</a>
          </div>
        </div>
      </div>

      <!-- These & More (Single) -->
      <div class="grid md:grid-cols-3 gap-8 items-center mb-12">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzPVN5Pcm9LnLOR7rBO_r2fBzfoRfFFyEIxGLgkmiznqBxuBAzsCZ1hdg&s=10" class="rounded-lg shadow-sm border border-[var(--line)] w-full" alt="These & More cover">
        <div class="md:col-span-2">
          <h3 class="text-2xl font-semibold">These &amp; More <span class="text-sm text-[var(--muted)]">(Single)</span></h3>
          <div class="mt-3 flex flex-wrap gap-2">
            <a class="pill" target="_blank" href="https://open.spotify.com/track/3SrBFUzmyREQVp6kCN8KCP?si=x5OHISPUTFG4KyAH-aO7BA">Spotify</a>
            <a class="pill" target="_blank" href="https://music.apple.com/us/album/these-more/1831152829?i=1831152834">Apple Music</a>
            <a class="pill" target="_blank" href="https://tidal.com/browse/album/452212932?u">Tidal</a>
            <a class="pill" target="_blank" href="https://genius.com/Krexx-nv-these-and-more-lyrics">Genius Lyrics</a>
          </div>
        </div>
      </div>

      <!-- Cause & Effect (Album + tracks) -->
      <div class="grid md:grid-cols-3 gap-8 items-start mb-12">
        <div>
          <img src="https://is1-ssl.mzstatic.com/image/thumb/Music221/v4/39/d1/b6/39d1b606-680e-1809-253b-3797d8eb4bfe/5063778364748_cover.jpg/1200x630bb.jpg" class="rounded-lg shadow-sm border border-[var(--line)] w-full mb-3" alt="Cause & Effect cover">
          <div class="flex flex-wrap gap-2">
            <a class="pill" target="_blank" href="https://open.spotify.com/album/7i98RkrhHqam9Ou9HSc8cT?si=yhMHTyrhQ_ScDvIXEvO5XQ">Spotify</a>
            <a class="pill" target="_blank" href="https://music.apple.com/ng/album/cause-effect/1826575177">Apple Music</a>
            <a class="pill" target="_blank" href="https://www.boomplay.com/share/album/113573245?srModel=COPYLINK&srList=IOS">Boomplay</a>
            <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/album/the-dungeons-depths?share-user-id=20597811">Audiomack</a>
            <a class="pill" target="_blank" href="https://music.youtube.com/playlist?list=OLAK5uy_nePVZYdpHWyT6htw9oI2klsSROcEGZz08&si=gzCBIvFPBgG61CFm">YouTube Music</a>
          </div>
        </div>
        <div class="md:col-span-2 flex flex-col gap-4">
          <iframe style="border-radius:10px;border:1px solid var(--line)" src="https://open.spotify.com/embed/album/7i98RkrhHqam9Ou9HSc8cT?utm_source=generator" width="100%" height="300" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy" title="Spotify: Cause & Effect"></iframe>

          <details class="card rounded-md p-4">
            <summary class="cursor-pointer font-semibold">Track links</summary>
            <div class="mt-3 grid md:grid-cols-2 gap-3">
              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">Better or Worse</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/2hUcWskASfNu5GRs4AFtqU?si=4BYIdpdsSteFcCwEQV59wg">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/better-or-worse/1826575177?i=1826575200">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211616812?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/4-better-or-worse-freestyle?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=Qa80_LWkv-k">YouTube Music</a>
                </div>
              </div>

              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">Hussle</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/3XqOfk1PBW59oB3gt7J1j2?si=gVzazy9ORGWR_YKJmpmsKw">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/hussle/1826575177?i=1826575335">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211619720?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/projectkrexx-hus?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=mJ2NnrC5D2Q">YouTube Music</a>
                </div>
              </div>

              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">On Code</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/3zFPV0Lm9hEdXR7BPRhzoq?si=2_2AFUm7QIieqzWdQ3Lwlw">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/on-code/1826575177?i=1826575347">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211619721?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/on-code?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=HRI2s7UzsZQ">YouTube Music</a>
                </div>
              </div>

              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">The Dialogue Room</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/2RKFLunMmaXiXCPIx63PXh?si=qaFET19bStCi-CvYvk6gHQ">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/the-dialogue-room/1826575177?i=1826575348">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211616815?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/the-dialogue-room?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=UTezFZlNEWA">YouTube Music</a>
                </div>
              </div>

              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">Rough Dust</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/5rL6YMAscYLrKdRn97HFwE?si=Sp4z0JigT5uK6GQXlaVRdg">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/rough-dust/1826575177?i=1826575601">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211619723?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/tsd-rough-dust-freestyle?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=6s0foaQxkv0">YouTube Music</a>
                </div>
              </div>

              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">Cause &amp; Effect</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/4hZciQwrRqgXhF4avVfvGE?si=7C-B4crpRfGHTP9ikCuW5Q">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/cause-effect/1826575177?i=1826575602">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211619724?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/cause-effect?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=usD9ch5FRxw">YouTube Music</a>
                </div>
              </div>

              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">Grin</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/41Yu0foKYp3IsJZiMRYiYJ?si=UzelaNksSuuPBVILL2dIIQ">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/grin/1826575177?i=1826575603">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211619726?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/it-is-what-it-is?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=WLM4OZPryrk">YouTube Music</a>
                </div>
              </div>

              <div class="p-3 rounded-md border border-[var(--line)] bg-[var(--surface)]">
                <div class="font-medium">Alive (feat. Jay Teazer)</div>
                <div class="mt-2 flex flex-wrap gap-2">
                  <a class="pill" target="_blank" href="https://open.spotify.com/track/5QBqKQWnfYeV11qjpnZrQ1?si=mcpDvCvPTrywyivXFTjmGQ">Spotify</a>
                  <a class="pill" target="_blank" href="https://music.apple.com/ng/album/alive-feat-jay-teazer/1826575177?i=1826575608">Apple Music</a>
                  <a class="pill" target="_blank" href="https://www.boomplay.com/share/music/211619727?srModel=COPYLINK&srList=IOS">Boomplay</a>
                  <a class="pill" target="_blank" href="https://audiomack.com/krexxnv/song/krexx-nv-x-jay-teazer-feel-alive?share-user-id=20597811">Audiomack</a>
                  <a class="pill" target="_blank" href="https://music.youtube.com/watch?v=4tMuUaiIVBM">YouTube Music</a>
                </div>
              </div>
            </div>
          </details>
        </div>
      </div>

      <!-- INTEL -->
      <div class="grid md:grid-cols-3 gap-8 items-center mb-12">
        <div>
          <img src="https://cdn-images.dzcdn.net/images/cover/9bf21fe6c49f5b98269302731b6ea774/1900x1900-000000-80-0-0.jpg" class="rounded-lg shadow-sm border border-[var(--line)] w-full mb-3" alt="INTEL (Inside The Eko Life)">
          <div class="mt-3 flex flex-wrap gap-2">
            <a class="pill" target="_blank" href="https://music.apple.com/ng/album/intel-inside-the-eko-life/1824506045">Apple Music</a>
            <a class="pill" target="_blank" href="https://open.spotify.com/album/27v0mFXY5hjNEDmc12Oaip?si=OR7-Wj7QT_6vSZKehJyJPg">Spotify</a>
            <a class="pill" target="_blank" href="https://tidal.com/browse/album/445925767?u">Tidal</a>
            <a class="pill" target="_blank" href="https://www.boomplay.com/share/album/93142586?srModel=COPYLINK&srList=IOS">Boomplay</a>
          </div>
        </div>
        <div class="md:col-span-2 flex items-center">
          <iframe style="border-radius:10px;border:1px solid var(--line)" src="https://open.spotify.com/embed/album/27v0mFXY5hjNEDmc12Oaip?utm_source=generator" width="100%" height="300" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy" title="Spotify: INTEL"></iframe>
        </div>
      </div>

      <!-- Body Mind & Soul -->
      <div class="grid md:grid-cols-3 gap-8 items-center mb-12">
        <div>
          <img src="https://images.genius.com/37c97dec8bb100ba4fb885b9eb48bdef.1000x1000x1.jpg" class="rounded-lg shadow-sm border border-[var(--line)] w-full mb-3" alt="Body Mind & Soul">
          <div class="mt-3 flex flex-wrap gap-2">
            <a class="pill" target="_blank" href="https://open.spotify.com/album/3dDJbaXfHHFndLUOdeJDQA?si=U6aHUBjXSQqKa01jEhzuxA">Spotify</a>
            <a class="pill" target="_blank" href="https://music.apple.com/ng/album/body-mind-soul-single/1825189805">Apple Music</a>
            <a class="pill" target="_blank" href="https://tidal.com/browse/album/446584061?u">Tidal</a>
          </div>
        </div>
        <div class="md:col-span-2 flex items-center">
          <iframe style="border-radius:10px;border:1px solid var(--line)" src="https://open.spotify.com/embed/album/3dDJbaXfHHFndLUOdeJDQA?utm_source=generator" width="100%" height="300" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy" title="Spotify: Body Mind & Soul"></iframe>
        </div>
      </div>

      <!-- The Dungeon's Depths -->
      <div class="grid md:grid-cols-3 gap-8 items-center">
        <div>
          <img src="https://source.boomplaymusic.com/group10/M00/06/11/10d4e51d7eb848aba23008d775fe2e17H3000W3000_320_320.jpg" class="rounded-lg shadow-sm border border-[var(--line)] w-full mb-3" alt="The Dungeon's Depths">
          <div class="mt-3 flex flex-wrap gap-2">
            <a class="pill" target="_blank" href="https://open.spotify.com/album/6iZsgyeeJJG2lV9mengGJW?si=VrhQwnfjRKyVX0HxLOZDjw">Spotify</a>
            <a class="pill" target="_blank" href="https://tidal.com/browse/album/441412388?u">Tidal</a>
            <a class="pill" target="_blank" href="https://www.boomplay.com/share/album/111999311?srModel=COPYLINK&srList=IOS">Boomplay</a>
          </div>
        </div>
        <div class="md:col-span-2 flex items-center">
          <iframe style="border-radius:10px;border:1px solid var(--line)" src="https://open.spotify.com/embed/album/6iZsgyeeJJG2lV9mengGJW?utm_source=generator" width="100%" height="300" frameborder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy" title="Spotify: The Dungeon's Depths"></iframe>
        </div>
      </div>

      <!-- Road Side Two -->
      <div class="grid md:grid-cols-3 gap-8 items-center mt-12">
        <div class="rounded-lg overflow-hidden shadow-sm card">
          <!-- Put the BLUE cover at /images/road-side-two.jpg -->
          <img src="images/road-side-two.jpg" onerror="this.src='images/road-side-two.jpg';" class="w-full h-full object-cover" alt="Road Side Two cover">
        </div>
        <div class="md:col-span-2">
          <h3 class="text-2xl font-semibold">Road Side Two</h3>
          <p class="text-sm text-[var(--muted)]">Debut joint EP with Shi Boi • 26 June 2025</p>
          <div class="mt-3 flex flex-wrap gap-2">
            <a class="pill" target="_blank" href="https://ditto.fm/road-side-two">Listen / Pre-save</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PRESS -->
  <section id="press" class="py-12 md:py-16">
    <div class="container mx-auto px-6">
      <h2 class="section-title text-center mb-8"><span class="accent-underline">Press</span></h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl mx-auto">
        <a target="_blank" href="https://www.vanguardngr.com/singer-krexx-nv-sets-new-standard-with-musical-uniqueness" class="block card rounded-lg p-6 hover:bg-[#161616] transition-colors">
          <p class="italic leading-snug">“Sets a new standard with musical uniqueness.”</p>
          <p class="mt-3 text-sm text-[var(--muted)]">Vanguard</p>
        </a>
        <a target="_blank" href="https://leadership.ng/krexx-nv-musical-maverick-storming-the-nigerian-music-industry" class="block card rounded-lg p-6 hover:bg-[#161616] transition-colors">
          <p class="italic leading-snug">“Musical maverick storming the Nigerian music industry.”</p>
          <p class="mt-3 text-sm text-[var(--muted)]">Leadership</p>
        </a>
        <a target="_blank" href="https://www.thisdaylive.com/index.php/2024/08/11/krexx-nv-creates-masterpiece-with-debut-album-intel" class="block card rounded-lg p-6 hover:bg-[#161616] transition-colors">
          <p class="italic leading-snug">“Creates a masterpiece with debut album INTEL.”</p>
          <p class="mt-3 text-sm text-[var(--muted)]">THISDAYLIVE</p>
        </a>
      </div>
      <div class="max-w-3xl mx-auto mt-6">
        <a target="_blank" href="https://medium.com/@jaythunderstrikes/the-dialogue-krexx-nv-x-lois-822648c3cae5" class="block card rounded-lg p-5 hover:bg-[#161616] transition-colors">
          <h3 class="font-semibold">Featured Interview</h3>
          <p class="text-[var(--muted)] mt-1">“The Dialogue — Krexx Nv x Lois” (Medium)</p>
        </a>
      </div>
    </div>
  </section>

  <!-- PROFILES & LYRICS -->
  <section id="links" class="py-12 md:py-16">
    <div class="container mx-auto px-6">
      <h2 class="section-title text-center mb-8"><span class="accent-underline">Profiles & Lyrics</span></h2>
      <div class="flex flex-wrap justify-center gap-3">
        <a class="pill" target="_blank" href="https://instagram.com/krexxnv">Instagram @krexxnv</a>
        <a class="pill" target="_blank" href="https://www.tiktok.com/@krexxnv">TikTok @krexxnv</a>
        <a class="pill" target="_blank" href="https://genius.com/artists/Krexx-nv">Genius — Artist Page</a>
        <a class="pill" target="_blank" href="https://genius.com/Krexx-nv-these-and-more-lyrics">“These &amp; More” Lyrics</a>
        <a class="pill" target="_blank" href="https://krexxnv.com">Official Website</a>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-12 md:py-16">
    <div class="container mx-auto px-6 text-center">
      <h2 class="section-title mb-4"><span class="accent-underline">Contact</span></h2>
      <p class="text-[var(--muted)] mb-4 max-w-xl mx-auto">Bookings, press, or sync & licensing.</p>
      <div class="flex flex-col md:flex-row justify-center items-center gap-8 mb-2">
        <a href="mailto:info@krexxnv.com" class="btn">info@krexxnv.com</a>
        <a href="tel:+2349167628105" class="btn">+234 916 762 8105</a>
      </div>
    </div>
  </section>

  <footer class="py-6">
    <div class="container mx-auto px-6 text-center text-[var(--muted)]">
      <p>&copy; <span id="year"></span> N.V’sion. All Rights Reserved.</p>
    </div>
  </footer>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>

  <!-- JSON-LD (basic) -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"MusicGroup",
    "name":"Krexx Nv",
    "alternateName":"N.V’sion",
    "genre":["Afrobeats","R&B","Rap"],
    "sameAs":["https://instagram.com/krexxnv","https://www.tiktok.com/@krexxnv","https://genius.com/artists/Krexx-nv","https://krexxnv.com"],
    "foundingLocation":"Lagos, Nigeria",
    "contactPoint":[{"@type":"ContactPoint","contactType":"press","email":"info@krexxnv.com"}]
  }
  </script>
</body>
</html>
