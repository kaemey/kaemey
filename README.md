<h1 align="center">
  Telegram Bot Class PHP
</h1>
<h3>Универсальный родительский класс для твоего проекта,<br> с помощью которого ты сможешь быстро разработать своего Telegram бота<br></h3>
<h2>Установка:</h2>
<h3>1. Скачать и распаковать проект</h3>
<h3>2. Заполнить config.php файл:</h3>
<h3>2.1. Занести в переменную $responses запросы и ответы на них</h3>
<h4>Основные ключи - это ввод от пользователя или от клавиатуры,</h4>
<h4>значение - массив из ответов, где ключ - тело ответа (строка, путь до файла),</h4>
<h4>а значение - метод ответа (текстовый, отправка фото, документа).</h4>
<h4>сообщения НЕрегистрозависимые (неважно: ПриВЕт или привет)</h4>
<h2>Пример</h3>
<img src="https://i.imgur.com/qm4Bkp7.png">
<h4>2.2. Занести в переменную $first_message сообщение, что приходит пользователю, что зашёл впервые.</h4>
<h4>2.3. Занести в переменную $calls_admins сообщения, что должны вызывать администраторов бота.</h4>
<h4>2.4. Занести в переменную $keyboard текст для клавиш клавиатуры.</h4>
<h4>2.5. Занести в переменные $host, $bd_name, $password, $table данные для подключения к твоей БД, <br>где будут храниться пользователи.</h4>
<h2>Пример</h3>
<img src="https://i.imgur.com/LcdaBcg.png">
<h3>3. При желании можно подключить оплату в QIWI,<br>
в таком случае будет необходимо добавить свою логику.<br>
Есть логика по-умолчанию для примера использования.<br>
Используемый в коде класс QIWI наследуется от <a href="https://github.com/QIWI-API/bill-payments-php-sdk">данного класса</a></h3>
<img src="https://i.imgur.com/HEmzfg6.png">
<h2>Первые шаги:</h2>
<h3>Необходимо привязать вебхук от BotFeather, для этого используйте следующий код в index.php:</h3>
<img src="https://i.imgur.com/OKjdrkc.png">
 <h3>Если браузер выдаст <br>{"ok":false,"error_code":400,"description":"Bad Request: bad webhook: An HTTPS URL must be provided for webhook"},<br> значит у вас не подключён SSL-сертификат (ваш сайт http, а нужен https).</h3>
