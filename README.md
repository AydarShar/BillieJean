usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

Стандартные команды Git используемые в различных ситуациях:

создание рабочей области (смотрите также: git help tutorial)
   clone     Клонирование репозитория в новый каталог
   init      Создание пустого репозитория Git или переинициализация существующего

работа с текущими изменениями (смотрите также: git help everyday)
   add       Добавление содержимого файла в индекс
   mv        Перемещение или переименование файла, каталога или символьной ссылки
   restore   Restore working tree files
   rm        Удаление файлов из рабочего каталога и индекса

просмотр истории и текущего состояния (смотрите также: git help revisions)
   bisect    Выполнение двоичного поиска коммита, который вносит ошибку
   diff      Вывод разницы между коммитами, коммитом и рабочим каталогом и т.д.
   grep      Вывод строк, соответствующих шаблону
   log       Вывод истории коммитов
   show      Вывод различных типов объектов
   status    Вывод состояния рабочего каталога

выращивание, отметка и настройка вашей общей истории
   branch    Вывод списка, создание или удаление веток
   commit    Запись изменений в репозиторий
   merge     Объединение одной или нескольких историй разработки вместе
   rebase    Повторное применение коммитов над верхушкой другой ветки
   reset     Сброс текущего состояния HEAD на указанное состояние
   switch    Switch branches
   tag       Создание, вывод списка, удаление или проверка метки, подписанной с помощью GPG

совместная работа (смотрите также: git help workflows)
   fetch     Загрузка объектов и ссылок из другого репозитория
   pull      Извлечение изменений и объединение с другим репозиторием или локальной веткой
   push      Обновление внешних ссылок и связанных объектов

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
