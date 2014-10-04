Nanny
========
Это кастомная русская версия программы NannyBot для игры Call of Duty 2. Оригинальным автором этой программы является smugllama. Написана полностью на Perl.
Оригинал можно скачать по этой ссылке http://smaert.com/nannybot.zip

По сравнению с оригиналом, почти всё было переведено на русский язык (шутки на английском остались),
также было исправлено много ошибок, уменьшены задержки, переработаны некоторые функции, добавлены несколько новых команд, дополнительный мод для админов, уменьшена агрессивность по отношению к игрокам.

Интсрукция по запуску в Windows:

1. Скачать и установить ActivePerl http://www.activestate.com/activeperl/downloads или Strawberry Perl http://strawberryperl.com
2. Настроить необходимые параметры в nanny.cfg (переименуйте example.cfg). Подробно расписывать не буду, т.к там есть пояснения к каждому параметру.
4. Запустить. В Windows можно запускать через nanny.bat

Интсрукция по запуску в Linux:

1. Скачать ActivePerl http://www.activestate.com/activeperl/downloads
2. Установить через Install.sh
3. Необходимо отредактировать переменную PATH, для того чтобы вместо оригинального Perl запускался ActivePerl, сделать это можно разными способами, однако самый простой - добавить путь в локальный файл .bashrc или .bash_profile.
Пример:      PATH=$PATH:/opt/ActivePerl-5.18/bin:$PATH    (Ваш путь к ActivePerl может отличатся)
4. Настроить необходимые параметры в nanny.cfg (переименуйте example.cfg). Подробно расписывать не буду, т.к там есть пояснения к каждому параметру
5. Запускать в терминале.

Запуск в Linux без ActivePerl:

Достаточно лишь установить через CPAN зависимые модули, DBI, DBD::SQLite, LWP::Simple

Опционально поддержка русской кодировки:

В Windows чтобы отображался русский язык необходимо запустить cyrillic_cmd_for_windows.bat, и после этого запускать саму программу.

В Linux достаточно в параметрах терминала установить кодировку Windows-1251.

Превью:

Ubuntu
![ScreenShot](http://s018.radikal.ru/i510/1405/6c/fa5144280d7b.png)
Windows
![ScreenShot](http://s020.radikal.ru/i720/1405/1f/8c05980fe23e.png)
