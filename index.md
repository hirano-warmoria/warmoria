
<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>warmoria | 採用</title>
  <meta name="description" content="新たな教育のカタチを作る仲間募集。STEAM教育スクール zunŌw を運営する warmoria の採用ページ。" />
  <style>
    :root{
      --bg:#0b1020;
      --card:rgba(255,255,255,.06);
      --line:rgba(255,255,255,.12);
      --text:rgba(255,255,255,.92);
      --muted:rgba(255,255,255,.70);
      --brand:#7c5cff;
      --brand2:#22d3ee;
      --shadow: 0 18px 60px rgba(0,0,0,.45);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Hiragino Kaku Gothic ProN", "Noto Sans JP", "Yu Gothic", sans-serif;
      color:var(--text);
      background:
        radial-gradient(1200px 600px at 20% 0%, rgba(124,92,255,.28), transparent 60%),
        radial-gradient(900px 500px at 85% 20%, rgba(34,211,238,.18), transparent 55%),
        radial-gradient(900px 700px at 40% 90%, rgba(124,92,255,.16), transparent 60%),
        var(--bg);
      min-height:100vh;
    }
    a{color:inherit; text-decoration:none}
    .wrap{max-width:1040px; margin:0 auto; padding:28px 18px 72px}
    .topbar{
      display:flex; align-items:center; justify-content:space-between;
      padding:10px 0 26px;
    }
    .logo{
      font-weight:800; letter-spacing:.3px; font-size:20px;
      display:flex; align-items:center; gap:10px;
    }
    .dot{
      width:10px; height:10px; border-radius:999px;
      background: linear-gradient(90deg, var(--brand), var(--brand2));
      box-shadow: 0 0 18px rgba(124,92,255,.55);
    }
    .pill{
      border:1px solid var(--line);
      background: rgba(255,255,255,.04);
      padding:10px 14px;
      border-radius:999px;
      font-size:13px;
      color:var(--muted);
    }
    .hero{
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap:18px;
      margin-top:10px;
    }
    @media (max-width: 880px){
      .hero{grid-template-columns:1fr}
    }
    .card{
      border:1px solid var(--line);
      background: var(--card);
      border-radius:18px;
      box-shadow: var(--shadow);
      overflow:hidden;
    }
    .heroMain{padding:34px 30px}
    .kicker{
      display:inline-flex; align-items:center; gap:10px;
      padding:8px 12px;
      border-radius:999px;
      border:1px solid var(--line);
      background: rgba(255,255,255,.04);
      font-size:12px;
      color:var(--muted);
    }
    h1{
      margin:14px 0 10px;
      font-size:42px;
      line-height:1.15;
      letter-spacing:-.4px;
    }
    @media (max-width: 560px){
      h1{font-size:34px}
    }
    .lead{
      margin:0;
      color:var(--muted);
      font-size:16px;
      line-height:1.8;
      max-width:60ch;
    }
    .ctaRow{display:flex; gap:10px; flex-wrap:wrap; margin-top:18px}
    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:12px 16px;
      border-radius:12px;
      border:1px solid var(--line);
      background: rgba(255,255,255,.04);
      color:var(--text);
      font-weight:700;
      font-size:14px;
    }
    .btnPrimary{
      border:0;
      background: linear-gradient(90deg, var(--brand), var(--brand2));
      color:#0b1020;
      box-shadow: 0 10px 30px rgba(124,92,255,.25);
    }
    .btn:hover{transform: translateY(-1px)}
    .btn{transition: .15s ease}
    .heroSide{padding:26px 22px}
    .sideTitle{margin:0 0 10px; font-size:14px; color:var(--muted); letter-spacing:.2px}
    .mini{
      border-top:1px solid var(--line);
      padding-top:14px;
      margin-top:14px;
      color:var(--muted);
      font-size:13px;
      line-height:1.85;
    }
    .section{
      margin-top:18px;
      padding:26px 26px;
    }
    .section h2{
      margin:0 0 10px;
      font-size:18px;
      letter-spacing:-.2px;
    }
    .grid{
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap:12px;
      margin-top:12px;
    }
    @media (max-width: 880px){
      .grid{grid-template-columns:1fr}
    }
    .item{
      border:1px solid var(--line);
      background: rgba(255,255,255,.03);
      border-radius:14px;
      padding:16px 14px;
      min-height:92px;
    }
    .item b{display:block; margin-bottom:6px}
    .item p{margin:0; color:var(--muted); font-size:13px; line-height:1.7}
    .footer{
      margin-top:18px;
      padding:18px 2px 0;
      color:rgba(255,255,255,.55);
      font-size:12px;
      display:flex;
      justify-content:space-between;
      gap:10px;
      flex-wrap:wrap;
    }
    .link{color:rgba(255,255,255,.78); text-decoration:underline; text-underline-offset:3px}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="topbar">
      <div class="logo"><span class="dot"></span>warmoria</div>
      <div class="pill">採用LP</div>
    </div>

    <div class="hero">
      <div class="card heroMain">
        <div class="kicker">新たな教育のカタチを作る仲間募集</div>
        <h1>学びは もっと自由で もっと楽しくていい</h1>
        <p class="lead">
          warmoria は STEAM教育スクール zunŌw を軸に、子どもたちが自ら動き出す瞬間をつくるチームです。
          一人ひとりを ちゃんと人として見る。授業の準備も掃除も すべてが場づくり。
        </p>

        <div class="ctaRow">
          <a class="btn btnPrimary" href="https://en-gage.net/warmoria/" target="_blank" rel="noopener">募集一覧を見る</a>
          <a class="btn" href="https://en-gage.net/warmoria/" target="_blank" rel="noopener">カジュアル面談を相談</a>
        </div>

        <div class="mini">
          価値観が合うかを大切にしています。まずは話を聞くだけでもOK。
        </div>
      </div>

      <div class="card heroSide">
        <p class="sideTitle">warmoria が大切にすること</p>
        <div class="item">
          <b>子どもを ちゃんと見る</b>
          <p>小さな変化に気づき、目の前の一人に向き合う。</p>
        </div>
        <div class="item" style="margin-top:12px">
          <b>場づくりも仕事</b>
          <p>準備や掃除まで含めて、学びの空気をつくる。</p>
        </div>
        <div class="item" style="margin-top:12px">
          <b>チームで未来を育てる</b>
          <p>一人で抱えず、改善し続ける文化をつくる。</p>
        </div>
      </div>
    </div>

    <div class="card section">
      <h2>事業</h2>
      <div class="grid">
        <div class="item">
          <b>STEAM教育スクール zunŌw</b>
          <p>理科実験・算数脳・プログラミングを横断して学ぶ。</p>
        </div>
        <div class="item">
          <b>個別指導塾 正学館</b>
          <p>一人ひとりに合わせた学習支援。</p>
        </div>
        <div class="item">
          <b>幼稚園・出張授業</b>
          <p>園や地域での授業・ワークショップを実施。</p>
        </div>
      </div>
    </div>

    <div class="card section">
      <h2>応募導線</h2>
      <div class="grid">
        <div class="item">
          <b>募集一覧を確認</b>
          <p><a class="link" href="https://en-gage.net/warmoria/" target="_blank" rel="noopener">engage の募集ページへ</a></p>
        </div>
        <div class="item">
          <b>まずは相談</b>
          <p>カジュアル面談で仕事内容や雰囲気を確認。</p>
        </div>
        <div class="item">
          <b>見学もOK</b>
          <p>現場の空気を見てから判断できる。</p>
        </div>
      </div>
    </div>

    <div class="footer">
      <div>© warmoria</div>
      <div><a class="link" href="https://en-gage.net/warmoria/" target="_blank" rel="noopener">募集一覧</a></div>
    </div>
  </div>
</body>
</html>
