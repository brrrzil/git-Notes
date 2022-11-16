# git-Notes
How to use Git
1. Скачать и установить Гит с git-csm.com
2. Настроить:   * git config --global user.name "AndreyN"
                * git config --global user.email "a.ne@mail.ru"
                * git config --list
3. * pwd - просмотр текущей папки
4. Переход к папке с проектом * cd d:/unity/sb...
5. Просмотр содержимого папки * ls -la
6. Проверить наличие репозитория в папке * git status
7. Создать репозиторий * git init
7.5 Дальше работает при закрытом Unity
8. Добавить файлы в репозиторий: * git add .
                                 * git commit -m 'комментарий'
                                 Убедиться, что всё загружено (не торопиться :) )
9. Информация о последнем коммите * git show (убеждаемся, что всё закоммичено)
            !!!ДЛЯ ВЫХОДА ИЗ ПРОСМОТРА НАЖИМАЕМ Q!!!

10. Подключаемся к удалённому репозиторию * git remote add origin https://github.com/myreposname
11. Отправляем локальный на удалённый * git push -u origin master
