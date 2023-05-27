<h1 align="center">Привет! Я - Анна👋</a>

<h2 align="center">Я QA Engineer</a>


<div id="badges">

  <a href="https://t.me/+79608774619">

    <img src="https://img.shields.io/badge/Telegram-inactive?logo=telegram&logoColor=white&style=for-the-badge" alt="Telegram Badge"/>
</a>
</div>

💻 Обучалась в онлайн-университете Skypro по специальности "Инженер по тестированию" <br>
📚 Продолжаю развитие в сфере тестирования

## Навыки и технологии
``Jira``,``qase.io``,``SQL``,`` Postman``,``Mockoon``, ``Swagger``, ``Trello``, ``Confluence``, <br>
``SoapUI``, ``Chrome DevTools``, ``PostgreSQL``, ``DBeaver``, ``Checkvist``, ``Sitechko``.

## Проекты

### 1️⃣ Тестирование веб-приложения для учителей от Skyeng <br>

#### Заказчик: Skyeng 📚 <br>
#### Сайт: http://skyeng.ru/ <br>
#### Основные требования: 
предоставить преподавателям возможность добавлять личные события во вкладке “Расписание”. Они служат напоминанием, что у преподавателя что-то запланировано на это время. <br>
#### Что нужно было сделать: <br>
1. Протестировать требования <br>
2. Написать тест-план <br>
3. Сделать декомпозицию вкладки расписание <br>
4. Написание тест-кейсов и чек-листов <br>
5. Проведение smoke тестирования <br>
6. Проведение функционального тестирования <br>
7. Проведение регрессионного тестирования <br>
8. Выполнение приемочного тестирования <br>
9. Тестирование API <br>

#### [Документация к проекту](https://docs.google.com/document/d/1KwkCh_gRAfiC7G064XySrrjeC8QjsXxQB1HDDupdY1Q/edit?usp=sharing)

#### Было проведено [тестирование требований](https://docs.google.com/document/d/16epjLObPLmSWFnM1wbYbG_3lDmCdzyGLICrPEM8CyhQ/edit?usp=sharing)


<details><summary>Декомпозиция вкладки расписание</summary><br>

![image](https://github.com/burovanya/portfolio-qa/blob/main/Miro.jpg)
</details>

<details><summary>Был написан тест-план:</summary><br>

Продукт: веб-приложение для учителей (личные события в расписании)
Заказчик: Skyeng
Сайт: http://skyeng.ru/ 

Основные требования: предоставить преподавателям возможность добавлять личные события во вкладке “Расписание”.
Преподаватель может использовать личные события для собственных встреч. Они служат напоминанием, что у преподавателя что-то запланировано на это время.

Все требования можно посмотреть по ссылке: https://docs.google.com/document/d/1KwkCh_gRAfiC7G064XySrrjeC8QjsXxQB1HDDupdY1Q/edit?usp=sharing 

Будут проведены следующие виды тестирования:

- Функциональное
- Smoke
- Приемочное
- Регрессионное
- Будет проведено тестирование API.

Функциональное тестирование:
- Таблица Excel с чек-листом и результатом Test run https://docs.google.com/spreadsheets/d/1RCOYeB4vpyZfAYGEAW-eszaTNe9v5MIr/edit#gid=3299894

Smoke тестирование:
- Test cases:https://docs.google.com/spreadsheets/d/1gESIFaH3XXg93uTXaUbJJ7cgrcwk4V3v5nTbKoxeNFE/edit?usp=sharing
- Test run:![image](https://github.com/burovanya/portfolio-qa/blob/main/smoke.jpg)

Регрессионное тестирование:
- Таблица Excel с чек-листом и результатом Test run https://docs.google.com/spreadsheets/d/14d1Q1jnyxSHXotMHR4JXSdVR5kg5HUqk/edit?usp=sharing&ouid=108703726781754003146&rtpof=true&sd=true

Тестирование API:
- Test cases: https://docs.google.com/spreadsheets/d/1QetCMho9SFI86aexS6et6UrAqV940NGNiSAATyUzWiI/edit?usp=sharing
- Postman-коллекция: https://github.com/burovanya/portfolio-qa/blob/main/%D0%9A%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F%202.postman_collection.json
- Test run Postman: https://github.com/burovanya/portfolio-qa/blob/main/%D0%9A%D1%83%D1%80%D1%81%D0%BE%D0%B2%D0%B0%D1%8F%202.postman_test_run.json

Расписание тестовых активностей
| Виды тестирования | Дата тестирования|
| ----------- | ----------- |
| Smoke тестирование | 4.01 - 4.01 |
| Функциональное тестирование | 4.01 - 4.01 |
| Регрессионное тестирование | 21.01-22.01 |
| Тестирование API | 25.03-26.03 |
  
</details>

#### Результаты тестирования
<details><summary>Баг-репорты:</summary><br>
  
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%201.png)
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%201.2.png)
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%202.png)
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%202.2.png)
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%203.png)
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%203.2.png)
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%204.png)
![image](https://github.com/burovanya/portfolio-qa/blob/main/Bug%204.2.png)
</details>

<details><summary>Отчет по Тестированию API</summary><br>

Было проведено 22 проверки через Postman.
15 позитивных тест-кейсов для проверки отображение личных событий в расписании, создания событий в будущем, прошлом и настоящем, редактирования событий, а также удаления.
7 негативных тест-кейсов для проверки создания, редактирования и удаления событий с невалидными данными.
Исходя из Test run багов обнаружено не было. Процент тест-кейсов со статусом Passed - 100%.

Через API удалось проверить несколько тест-кейсов, которые невозможно проверить через UI. Например, был отправлен запрос с пустыми полями, а также только с пустым названием.
Более того, через API удалось создать личное событие в прошлом, которое выходит за рамки текущей недели. Эта функция также не работает через UI.
Также проведена проверка негативных тест-кейсов с удалением удаленного события, временем выходящим за рамки 24 часов, буквами в полях “День” и “Время”, и ссылками во всех полях. Все вышеперечисленные проверки можно было совершить только через API.
</details>

<details><summary>Метрики</summary><br>

1. Коэффициент регрессии. Всего при проверки старого функционала был обнаружен 1 дефект. В новом функционале 3 дефекта. Коэффициент равен 0,25, что свидетельствует о том, что был внесен маленький процент ошибок в существующий функционал при реализации новых требований.

2. Успешное прохождение чек-листов: 96,5%

3. Успешное прохождение тест-кейсов: 66,7%

4. Покрытие требований тестированием: 100%.
</details>

<details><summary>Рекомендации</summary><br>

1. Основная рекомендация - исправить баги с серьезностью S1 и S2. Необходимо исправить баги, опираясь на серьезность и приоритет.

2. Для удобства использования можно добавить функцию уведомления о предстоящем личном событии.

3. Для удобства использования я думаю, необходимо предоставить преподавателям возможность переносить уроки более, чем на 14 дней вперед.
</details>
  
<details><summary>Выводы</summary><br>
  
В общей сложности 30 часов было потрачено на тестирование нового элемента календаря “Личные события“, разработку тестового плана, декомпозиции, тест-кейсов, чек-листов и создание отчета.
По результатам проверки я считаю, что продукт к релизу не готов, так как был обнаружен блокирующий баг, при проверке заявленной стекхолдерами функции добавления личных событий в прошлом, выходя за рамки текущей недели. Данный баг не был обнаружен при тестировании API. Также был обнаружен критический баг при проверке старой функциональности (перенос и отмена уроков). 
</details>



