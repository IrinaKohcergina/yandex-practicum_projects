# scooter_rental_service
Проект курса Яндекс Практикума "Аналитик данных". Сервис аренды самокатов.
## Статистический анализ данных на примере сервиса аренды самокатов

**Данные** популярного сервиса аренды самокатов GoFast о некоторых пользователях из нескольких городов, а также об их поездках и подписках. Чтобы совершать поездки по городу, пользователи сервиса GoFast пользуются мобильным приложением. Сервисом можно пользоваться без подписки или с подпиской Ultra.

**Задача** проанализировать данные и проверить гипотезы, которые могут помочь бизнесу вырасти.

Гипотезы:
1.	Тратят ли пользователи с подпиской больше времени на поездки? Если да, то пользователи с подпиской могут быть «выгоднее» для компании.
2.  Расстояние одной поездки в 3130 метров — оптимальное с точки зрения износа самоката. Можно ли сказать, что среднее расстояние, которое проезжают пользователи с подпиской за одну поездку, не превышает 3130 метров?
3.  Будет ли помесячная выручка от пользователей с подпиской по месяцам выше, чем выручка от пользователей без подписки.
4.  Произойдет ли значимое снижение количества обращений в техподдержку после обновления серверов, с которыми взаимодействует мобильное приложение. Выяснить, какой тест понадобился бы для проверки этой гипотезы?

Нужно выяснить, какое минимальное количество промокодов нужно разослать по акции с раздачей промокодов на один бесплатный месяц подписки, в рамках которой как минимум 100 существующих клиентов должны продлить эту подписку, чтобы вероятность не выполнить план была примерно 5%. Подбрать параметры распределения, описывающего эту ситуацию, построить график распределения и сформулируйте ответ на вопрос о количестве промокодов.

**Библиотеки:** pandas, numpy, scipy.stats, math, matplotlib.pyplot
