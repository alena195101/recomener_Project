# Проект по расчету вероятности покупки рекомендованного товара(Ozon)

В качестве учебной практики выполнялся проект в компании Ozon. В команде из двух человек. 
Участники:
 <li>   Тимофеева Алена
 <li>   Парфенов Павел

# Задача
Улучшение  существующей рекомендательной  системы с помощью подсчета вероятности покупки товаров, предложенных системой.

Необходимо разработать дополнительные признаки, отражающие зависимости и схожеть рекоменодованного товара с просмотренным для дальнейшего предсказания вероятности покупки. А также выбрать модель и метрики для оценки качества, сравнение результатов с baseline.

# Что было сделано 
Всего было разработано 22 признака. Каждый участник проекта реализовал 11 из них. Все разработанные признаки можно поделить на 4 основные группы:
<li>   Признаки популярности и новизны товаров;
<li>   Коллаборативная фильтрация;  
<li>   Признаки, основанные на пользовательских сессиях;
<li>   Схожесть по текстовому описанию.
 
### Машинное обучение
Для предсказания вероятности использовался классификатор от CatBoost, с подобранными товарами

# Вывод
В ходе работы были понят подход к решению задачи и выполнены все поставленные задачи. При сравнении результатов получилось, что выбранный алгоритм с новыми признаками работает лучше чем то, что ранее использовалась в продакшене. 

Обзор проделанной работы можно увидеть в презинтации. Там наглядно показано что и для чего было сделано.

