

# Инструкция для работы с Git и удаленными репозиториями

## Что такое Git?
Git - одна из реализаций распределенных систем контроля версий, имеющая как локальные, так и удаленные репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием и у вас создатся репозиторий(скрытая папка .git).  git init – инициализация локального репозитория.

### git add
Для добавления измейнений в коммит используется команда *git add*. Что бы использовать команду *git add* напишите *git add <имя файла>*. git add – добален ие файла или файлов к следующему коммиту. 

### git status
Для того чтоб просмотреть состояние репозитория, используется команда *git status* git status – получение информацию от git о его текущем состоянии.

### Создание коммитов
Для того, чтоб создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: git commit -m *<сообщение к коммиту>*. Все файлы для коммита должны быть **добавлены** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.
ы
## Перемещение между сохранениями checkout
Что бы переместиться из одного коммита в другой, используем комманду *git checkout*. Например: 
**git checkout <7bfce9d306b7915dbcbf7fbedfbbc2d13e0db7c7>**

## Журнал изменений
Для того, чтоб посмотреть все сделанные изменения в репозитории используется команда *git log*


### Ветки в git

### Создание ветки

Для того чтоб создать ветку используется команда *git branch* . **git branch <имя ветки>**

### Слиdяние веток
Команда *git merge <ИмяВетки>* производит слияние указаной ветки в ту, в которой мы находимся в момент написания команды.

## Удаление веток
Что бы удалить ветку используем команду *git branch -d <имя ветки>*.

# *Работа с удаленными репозиториями*

## Где находятся удаленные репозитории

## Подключение к удаленному репозиторию
Команда *git remote* используется для выполнения удаленных подключений, таких как подключение локального репозитория Git к удаленному репозиторию GitHub.

## git pull info
Команда *git pull* используется для извлечения и загрузки содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым.git 