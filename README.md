Документация по командам и не только Executer 2 

Чтобы добавить бота на сервер, необходимо создать нового бота на Discord Developer Portal, а затем добавить его токен в конфиг, после чего запустить бота

&echo "имя канала"(опцианально)  "текст" - отправляет сообщение в заданный канал от имени @Диктатор. Если канал не задан, отправляет в текущий, при этом удаляя сообщение с вызовом команды
&echbind "режим" "имя бинда"(только для add или remove) "бинд"(только для режима add) - добавляет (add) или убирает (remove) бинд или показывает (list) список биндов для &echo. Текст в &echo, совпадающий с именем бинда, заменяется на содержимое бинда
 
Экономика:
За каждое написанное сообщение вы получаете 0-1 стальк. Стальк (&) - валюта бота и стальковой системы. Количество получаемых стальков можно увеличить с помощью некоторых ролей

Команды:
&balance "имя пользователя"(опционально) - показывает баланс пользователя. Если пользователь не задан, показывает баланс участника, использовавшего команду.
&pay "имя пользователя" "количество стальков"-перечисляет заданное количество стальков указанному пользователю
&tryluck "количество стальков" - лотерея, позволяющая либо удвоить поставленное, либо потерять. Изначально шанс 50/50, однако с помощью некоторых предметов его можно увеличить
&luckity - показывает ваш шанс на выигрыш в &tryluck, а также шанс сохранить стальки при проигрыше
&buyrole "имя роли" - позволяет купить одну из ролей за стальки.
&sellrole "имя роли" - позволяет продать одну из стальковых ролей за 70% изначальной стоимости
&itemsinfo - показывает информацию о доступных для покупки предметов. Бонусы предметов складываются
&buyitem "имя предмета" - позволяет купить предмет за стальки
&inventory или &inv  - показывает ваш инвентарь с описанием предметов и их количеством
&sellitem "имя предмета" - позволяет продать стальковый предмет за 70% изначальной стоимости
&marketsell "тип"   "имя предмета/роли" "цена" - выставляет предмет/стальковую роль на рынок за указанную цену.
&leaders - показывает лидеров по сталькам

Дополнение: чтобы поставить новую строку в echbind, нужно написать  "\n". Также, бинд не должен быть длиннее 2000 символов, иначе ничего не заработает. Для использования list должны быть открыты личные сообщения от участников сервера
&patr-
&pic "номер файла"(опционально) - отправляет случайную или заданную пикчу за 1 стальк
&ssearch "название трека" или номер трека"(опционально) - ищет треки и отправляет список названий
&play-проигрывает плейлист
&leave - отключает бота от войса

Команды администрации:
&prefix "префикс" - изменяет префикс на указанный. Список доступных префиксов - " !~@&?^%$№/* "
&exuser "режим" "имя" "id пользователя" - добавляет (add) или удаляет (remove) пользователя из лог-исключений
&exchan "режим" "имя канала" "id канала" - добавляет (add) или удаляет (remove) канал из исключений для &echo
&addrole "пинг юзера" "id роли" - добавляет участнику указанную роль
&remrole "пинг юзера" "id роли" - забирает у участника указанную роль
&getitem "id цели" "имя предмета" - выдаёт запросившему участнику 1 единицу указанного предмета
&delitem "id цели"  "имя предмета" - забирает у запросившего участника 1 единицу указанного предмета
&delete или &del или &clear "количество сообщений" - удаляет указанное количество сообщений. Фактически, удаляет на одно сообщение больше, чтобы учесть вызов команды
&membercount - отображает количество участников сервера
&reboot "секунды до рестарта"(опционально) - выключает, а затем запускает бота через указанное время. Если время не указано, применяется 5 секунд. ВНИМАНИЕ: бот СНАЧАЛА выключается, а уже ПОТОМ отсчитывает время до запуска
&exit или &close - выключает бота

&sskip - пропускает случайный или заданный трек в очереди
&lewd - аналог пик, предназначенный для nsfw. Доступен только в lewd-канале
&sadd "номер трека"или"название трека"(опционально) - добавляет в очередь случайный или заданный трек. Имеет специальный аргумент "QQu" (вместо трека), используемый чтобы просмотреть треки в очереди
&playlist или &plist "режим" - добавляет (add) или удаляет (del) заданный трек из плейлиста, очищает плейлист (clear), показывает плейлист (list или ничего), добавляет плейлист в очередь (play)
