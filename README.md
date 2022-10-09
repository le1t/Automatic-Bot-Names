Данный плагин автоматически переименует всех ботов.
Имя ботов берется из botnames.txt .
Так же можно добавить любое имя ботов, изменив botnames.txt по пути: addons -> sourcemod -> configs

Настройка конфига по пути: cfg -> sourcemod -> Automatic_Bot_Names.txt

1360 имен использованы из ботов для CS 1.5 - 1.6 Ping Of Death Bot [POD] и Yet Another POD-Bot [YaPB]

1234.png

Спойлер: Опционально:

1. В архив включен файл с 63000 именами для ботов.
Располагается по пути addons -> sourcemod -> configs -> Опционально 63000 имен ботов -> botnames.txt .
Этот файл нужно скопировать и заменить по пути addons -> sourcemod -> configs .

2. Чтобы убрать в TAB`e слово БОТ на стороне клиента, нужно открыть файл по пути: csgo -> resource -> csgo_russian.txt и удалить слово БОТ и BOT в кавычках в этих строках:

"SFUI_bot_controlled_by" "(%s1)"
"SFUI_bot_decorated_name" "%s1"

"SFUI_scoreboard_lbl_bot" ""

Оригинальный плагин: Automatic Bot Names by agrif
Дополнительная информация: Настройка

Скомпилировано на SM v1.11.0.6911


Требования	
SM 1.10+
Переменные
// объявлять ботов при добавлении
// -
// Default: "0"
sm_botnames_announce "0"

// имя столбца, содержащего имена ботов, при загрузке из БД (базы данных)
// -
// Default: "name"
sm_botnames_db_column "name"

// при загрузке по порядку из БД задает, следует ли упорядочивать по убыванию, а не по возрастанию
// -
// Default: "0"
sm_botnames_db_descending "0"

// при загрузке из БД это ограничивает количество загружаемых имен, или "0" без ограничений
// -
// Default: "0"
sm_botnames_db_limit "0"

// имя БД для загрузки имени ботов, или "" для загрузки из файла botnames.txt
// -
// Default: ""
sm_botnames_db_name ""

// при использовании БД задает по какому столбцу упорядочивать, или "" для отсутствия упорядочивания
// -
// Default: ""
sm_botnames_db_order_by ""

// имя таблицы, откуда будут загружаться имена ботов (если используется )
// -
// Default: "botnames"
sm_botnames_db_table "botnames"

// следует ли принудительно использовать кодировку UTF8 для MySQL
// -
// Default: "0"
sm_botnames_db_use_utf8 "0"

// задержка на переименование ботов
// -
// Default: "9.0"
// Minimum: "1.000000"
sm_botnames_delay "9.0"

// включено ли переименование ботов
// -
// Default: "1"
sm_botnames_enabled "1"

// добавить префикс к имени бота (можно пробел, если нужно)
// -
// Default: ""
sm_botnames_prefix ""

// рандомные имена (не попорядку) из botnames.txt
// -
// Default: "1"
sm_botnames_random "1"

// сообщения о подключении/изменении команды/изменении имени бота
// -
// Default: "1"
sm_botnames_suppress "1"

Установка	
Распаковать архив с соблюдением всех путей к файлам.
