# Язык PHP

## Настройка для Windows

 1. Установить редактор VS Code, расширения [php cs fixer](https://marketplace.visualstudio.com/items?itemName=junstyle.php-cs-fixer), [Beautify Format](https://marketplace.visualstudio.com/items?itemName=DataBeautify.beautify-format), [EOL Guardian](https://marketplace.visualstudio.com/items?itemName=devflorez.eol-guardian).
 2. Скачать PHP для ОС Windows c официального сайта:

    - для PHP 8.5.1  [64-разрядной](https://windows.php.net/downloads/releases/php-8.5.1-nts-Win32-vs17-x64.zip)
    - для PHP 8.5.1  [32-разрядной](https://windows.php.net/downloads/releases/php-8.5.1-nts-Win32-vs17-x86.zip)

 3. Создать папку на диске С:\php
 4. Распаковать содержимое архива в С:\php
 5. В переменную среды PATH добавить путь С:\php
 6. Скачать [php-cs-fixer](https://cs.symfony.com/download/php-cs-fixer-v3.phar) в папку С:\php

---

Проверка работы PHP через консоль терминала в редакторе VS Code:

    php -v

В терминале VS Code появится сообщение о версии PHP или ошибка:

    PHP 8.5.1 (cli) (built: Dec 17 2025 10:54:30) (NTS Visual C++ 2022 x64)
    или
    Имя "php" не распознано как имя командлета - проверить путь в переменной среды PATH
    или
    is not compatible with this PHP build -  установленная версия Visual C++ не соответствует версии сборки PHP

Найти нужную версию Visual C++ в интернете с любого оффициального источника, поисковый запрос:

    - Visual C++ 2015-2022 Redistributable x64
    - Visual C++ 2015-2022 Redistributable x32

Установить актуальную версию VC++ Runtime.

## Примеры и задачи

- [php_1](https://github.com/petrmileshko/study_php/tree/main/php_1) , [php_2](https://github.com/petrmileshko/study_php/tree/main/php_2), [php_3](https://github.com/petrmileshko/study_php/tree/main/php_3)
