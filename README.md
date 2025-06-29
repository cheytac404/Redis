# Домашнее задание к занятию "`Кеширование Redis/memcached`" - `Губанов Сергей`

### Задание 1. Кеширование 

Приведите примеры проблем, которые может решить кеширование. 

*Приведите ответ в свободной форме.*
1. Медленный доступ к данным
Решение: Кэш хранит часто запрашиваемые данные в памяти (RAM), обеспечивая быстрый доступ

2. Частые повторяющиеся запросы

Решение: Ответ на первый запрос кэшируется и используется повторно

3. Высокая нагрузка на сервер
Решение: Кэш снижает число запросов к тяжёлым компонентам (БД, фйловая система)

4. Медленная генерация HTML или API-ответов
Решение: Кэш позволяет сохранить уже созданные результаты

5. Задержки в сетевых вызовах
Решение: Кэш сохраняет данные снаружи, чтобы не обращаться к ним при каждом запросе




---

### Задание 2. Memcached

Установите и запустите memcached.

*Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.*
![alt text](![alt text](https://github.com/cheytac404/Redis/blob/main/sys.png))
---

### Задание 3. Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5. 

*Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.*
![alt text](![alt text](https://github.com/cheytac404/Redis/blob/main/mem.png))
---

### Задание 4. Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями. 

*Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.*
![alt text](https://github.com/cheytac404/Redis/blob/main/red.png)
---