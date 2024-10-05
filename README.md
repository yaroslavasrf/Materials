# Урок 1

## Виртуальное окружение: 

Создать окружение с именем _name_
```sh
python -m venv name
```

Зайти в окружение name
```sh 
source name/bin/activate
```

Установить все библиотеки из файла _requirements.txt_
```sh
pip instal -r requirements.txt
```

## Основные команды git
Создать репозиторий
```sh
git init
```

Добавить измененный/созданный файл (например filename.txt): 
```sh 
git add filename.txt
```

Сохранить изменения (взамен _message_ - краткое описание того, что сделали): 
```sh
git commit -m "message"
```

Отправить изменения на github: 
```sh
git push origin main
```

Посмотреть текущие изменения (выведет все новые и измененные файлы): 
```sh
git status
```

