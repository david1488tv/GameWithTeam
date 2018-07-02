# GameWithTeam
Для бэка

00) Установить Node.js
01) Перейти в папку backend
10) В командной строке выполнить команду npm i
11) Ничего больше не трогать без ведома тима-лида

В папке backend:

00) controllers - содержатся и будут добавляться основные контроллеры для сайта. Пока там лежит только контроллер для регистрации.
01) models - модели, которые являются основой для таблиц БД. Пока есть модель пользователей.
10) routes - маршруты, которые будут на нашем сайте. Пока там только один маршрут для регистрации.
11) config.js - файл с конфигурацией для БД. Можно менять ЛОКАЛЬНО. Но заливать его с вашими изменениями НЕ НАДО. Если и залили, то сообщите об этом в беседе.
100) main.js - основные сведения о самом веб-приложении. НИЧЕГО НЕ МЕНЯТЬ! УБЬЕТ!
101) package.json - файл, который хранит в себе все необходимые зависимости для нашего приложения. Можно погуглить про них и почитать для чего каждый. Также он содержит два скрипта, которые нам нужны - debug и api. Юзаем всегда debug командой npm run debug. Но перед этим убедиться, что поднят сервер БД и его настройки полностью соответствуют с файлом config.js. НИЧЕГО НЕ МЕНЯТЬ!
110) Для работы вам нужно создать БД и всё. Далее выполнить команду npm run debug в папке backend.

Папка frontend:

00) Только один файл-заготовка package.json для зависимостей во фронте. Потом объясню, если надо будет, как его заполнить.
01) Заливать сюда всё, что касается фронта.

Папка game:

00) Только один файл-заготовка package.json для зависимостей во фронте. Потом объясню, если надо будет, как его заполнить.
01) Заливать сюда всё, что касается игры
//prigoraet