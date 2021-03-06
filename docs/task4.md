# Создание страницы "Ресурсы студенческого сообщества ЮГУ"

В данном задании мы будем создавать таблицу со списком ресурсов студенческого сообщества ЮГУ

## Как создать таблицу в Makrdown
Для создание таблицы воспользуйтесь следующим синтаксисом

```md
|Название столбца|Второй столбец|
|----------------|--------------|
|строка 1        |     строка 2 |
|очень большая строка 3|очень большая строка 4|
|с1|c2|
```

Как это будет выглядеть

|Название столбца|Второй столбец|
|----------------|--------------|
|строка 1        |     строка 2 |
|очень большая строка 3|очень большая строка 4|
|с1|c2|

## Синтаксис описания таблиц

- `|Название стобца|` - Это описание заголовка таблицы. Обратите внимание, что заголовок заключен в символы `|`.  
Символ `|` нужен для разделения столбцов таблицы, а также служит для начала и конца строки таблицы
- `|----------------|` или минимальная запись `|-|` - служит для разделения заголовков таблицы и ее строк.  
  В минимальном варианте таблица должная содержать хотя бы один заголовок и хотя бы один разделитель заголовком и строк
- `|строка 1        |` - это синтаксис записи строк таблиц. Между символами `|` находится содержимое строки таблицы
  
## Создание таблицы со ссылками и картинками

В качестве содержимого для строк таблиц можно использовать не только текст, а все что может предоставить вам Markdown.

Давайте создадим таблицу:  

```markdown
|Название ресурса|Ссылка|Внешний вид ресурса|
|----------------|------|-------------------|
|ЮГУ: Югорский государственный университет (группа в ВК)|[https://vk.com/ugrasu](https://vk.com/ugrasu)|![:](img/table/ugu_vk.png)
|Студенческий медиацентр ЮГУ|[https://vk.com/stud_smi_ugrasu](https://vk.com/stud_smi_ugrasu)|![:](img/table/ice_vk.png)
|YouTube канал ЮГУ|[Канал](https://www.youtube.com/channel/UCx43iULpSe_8zHtW2htXTtw/featured)|![:](img/table/youtube.png)
```

Данный код будет преобразован в таблицу ниже:

|Название ресурса|Ссылка|Внешний вид ресурса|
|----------------|------|-------------------|
|ЮГУ: Югорский государственный университет (группа в ВК)|[https://vk.com/ugrasu](https://vk.com/ugrasu)|![:](img/table/ugu_vk.png)
|Студенческий медиацентр ЮГУ|[https://vk.com/stud_smi_ugrasu](https://vk.com/stud_smi_ugrasu)|![:](img/table/ice_vk.png)
|YouTube канал ЮГУ|[Канал](https://www.youtube.com/channel/UCx43iULpSe_8zHtW2htXTtw/featured)|![:](img/table/youtube.png)



## Описание задания
Создать таблицу со списком ресурсов студенческого сообщества ЮГУ