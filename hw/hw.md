## MongoDB ## 

Установила на свой ноутбук, то есть на локальный компьютер.

Вид данных: ID покупателя, пол, возраст и зарплата.

![](1.png)



### CRUD

#### Insert_many
Вставим двоих новых людей
![](2.png)

#### Query
Найдем людей определенного возраста и с определенной зарплатой
![](3.png)

Теперь ищем либо таких, либо таких, то есть используем $or
![](4.png)

![](5.png)

#### Update

При добавлении двух людей, я опечаталась: написала female  с маленькой буквы - исправим это

![](6.png)

#### Delete
Добавила человека со странным полом, удалим его, как бракованную запись.
![](7.png)

#### Index
Сначала не будм использовать индекс, оставим все как есть.
![](8.png)

Уменьшим количество просматриваемых файлов с помощью индексов
![](9.png)
![](11.png)
![](10.png)
Видим, что просмотрено было всего лишь 2 файла.
