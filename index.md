<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Мой сайт</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
</head>
<body>
  <div class="content">
    <h1>Person10301</h1>
    <p>Listen and enjoy AURORA in <a href="https://youtube.com/@auroramusic" class="link">YouTube</a></p>
  </div>
  <div class="button-container">
    <a href="https://t.me/person10301" class="button"><i class="fab fa-telegram-plane"></i></a>
    <a href="https://vk.com/person10301" class="button"><i class="fab fa-vk"></i></a>
    <a href="https://4pda.to/forum/index.php?showuser=9050872" class="button">
      <svg class="custom-icon" width="44" height="44" viewBox="0 0 108 108" xmlns="http://www.w3.org/2000/svg">
        <path fill="#FFFFFF" d="m54 25a29 29 0 1 0 29 29 29 29 0 0 0-29-29zm13.69 45.92h-11.69l-.08-6.4h-20.45v-10l15.33-17.44h16.89z"/>
        <path fill="#FFFFFF" d="m47.16 56.6 8.59.01v-9.56z"/>
      </svg>
    </a>
    <a href="https://github.com/person10301" class="button"><i class="fab fa-github"></i></a>
  </div>
  <div class="ecology-message">
    <p><a href="https://news.mongabay.com/" class="link">Please, don't forget about Ecology🌍</a></p>
  </div>
  <script>
    function triggerGlitch() {
      const content = document.querySelector('.content');
      const buttons = document.querySelectorAll('.button');
      const message = document.querySelector('.ecology-message');
      content.style.animation = 'none';
      buttons.forEach(btn => btn.style.animation = 'none');
      message.style.animation = 'none';
      content.offsetHeight; // Перезапуск анимации
      content.style.animation = 'glitch-background 2s linear infinite';
      buttons.forEach(btn => btn.style.animation = 'button-glitch 2s linear infinite');
      message.style.animation = 'message-glitch 2s linear infinite';
      // Случайные цвета
      const randomHue = Math.random() * 360;
      content.style.color = `hsl(${randomHue}, 70%, 90%)`;
      buttons.forEach(btn => btn.style.color = `hsl(${randomHue + 30}, 70%, 90%)`);
      message.style.color = `hsl(${randomHue + 60}, 70%, 90%)`;
    }

    setInterval(() => {
      if (Math.random() > 0.1) { // 90% шанс запуска
        triggerGlitch();
      }
    }, Math.random() * 2000 + 2000); // 2-4 секунды
  </script>
</body>
</html>
