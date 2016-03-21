---
layout: default
title: Метод Groups.Edit
permalink: groups/edit/
comments: true
---
# Метод Groups.Edit
Редактирует сообщество.

Страница документации ВКонтакте [groups.edit](https://vk.com/dev/groups.edit).

## Синтаксис
``` csharp
public bool Edit(long groupId, GroupInfo groupInfo)
```

## Параметры
+ **groupId** - Идентификатор сообщества. положительное число, обязательный параметр

Класс **`GroupInfo`** содержит следующие свойства:

+ **Title** - Название сообщества. строка
+ **Description** - Описание сообщества. строка
+ **ScreenName** - Короткое имя сообщества. строка
+ **Access** - Тип группы. Возможные значения: 
0 — открытая; 
1 — закрытая; 
2 — частная. 
положительное число
+ **Website** - Адрес сайта, который будет указан в информации о группе. строка
+ **Subject** - Тематика сообщества. Возможные значения: 
1 — авто/мото; 
2 — активный отдых; 
3 — бизнес; 
4 — домашние животные; 
5 — здоровье; 
6 — знакомство и общение; 
7 — игры; 
8 — ИТ (компьютеры и софт); 
9 — кино; 
10 — красота и мода; 
11 — кулинария; 
12 — культура и искусство; 
13 — литература; 
14 — мобильная связь и интернет; 
15 — музыка; 
16 — наука и техника; 
17 — недвижимость; 
18 — новости и СМИ; 
19 — безопасность; 
20 — образование; 
21 — обустройство и ремонт; 
22 — политика; 
23 — продукты питания; 
24 — промышленность; 
25 — путешествия; 
26 — работа; 
27 — развлечения; 
28 — религия; 
29 — дом и семья; 
30 — спорт; 
31 — страхование; 
32 — телевидение; 
33 — товары и услуги; 
34 — увлечения и хобби; 
35 — финансы; 
36 — фото; 
37 — эзотерика; 
38 — электроника и бытовая техника; 
39 — эротика; 
40 — юмор; 
41 — общество, гуманитарные науки; 
42 — дизайн и графика. 
строка
+ **Email** - Электронный адрес сообщества. строка
+ **Phone** - Номер телефона сообщества. строка
+ **Rss** - Адрес rss для импорта новостей (доступен только группам, получившим соответствующее разрешение, обратитесь в http://vk.com/support для получения разрешения). строка
+ **EventStartDate** - Дата начала события. положительное число
+ **EventFinishDate** - Дата окончания события. положительное число
+ **EventGroupId** - Идентификатор группы, которая является организатором события (только для событий). положительное число
+ **PublicCategory** - Категория публичной страницы. положительное число
+ **PublicSubcategory** - Подкатегория публичной станицы. положительное число
+ **PublicDate** - Дата основания компании, организации, которой посвящена публичная страница в виде строки формата "dd.mm.YYYY". строка
+ **Wall** - Стена: 
0 – выключена 
1 – открытая 
2 – ограниченная (доступно только для групп и событий) 
3 – закрытая (доступно только для групп и событий) положительное число
+ **Topics** - Обсуждения: 
0 – выключены 
1 – открытые 
2 – ограниченные (доступно только для групп и событий) положительное число
+ **Photos** - Фотографии: 
0 – выключены 
1 – открытые 
2 – ограниченные (доступно только для групп и событий) положительное число
+ **Video** - Видеозаписи: 
0 – выключены 
1 – открытые 
2 – ограниченные (доступно только для групп и событий) положительное число
+ **Audio** - Аудиозаписи: 
0 – выключены 
1 – открытые 
2 – ограниченные (доступно только для групп и событий) положительное число
+ **Links** - Ссылки: (доступно только для публичных страниц) 
0 – выключены 
1 – включены флаг, может принимать значения 1 или 0
+ **Events** - События: (доступно только для публичных страниц) 
0 – выключены 
1 – включены флаг, может принимать значения 1 или 0
+ **Places** - Места: (доступно только для публичных страниц) 
0 – выключены 
1 – включены флаг, может принимать значения 1 или 0
+ **Contacts** - Контакты: (доступно только для публичных страниц) 
0 – выключены 
1 – включены флаг, может принимать значения 1 или 0
+ **Docs** - Документы: 
0 – выключены 
1 – открытые 
2 – ограниченные (доступно только для групп и событий) положительное число
+ **Wiki** - Вики материалы: 
0 – выключены 
1 – открытые 
2 – ограниченные (доступно только для групп и событий) положительное число

## Результат
В случае успеха возвращает **true**.

## Пример
``` csharp
// Пример кода
```

## Версия Вконтакте API v.5.44
Дата обновления: 19.01.2016 16:15:07