# Инструкция по работе с Git - om

Чтобы создать репозиторий, мы используем команду:

**git init** - создаёт локальный репозиторий

Для работы в репозитории мы используем команды:

1. **git add filename** - сохранить файл с именем filename в репозитории
2. **git add .** - сохранить **АБСОЛЮТНО** все файлы в вашем репозитории
3. **git status** - получить информацию от git о его текущем состоянии
4. **git commit -m “message”** – создание коммита
5. **git log** – вывод на экран истории всех коммитов с их хеш-кодами
6. **git checkout** – переход от одного коммита к другому
7. **git checkout master(main)** – вернуться к актуальному состоянию и продолжить работу
8. **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом

Чтобы вставить картинку, нужно написать ! [ текст ] ( картинка )
![Здесь должна быть картинка](arni.jpg)





Семинар урок 2

Хождение по веткам, сливаем ветки в main, делаем конфликт

1. **git branch** - посмотреть ветки
2. **git merge 'name_branch'** - слить ветку нейм_бранч в мейн
3. **git branch -d 'name_branch'** - удалить ветку нейм_бранч
4. **git checkout 'name_branch'** - перейти на ветку
5. **git branch -m 'name_branch'** - переименовать текущую ветку
6. **git branch name_branch** - создать ветку name_branch
7. **git log** - показать историю коммитов
8. **git log --graph** - показать историю коммитов в графическом виде
9. **git checkout -b 'name_branch'** - создать и сразу перейти в ветку
10. **git clone <url-адрес репозитория>** – клонирование внешнего репозитория на  локальный ПК
11. **git pull** – получение изменений и слияние с локальной версией
12. **git push** – отправляет локальную версию репозитория на внешний