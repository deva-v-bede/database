<h1 name="content" align="center"><a href=""><img src="https://github.com/user-attachments/assets/e080adec-6af7-4bd2-b232-d43cb37024ac" width="20" height="20"/></a> MSSQL</h1>

<p align="center">
  <a href="#-lab1"><img alt="lab1" src="https://img.shields.io/badge/Lab1-crimson"></a> 
  <a href="#-lab2"><img alt="lab2" src="https://img.shields.io/badge/Lab2-forestgreen"></a>
  <a href="#-lab3"><img alt="lab3" src="https://img.shields.io/badge/Lab3-darkorange"></a>
  <a href="#-lab4"><img alt="lab4" src="https://img.shields.io/badge/Lab4-steelblue"></a>
  <a href="#-lab5"><img alt="lab5" src="https://img.shields.io/badge/Lab5-tomato"></a>
  <a href="#-lab6"><img alt="lab6" src="https://img.shields.io/badge/Lab6-olive"></a> 
  <a href="#-lab7"><img alt="lab7" src="https://img.shields.io/badge/Lab7-chocolate"></a>
  <a href="#-lab8"><img alt="lab8" src="https://img.shields.io/badge/Lab8-rosybrown"></a>
  <a href="#-lab9"><img alt="lab9" src="https://img.shields.io/badge/Lab9-maroon"></a> 
</p>

<h3 align="center">
  <a href="#client"></a>
Вариант №9: Автоматизация супермаркета
</h3>

Информация о торговых точках, предназначенных для аренды: адрес, этаж, площадь, наличие кондиционера, стоимость аренды в месяц.
Клиенты: название, юр.адрес, банковские реквизиты, телефон, ФИО контактного лица.


Реализовать:
- Подбор варианта аренды для клиента, расчет оплаты с возможностью предоставления некоторых видов скидок;
- Заключение договора;
- Хранение информации о ежемесячных платежах, поступающих от арендаторов;
- Поиск клиентов-должников, не внесших своевременно ежемесячный платеж


# <img src="https://github.com/user-attachments/assets/e080adec-6af7-4bd2-b232-d43cb37024ac" width="20" height="20"/> Lab1
[Назад](#content)
<h3 align="left">
  <a href="#client"></a>
</h3>

Разработать ER-модель данной предметной области: выделить сущности, их атрибуты, связи между сущностями. 
Для каждой сущности указать ее имя, атрибут (или набор атрибутов), являющийся первичным ключом, список остальных атрибутов.
Для каждого атрибута указать его тип, ограничения, может ли он быть пустым, является ли он первичным ключом.

Для каждой связи между сущностями указать: 
- тип связи (1:1, 1:M, M:N)
- обязательность

ER-модель д.б. представлена в виде ER-диаграммы (картинка)
По имеющейся ER-модели создать реляционную модель данных и отобразить её в виде списка сущностей с их атрибутами и типами атрибутов,  для атрибутов указать, является ли он первичным или внешним ключом 

<h3 align="left">
  <a href="#client"></a>
1.1 ER-модель:

 
1.2 Реляционная модель:



# <img src="https://github.com/user-attachments/assets/e080adec-6af7-4bd2-b232-d43cb37024ac" width="20" height="20"/> Lab2
[Назад](#content) 
<h3 align="left"> 
  <a href="#client"></a>
</h3>

В соответствии с реляционной моделью данных, разработанной в Лаб.№1, создать реляционную БД на учебном сервере БД:
- создать таблицы, определить первичные ключи и иные ограничения
- определить связи между таблицами
- создать диаграмму
- заполнить все таблицы адекватной информацией (не меньше 10 записей в таблицах, наличие примеров для связей типа 1:M)

<h3>
  
2.1 [SQL-код создания таблиц]

2.2 Диаграмма БД "Supermarket":
  

  
2.3 Примеры заполненных таблиц:
</h3>
<h4>
  
  1) "Товар":
  


  2) "Покупатель":
     


  3) "Покупка":
     
 

# <img src="https://github.com/user-attachments/assets/e080adec-6af7-4bd2-b232-d43cb37024ac" width="20" height="20"/> Lab3
[Назад](#content)
<h3 align="left">
  <a href="#client"></a>
</h3>
