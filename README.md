# git-Notes
How to use Git
1. Скачать и установить Гит с git-csm.com
2. Запустить Git-Bash
3. Настроить:   git config --global user.name "AndreyN"
                git config --global user.email "a.ne@mail.ru"
                git config --list

4. pwd - просмотр текущей папки
5. cd d:/unity/sb... - Переход к папке с проектом
6. ls -la - Просмотр содержимого папки
7. git status - Проверить наличие репозитория в папке
8. git init - Создать репозиторий
9. git show - Просмотр последнего коммита (Enter - пролистывать; Q - выход)

=== Дальше работает при закрытом Unity ===

10. git add . - Добавить файлы в репозиторий
11. git commit -m 'комментарий'
=== Убедиться, что всё загружено (не торопиться :) ) ===
12. git show - Просмотр последнего коммита (Enter - пролистывать; Q - выход)
13. (git remote rm origin - Если нет подключения к удалённому репозиторию)
14. Подключаемся к удалённому репозиторию:
    1-й вариант: git remote add origin https:// github.com/brrrzil/sb-gb-zeus.git
    2-й вариант: git remote add origin https://github.com/myreposname
15. git push -u origin master - Отправляем локальный на удалённый
