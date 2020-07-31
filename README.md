## Анализ оттока клиентов в фитнес-клубе 

 ***
Фитнес-клуб решил сократить отток клиентов, для этого были собраны  
данные о клиентах, а также его активности за последние два месяца.

Для того чтобы решить эту задачу выполнен анализ всех предоставленных  
параметров, а также их влияние на факт оттока клиента.

На основании этих данных определены параметры, по которым была обучена  
модель для прогноза оттока клиентов. Было выбрано две модели:  
 - Логистическая регрессия
 - Случайный лес

После оценки обоих моделей, определена более высокая точность прогноза для  
"Логистической регресии", для модели "Случайны лес" дополнительно проверена  
точность с изменением стандартных параметров.

Также в проекте проведена кластеризация пользователей для определения  
основных портретов клиентов. С помощью алгоритма **K-means** все клиенты  
были поделены на 5 групп. Для каждой группы был проведён повторный  
параметров и их влияние на факт оттока клиента.

В определённых алгоритмом группах можно выделить особенности для каждой группы:  
величину оттока, активность и другие параметры, влияющие на факт оттока клиента.
