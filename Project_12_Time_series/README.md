## Проект 12. Прогнозирование заказов такси

Компания «Чётенькое такси» собрала исторические данные о заказах такси в аэропортах. Чтобы привлекать больше водителей в период пиковой нагрузки, нужно спрогнозировать количество заказов такси на следующий час. 

### Цель проекта

Построить модель машинного обучения, которая поможет предсказать количество заказов такси на следующий час.

### Условия задачи

- Сделать тестовую выборку размером 10% от исходных данных.
- Значение метрики RMSE на тестовой выборке должно быть не больше 48.

### Ход проекта 

1. Загрузка данных и ресемплирование их по одному часу.
2. Анализ данных.
3. Обучение разных моделей с различными гиперпараметрами. 
4. Проверка данных на тестовой выборке и выводы.

### Навыки и инструменты

- Python
- Pandas
- NumPy
- Matplotlib
- Sklearn
- CatBoost
- LightGBM
- Statsmodels


### Общий вывод

Лучшая модель градиентного бустинга `LGBMRegressor` на тестовой выборке показала значение метрики *RMSE* = 41.3. Это значение не превышает 48, что соответствует изначальному требованию в условии задачи проекта.

