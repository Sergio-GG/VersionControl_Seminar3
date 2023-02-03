# VersionControl_Seminar3

Репозиторий для пулл-реквестов по Введению в контроль версий в Geekbrains

## Что такое система контроля версий Git?

Git - это одна из реализаций распределенных ситстем контроля версий , которая работает как  с локальными, так и удаленными репозиториями. Является самой популярной реализацией систем контроля в мире. 

## Подготовка репозитория

Для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием. C этого начинается работа в теминале.

## Git add - add, add

Для добавления изменений в  commit используется команда *git add*. Чтобы использовать команду  *git add*,  напишите *git add имя_файла* или *git add*

## Создание коммитов

Для того, чтобы создать commit (сохранение), необходимо выполнить команду *git commit -m "Сообщение"* или *git commit -am "Сообщение"*. Обычно следует сразу за командой *git add*.

## Создание веток

Для того, чтобы создать ветку, нужно использовать *git branch имя_ветки* или *git checkout -b имя_ветки* (последняя команда переместит в новую ветку)

## Git log

Чтобы посмотреть история коммитов , нажмите *git log*. Если нужно кратко, то *git log  --oneline*. Для отображения веток команда *git log --graph*. Чтобы отобразить журнал сжато, используется команда *git log --oneline*.

## Слияние веток

Чтобы слить ветки в текущую, нажмите *git merge имя_файла*.

## Conflict branch

Создание ветки для отображения.

## Основные команды в Git

*git --version* - команда для проверки версий git

*git init* - инициализируем пустой репозиторий

*git status* - проверяем текущий статус

*git add*  - файла с расширением - добавляем версионность файлу

*git add .* - добавляет версионность всем файлам в папке

*git commit -m 'Сообщение'* - команда для фиксации файлов

*git commit -am* - фиксация изменений без использования git add

*git diff* - вывод изменений на текущий момент по отношению к последнему commit

*git log* - вывод истории commit  в хронологическом порядке

*git checkout хэш коммита* - переход между коммитами

*git checkout master* - возврат текущему состоянию

*git clone ссылка* - команда для загрузки удаленного репозитория

*git push*  - команда для отправки из локального репозитория в удаленный

*git pull* - команда для подгрузки изменений из удаленного репозитория в локальный

*git branch* - посмотреть список веток

*git branch название_ветки* - создать новую ветку

*git checkout -b название_ветки* - перейти к другой ветке и , если ее нет, то создать

*git branch -d название_ветки* - удалить ветку

Скриншот домашнего заданияЖ

![Screenshot](../../screenshot.png)

[Ссылка на страницу](https://github.com/GiliazovaPullrequests/VersionControl_Seminar3/pull/320)