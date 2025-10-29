


<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Nitin_modz | Connect</title>
<style>
/* === Neon Style Setup === */
:root {
  --neon1: #00fff0;
  --neon2: #ff00c8;
  --neon3: #00ff84;
  --dark-bg: #02040a;
  --card-bg: rgba(20, 20, 30, 0.6);
  --text: #eafff9;
  font-family: 'Poppins', sans-serif;
}

* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  background: linear-gradient(120deg, #04000f, #0b001e, #001f2e);
  background-size: 600% 600%;
  animation: bgmove 10s ease infinite;
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  color: var(--text);
  overflow-x: hidden;
}

/* Background animation */
@keyframes bgmove {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

/* Container */
.container {
  width: 90%;
  max-width: 850px;
  background: var(--card-bg);
  border: 1px solid rgba(255,255,255,0.1);
  border-radius: 20px;
  padding: 30px;
  backdrop-filter: blur(20px);
  box-shadow: 0 0 25px rgba(0,255,200,0.2);
}

/* Logo Title */
.logo {
  text-align: center;
  margin-bottom: 30px;
}
.logo h1 {
  font-size: 2.5rem;
  color: var(--neon1);
  text-shadow:
    0 0 10px var(--neon1),
    0 0 20px var(--neon1),
    0 0 40px var(--neon2);
  animation: glowPulse 3s infinite;
}
@keyframes glowPulse {
  0%, 100% { text-shadow: 0 0 10px var(--neon1), 0 0 40px var(--neon2); }
  50% { text-shadow: 0 0 25px var(--neon2), 0 0 60px var(--neon3); }
}

/* Link Cards */
.links {
  display: flex;
  flex-direction: column;
  gap: 18px;
}
.card {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.15);
  border-radius: 14px;
  padding: 14px 20px;
  transition: 0.3s;
  box-shadow: 0 0 12px rgba(0,0,0,0.3);
}
.card:hover {
  transform: translateY(-5px) scale(1.02);
  box-shadow: 0 0 25px var(--neon1);
}
.card .info {
  display: flex;
  flex-direction: column;
}
.card .info h3 {
  font-size: 1.1rem;
  color: var(--neon3);
}
.card .info p {
  font-size: 0.85rem;
  color: #c8f8ff;
}

/* Button Style */
.card a {
  text-decoration: none;
  color: var(--text);
  padding: 8px 14px;
  border-radius: 10px;
  border: 1px solid var(--neon1);
  background: linear-gradient(90deg, var(--neon1), var(--neon2));
  box-shadow: 0 0 10px var(--neon1), 0 0 20px var(--neon2);
  transition: 0.25s;
}
.card a:hover {
  background: linear-gradient(90deg, var(--neon2), var(--neon1));
  transform: scale(1.05);
}

/* Footer */
footer {
  margin-top: 25px;
  text-align: center;
  color: #99ffff;
  font-size: 0.85rem;
}
</style>
</head>
<body>
  <div class="container">
    <div class="logo">
      <h1>Nitin_modz</h1>
    </div>

    <div class="links">
      <div class="card">
        <div class="info">
          <h3>🎮 YouTube - Sanatani Gamer 90</h3>
          <p>@sanatanigamer90</p>
        </div>
        <a href="https://youtube.com/@sanatanigamer90?si=gywPA0dIIy6Y5652" target="_blank">Open</a>
      </div>

      <div class="card">
        <div class="info">
          <h3>🎬 YouTube - Nitin NM</h3>
          <p>@nitinnm4627</p>
        </div>
        <a href="https://youtube.com/@nitinnm4627?si=81BNKXJj9pfYSiua" target="_blank">Open</a>
      </div>

      <div class="card">
        <div class="info">
          <h3>💬 Telegram Channel</h3>
          <p>Join for updates & mods</p>
        </div>
        <a href="https://t.me/+MVN6iStjmxIxNTBl" target="_blank">Join</a>
      </div>

      <div class="card">
        <div class="info">
          <h3>📱 WhatsApp</h3>
          <p>Message me directly</p>
        </div>
        <!-- apna number yahan daalna (example: 9198XXXXXXXX) -->
        <a href="https://wa.me/9198XXXXXXXX" target="_blank">Chat</a>
      </div>

      <div class="card">
        <div class="info">
          <h3>📧 Gmail</h3>
          <p>nitinmaurya902h@gmail.com</p>
        </div>
        <a href="mailto:nitinmaurya902h@gmail.com">Send Mail</a>
      </div>
    </div>

    <footer>✨ Designed with 💖 by Nitin_modz ✨</footer>
  </div>
</body>
</html>
