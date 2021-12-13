# Инструкция по работе с Git

## Создание локального репозитория
Создать локальный репозиторий с помщью комнды *git init*. для этого надо применить эту команду в той папке, где будет репозиторий.

## Добавление файлов в репозиторий
Версионность к файлу добавляется с помощью команды **git add**.Команда применяется следующим образом *git add <название файла>*

### Просмотр состояния репозитория
Для того, чтобы просмотреть состояние репозитория используется команда *git status*.

## Создание коммита
Для того, чтобы создать новый комит необходимо использовать команду *git commit*. Применяется она следующим образом *git commit -m <сообщение комиту>*. Сообщение к коммиту ***СООБЩЕНИЕ КОМИТУ ПИСАТЬ ОБЯЗАТЕЛЬНО***

## Просмотр наличия изменений
Для того, чтобы просмотреть наличие измений в локальном репозитории, необходимо использовать команду *git diff*. Вы увидите были ли изменения в файлах, или их не было.

## Просмотр разницы между текущей версией и последней сохраненной
Для того чтобы посмотреть разницу между последним коммитом и текущей версией фала используется команда *git diff*. Достаточно ее применить в папке с репозиторием

## Журнал изменений
Для просмотра истории коммитов используется команда *git log*. Её нужно применить в папке с репозиторием

## Перемещине между изменениями
Для того чтобы переместить на одно из прошлых изменений небходимо использавать команду "git checkout". Применяется в папке с репозиторием следующим образом: *git checkout <номер репозитория>*
Для возврата к последнему коммиту ветки неюходимо использовать команду *git checkout master*

## Синтаксис языка Markdown
Для того чтобы пользоваться данным языком необходимо знать его синтаксис.

Списки в языке Markdown обозначаются
1. Нумерованные списки обозначаются цифрами 1.,2., и т.д.
2. Перед информацией списка

Так же их можно обозночать по другому
* Например используя символ * перед текстом
* В видимой части будет появляться точка перед текстом не нумерованного списка

Но это еще не все
***
    Существуют вложенные списки
    Для того чтобы их сделать
    Достаточно просто нажать 3 раза пробел

## Чтобы озаглавить текст
# Необходимо использовать или две ## как в тексте на строку выше или одну # как в этой строке

Мы можем делать текст 
   1. *курсивным* поставив до и после него звездочку *
   2. **жирным** поставив до и после него двойные звездочки **
   3. ~~зачернутый текст~~ если это необходимо, используем ~~
   
### Ссылки и картинки   
Иногда на необходимо в текст вставить [ссылку](описание при наведении "Сайт моего обучения") с тайтлом [cсылка](https://gb.ru/education "Сайт моего обучения"), или без заголовка [ссылку](описание при наведении ) [ссылка](https://gb.ru/education), еще существует <безанкорная> <https://gb.ru/> ссылка  

А картинки вставляются по аналогии со ссылками. Нужно поставить восклицательные знак перед синтаксисом ссылки ![лого GB](https://conicheva84.ru/wp-content/uploads/2018/12/geekbrains_2.jpg "Лого GB")

### А что если нам нужно процитировать какую-нибудь запись?
>Тогда нам нужно будет использовать символ >
>> И так по аналогии
>>> Делая все больше и больше **сносок**
---
Но мы же разработчики и нам необходимо будет уметь выделять `исходный код`.
>> Для это будем пользоваться обратными опострофами `` заключив информацию в них.

Ну а что если нам нужно отделить чертой текст? Я делал это выше используя *** нажав enter после введенного текста и использовав эти символы
***
#### **Используй эту памятку если что то забудешь**
