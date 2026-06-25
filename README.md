Berikut adalah contoh halaman profil data diri HTML dengan desain modern dan kesan mewah (clean, elegan, dengan style card dan gradient):

```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Profil Diri - Dacosta</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #fff;
    }

    .card {
      width: 360px;
      background: rgba(255, 255, 255, 0.08);
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 20px;
      padding: 25px;
      backdrop-filter: blur(15px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.5);
      text-align: center;
    }

    .avatar {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      margin: 0 auto 15px;
      background: linear-gradient(45deg, #f9d423, #ff4e50);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 40px;
      font-weight: bold;
      color: #fff;
    }

    h1 {
      font-size: 22px;
      margin-bottom: 5px;
    }

    p {
      font-size: 14px;
      opacity: 0.8;
      margin-bottom: 15px;
    }

    .info {
      text-align: left;
      margin-top: 20px;
    }

    .info div {
      background: rgba(255,255,255,0.07);
      padding: 10px 12px;
      border-radius: 10px;
      margin-bottom: 10px;
      font-size: 14px;
    }

    .label {
      font-weight: 600;
      color: #ffd369;
    }
  </style>
</head>

<body>

  <div class="card">
    <div class="avatar">D</div>
    <h1>Dacosta</h1>
    <p>Profil Pengguna Modern</p>

    <div class="info">
      <div><span class="label">Nama:</span> Dacosta</div>
      <div><span class="label">Alamat:</span> Bandung</div>
      <div><span class="label">Email:</span> Caravariosdacosta@gmail.com</div>
    </div>
  </div>

</body>
</html>
```

Kalau kamu mau, saya juga bisa:

* bikin versi **lebih mewah seperti dashboard Apple**
* tambah **foto profil asli**
* tambah **animasi hover**
* atau dibuat versi **dark mode + neon cyberpunk**

Tinggal bilang saja.
