<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Giới thiệu bản thân - Neon Anime</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #10131c, #1b1f2a);
      color: #ffffff;
      overflow-x: hidden;
      height: 100vh;
      position: relative;
    }

    .cursor-light {
      position: absolute;
      pointer-events: none;
      width: 150px;
      height: 150px;
      background: radial-gradient(circle, rgba(0, 255, 255, 0.3) 0%, transparent 80%);
      border-radius: 50%;
      transform: translate(-50%, -50%);
      transition: top 0.03s, left 0.03s;
      z-index: 1;
    }

    header {
      text-align: center;
      padding: 60px 20px;
      position: relative;
      background-color: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(5px);
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    }

    header::before {
      content: "";
      background-image: url('https://wallpapercave.com/wp/wp9392202.jpg');
      background-size: cover;
      background-position: center;
      opacity: 0.25;
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 0;
    }

    header h1 {
      font-size: 3.5em;
      color: #00ffff;
      text-shadow: 0 0 20px #00ffff;
      position: relative;
      z-index: 1;
    }

    header p {
      color: #ccc;
      margin-top: 10px;
      position: relative;
      z-index: 1;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      position: relative;
      z-index: 2;
    }

    section {
      margin-bottom: 40px;
      background: rgba(255, 255, 255, 0.03);
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.2);
      border: 1px solid rgba(0, 255, 255, 0.2);
    }

    h2 {
      color: #00ffff;
      margin-bottom: 10px;
      text-shadow: 0 0 10px #00ffff;
    }

    p {
      line-height: 1.6;
    }

    .contact-links a {
      display: flex;
      align-items: center;
      gap: 10px;
      margin: 10px 0;
      color: #00ffff;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .contact-links a:hover {
      color: #ffffff;
      text-shadow: 0 0 15px #00ffff;
      transform: translateX(5px);
    }

    .contact-links img {
      width: 24px;
      height: 24px;
      filter: drop-shadow(0 0 5px #00ffff);
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      background-color: rgba(255, 255, 255, 0.05);
      border-top: 1px solid rgba(255, 255, 255, 0.1);
    }

    .gif-box {
      text-align: center;
      margin-top: 20px;
    }

    .gif-box img {
      width: 280px;
      max-width: 95%;
      border: 4px double #00ffff;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.4);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .gif-box img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.6);
    }

    .gif-box p {
      margin-top: 10px;
      font-style: italic;
      color: #ccc;
    }
  </style>
</head>
<body>
  <div class="cursor-light" id="cursorLight"></div>

  <header>
    <h1>Nguyễn Văn A</h1>
    <p>Nhà phát triển Web - Phong cách Tương Lai</p>
  </header>

  <div class="container">
    <section>
      <h2>Giới thiệu</h2>
      <p>
        Xin chào! Tôi là Nguyễn Văn A – nhà phát triển web đam mê công nghệ tương lai, thiết kế trải nghiệm người dùng ấn tượng và hiệu ứng neon huyền ảo.
      </p>

      <div class="gif-box">
        <img src="https://media.giphy.com/media/3o6Zt481isNVuQI1l6/giphy.gif" alt="GIF giới thiệu" />
        <p>"Mỗi lập trình viên đều bắt đầu như một cuốn sách trắng..."</p>
      </div>
    </section>

    <section>
      <h2>Thông tin cá nhân</h2>
      <p><strong>Email:</strong> nguyenvana@example.com</p>
      <p><strong>Điện thoại:</strong> 0909 123 456</p>
      <p><strong>Địa chỉ:</strong> Hà Nội, Việt Nam</p>

      <div class="gif-box">
        <img src="https://media.giphy.com/media/ZqlvCTNHpqrio/giphy.gif" alt="GIF sách cổ điển" />
        <p>"Mỗi dòng code là một trang sách đời tôi..."</p>
      </div>
    </section>

    <section class="contact-links">
      <h2>Contact for Work</h2>
      <a href="https://www.facebook.com/huynhtiendat.user" target="_blank" rel="noopener noreferrer">
        <img src="https://cdn-icons-png.flaticon.com/512/145/145802.png" alt="Facebook icon" />
        Facebook
      </a>
      <a href="https://www.instagram.com/kirosdesut712.user/" target="_blank" rel="noopener noreferrer">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram icon" />
        Instagram
      </a>
      <a href="https://t.me/htd_user" target="_blank" rel="noopener noreferrer">
        <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" alt="Telegram icon" />
        Telegram
      </a>
    </section>
  </div>

  <footer>
    &copy; 2025 Nguyễn Văn A. All rights reserved.
  </footer>

  <script>
    const cursor = document.getElementById("cursorLight");
    document.addEventListener("mousemove", (e) => {
      cursor.style.left = e.pageX + "px";
      cursor.style.top = e.pageY + "px";
    });
  </script>
</body>
</html>
