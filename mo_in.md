# Инструкция для работы с маркдаун

## Выделение текста

Что бы выделить текст курсивом необходимо обромить его звездочками (*текст*), или знаком нижнего подчеркивания (_вот так_)

Что бы выделить текст полужирным необходимо выделить его двойными звездочками (**текст**), или двойным знаком нижнего подчеркивания(__вот так__)

Альтернативные способы выделения текста жирным или курсивом нужны для того что бы мы могли совмещать ети два способа. Например: _текст может быть курсивом и при этом **полужирным**_.

## Списки

Что бы добавить ненумерованые списки необходимо пункты выделить звездочкой (*)или знаком "+"
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4
+ Элемент 5

Что бы добавить нумерованые списки, необходимо пункты просто пронумеровать, вот так:
1. Элемент 1
2. Элемент 2
3. Элемент 3

## Работа с изображением

Что бы вставить изображение в текст, достаточно написать следующее: ![привет, это сися](сися.avif)

## Ссылки
Для того что бы сделать ссылку нужно вставить ее в скобочки вот так [тут можно делать текст для ссылки](https://git-scm.com/book/ru/v2/%D0%9F%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5-C%3A-%D0%9A%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B-Git-%D0%92%D0%B5%D1%82%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B8-%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D1%8F)
Сама ссылка находить в круглых скобочках.


## Работа с таблицами

Что бы создать горизонтальну линию нужно сделать тире"-"

---
| Один | Пять | Сто | 
|------|------|-----|
| Два  | Шесть| Двести|
| Три  | Семь | Триста|

Вот так делаються таблицы вроде.

## Цитаты
Что бы сделать цитаты нужно поставить знак ">". Например:
> Цитата номер один
>> Цитата номер два
>>> Цитата номер три 

## Еще одна таблица

<table>
    <tr>
        <th>Заголовок 1</th>
        <th>Заголовок 2</th>
    </tr>
    <tr>
        <td>Ячейка 1.1</td>
        <td>Ячейка 2.1</td>
    </tr>
    <tr>
        <td>Ячейка 1.2</td>
        <td>Ячейка 2.2</td>
    </tr>
</table>

## Работа с удаленными репозиториями

git clone-команда позволяет склонировать репозиторий на наш ПК.

git pull-команда позволяет скачать все из текущего репозитория и автоматически сделает слияние с нашей версией.

git push-команда вашу версию репозитория во внешнюю.

## Как сделать pull request 
+ Делаем *fork* репозиторий
+ Делаем скол *своей версии*
+ Создаем новую ветку, и в *нее* вносим свои изменения
+ Фиксируем изменения при помощи коммитов
+ Отправляем версию в *свой github*
+ На сайте github нажимаем кнопку *pull request*