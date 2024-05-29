# git-Notes
How to use Git
1. Скачать и установить Гит с git-csm.com
2. Запустить Git-Bash
3. Настроить:   git config --global user.name "AndreyN"
                git config --global user.email "a.ne@mail.ru"
                git config --list

1. pwd - просмотр текущей папки
2. cd d:/unity/sb... - Переход к папке с проектом
3. ls -la - Просмотр содержимого папки
4. git status - Проверить наличие репозитория в папке; Показать изменения
5. git init - Создать репозиторий
6. git show - Просмотр последнего коммита (Enter - пролистывать; Q - выход)
7. git log - Просмотр всех коммитов

=== Дальше работает при закрытом Unity ===

1. git add . - Добавить файлы в репозиторий
2. git commit -m 'комментарий' - Добавить изменения в репозиторий
=== Убедиться, что всё загружено (не торопиться :) ) ===
3. (git remote rm origin - Если нет подключения к удалённому репозиторию)
4. Подключаемся к удалённому репозиторию:
    1-й вариант: git remote add origin https:// github.com/brrrzil/sb-gb-zeus.git
    2-й вариант: git remote add origin https://github.com/myreposname
5. git push -u origin master - Отправляем локальный на удалённый
