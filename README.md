﻿# Инструкция 


> Вы установили себе Git и можете им пользоваться. Давайте теперь его настроим, чтобы когда вы создавали commit, указывался автор, кто его создал.

> Открываем терминал (Linux и MacOS) или консоль (Windows) и вводим следующие команды.
> 
> #Установим имя для вашего пользователя
> 
> #Вместо <ваше_имя> можно ввести, например, Grisha_Popov
> 
> #Кавычки оставляем
> 
```
git config --global user.name "<ваше_имя>"
```

> #Теперь установим email. Принцип тот же.
```
git config --global user.email "<адрес_почты@email.com>"
```

## git init
команда ``git init`` создает\инициализурет репозиторий

## git add
команда ``git add .`` или ``git add --all`` - добавляет все файлы в репозиторий

``git add <имя файла>`` добавляет в репозиторий конкретный файл

## git сommit
  
команда ``git commit -m "<комментарий>"``  создает коммит

![](1.jpg)

> Чаще всего их создают, когда:
> - Создан новый функционал
> - Добавлен новый блок на верстке
> - Исправлены ошибки по коду
> - Вы завершили рабочий день и хотите сохранить код


## git status
  
команда ``git status``  показывает:
- на какой мы ветке
- изменения в файлах
- неотслеживаемые изменения и файлы
```
git status
```
## git log
  
команда ``git log``  показывает историю ветки
```
git log
```
[подробнее можно почитать по этой ссылке](https://habr.com/ru/post/541258/)

[и по этой](https://habr.com/ru/post/542616/)

git checkout