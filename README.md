# Markdown
Упражнение. Синтаксис markdown
Упражнение 1. Для каждой строки ниже повторите с использовани maekdown.
<pre>
Код:
# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня
</pre>
***Результат:***

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня

----************************************************************************************---

Блочная цитата
A plain code block
<pre>
Код: 
***Курсивный текс* и _Курсивный текс_ 
**Жирный текст** и __Жирный текст__ 
***Жирный и курсивный текст***** 
</pre>
***Результат:***

***Курсивный текс* и _Курсивный текс_ <br>
**Жирный текст** и __Жирный текст__ <br>
***Жирный и курсивный текст***** 

----************************************************************************************---

<pre>
Код: 
 > Markdown это облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.
>
> Материал из Википедии — свободной энциклопедии
</pre>
***Результат:***

> Markdown это облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.
>
> Материал из Википедии — свободной энциклопедии


----************************************************************************************---

Ненумерованный список:

-	Пункт 1
-	Пункт 2
     + подпункт 1
     + подпункт 2

* Пункт 1
* Пункт 2
   + подпункт 1
   + подпункт 2

1. ordered list
2. item 2
   + sub-item 1
   + sub-item 2
   
Упорядоченный список:

1.	Пункт 1
2.	Пункт 2
   a.подпункт 1
   b.подпункт 2
***

1. Пункт списка
2. Пункт списка
   1. Подпункт
   2. Подпункт
   3. Подпункт
***
* Пункт списка
* Пункт списка
  * Подпункт
  * Подпункт
* Пункт списка
***
1. Нумерованный пункт
2. Нумерованный пункт
   * Маркированный подпункт
   * Маркированный подпункт
1. Нумерованный пункт
***
1. [x] Отмеченный пункт
2. [] Неотмеченный пункт
3. [] Неотмеченный пункт
***
- [x] Отмеченный пункт
- [] Неотмеченный пункт
- [] Неотмеченный пункт
***
<pre>
 Код:
- Первый пункт.
- Второй пункт.
- Третий пункт.
</pre>
***Результат:***

- Первый пункт.
- Второй пункт.
- Третий пункт.  

----************************************************************************************---
<pre>
 Код:
1. Первый пункт.
2. Второй пункт.
3. Третий пункт.
</pre> 
***Результат:***

1. Первый пункт.
2. Второй пункт.
3. Третий пункт.   

----************************************************************************************---

<pre>
Код:
1. Первый пункт.
- Первый подпункт.
- Второй подпункт.
- Третий подпункт.
2. Второй пункт.
- Первый подпункт.
- Второй подпункт.
- Третий подпункт.
</pre>
***Результат:***
  
1. Первый пункт.
- Первый подпункт.
- Второй подпункт.
- Третий подпункт.
2. Второй пункт.
- Первый подпункт.
- Второй подпункт.
- Третий подпункт.

----************************************************************************************---

<pre>
Код:
~~вычеркнутый текст~~
__подчеркнутый текст__

инструкции: --

черточка: ---

многоточие: ...

встроенное уравнение: $A = \pi*r^{2}$

горизонтальная линейка (или разрыв слайда):

***
---
___

$Е = мс^{2}$

>Цитата с *курсивом*
 
</pre>
***Результат:***

~~вычеркнутый текст~~
__подчеркнутый текст__

инструкции: --

черточка: ---

многоточие: ...

встроенное уравнение: $A = \pi*r^{2}$

горизонтальная линейка (или разрыв слайда):

***
---
___

$Е = мс^{2}$

>Цитата с *курсивом*

----************************************************************************************---

<pre>
Код:
Table Header  | Second Header
------------- | -------------
Table Cell    | Cell 2
Cell 3        | Cell 4

Стол:
Заголовок 1	| Заголовок 2
----------- | ------------
Ячейка 1	   | Ячейка 2
Ячейка 3	   | Ячейка 4
</pre>
***Результат:***

Table Header  | Second Header
------------- | -------------
Table Cell    | Cell 2
Cell 3        | Cell 4

Стол:
Заголовок 1	| Заголовок 2
----------- | ------------
Ячейка 1	   | Ячейка 2
Ячейка 3	   | Ячейка 4

----************************************************************************************---

<pre>
Код: 
```{r}
paste("Hello", "World!")
```
</pre>
***Результат:***

```{r}
paste("Hello", "World!")
```

----************************************************************************************---
<pre>
Код:
# Dividing slides 1
Pandoc will start a new slide at each first level header
## Header 2
… as well as each second level header
***
You can start a new slide with a horizontal rule`***` if you do not want
a header.
## Bullets
Render bullets with
- a dash
- another dash
## Incremental bullets
>- Use this format
>- to have bullets appear
>- one at a time (incrementally)
</pre>
***Результат:***

# Dividing slides 1
Pandoc will start a new slide at each first level header
## Header 2
… as well as each second level header
***
You can start a new slide with a horizontal rule`***` if you do not want
a header.
## Bullets
Render bullets with
- a dash
- another dash
## Incremental bullets
>- Use this format
>- to have bullets appear
>- one at a time (incrementally)

----************************************************************************************---

[ссылка]Гиперссылка (на rmarkdown.rstudio.com) (http://rmarkdown.rstudio.com) 

**[Полужирная ссылка](http://example.com)**	

[![Лого](http://img.yandex.net/i/logo95x37x8.png)](https://yandex.ru)

[Почта ya](mailto:ya@yandex.ru)















