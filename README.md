# Данный репозиторий хранит практические задания к курсу "Базы данных и SQL (семинары)".

## Первое практическое задание. Файл "learn_sql_hw_1.txt".

1. Создайте таблицу с мобильными телефонами, используя графический интерфейс. Заполните БД данными (поля и наполнение см. в презентации)

2. Выведите название, производителя и цену для товаров, количество которых превышает 2

3. Выведите весь ассортимент товаров марки “Samsung”

4. (по желанию) С помощью регулярных выражений найти:
    * Товары, в которых есть упоминание "Iphone"
    * Товары, в которых есть упоминание"Samsung"
    * Товары, в которых есть ЦИФРЫ
    * Товары, в которых есть ЦИФРА "8"

## Второе практическое задание. Файл "learn_sql_hw_2.txt".

1. Используя операторы языка SQL, создайте табличку “sales”. Заполните ее данными.

2. Для данных таблицы “sales” укажите тип заказа в зависимости от кол-ва : меньше 100 - Маленький заказ; от 100 до 300 - Средний заказ; больше 300 - Большой заказ.

3. Создайте таблицу “orders”, заполните ее значениями. Выберите все заказы. В зависимости от поля order_status выведите столбец full_order_status: OPEN – «Order is in open state» ; CLOSED - «Order is closed»; CANCELLED - «Order is cancelled»

4. Чем NULL отличается от 0?

*Данные для таблиц “sales” и “orders” размещены на слайде "домашнее задание" презентации "Семинар №2. Базы данных и SQL"*

## Третье практическое задание. Файл "learn_sql_hw_3.txt".

Работаем с таблицей staff (скрипт создания в материалах к уроку)

1. Отсортируйте данные по полю заработная плата (salary) в порядке: убывания; возрастания

2. Выведите 5 максимальных заработных плат (salary)

3. Посчитайте суммарную зарплату (salary) по каждой специальности (роst)

4. Найдите кол-во сотрудников с специальностью (post) «Рабочий» в возрасте от 24 до 49 лет включительно.

5. Найдите количество специальностей.

6. Выведите специальности, у которых средний возраст сотрудников меньше 30 лет.

## Четвертое практическое задание. Файл "learn_sql_hw_4.txt".

1. Подсчитать общее количество лайков, которые получили пользователи младше 12 лет.

2. Определить кто больше поставил лайков (всего): мужчины или женщины.

3. Вывести всех пользователей, которые не отправляли сообщения.

4. (по желанию)* Пусть задан некоторый пользователь. Из всех друзей этого пользователя найдите человека, который больше всех написал ему сообщений.

## Пятое практическое задание. Файл "learn_sql_hw_5.txt".

Для решения задач используйте базу данных lesson_4 (скрипт создания, прикреплен к 4 семинару).

1. Создайте представление, в которое попадет информация о пользователях (имя, фамилия, город и пол), которые не старше 20 лет.

2. Найдите кол-во, отправленных сообщений каждым пользователем и выведите ранжированный список пользователь, указав указать имя и фамилию пользователя, количество отправленных сообщений и место в рейтинге (первое место у пользователя с максимальным количеством сообщений) . (используйте DENSE_RANK).

3. Выберите все сообщения, отсортируйте сообщения по возрастанию даты отправления (created_at) и найдите разницу дат отправления между соседними сообщениями, получившегося списка. (используйте LEAD или LAG).