
<html lang='ja'>
<head>
  <meta charset='utf-8' />
  <meta name='viewport' content='width=device-width, initial-scale=1' />
  <title>warmoria</title>
  <meta name='description' content='STEAM教育 zunŌw を軸に、子どもたちの学びをもっと自由に、もっと楽しく。warmoria の紹介ページ。' />

  <style>
    :root{
      --bg1:#fff7ed;
      --bg2:#fff1e6;
      --ink:#2b1b12;
      --muted:#6b4b3a;
      --card:#ffffffcc;
      --line:#f2d2bf;
      --orange:#f97316;
      --orange2:#fb923c;
      --cream:#fff7ed;
      --shadow: 0 18px 60px rgba(43,27,18,.14);
      --radius: 18px;
    }

    *{box-sizing:border-box}
    body{
      margin:0;
      color:var(--ink);
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Hiragino Kaku Gothic ProN, Noto Sans JP, Yu Gothic, sans-serif;
      background:
        radial-gradient(1200px 700px at 18% 0%, rgba(249,115,22,.26), transparent 60%),
        radial-gradient(900px 600px at 85% 16%, rgba(251,146,60,.22), transparent 55%),
        linear-gradient(180deg, var(--bg1), var(--bg2));
      min-height:100vh;
    }

    a{color:inherit; text-decoration:none}
    .wrap{max-width:1120px; margin:0 auto; padding:22px 18px 72px}

    .topbar{
      display:flex; align-items:center; justify-content:space-between;
      gap:12px;
      padding:10px 0 18px;
    }
    .brand{
      display:flex; align-items:center; gap:10px;
      font-weight:900; letter-spacing:.2px;
    }
    .mark{
      width:12px; height:12px; border-radius:999px;
      background: linear-gradient(90deg, var(--orange), var(--orange2));
      box-shadow: 0 0 0 6px rgba(249,115,22,.12);
    }
    .pill{
      font-size:12px;
      color:var(--muted);
      background: rgba(255,255,255,.55);
      border:1px solid var(--line);
      padding:8px 12px;
      border-radius:999px;
      backdrop-filter: blur(8px);
    }

    .card{
      background: var(--card);
      border:1px solid var(--line);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      overflow:hidden;
      backdrop-filter: blur(10px);
    }

    .hero{
      display:grid;
      grid-template-columns: 1.25fr .75fr;
      gap:14px;
    }
    @media (max-width: 900px){
      .hero{grid-template-columns:1fr}
    }

    .heroMain{padding:30px 28px}
    .kicker{
      display:inline-flex; align-items:center; gap:10px;
      padding:8px 12px;
      border-radius:999px;
      border:1px solid var(--line);
      background: rgba(255,255,255,.55);
      color:var(--muted);
      font-size:12px;
      font-weight:700;
    }
    h1{
      margin:14px 0 10px;
      font-size:40px;
      line-height:1.14;
      letter-spacing:-.3px;
    }
    @media (max-width: 560px){
      h1{font-size:32px}
    }
    .lead{
      margin:0;
      color:var(--muted);
      font-size:15.5px;
      line-height:1.9;
      max-width:62ch;
    }

    .ctaRow{display:flex; gap:10px; flex-wrap:wrap; margin-top:18px}
    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      padding:12px 16px;
      border-radius:12px;
      border:1px solid var(--line);
      background: rgba(255,255,255,.65);
      color:var(--ink);
      font-weight:900;
      font-size:14px;
      transition: .15s ease;
    }
    .btn:hover{transform: translateY(-1px)}
    .btnPrimary{
      border:0;
      background: linear-gradient(90deg, var(--orange), var(--orange2));
      color:#1f130c;
      box-shadow: 0 14px 34px rgba(249,115,22,.25);
    }

    .heroSide{padding:22px}
    .sideTitle{
      margin:0 0 10px;
      color:var(--muted);
      font-size:13px;
      font-weight:900;
      letter-spacing:.2px;
    }
    .mini{
      border:1px solid var(--line);
      background: rgba(255,255,255,.6);
      border-radius:14px;
      padding:14px 14px;
      margin-top:10px;
    }
    .mini b{display:block; margin-bottom:6px}
    .mini p{margin:0; color:var(--muted); font-size:13px; line-height:1.8}

    .heroImg{
      margin-top:12px;
      border-radius:14px;
      border:1px solid var(--line);
      overflow:hidden;
      background:#fff;
    }
    .heroImg img{
      width:100%;
      height:210px;
      object-fit:cover;
      display:block;
    }

    .section{margin-top:14px; padding:22px 22px}
    .section h2{margin:0 0 10px; font-size:18px; letter-spacing:-.2px}
    .grid{
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap:12px;
      margin-top:12px;
    }
    @media (max-width: 900px){
      .grid{grid-template-columns:1fr}
    }
    .item{
      border:1px solid var(--line);
      background: rgba(255,255,255,.62);
      border-radius:14px;
      padding:16px 14px;
      min-height:96px;
    }
    .item b{display:block; margin-bottom:6px}
    .item p{margin:0; color:var(--muted); font-size:13px; line-height:1.75}

    .gallery{
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap:10px;
      margin-top:12px;
    }
    @media (max-width: 900px){
      .gallery{grid-template-columns:1fr}
    }
    .ph{
      border:1px solid var(--line);
      border-radius:14px;
      overflow:hidden;
      background:#fff;
    }
    .ph img{
      width:100%;
      height:230px;
      object-fit:cover;
      display:block;
    }

    .footer{
      margin-top:16px;
      padding:14px 2px 0;
      color:rgba(43,27,18,.55);
      font-size:12px;
      display:flex;
      justify-content:space-between;
      gap:10px;
      flex-wrap:wrap;
    }
    .link{
      color:rgba(43,27,18,.85);
      text-decoration:underline;
      text-underline-offset:3px;
      font-weight:800;
    }
  </style>
</head>

<body>
  <div class='wrap'>
    <div class='topbar'>
      <div class='brand'><span class='mark'></span>warmoria</div>
      <div class='pill'>warm, original, create</div>
    </div>

    <div class='hero'>
      <div class='card heroMain'>
        <div class='kicker'>新たな教育のカタチを作る</div>
        <h1>学びはもっと自由で<br>もっと楽しくていい</h1>
        <p class='lead'>
          warmoria は STEAM教育スクール zunŌw を軸に、子どもたちが自ら動き出す瞬間をつくるチーム。
          一人ひとりをちゃんと人として見る。準備や掃除まで含めて場をつくる。
        </p>

        <div class='ctaRow'>
          <a class='btn btnPrimary' href='https://en-gage.net/warmoria/' target='_blank' rel='noopener'>採用の募集一覧</a>
          <a class='btn' href='https://fn-zunow.com/' target='_blank' rel='noopener'>zunŌwを見る</a>
          <a class='btn' href='https://fn-zunow.com/workshop' target='_blank' rel='noopener'>zunŌwを導入したい方</a>
        </div>
      </div>

      <div class='card heroSide'>
        <p class='sideTitle'>warmoria が大切にすること</p>

        <div class='mini'>
          <b>子どもを ちゃんと見る</b>
          <p>小さな変化に気づき、目の前の一人に向き合う</p>
        </div>

        <div class='mini'>
          <b>場づくりも仕事</b>
          <p>準備も掃除も含めて、学びの空気をつくる</p>
        </div>

        <div class='mini'>
          <b>チームで未来を育てる</b>
          <p>改善を続け、良い学びを積み上げる</p>
        </div>

        <div class='heroImg'>
