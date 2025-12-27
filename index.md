<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Информация</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            color: #333;
        }
        /* Скрытые ссылки — выглядят как обычный текст */
        a.hidden {
            color: inherit;        /* тот же цвет, что и окружающий текст */
            text-decoration: none; /* без подчёркивания */
        }
        a.hidden:hover {
            text-decoration: underline; /* опционально: подчёркивание при наведении */
        }
    </style>
</head>
<body>

    <h1>Заголовок страницы</h1>

    <p>
        Здесь вы можете написать любой текст. Например: 
        Если вам нужна дополнительная информация по теме А, 
        обратитесь к соответствующему ресурсу. 
        По теме Б тоже есть материалы. 
        А по теме В — отдельный документ.
    </p>

    <p>
        Слова или фразы, под которыми спрятаны ссылки, выглядят абсолютно обычно: 
        <a href="https://example.com/info-a" class="hidden" target="_blank">тема А</a>, 
        <a href="https://example.com/info-b" class="hidden" target="_blank">тема Б</a> и 
        <a href="https://drive.google.com/your-file" class="hidden" target="_blank">тема В</a>.
        При наведении курсора вы увидите, что это ссылка.
    </p>

    <p>
        Вы можете добавить сколько угодно таких скрытых ссылок. 
        Просто оберните нужное слово или фразу в тег:
    </p>

    <pre>
&lt;a href="https://ваша-ссылка.ru" class="hidden" target="_blank"&gt;слово или фраза&lt;/a&gt;
    </pre>

    <p>Всё. Никаких дополнительных файлов не требуется.</p>

</body>
</html>
