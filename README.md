Nanny
========
Это кастомная русская версия программы NannyBot для игры Call of Duty 2. Оригинальным автором этой программы является smugllama. Написана полностью на Perl.
Оригинал можно скачать по этой ссылке http://smaert.com/nannybot.zip

По сравнению с оригиналом, почти всё было переведено на русский язык (шутки на английском остались),
также было исправлено много ошибок, уменьшены задержки, переработаны некоторые функции, добавлены несколько новых команд, дополнительный мод для админов, уменьшена агрессивность по отношению к игрокам.

Интсрукция по запуску в Windows:

1. Скачать и установить Strawberry Perl http://strawberryperl.com
2. Настроить необходимые параметры в nanny.cfg (переименуйте example.cfg). Подробно расписывать не буду, т.к там есть пояснения к каждому параметру.
3. Запустить. В Windows можно запускать через nanny.bat

Интсрукция по запуску в Linux:

1. Установить через CPAN зависимые модули: DBI, DBD::SQLite, LWP::Simple
2. Настроить необходимые параметры в nanny.cfg (переименуйте example.cfg). Подробно расписывать не буду, т.к там есть пояснения к каждому параметру.
3. Запустить в терминале. В Linux можно запускать через nanny.sh

Интсрукция по запуску в Mac OSX:
1. Настроить необходимые параметры в nanny.cfg (переименуйте example.cfg). Подробно расписывать не буду, т.к там есть пояснения к каждому параметру.
2. Запустить в терминале. В OSX можно запускать через nanny.sh

Опционально: поддержка русской кодировки:

В Windows чтобы отображался русский язык необходимо в свойствах командной строки указать шрифт "Lucida Console"

В Linux в параметрах терминала установить кодировку Windows-1251

В Mac OSX поддержки кодировки нет

Превью:

Ubuntu
![ScreenShot](http://i.imgur.com/WjR2jse.png)
Windows
![ScreenShot](http://i.imgur.com/9xD8ME5.png)
