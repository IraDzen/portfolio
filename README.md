## Портфолио

[Резюме](https://iradzen.github.io/)

### О себе

После 5 лет руководства сетью аптек я решила изучить новую перспективную профессию QA инженера. Закончила курсы SkyPro и прошла обучение и практику под руководством ментора. Продолжаю самостоятельное обучение, практикуюсь в написании тест кейсов и работе с различными инструментами. У меня хорошие аналитические способности, отличные софт скиллы и есть опыт руководства командой. Ищу работу или стажировку.

### Примеры тест-кейсов

### Пример тестирование API

API для доступа к информация по запускам ракет SpaceX

[Коллекция Postman](https://documenter.getpostman.com/view/27289013/2s93eYUBqg)  
[Документация API](https://docs.spacexdata.com/)

### Умения, навыки и инструменты

Ручное тестирование  
Функциональное тестирование  
Регрессионное тестирование  
Теория тестирования  
Работа с требованиями  
Работа с тестовой документацией  

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

* [Курс "Инженер по тестированию" SkyPro](https://sky.pro/courses/programming/qa-engineer)
* Роман Савин. Тестирование Дот Ком
* [QA Bible](https://vladislaveremeev.gitbook.io/qa_bible/)
* [Курс лекций "Тестирование ПО. Профессиональный курс подготовки QA"](https://www.youtube.com/watch?v=MmbVEwYnWTs&list=PLZqgWWF4O-zg03RGSZ2GpHLE3BmO8bjKo)
* Стив Круг. Не заставляйте меня думать.
* Расс Унгер. Кэролайн Чендлер. UX дизайн.
