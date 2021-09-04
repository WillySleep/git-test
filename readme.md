# ВАЖНОЕ
## Инициализация
`git init` - Инициализация

## Commit

#### Создать Commit

`git commit -m "<ИМЯ КОМИТА>"` - Создать комит

#### Добавление файла(ов) в Commit

`git add <ИМЯ ФАЙЛА>` - Добавить файл в комит

`git add .` - Добавить ВСЕ файлы к комит


## Ветки

`git branch <ИМЯ ВЕТКИ>` - Создать ветку

#### Редактирование Ветки

`git branch -M <ИМЯ ВЕТКИ>` - Переименовать ТЕКУЩУЮ ветку

`git branch -D <ИМЯ ВЕТКИ>` - Удалить ветку

`git merge <ИМЯ ВЕТКИ (НЕ ТЕКУЩЕЙ)>` - Соеденить ветку с текущей веткой

#### Прочее про Ветки

`git checkout <ИМЯ УЖЕ СОЗДАННОЙ ВЕТКИ>` - Переключиться на ветку

`git checkout -b <ИМЯ НЕ СОЗДАННОЙ ВЕТКИ>` - Создать ветку, и сразу пернключиться на неё

ЕСТЬ ФАЙЛ `.gitignore`, КОТОРЫЙ ЗАПРЕЩЯЕТ КОМИТУ, ДОСТУП К УКАЗАННЫМ ПАПКАМ И ФАЙЛАМ

## Клонирование

`git clone <ССЫЛКА>` - Клонировать репозиторый в текущую папку

## Получение файлов

`git pull` - Получить все файлы из репозитория

# Репозиторий и Пушь

`git remote add origin https://github.com/<ПОЛЬЗОВАТЕЛЬ>/<ИМЯ РЕПОЗИТОРИИ>.git` - Указываем на какой репозиторий разсчитывать

`git push -u origin <ИМЯ ВЕТКИ>` - Делпем PUSH определённой ветки

# Консоль (Полезные команды)

| Команда         | Описание команды            |
| ----------------|:---------------------------:|
| `git --version` | Просмотреть команды         |
| `ls (dir)`      | Список текущик папок/файлов |
| `cd`            | Изменить директорию         |
| `mkdir`         | Создать директорию/папку    |

# Пример добавления (Личное)

| Команда                           | Описание команды            |
| ----------------------------------|:----------------------------|
| `git add .`                       | Добавляем файлы в Commit    |
| `git commit -m "Обновлён Readme"` | Делаем Commit               |
| `git push -u origin master`       | Пушим в репозиторий         |
