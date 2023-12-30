# Создали working_with_git 

## Создание репозитория:

```sh
git init
```

### Добавить к индексации
```sh
git add
```

### Зафиксировать изменения
```sh
git commit -m "Message text"
```

### Псмотреть лог в полном виде
```sh
git log
```

### Посмотреть лог в сокращенном виде
```sh
git log --oneline
```

### Перемещение по веткам
```sh
git checkout <file_name>
```

### Отображение всех веток
```sh
git branch
```

### Создание новой ветки
```sh
git branch <имя_ветки>
```

### Удаление ветки
```sh
git branch -d <имя_ветки>
```

### Клонирование внешнего репозитория 
```sh
git clone
```

### Команда, позволяющая скачать все из текущего репозитория и автоматически слить с нашей версией 
```sh
git pull
```

### Команда, позволяющая отправить нашу версию репозитория на внешний репозиторий
```sh
git push
```

# Работа с удаленным репозиторием

1. Создали аккаунт на Github.com
2. Создать локальный репозиторий.
3. Выкачать *(pull)* актуальное состояние из удаленного репозитория.
4. "Подружить" Ваш локальный и удаленный репозиторий. Github при создании нового репозитория подскажет как это можно сделать!
5. Провести изменения "с другого компьютера"
6. Отправить *(push)* Ваш локальный репозиторий в удаленный *(на github)*, при этом, возможно, нужно будет авторизоваться на удаленном репозитории.

## Работа с НЕ Вашим удаленным репозиторием 

1. Делаем форк *(fork)* интересующего нас репозитория.
2. Мы делаем *git clone* для нашей версии этого репозитория.
3. Мы создаем ветку с предлагаемыми изменениями.
4. Производим все изменения ТОЛЬКО в этой ветке.
5. Отправляем эти изменения на свой аккаунт *(push)*.
6. В окне на Github появляется возможность отправить *pull request*.