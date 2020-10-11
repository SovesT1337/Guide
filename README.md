# Гайд для Linux по git
### Установка

**Для убунту**

sudo apt install git

**Для МакОС**

https://git-scm.com/download/mac

### Настройка

git config --global user.name "ваше имя"

git config --global user.email "github email"

### Работа с лабами

Находим нужную нам лабу и тыкаем по этой кнопочке

![](https://camo.githubusercontent.com/00c8cb4d3424672f90d1e15d5daf8da7b3a3f9ef/687474703a2f2f692e737461636b2e696d6775722e636f6d2f6c72346d6c2e706e67)

Теперь у вас есть клонироанный репозиторий лабы 

Далее ее надо скачать к себе на пк и начать работать. Жмем на кнопку и копируем ссылку

![](https://miro.medium.com/max/576/1*CSsM8NturhjcrN2npNMLQg.png)

Идем в терминал 

git clone то_что_вы_только_что_скопировали

Нужно создать новую ветку

Переходим в терминале в место куда скачалась лаба и прописываем

git checkout -b название_ветки

git submodule update --init

Можно работать с лабой

### Сдача

Чтоб сдать лабу надо загрузить ее на гитхаб

Открываем терминал и переходим туда где лежит лаба

git status

Видим файлы которые нам нужно добавить 

git add название_измененного_файла

Еще раз проверяем ничего ли мы не забыли

git status

Имена файлов должны быть зеленого цвета

Создаем коммит

git commit -m “сообщение_коммита”

Загружаем на гитхаб

git push origin название_ветки

Все готово!

### P.S.

За орфографию и отсутсвие пунктуации извините 

**Copyright 2020 A-Lazar-A**
