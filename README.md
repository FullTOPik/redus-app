# redus-app

## Запуск
 1. Создайте `.env` файл
 2. Скопирейте значения из `.env.example` файла
 3. Вставьте значения в `.env` файл
 4. Запустить приложение командой `docker-compose up`

## Тестирование
1. Зарегистрируйтесь на сайте `https://trending.bid/` и скопирейте `PHPSESSID`, который находится в `cookie`
2. Запустите приложение
3. Отправьте post запрос на `http://localhost:3000/auth`, записав в теле запроса `PHPSESSID`
4. Отправьте get запрос на `http://localhost:3000/balance`