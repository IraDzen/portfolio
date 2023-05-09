## Портфолио

[Резюме](https://iradzen.github.io/)

### О себе

После 5 лет руководства сетью аптек я решила изучить новую перспективную профессию QA инженера. Закончила курсы SkyPro и прошла обучение и практику под руководством ментора. Продолжаю самостоятельное обучение, практикуюсь в написании тест кейсов и работе с различными инструментами. У меня хорошие аналитические способности, отличные софт скиллы и есть опыт руководства командой. Ищу работу или стажировку.

### Примеры тест-кейсов

### Пример тестирование API

API для доступа к информации о запусках ракет SpaceX

[Коллекция Postman](https://documenter.getpostman.com/view/27289013/2s93eYUBqg)  
[Документация API](https://docs.spacexdata.com/)

Также разбиралась в документации и делала различные запросы к нескольким API из списка [бесплатных общедоступых API](https://rapidapi.com/collection/list-of-free-apis).

### Умения, навыки и инструменты

Ручное тестирование  
Функциональное тестирование  
Регрессионное тестирование  
#### Автоматизированное тестирование 
Умею записывать сценарии автоматизированных тестов с использованием сервиса [bugbug.io](https://bugbug.io)  
#### Тестирование API. REST API. HTTP.
Структура HTTP запроса. Заголовки. Методы GET, POST, PUT, DELETE.  

#### Теория тестирования. Виды и методы тестирования.  
Работа с требованиями  
Составление, проверка полноты и непротиворечивости, уточнение требований.
Работа с тестовой документацией  
Умею добавлять тест кейсы и прогонять их в TestRail.
Жизненный цикл ПО. Scrum. KanBan.
Jira. Управление проектами и задачами.
Имею представление об устройстве сети (IP, DNS, HTTP) и клиент-серверной архитектуре
Slack
Trello
UX/Дизайн
Имею представление об основах UX, веб дизайна и типографики. Умею делать простые макеты в Figma.
Copywriting
Умею составлять грамотные рекламные и маркетинговые тексты
Имею опыт работы с маркетингом и продажами. Привлечение клиентов.

Системы контроля версий. Git.
Клонирование репозитория. Ветки. Commit.

Окружение. Общее представление о CI и его типичных этапах.

БД, SQL
Умею писать запросы средней сложности с использованием операторов **WHERE, ORDER BY, JOIN, GROUP BY** и других. Практиковалась с БД postgres. Для работы с БД использовала программу DBeaver.
Примеры:  

Вывести топ 10 департаменов с количеством населенных пунктов > 100  
```sql
SELECT d.name, COUNT(t.name) from departments d
JOIN towns t ON d.code = t.department
GROUP BY d.name
HAVING COUNT(t.name) > 100
ORDER BY COUNT(t.name) DESC
LIMIT 10
```

Вывести название клиента и общу выручку. Отсортировать по убыванию выручки.
```sql
SELECT c.CustomerName , SUM(p.Price) FROM OrderDetails od
JOIN Orders o ON od.OrderID = o.OrderID
JOIN Customers c ON c.CustomerID = o.CustomerID
JOIN Products p ON p.ProductID = od.ProductID
GROUP BY c.CustomerName
ORDER BY SUM(p.Price) DESC
```

Вывести все города и населенные пункты Франции с названием департамента и региона в алфавитном порядке по возрастанию  
```sql
SELECT t.name ,d.name ,r.name from towns t
JOIN departments d ON t.department = d.code
JOIN regions r ON r.code = d.region
ORDER BY t.name ASC
```

### Обучающие материалы и книги

* Роман Савин. Тестирование Дот Ком
* [Курс "Инженер по тестированию" SkyPro](https://sky.pro/courses/programming/qa-engineer)
* [QA Bible](https://vladislaveremeev.gitbook.io/qa_bible/)
* [Курс лекций "Тестирование ПО. Профессиональный курс подготовки QA"](https://www.youtube.com/watch?v=MmbVEwYnWTs&list=PLZqgWWF4O-zg03RGSZ2GpHLE3BmO8bjKo)
* Стив Круг. Не заставляйте меня думать.
* Расс Унгер. Кэролайн Чендлер. UX дизайн.
