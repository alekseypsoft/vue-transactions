# Решение задачи с транзакциями

##  Сайт нужно открыть по адресу
``http://localhost``

## Для сайта поставлен sail. Если использовать sail нужно делать ``sail up``



# Условие задачи
Дана база данных финансовых транзакций и прототип страницы для отображения данных по пользователям. https://codesandbox.io/p/devbox/php-mysql-transactions-task-gc7mhw?file=/index.php

Структура базы данных:

Таблица users содержит данные о пользователях. Таблица user_accounts содержит список счетов пользователей где у каждого пользователя может быть несколько счетов. Таблица transactions содержит информацию о перемещении средств с одного счета на другой. Транзакции могут быть между счетами разных пользователей и между разными счетами одного пользователя.

Задание:

Средствами PHP реализовать отображение месячного баланса выбранного пользователя за каждый календарный месяц. Под месячным балансом понимается сумма всех входящих транзакций по всем счетам пользователя минус сумма всех исходящих транзакций по всем счетам пользователя за календарный месяц. Баланс может быть отрицательным.

Выбор пользователя должен осуществляться из выпадающего списка. В выпадающем списке должны отображаться только те пользователи у которых имеются транзакции. Результат должен отображаться в виде таблицы, где первой колонкой отображается месяц, а второй - месячный баланс.

Требования:

1. Запросы к backend должны отправляются без перезагрузки страницы; 2. Код должен быть написан без использования фреймворков; 3. Код должен быть написан понятно и аккуратно, с соблюдением табуляции и прочих элементов написания, без лишних элементов и функций, не имеющих отношения к функционалу тестового задания, снабжен понятными комментариями.

Результат должен быть предоставлен в виде ссылки на код в песочнице https://codesandbox.io. Структура и данные базы данных изменению не подлежат.

Обратите внимание:
Цель вышеуказанного тестового задания заключается исключительно в оценке Ваших знаний и навыков. Участие полностью добровольное, некоммерческое и не оплачиваемое.





