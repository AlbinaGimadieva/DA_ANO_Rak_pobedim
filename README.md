# Проект по анализу данных и построению дашборда для АНО "Рак победим"

- Проведена предобработка данных о подопечных фонда: выделены город проживания, локализация и стадия заболевания, этап лечения и др. показатели подопечных АНО "Рак победим".
- Сделаны выводы по полученным данным и представлены рекомендации по дальнейшему сбору данных.
- Построен дашборд в DataLens по предобработанным данным о подопечных (Вкладка 1) и донорах (Вкладка 2) фонда.

**Дано:** в рамках проекта работаем с реальными сырыми данными от АНО [Рак победим](https://rak-pobedim.com/). Нужно будет провести предобработку данных и дать рекомендации по сбору информации. Проанализировать информацию о подопечных и донорах, построить дашборд, на основании которого сотрудник фонда сформирует отчетность за 2023 год.

**Данные:** в нашем распоряжении два датасета:
* данные о [подопечных](https://docs.google.com/spreadsheets/d/1_S4m-SK2juop8FkCMVCFIAJcUi2zFBj25VVOsUAaOT4/edit#gid=1721685457)
* данные о [донорах](https://docs.google.com/spreadsheets/d/1OfWqpwyiTnM9fTbrgxIkK_xXJL5803p-Y-FmECmOspU/edit#gid=42853625) 

Для выполнения предобработки в части единообразия написания в полях 'Город', 'Сфера деятельности', 'Диагноз', 'Этап', 'Помощь' рекомендуется использовать [справочник](https://docs.google.com/spreadsheets/d/1ODxYYhWq1OMntpGo9gD8jYKJQV6lGfw0fAtkyhCr1Q0/edit#gid=822464959). 

**Цель:** построение двухстраничного дашборда: на первой вкладке которого будут отражены метрики по подопечным фонда, на второй - метрики по донорам фонда. Дашборд будет использован для формирования отчёта фонда следующего [вида](https://disk.yandex.ru/i/pJMgzISgQtTQwA). 

**Стек проекта:** Python, Pandas, Matplotlib, Seaborn, Re, FuzzyWuzzy, Yandex Datalens.
