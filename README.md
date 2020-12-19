﻿##ОТЧЁТ О ЛАБОРАТОРНОЙ РАБОТЕ №6 
## ПО ОСНОВАМ ПРОГРАММИРОВАНИЯ



###Ход работы:
На сайте GitHub делаем копию https://github.com/Kurtyanik/LR6/ через форк

![Копированный репозиторий](screenshots/scr1.png)

С помощью команды _cd D:/_ в консоли Git Bash переходим на диск D, создаем папку lab6 (_mkdir lab6_) и переходим в нее по команде _cd_

![Переход внужнную папку](screenshots/scr2.png)

Используем команду _git init_ для инициализации гит в данной папке. Затем связываем локальный и удаленный гит командой _git remote add origin_ и клонируем в папку lab6 

![Инициализация, связь, копирование](screenshots/scr3.png)

Добавляем новый пустой файл "newFile.txt" через сайт github.com.  Подгружаем изменения с удаленного репозитория

![Пустой файл "newFile.txt"](screenshots/scr4.png)
![Пустой файл "newFile.txt" в репозитории](screenshots/scr5.png)

Через _git log_ выводим все изменения

![Коммиты](screenshots/scr6.png)

Получаем подробную информацию о последнем изменении

![ПОследний коммит](screenshots/scr7.png)

Создаем и переходим в ветку **branch1* командой git checkout -b origin/branch1

![Создание и переход в branch1](screenshots/scr8.png)

Возвращаемся в ветку master и производим слияние. Перед этим необходимо исправить файл mergefile.txt для удаления противоречивой информации. Отправляем через push данные на удаленные репозиторий. 

![Слияние веток](screenshots/scr9.png)

Добавляем пустой файл

![Добавление пустого файла](screenshots/scr10.png)

Запрашиваем коммиты чеез _git log_

![Коммиты](screenshots/scr11.png)

Удаляем последний коммит с помощью _git reset --hard HEAD~1_ и отправляем данные об изменении ветки

![Откат последнего коммита](screenshots/scr12.png)
![push](screenshots/scr13.png)
![репозиторий после удаления последнего коммита](screenshots/scr14.png)

Создаем ветку **otchetLR** и переходим в нее
Далее вызываем графическое изображение веток в консоль

![графическое представление веток](screenshots/scr15.png)

Оформляю отчёт в файле **README.md** используя блокнот
![Readme](screenshots/scr6.png)

Все изображения скриншотов находятся в папке **screenshots**


