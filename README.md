﻿# Инструкция для работы с Git и удаленными репозиториями

##Что такое Git?
Git - это одна из реализаций распределенных систем контроля версии, имеющая как локальные, так и удаленные репозитории. Является самой популярной системой контроля версии в мире.
## Подготовка репозитория
Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создается репозиторий (появится скрытая папка .git)

## Создание коммитов 

### Git add
Для добавления изменений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, что бы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо необходимо в папке с репозиторием написать *git status*, и Вы увидете были ли изменения в файлах, или их не было.

### Создание комитов
git commit -m "Комментарий к коммиту" — фиксирует изменения. До выполнения этой команды локальные изменения никуда не запишутся.
Нужно правильно разбивать изменения и давать полные комментарии к коммитам. content to append
