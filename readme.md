# Язык PHP

## Настройка для Windows

 1. Установить редактор VS Code, расширения PHP Intelephense, PHP Debug.
 2. Скачать PHP для ОС Windows c официального сайта:

    - для PHP 8.5.1  [64-разрядной](https://windows.php.net/downloads/releases/php-8.5.1-nts-Win32-vs17-x64.zip)
    - для PHP 8.5.1  [32-разрядной](https://windows.php.net/downloads/releases/php-8.5.1-nts-Win32-vs17-x86.zip)

 3. Создать папку на диске С:\php
 4. Распаковать содержимое архива в С:\php
 5. В переменную среды PATH добавить путь С:\php

---

Проверка работы PHP через консоль в редакторе VS Code:

    - php -v

В терминале VS Code появится версия PHP или ошибка:

    - Имя "php" не распознано как имя командлета - проверить путь в переменной среды PATH
    - is not compatible with this PHP build -  установленная версия VC++ Runtime не соответсвует версии PHP

VC++ Runtime (Найти в интернете с любого оффициального источника) поиск:

    - Visual C++ 2015-2022 Redistributable x64
    - Visual C++ 2015-2022 Redistributable x32

Установить актуальную версию VC++ Runtime.

## Примеры и задачи

- [p1](https://github.com/petrmileshko/study_php/tree/main/php_1)
