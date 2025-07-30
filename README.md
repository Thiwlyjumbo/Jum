<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>สุขสันต์วันเกิด ฟอร์ด 🎉</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Arial', sans-serif; }

    body {
      background: linear-gradient(135deg, #cceeff, #99ddff);
      height: 100vh;
      overflow: hidden;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      animation: backgroundShift 15s ease infinite alternate;
    }

    @keyframes backgroundShift {
      0% { background: linear-gradient(135deg, #cceeff, #99ddff); }
      100% { background: linear-gradient(135deg, #99ccff, #66ccff); }
    }

    .card {
      background-color: rgba(255, 255, 255, 0.9);
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
      text-align: center;
      animation: float 3s ease-in-out infinite;
      width: 90%;
      max-width: 500px;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
    }

    h1 {
      font-size: 2.5rem;
      color: #0066cc;
      margin-bottom: 1rem;
      animation: popUp 1s ease;
    }

    p {
      font-size: 1.2rem;
      color: #333;
      margin-bottom: 1.5rem;
      animation: fadeIn 2s ease;
    }

    @keyframes popUp {
      0% { transform: scale(0.5); opacity: 0; }
      100% { transform: scale(1); opacity: 1; }
    }

    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      text-align: left;
    }

    textarea {
      width: 100%;
      height: 100px;
      border: 2px solid #66ccff;
      border-radius: 10px;
      padding: 1rem;
      font-size: 1rem;
      resize: none;
      background-color: #f0faff;
    }

    button {
      padding: 0.7rem 1.5rem;
      border: none;
      border-radius: 10px;
      background-color: #0099ff;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background-color: #0077cc;
    }

    .balloon {
      position: absolute;
      bottom: -150px;
      width: 40px;
      height: 60px;
      background-color: #00aaff;
      border-radius: 20px 20px 20px 20px;
      animation: rise 10s linear infinite;
    }

    @keyframes rise {
      0% { transform: translateY(0) rotate(0deg); opacity: 1; }
      100% { transform: translateY(-120vh) rotate(360deg); opacity: 0; }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>สุขสันต์วันเกิด ฟอร์ด 🎂🎉</h1>
    <p>ขอให้ฟอร์ดมีความสุขทุกปี สดใสทุกวัน ยิ้มให้เยอะ ๆ นะ 💙<br>จาก: ทิวลี่</p>

    <form action="https://formsubmit.co/YOUR_EMAIL_HERE" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_subject" value="ฟอร์ดส่งข้อความวันเกิดกลับมาจากเว็บ!">
      <label for="message">ฟอร์ดอยากบอกอะไรกับทิวลี่? 💌</label>
      <textarea name="message" id="message" placeholder="พิมพ์ข้อความตรงนี้..."></textarea>
      <button type="submit">ส่งให้ทิวลี่เลย! 🚀</button>
    </form>
  </div>

  <!-- ลูกโป่งลอย -->
  <div class="balloon" style="left: 20%; animation-delay: 0s;"></div>
  <div class="balloon" style="left: 40%; animation-delay: 3s;"></div>
  <div class="balloon" style="left: 60%; animation-delay: 6s;"></div>
  <div class="balloon" style="left: 80%; animation-delay: 1.5s;"></div>
</body>
</html>
