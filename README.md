# БАЗОВЫЙ СИНТАКСИС MARKDOWN

В данной статье рассмотрим язык разметки Markdown. На примерах быстро и легко разберемся в его простом синтаксисе. 
В представленных ниже таблицах увидим как выглядит тест в зависимости от источника просмотра.

## ЗАГОЛОВКИ

Чтобы выбарать уровень заголовка, необходимо поставить символ (#) перед его началом, где колличество символов (#) будут соответствовать уровню. Один симовл (#) - это первый и (#####) - пятый уровень.

|Markdown|Готовый вариант|
|--------|---------------|
|# Заголовок 1 уровня|<span style='font-size: 34px;'>Заголовок 1 уровня</span>|
|## Заголовок 2 уровня|<span style='font-size: 28px;'>Заголовок 2 уровня</span>|
|### Заголовок 3 уровня|<span style='font-size: 24px;'>Заголовок 3 уровня</span>|
|#### Заголовок 4 уровня|<span style='font-size: 20px;'>Заголовок 4 уровня</span>|
|##### Заголовок 5 уровня|<span style='font-size: 18px;'>Заголовок 5 уровня</span>|

## ШРИФТЫ

С помощью Markdown возможно выделить шрифт, как и в обычном редакторе, **жирным** (как слово целиком, так и его ч**аст**ь), *курсивом*(также ***жирным курсивом***) или <u>подчеркиванием<u/>, а также ~~зачеркнуть текст~~. 

|Markdown|Готовый вариант|
|--------|---------------|
|  \*\*Выделяю жирным** | **Выделяю жирным** |
|  \_\_Выделяю жирным\_\_ | **Выделяю жирным** |
|Выделяю жирным ч\*\*ас\*\*ть слова|Выделяю жирным ч**ас**ть слова|
|\*Выделяю курсивом\*|*Выделяю курсивом*|
|\_Выделяю курсивом\_|_Выделяю курсивом_|
|\*\*\*Выделяю жирным курсивом\*\*\*|***Выделяю жирным курсивом***|
|\_\_\_Выделяю жирным курсивом\_\_\_|___Выделяю жирным курсивом___|
|$<u>Подчеркиваю текст/<u/>$|<u>Подчеркиваю текст<u/>|
|\~\~Зачеркиваю текст\~\~|~~Зачеркиваю текст~~|

> *P.S. Если необходимо отобразить специальные символы как обычный текст, нужно воспользоваться способом Экранирования. В большинстве случаях достаточно поставить обратный слэш (\)перед нужным символом.*

 ## ЦИТАТЫ
В Markdown возможно вставить цитату в тексте следующим образом. 
Необходимо перед началом цитаты посавить символ (>). Если цитата состоит из нескольких предложений, то условием продолжения текста цитаты служит проставление в начале каждой строки символа (>), то же касается пустой строки

#### Markdown
>\> Начало цитаты 
>\> 
>\> Конец цитаты
#### Готовый вариант
> Начало цитаты 
> 
> Конец цитаты
 
 Если вы хотите вставить в блок цитаты несколько параграфов, то необходимо поставить столько сиволов (>), сколько будет уровней цитирования. Также внутри блока цитат можно  использовать элементы оформления текста.

 #### Markdown
>\> Начало цитаты 
>\>\> Вложенная цитата второго уровня
>\>\>\> Вложенная цитата третьего уровня
#### Готовый вариант
> Начало цитаты 
>> Вложенная цитата второго уровня
>>> Вложенная цитата третьего уровня

## Списки
С помощью Markdown можно создвавть нумерованные и не нумерованные списки. В нумерованных списках достаточно начать с цифры 1 и редактор самостоятельно будет вести счёт по р=порядку с каждой строки. Что касается ненумерованных списков, то перед каждым пунктом можно поставить символы (-), (*), (+).

#### Markdown
Нумерованные списки:
1. Первый пункт
2. Второй пункт
3. Третий пункт
Ненумерованные списки:
\- Первый пункт
\- Второй пункт
\- Третий пункт

\* Первый пункт
\* Второй пункт
\* Третий пункт

\+ Первый пункт
\+ Второй пункт
\+ Третий пункт

#### Готовый вариант
Нумерованные списки:
1. Первый пункт
2. Второй пункт
3. Третий пункт

Ненумерованные списки:
- Первый пункт
- Второй пункт
- Третий пункт

* Первый пункт
* Второй пункт
* Третий пункт

+ Первый пункт
+ Второй пункт
+ Третий пункт
  
  ## ТАБЛИЦЫ
Используя Marcdown можно вставть таблицу в текст. Для создания таблицы нам понаобятся слдующие символы - (|), (-). Столбцы разделяются с помощью символа (|), шапка таблицы разедяется символами (-). 

#### Markdown
\|Заголовок\|Заголовок\|
\|---------\|\--------\|
\|Текст    \|Текст    \|  
\|Текст    \|Текст    \|

#### Готовый вариант
|Заголовок|Заголовок|
|---------|--------|
|Текст    |Текст    |  
|Текст    |Текст    |

