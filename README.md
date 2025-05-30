/* Стили для фонового изображения и размытия */
body {
  /* Установка фонового изображения */
  background-image: url('images/background.jpg');
  background-size: cover; /* Растягивает изображение на весь экран */
  background-position: center; /* Центрирует изображение */
  background-repeat: no-repeat; /* Запрещает повторение изображения */
  background-attachment: fixed; /* Фиксирует фон при прокрутке */
  margin: 0; /* Убирает отступы */
  min-height: 100vh; /* Высота минимум на весь экран */
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white; /* Цвет текста для читаемости */
  font-family: Arial, sans-serif;
}

/* Полупрозрачный слой с размытием для контента */
.content {
  background: rgba(0, 0, 0, 0.5); /* Полупрозрачный черный фон */
  backdrop-filter: blur(10px); /* Размытие фона за контентом */
  padding: 20px;
  border-radius: 10px; /* Скругленные углы */
  text-align: center;
  max-width: 80%; /* Ограничение ширины для читаемости */
}

/* Стили для заголовков и текста */
h1, p {
  margin: 10px 0;
}
