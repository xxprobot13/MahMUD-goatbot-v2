<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>🎀 Mah MUD</title>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    .app {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
    }
    .card {
      background-color: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0px 2px 10px rgba(0,0,0,0.1);
    }
    .card__title--img img {
      width: 100px;
      border-radius: 50%;
    }
    .card__title--name {
      font-size: 24px;
      font-weight: bold;
    }
    .veri__check i {
      color: #4CAF50;
    }
    .card__title--description {
      margin-top: 10px;
      color: #777;
    }
    .row {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .col {
      margin: 10px;
    }
    .card__item {
      background-color: #eee;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .link__icon i {
      font-size: 24px;
      color: #333;
    }
    .link_docs_icon {
      margin-top: 15px;
    }
    .link_docs_text {
      background-color: #007bff;
      color: white;
      padding: 8px 16px;
      border-radius: 8px;
      display: inline-block;
      margin: 5px;
    }
    .card__footer {
      display: flex;
      justify-content: center;
      margin-top: 20px;
      gap: 30px;
    }
    .footer__item i {
      color: crimson;
    }
    h1, h3, h5 {
      margin: 10px 0;
    }
  </style>
</head>

<body>

  <img src="https://i.ibb.co/RQ28H2p/banner.png" alt="banner" width="100%">
  <h1>
    <img src="https://i.imgur.com/ZfuZrPc.jpeg" width="22px" alt="icon">
    Goat Bot - Bot Chat Messenger
  </h1>

  <p>
    <a href="https://nodejs.org/dist/v16.20.0">
      <img src="https://img.shields.io/badge/Nodejs%20Support-16.x-brightgreen.svg?style=flat-square" alt="Nodejs Support v16.x">
    </a>
    <img alt="size" src="https://img.shields.io/github/repo-size/ntkhang03/Goat-Bot-V2.svg?style=flat-square&label=size">
    <img alt="code-version" src="https://img.shields.io/badge/dynamic/json?color=brightgreen&label=code%20version&prefix=v&query=%24.version&url=https://github.com/ntkhang03/Goat-Bot-V2/raw/main/package.json&style=flat-square">
    <img alt="visitors" src="https://visitor-badge.laobi.icu/badge?style=flat-square&page_id=ntkhang3.Goat-Bot-V2">
    <img alt="license" src="https://img.shields.io/badge/license-MIT-green?style=flat-square&color=brightgreen">
  </p>

  <p>The original author of this Bot is <strong>Ntkhang</strong>. This fork is maintained by: <strong>MahMUD</strong></p>
  <p>If you find any issues, please report them!</p>

  <div>
    <h3>Facebook: <a href="https://www.facebook.com/mahmud.x07" style="color: black;">Mah M UD</a></h3>
  </div>

  <p>
    <a href="https://www.facebook.com/mahmud.x07" target="_blank" rel="noopener noreferrer">
      <img src="https://i.imgur.com/M6xV2Np.jpeg" width="100">
    </a>
  </p>

  <h5>>🎀 Mah MUD</h5>

  <div class="app">
    <div class="card">
      <div class="card__title">
        <div class="card__title--img">
          <img src="https://i.imgur.com/GGvARUp.jpeg" alt="Mah M UD">
        </div>
        <div class="card__title--name">
          <h1>Mah M UD</h1>
          <div class="veri__check">
            <i class="fas fa-check"></i>
          </div>
        </div>
        <div class="card__title--description">
          <p><br>⁓ MY STORY IN A FRAME ⁓<br>🎀🦋<br></p>
        </div>
      </div>

      <div class="card__body mt-10">
        <div class="row">
          <div class="col col-lg-3">
            <div class="card__item">
              <a href="https://www.facebook.com/mahmud.x07" class="card__link">
                <div class="link__icon"><i class="fab fa-facebook"></i></div>
              </a>
            </div>
          </div>

          <div class="col col-lg-3">
            <div class="card__item">
              <a href="https://www.facebook.com/mahmud.x07" class="card__link">
                <div class="link__icon"><i class="fab fa-facebook-messenger"></i></div>
              </a>
            </div>
          </div>

          <div class="col col-lg-3">
            <div class="card__item">
              <a href="https://wa.me/+88" class="card__link">
                <div class="link__icon"><i class="fab fa-whatsapp"></i></div>
              </a>
            </div>
          </div>

          <div class="col col-lg-3">
            <div class="card__item">
              <a href="https://www.instagram.com" class="card__link">
                <div class="link__icon"><i class="fab fa-instagram"></i></div>
              </a>
            </div>
          </div>
        </div>

        <div class="link_docs_icon">
          <a href="/docs" class="card__link">
            <div class="link_docs_text">API DOCS</div>
          </a>
        </div>

        <div class="link_docs_icon">
          <a href="/api-docs" class="card__link">
            <div class="link_docs_text">API DOCS-V2</div>
          </a>
        </div>
      </div>

      <div class="card__footer">
        <div class="footer__item">
          <i class="fas fa-heart"></i> 4.5M
        </div>
        <div class="footer__item">
          <i class="fa fa-comment"></i> 1.7M
        </div>
        <div class="footer__item">
          <i class="fa fa-share"></i> 2.2M
        </div>
      </div>
    </div>
  </div>

  <img align="center" src="https://i.imgur.com/UM3ekFf.jpeg" width="100%"/>

  <p>🔹 Ariyan Mahmud</p>

</body>
</html>
