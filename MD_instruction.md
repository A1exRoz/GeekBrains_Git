# [Ссылка на Шпаргалку по Markdown](https://github.com/A1exRoz/Markdown-Cheatsheet "GitHub") 
Все ссылки кликабельны и ведут на оргинал.  
Нашел на просторах интернета и перепечатал в ручную. Зато честно))
![logo](https://pngimg.com/uploads/github/github_PNG88.png "GitHub")

## 1. [Заголовки](https://github.com/A1exRoz/Markdown-Cheatsheet#headers)
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
Кроме того, H1 и H2 можно обозначить подчеркиванием:
```
Alt-H1
======

Alt-H2
------
```
## 2. [Выделение](https://github.com/A1exRoz/Markdown-Cheatsheet#emphasis)
```
Курсив обозначается *звездочками* или _подчеркиванием_.

Полужирный шрифт - двойными **звездочками** или __подчеркиванием__.

Комбинированное выделение **звездочками и _подчеркиванием_**.

Для зачеркнутого текста используются две тильды . ~~Уберите это.~~
```
## 3. [Списки](https://github.com/A1exRoz/Markdown-Cheatsheet#lists)
```
1. Первый пункт нумерованного списка
2. Второй пункт
⋅⋅*Ненумерованный вложенный список.
1. Сами числа не имеют значения, лишь бы это были цифры
⋅⋅1. Нумерованный вложенный список
4. И еще один пункт.

⋅⋅⋅Внутри пунктов списка можно вставить абзацы с таким же отступом. Обратите внимание на пустую строку выше и на пробелы в начале (нужен по меньшей мере один, но здесь мы добавили три, чтобы также выровнять необработанный Markdown).

⋅⋅⋅Чтобы вставить разрыв строки, но не начинать новый параграф, нужно добавить два пробела перед новой строкой.⋅⋅
⋅⋅⋅Этот текст начинается с новой строки, но находится в том же абзаце.⋅⋅
⋅⋅⋅(В некоторых обработчиках, например на Github, пробелы в начале новой строки не нужны.)

* Ненумерованный список можно размечать звездочками
- Или минусами
+ Или плюсами
```

## 4. [Ссылки](https://github.com/A1exRoz/Markdown-Cheatsheet#links)
```[Обычная ссылка в строке](https://www.google.com)```

```[Обычная ссылка с title](https://www.google.com "Сайт Google")```

```[Ссылка со сноской][Произвольный регистронезависимый текст]```

```[Относительная ссылка на документ](../blob/master/LICENSE)```

```[Для ссылок со сноской можно использовать цифры][1]```

Или можно просто вставить ссылку в квадратные скобки ```[текст ссылки]```

Произвольный текст, после которого можно привести ссылки.

[произвольный регистронезависимый текст]: https://www.mozilla.org
[1]: http://slashdot.org
[текст ссылки]: http://www.reddit.com

## 5.  [Изображения](https://github.com/A1exRoz/Markdown-Cheatsheet#images)
Вот наш логотип (наведите указатель, чтобы увидеть текст заголовка):

Внутри строки:  
![alt-текст](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Текст заголовка логотипа 1")

В сноске:  
![alt-текст][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Текст заголовка логотипа 2"

## 6. [Подсветка кода и синтаксиса](https://github.com/A1exRoz/Markdown-Cheatsheet#code)
`Код` в строке обрамляется `обратными апострофами`.
```javascript
var s = "Подсветка JavaScript";
alert(s);
```
 
```python
s = "Подсветка Python"
print s
```
 
```
Язык не указан, синтаксис не подсвечен.
Но мы вставим в него <b>тег</b>.
```


## 7. [Таблицы](https://github.com/A1exRoz/Markdown-Cheatsheet#tables)
Вертикальные линии обозначают столбцы.
```
| Таблицы       | Это                | Круто |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    | $1600 |
| столбец 2     | выровнен по центру |   $12 |
| зебра-строки  | прикольные         |    $1 |
```
Внешние вертикальные линии (|) не обязательны и нужны только, чтобы сам код Markdown выглядел красиво. Тот же код можно записать так:
```
Markdown | не такой | красивый
--- | --- | ---
*Но выводится* | `так же` | **клево**
1 | 2 | 3
```
## 8. [Цитаты](https://github.com/A1exRoz/Markdown-Cheatsheet#blockquotes)
```> С помощью цитат очень удобно в письме обозначать исходный текст.```
```> Эта строка - часть той же цитаты.```

Разрыв цитаты.

```> Это очень длинная строка, но она будет правильно процитирована даже при размещении на нескольких строках. Продолжаем писать, чтобы эта строка не вмещалась на одной строке в любом окне. Кстати, в цитаты можно *вставлять* даже **Markdown**.```

## 9. [Встроенный HTML](https://github.com/A1exRoz/Markdown-Cheatsheet#html)
```<dl>
  <dt>Список определений</dt>
  <dd>Это то, что люди иногда используют.</dd>

  <dt>Markdown внутри HTML</dt>
  <dd>Работает *не очень** хорошо. Используйте HTML-<em>теги</em>.</dd>
</dl>
```
## 10. [Горизонтальная линия](https://github.com/A1exRoz/Markdown-Cheatsheet#hr)
Три и более...

---

Дефисы ```---```

***

Звездочки ```***```

___

Подчеркивания ```___```

## 11. [Новая строка](https://github.com/A1exRoz/Markdown-Cheatsheet#lines)
```
Это начальная строка

Эта строка отделена от предыдущей двумя новыми строками и станет *отдельным абзацем*.

Это тоже отдельный абзац, но...⋅⋅<[здесь два пробела]
Эта строка отделена одной новой строкой, поэтому она находится в *том же абзаце*.
```
## 12. [Видео](https://github.com/A1exRoz/Markdown-Cheatsheet#videos)
Ролики нельзя вставить напрямую, но можно вставить изображение со ссылкой на видео, например:
<a href="тут должна быть ссылка на видео" target="_blank"><img src="тут должна быть ссылка на картинку" 
alt="ALT-ТЕКСТ ИЗОБРАЖЕНИЯ" width="240" height="180" border="10" /></a>

На чистом Markdown, но без размеров изображения и рамки:

[![ALT-ТЕКСТ ИЗОБРАЖЕНИЯ](ссылка_на_картинку)](ссылка_на_видео)