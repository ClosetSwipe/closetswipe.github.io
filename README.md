<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ClosetSwipe • Download Now</title>
  <meta name="description" content="ClosetSwipe is the swipe-first fashion resale app. Download now and start discovering, styling, and selling instantly." />

  <!-- Inter font -->
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg: #9DCCAA;
      --card: #ffffff;
      --text: #1f2a24;
      --subtle: #2f3a35;
      --accent: #3E5F47;
      --accent-press: #2f4a38;
      --ring: rgba(62,95,71,0.35);
      --ok: #1f9d5a;
      --err: #b23a48;
      --pink: #f05e86;
    }
    *{box-sizing:border-box}
    html,body{
      height:100%;
      margin:0;
      font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:var(--text);
      background:var(--bg);
    }
    .wrap{
      min-height:100%;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:24px;
    }
    .card{
      width:100%;
      max-width:720px;
      background:var(--card);
      border-radius:24px;
      box-shadow: 0 10px 30px rgba(0,0,0,.10);
      padding: clamp(20px, 6vw, 48px);
      position:relative;
      overflow:hidden;
    }
    .badge{
      display:inline-flex;
      gap:8px;
      align-items:center;
      font-weight:600;
      font-size:12px;
      letter-spacing:.08em;
      text-transform:uppercase;
      color:var(--subtle);
      background: #eef7f0;
      padding:8px 12px;
      border-radius:999px;
    }
    h1{
      margin:16px 0 8px;
      font-weight:800;
      line-height:1.05;
      font-size: clamp(28px, 6vw, 48px);
      letter-spacing:-0.02em;
    }
    .pink{ color: var(--pink); }

    p.lede{
      margin:0 0 28px;
      font-size: clamp(16px, 2.6vw, 18px);
      color:#4a5a52;
    }
    form{
      display:flex;
      gap:12px;
      flex-wrap:wrap;
    }
    .field{
      flex:1 1 260px;
      display:flex;
      align-items:center;
      background:#f6fbf7;
      border:1.5px solid transparent;
      border-radius:14px;
      padding:6px 10px 6px 14px;
    }
    input[type="email"]{
      border:0;
      outline:0;
      width:100%;
      font-size:16px;
      background:transparent;
      padding:10px 6px;
    }
    button{
      border:0;
      cursor:pointer;
      border-radius:14px;
      padding:12px 18px;
      font-weight:700;
      font-size:16px;
      color:#fff;
      background:var(--accent);
      box-shadow:0 6px 18px rgba(62,95,71,0.35);
    }
  </style>
</head>
<body>
  <main class="wrap">
    <section class="card" aria-labelledby="title">
      <span class="badge">ClosetSwipe • Live</span>

      <h1 id="title">
        <span class="pink">Swipe</span>. Style. Sell.
      </h1>

      <p class="lede">
        ClosetSwipe is the swipe-first fashion resale app. Discover pieces you love,
        save them in seconds, and sell effortlessly — all in one place.
      </p>

      <form id="waitlist-form" novalidate>
        <label class="field" for="email">
          <input id="email" name="email" type="email"
                 placeholder="your@email.com" required />
        </label>
        <button id="submitBtn" type="submit">Download now</button>
      </form>
    </section>
  </main>
</body>
</html>
