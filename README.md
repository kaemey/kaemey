<h1 align="center">
  Telegram Bot Class PHP
</h1>
<h3>Универсальный родительский класс для твоего проекта,<br> с помощью которого ты сможешь быстро разработать своего Telegram бота<br></h3>
<h2>Установка:</h2>
<h3>1. Скачать и распаковать проект</h3>
<h3>2. Заполнить config.php файл:</h3>
<h3 align="center">2.1. Занести в переменную $responses запросы и ответы на них</h3>
<h4 align="center">Основные ключи - это ввод от пользователя или от клавиатуры,</h4>
<h4 align="center">значение - массив из ответов, где ключ - тело ответа (строка, путь до файла),</h4>
<h4 align="center">а значение - метод ответа (текстовый, отправка фото, документа).</h4>
<h4 align="center">сообщения регистронезависимые (неважно: ПриВЕт или привет)</h4>
<h3 align="center">Пример</h3>
<img src="https://i.imgur.com/qm4Bkp7.png">
<h4 align="center">2.2. Занести в переменную $first_message сообщение, что приходит пользователю, что зашёл впервые.</h4>
<h4 align="center">2.3. Занести в переменную $calls_admins сообщения, что должны вызывать администраторов бота.</h4>
<h4 align="center">2.4. Занести в переменную $keyboard текст для клавиш клавиатуры.</h4>
<h4 align="center">2.5. Занести в переменные $host, $bd_name, $password, $table данные для подключения к твоей БД, где будут храниться пользователи.</h4>
<h4 align="center">Пример</h3>
<img src="https://i.imgur.com/LcdaBcg.png">
