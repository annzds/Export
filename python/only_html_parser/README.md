﻿diary_export.exe 
самораспоковывающийся архив под windows. Запускает код по выгрузке дневника.

На дневнике с ~5500 записями и ~28 000 комментариев выгрузка длилась порядка полутора часов. Код может плохо воспринимать засыпание компьютера.

КОНСОЛЬ НА ЗАДНЕМ ФОНЕ НЕ ЗАКРЫВАТЬ.

Вводите логин-пароль и выбираете директорию. ОБЯЗАТЕЛЬНО выбираете директорию и желательно не ту, что по умолчанию - она может испаряться с закрытием проги. Неверные логин/пароль отлавливаются, но все же тестировать прогу на внезапные действия пользоватлей не советую - она слеплена насырую.

Кнопка "Начать" блокируется на время выполнения.
В выбранной папке создается еще одна папка с именем "diary_x", где х - короткое имя вашего дневника (то, что пишется в браузере перед ".diary.ru"). В папке создаются файлы account.json и несколько файлов posts_x.json. Все их можно открыть в браузере или любом текстовом редакторе.

Надпись "собираем информацию о записях" может висеть довольно долго, если у вас давно ведущийся дневник. Во время непосредственно выгрузки записей (и комментариев к ним) внизу окна пишется, сколько выгружено.
Записи сохраняются пакетами по 20, чтобы каждый файл не оказался тяжелым (комментарии весят обычно больше записей, актуальо для активных сообществ).