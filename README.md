## Portfolio

[Резюме](https://iradzen.github.io/)

### О себе

### Примеры тест-кейсов

### Пример тестирование API
[Коллекция Postman](https://documenter.getpostman.com/view/27289013/2s93eYUBqg)

[Документация](https://docs.spacexdata.com/)

### Умения, навыки и инструменты

Ручное тестирование
Функциональное тестирование
Регрессионное тестирование
Теория тестирования
Работа с требованиями
Работа с тестовой документацией

БД, SQL
Умею писать запросы средней сложности с использованием операторов **WHERE, ORDER BY, JOIN, GROUP BY** и других. Примеры:

Вывести топ 10 департаменов с количеством населенных пунктов > 100
```
select d."name" , count(t."name") from departments d
join towns t on d.code = t.department
group by d."name"
having count(t."name") > 100
order by count(t."name") desc
limit 10
```

Вывести клиентов по убыванию выручки
```
SELECT c.CustomerName , SUM(p.Price) FROM OrderDetails od
JOIN Orders o ON od.OrderID = o.OrderID
JOIN Customers c ON c.CustomerID = o.CustomerID
JOIN Products p ON p.ProductID = od.ProductID
GROUP BY c.CustomerName
ORDER BY SUM(p.Price) DESC
```

### Обучающие материалы и книги

* Роман Савин. Тестирование Дот Ком
* [Курс лекций "Тестирование ПО. Профессиональный курс подготовки QA"](https://www.youtube.com/watch?v=MmbVEwYnWTs&list=PLZqgWWF4O-zg03RGSZ2GpHLE3BmO8bjKo)
