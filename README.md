# -<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>蘆竹南崁冷凍空調設備</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #e6f2f8; /* 淺淡藍背景 */
      color: #333;
      line-height: 1.6;
    }
    header, section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
      border-bottom: 1px solid #ccc;
    }
    header {
      text-align: center;
    }
    h1 {
      color: #0077cc;
      margin-bottom: 10px;
    }
    a {
      color: #0077cc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .section-title {
      color: #0077cc;
      border-left: 2px solid #0077cc;
      padding-left: 10px;
      margin-top: 40px;
      margin-bottom: 20px;
      font-weight: bold;
    }
    .social-links a {
      margin-right: 15px;
    }
    .projects img {
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 10px;
    }
    input, textarea, select, button {
      padding: 10px;
      background: #fff;
      color: #333;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 14px;
    }
    button {
      background: #0077cc;
      cursor: pointer;
      font-weight: bold;
      color: #fff;
      border: none;
    }
    button:hover {
      background: #005fa3;
    }
    footer {
      text-align: center;
      font-size: 14px;
      color: #777;
      padding: 20px;
      border-top: 1px solid #ccc;
    }
  </style>
</head>
<body>

  <header>
    <h1>蘆竹南崁冷凍空調設備</h1>
    <p>選擇專業只讓您信任<br>師傅：林清池先生</p>
  </header>

  <section>
    <h2 class="section-title">關於我</h2>
    <p>冷氣保養、安裝、拆除、移位、維修及商業用冰箱等等問題都歡迎詢問，專業的態度、誠懇答覆給予顧戶的信任及解決問題的答案。</p>
  </section>

  <section>
    <h2 class="section-title">聯絡方式</h2>
    <p>LINE: <a href="https://line.me/R/ti/p/@758mtfzp" target="_blank">點我立即加 LINE</a></p>
    <p>電話: 0933040487</p>
  </section>

  <section>
    <h2 class="section-title">預約服務</h2>
    <form onsubmit="handleBooking(event)">
      <input type="text" placeholder="姓名" required />
      <input type="text" placeholder="聯絡方式（電話或 LINE ID）" required />
      <select required>
        <option value="">選擇服務項目</option>
        <option>冷氣安裝</option>
        <option>冷氣保養</option>
        <option>冷氣維修</option>
        <option>商業冰箱</option>
        <option>其他</option>
      </select>
      <input type="date" required />
      <button type="submit">送出預約</button>
    </form>
    <div id="booking-result"></div>
  </section>

  <section>
    <h2 class="section-title">作品展示</h2>
    <div class="projects">
      <p><a href="https://www.instagram.com/sun.2021sun" target="_blank">Instagram 作品集</a></p>
      <p><a href="https://www.facebook.com/profile.php?id=61555762840015" target="_blank">Facebook 作品集</a></p>

      <img src="https://via.placeholder.com/800x400?text=冷氣安裝案例" alt="作品1" />
      <img src="https://via.placeholder.com/800x400?text=保養實例" alt="作品2" />

      <!-- 使用者上傳的圖片 -->
      <img src="8DC4C435-9F4D-4706-88F1-C7E15244FA85.jpeg" alt="清洗前後比較" />
      <img src="A9510433-9526-4D5E-8FBC-FEA61BDDE0A4.jpeg" alt="維修實況" />
      <img src="339C6AA7-43EA-4BB8-9195-D594062BE88F.jpeg" alt="服務資訊卡" />
    </div>
  </section>

  <section>
    <h2 class="section-title">社群連結</h2>
    <div class="social-links">
      <a href="https://www.instagram.com/sun.2021sun" target="_blank">Instagram</a>
      <a href="https://www.facebook.com/profile.php?id=61555762840015" target="_blank">Facebook</a>
    </div>
  </section>

  <section>
    <h2 class="section-title">提問表單</h2>
    <form onsubmit="handleQuestion(event)">
      <input type="text" placeholder="你的名字" required />
      <textarea rows="4" placeholder="請輸入你的問題" required></textarea>
      <button type="submit">送出問題</button>
    </form>
    <div id="question-result"></div>
  </section>

  <footer>
    &copy; 2025 蘆竹南崁冷凍空調設備 | 所有權利保留
  </footer>

  <script>
    function handleBooking(event) {
      event.preventDefault();
      document.getElementById('booking-result').innerText = "預約成功，我們會盡快與你聯繫！";
    }

    function handleQuestion(event) {
      event.preventDefault();
      document.getElementById('question-result').innerText = "問題已送出，謝謝你的提問！";
    }
  </script>

</body>
</html>
