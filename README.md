<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Portofolio Ziddy</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-image: url('https://files.catbox.moe/fl92zo.jpg'); /* Ganti jika ingin */
      background-size: cover;
      background-position: center;
      font-family: Arial, sans-serif;
      color: #00ff00;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .kotak {
      width: 400px;
      height: 600px;
      border: 4px solid #ff0000;
      box-shadow: 0 0 20px #ff0000;
      background-color: rgba(0, 0, 0, 0.85);
      border-radius: 20px;
      text-align: center;
      padding: 30px 20px;
      animation: zoomIn 1s ease-out;
      overflow: hidden;
      box-sizing: border-box;
      position: relative;
    }

    .kotak img,
    .nama,
    .garis {
      opacity: 0;
      transform: translateY(30px);
      animation: fadeUp 1s ease-out forwards;
    }

    .kotak img {
      animation-delay: 0.3s;
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 3px solid #00ff00;
      box-shadow: 0 0 10px #00ff00;
      margin-bottom: 15px;
    }

    .nama {
      animation-delay: 0.6s;
      font-size: 26px;
      font-weight: bold;
      text-shadow: 0 0 5px #00ff00;
      margin-bottom: 10px;
    }

    .garis {
      animation-delay: 0.9s;
      width: 85%;
      height: 2px;
      background-color: #00ff00;
      margin: 0 auto 10px auto;
      box-shadow: 0 0 5px #00ff00;
    }

    .keterangan-area {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 340px;
      overflow: hidden;
    }

    .keterangan {
      position: absolute;
      bottom: -100%;
      width: 100%;
      animation: naik 10s linear infinite;
      font-size: 16px;
      line-height: 1.7;
      text-shadow: 0 0 3px #00ff00;
    }

    @keyframes zoomIn {
      from {
        transform: scale(0.8);
        opacity: 0;
      }
      to {
        transform: scale(1);
        opacity: 1;
      }
    }

    @keyframes fadeUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes naik {
      0% {
        bottom: -100%;
      }
      100% {
        bottom: 250px; /* HAMPIR MENGENAI GARIS */
      }
    }
  </style>
</head>
<body>

  <div class="kotak">
    <img src="https://files.catbox.moe/xm0r9r.jpg" alt="Foto Profil">
    <div class="nama">Ziddy Mods</div>
    <div class="garis"></div>

    <div class="keterangan-area">
      <div class="keterangan">
        Ziddy Mods adalah penyedia layanan hosting yang terus berkembang, dipelopori oleh semangat anak muda yang tidak pernah mengenal kata menyerah. Di balik nama Ziddy Mods, ada dedikasi dan kerja keras untuk menghadirkan solusi digital terbaik bagi para pengguna di seluruh Indonesia.

<p> Dengan fokus utama pada penjualan produk hosting, Ziddy Mods menawarkan layanan cepat, aman, dan terjangkau. Meskipun menghadapi banyak tantangan, semangat pantang menyerah menjadi kunci utama Ziddy Mods terus bertahan dan berkembang dalam dunia digital yang penuh persaingan.

<p> Ziddy Mods bukan hanya sekadar bisnis, tapi juga simbol dari tekad, kreativitas, dan kepercayaan diri generasi muda dalam membangun masa depan yang lebih baik melalui teknologi.
    
