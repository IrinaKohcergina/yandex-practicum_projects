# book_reading_service
## SQL  
## Анализ базы данных сервиса для чтения книг по подписке
**Задача:** проанализировать базу данных крупного сервиса для чтения книг по подписке для формирования ценностного предложения для нового продукта.

База данных содержит информацию о книгах, издательствах, авторах, а также пользовательские обзоры книг.

**Библиотеки:** pandas, sqlalchemy (text, create_engine)

**Основные выводы:** 
- С помощью ***SQL*** запросов получены данные из всех таблиц базы данных,
- Вычислено количество книг, выпущенных после 01.01.2020 г.,
- Количество обзоров и средняя оценка каждой книги,
- Издательство, которое выпустило наибольшее число книг толще 50 страниц,
- Автор с самой высокой средней оценкой книг,
- Среднее количество обзоров от пользователей, которые поставили больше 48 оценок.
