<p style="align:center">Markdown</p>

```
Код:
# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня
```

***Результат:***

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня
#### Заголовок четвертого уровня
##### Заголовок пятого уровня
###### Заголовок шестого уровня
***

Блочная цитата
A plain code block
```
Код: 
***Курсивный текс* и _Курсивный текс_ 
**Жирный текст** и __Жирный текст__ 
***Жирный и курсивный текст***** 
```
***Результат:***

***Курсивный текс* и _Курсивный текс_ <br>
**Жирный текст** и __Жирный текст__ <br>
***Жирный и курсивный текст***** 
***

```
Код: 
 > Markdown это облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.
>
> Материал из Википедии — свободной энциклопедии
```
***Результат:***

> Markdown это облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.
>
> Материал из Википедии — свободной энциклопедии
----
Код:
```
> [!NOTE]  
> Выделяет информацию, которую пользователи должны учитывать, даже при беглом просмотре.

> [!TIP]
> Необязательная информация, которая поможет пользователю добиться большего успеха.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Важнейшая информация, необходимая для успеха пользователей.

> [!CAUTION]
> Потенциальные отрицательные последствия действия.
```
***Результат:***
> [!NOTE]  
> Выделяет информацию, которую пользователи должны учитывать, даже при беглом просмотре.

> [!TIP]
> Необязательная информация, которая поможет пользователю добиться большего успеха.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Важнейшая информация, необходимая для успеха пользователей.

> [!CAUTION]
> Потенциальные отрицательные последствия действия.

----
Код:
```
:::type "title"
Content
:::
```
***Результат:***

:::type "title"
Content
:::
----
Код:
```
Left(открывающая) кавычка: &#8220;
Right (закрывающая) кавычка: &#8221;
Right (закрывающая) одинарная кавычка или апостроф: &#8217;
Left (открывающая) одинарная кавычка (используется редко): &#8216;
лампочка &#128161;
```
***Результат:***

Left(открывающая) кавычка:  &#8220;<br>
Right (закрывающая) кавычка:  &#8221;<br>
Right (закрывающая) одинарная кавычка или апостроф:  &#8217;<br>
Left (открывающая) одинарная кавычка (используется редко):  &#8216;<br>
лампочка &#128161;
----
Код:
```
Спойлер
<details>
    <summary>Название</summary>
    Какой-нибудь длиинный дополнительный текст, который по умолчанию должен быть скрыт. Его можно показать, нажав на спойлер.
</details>
```
***Результат:***
<details>
    <summary>Название</summary>
    Какой-нибудь длиинный дополнительный текст, который по умолчанию должен быть скрыт. Его можно показать, нажав на спойлер.
</details>

- [X] @octocat :+1: This PR looks great - it's ready to merge! :shipit:
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ]  \(Optional) Open a followup issue

```mermaid
  info
```
----
Код:
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```
***Результат:***
Here is a simple footnote[^1].
A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
  
```
Ненумерованный список:
- Пункт 1
- Пункт 2
   * подпункт 1
   * подпункт 2

* Пункт 1
* Пункт 2
   + подпункт 1
   + подпункт 2

- Пункт 1
- Пункт 2
    - подпункт 1
    - подпункт 2
      - подпункт 1
      - подпункт 2

1. ordered list
2. item 2
   + sub-item 1
   + sub-item 2
```
***Результат:***

Ненумерованный список:

-	Пункт 1
-	Пункт 2
     * подпункт 1
     * подпункт 2

* Пункт 1
* Пункт 2
   + подпункт 1
   + подпункт 2

-	Пункт 1
-	Пункт 2
    - подпункт 1
    - подпункт 2
      - подпункт 1
      - подпункт 2

1. ordered list
2. item 2
   + sub-item 1
   + sub-item 2
***

```
1. Пункт списка
2. Пункт списка
   1. Подпункт
   2. Подпункт
   3. Подпункт

* Пункт списка
* Пункт списка
  * Подпункт
  * Подпункт
* Пункт списка
```
***Результат:***

1. Пункт списка
2. Пункт списка
   1. Подпункт
   2. Подпункт
   3. Подпункт   

* Пункт списка
* Пункт списка
  * Подпункт
  * Подпункт
* Пункт списка
***
```
1. Нумерованный пункт
2. Нумерованный пункт
   * Маркированный подпункт
   * Маркированный подпункт
1. Нумерованный пункт
```
***Результат:***

1. Нумерованный пункт
2. Нумерованный пункт
   * Маркированный подпункт
   * Маркированный подпункт
1. Нумерованный пункт
***
```
1. Это
1. родительский нумерованный список
1. и это
1. вложенный нумерованный список
1. (fin)
```
***Результат:***

1. Это
1. родительский нумерованный список
1. и это
1. вложенный нумерованный список
1. (fin)
***
```markdown
> [!div class="checklist"]
> * List item 1
> * List item 2
> * List item 3
```
***Результат:***

> [!div class="checklist"]
> * List item 1
> * List item 2
> * List item 3
***

```
1. [x] Отмеченный пункт
2. [] Неотмеченный пункт
3. [] Неотмеченный пункт
```
***Результат:***
1. [x] Отмеченный пункт
2. [ ] Неотмеченный пункт
3. [ ] Неотмеченный пункт
***
```
- [x] Отмеченный пункт
- [] Неотмеченный пункт
- [] Неотмеченный пункт
```
***Результат:***
- [x] Отмеченный пункт
- [] Неотмеченный пункт
- [] Неотмеченный пункт
***
```
- [x] Отмеченный пункт
- [ ] Неотмеченный пункт
- [  ] Неотмеченный пункт
```
***Результат:***
- [x] Отмеченный пункт
- [ ] Неотмеченный пункт
- [  ] Неотмеченный пункт
***
```
 Код:
- Первый пункт.
- Второй пункт.
- Третий пункт.
```
***Результат:***

- Первый пункт.
- Второй пункт.
- Третий пункт.  
***
```
 Код:
1. Первый пункт.
2. Второй пункт.
3. Третий пункт.
``` 
***Результат:***

1. Первый пункт.
2. Второй пункт.
3. Третий пункт.   
***
```
Код:
1. Первый пункт.
   - Первый подпункт.
   - Второй подпункт.
   - Третий подпункт.
2. Второй пункт.
- Первый подпункт.
- Второй подпункт.
- Третий подпункт.
```
***Результат:***
  
1. Первый пункт.
   - Первый подпункт.
   - Второй подпункт.
   - Третий подпункт.
2. Второй пункт.
- Первый подпункт.
- Второй подпункт.
- Третий подпункт.
***
```
1. пункт 1
5. пункт 5
15. Item 15
55. Item 55
```
***Результат:***
1. пункт 1
5. пункт 5
15. Item 15
55. Item 55
***
```
1. 1 Пункт
2. Пункт вложенность:
    1. 1 вложенный пункт
    2. 2 вложенный пункт
       * вложенный пункт
       * вложенный пункт
3. Снова первый уровень
```
***Результат:***
1. 1 Пункт
2. Пункт вложенность:
    1. 1 вложенный пункт
    2. 2 вложенный пункт
       * вложенный пункт
       * вложенный пункт
3. Снова первый уровень
***
```
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

Функция `exit()`

``Тут написан обычный символ апострофа (`).``

``Тут написан обычный символ ковычка (').``

``Тут написан обычный символ звездочка (*).``

Один апостроф внутри строчного кода: `` ` ``
Ограниченная апострофами строка внутри строчного кода: `` `foo` ``

Одина звездочка внутри строчного кода: `` * ``
Ограниченная звездочками строка внутри строчного кода: `` *foo* ``

> **Note**
> Это заметка.

> **Warning**
> Это предупреждение.
```
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

Функция `exit()` 

``Тут написан обычный символ апострофа (`).``

``Тут написан обычный символ ковычка (').``

``Тут написан обычный символ звездочка (*).``

Один апостроф внутри строчного кода: `` ` ``
Ограниченная апострофами строка внутри строчного кода: `` `foo` ``

Одина звездочка внутри строчного кода: `` * ``
Ограниченная звездочками строка внутри строчного кода: `` *foo* ``

> **Note**
> This is a note

> **Warning**
> This is a warning
***
```
      <?
      phpinfo();
      $s = "Hello, World!\n";
      print $s;
```
***
```
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


| Заголовок 1 | Заголовок 2 | Заголовок 3 |
| --- | --- | --- |
| ячейка 11 | ячейка 12 | ячейка 13 |
| ячейка 21 | ячейка 22 | ячейка 23 |
 
```
***Результат:***

Table Header  | Second Header
------------- | -------------
Table Cell    | Cell 2
Cell 3        | Cell 4

Заголовок 1	| Заголовок 2
----------- | ------------
Ячейка 1	   | Ячейка 2
Ячейка 3	   | Ячейка 4

| Заголовок 1 | Заголовок 2 | Заголовок 3 |
| --- | --- | --- |
| ячейка 11 | ячейка 12 | ячейка 13 |
| ячейка 21 | ячейка 22 | ячейка 23 |
***
```
Код: 
```{r}
paste("Hello", "World!")
```

***Результат:***

```{r}
paste("Hello", "World!")
```
***
```
Код:
# Разделение слайдов 
Pandoc будет начинать новый слайд с каждого заголовка первого уровня.
## Заголовок 1
… а также каждый заголовок второго уровня
***
Вы можете начать новый слайд с горизонтальной линейки `***`, если не хотите.
заголовок.
## Заголовок 2
>- Используйте этот формат
>- чтобы появился Заголовок 3
>- по одному (постепенно)
```
***Результат:***

# Разделение слайдов 
Pandoc будет начинать новый слайд с каждого заголовка первого уровня.
## Заголовок 1
… а также каждый заголовок второго уровня
***
Вы можете начать новый слайд с горизонтальной линейки `***`.

## Заголовок 2
>- Пункт 1
>- Пункт 2
>- Пункт 3
***
Текст, потом сноска`*` и вторая`**`.

Текст, потом цифровая сноска`*1` и вторая`*2`.
***
[ссылка](Гиперссылка (на rmarkdown.rstudio.com) (http://rmarkdown.rstudio.com) 

**[Полужирная ссылка на rmarkdown.rstudio.com]([http://example.com](http://rmarkdown.rstudio.com))**	

[![Лого](http://img.yandex.net/i/logo95x37x8.png)](https://yandex.ru)

[Почта yandex](mailto:yandex@yandex.ru)
[Почта mail](mailto:yandex@mail.ru)
[Почта rambler](mailto:yandex@rambler.ru)
***
![image](https://github.com/tvgVita69/Markdown/assets/98489171/c9a77fb4-540a-4610-bff8-01ba415b4ae8)

![image](https://github.com/tvgVita69/Markdown/assets/98489171/cf11aaea-276e-4dbd-9307-8339324e8963)













