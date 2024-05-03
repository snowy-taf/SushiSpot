#Installation

Устанавливаем XAMPP с PHP с официального сайта (не забываем добавить PHP в PATH):
"https://www.apachefriends.org/"

Клонируем репозиторий:
"git clone https://github.com/snowy-taf/sushispot.git"

Запускаем XAMPP и запускаем PHPMyAdmin.

Заходим в корневую папку проекта и в терминале переходим в example-app:
"cd example-app"

Применяем миграции:
"php artisan migrate"

Импортируем дамп базы данных в PHPMyAdmin.

Запускаем локальный сервер:
"php artisan serve"