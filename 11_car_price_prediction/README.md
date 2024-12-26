Задача:
Построить модель для определения стоимости автомобиля на основе предоставленных данных. Заказчику важны: • качество предсказания; • скорость предсказания; • время обучения.

Итог: 
Протестирваны модели  CatBoost, LightGBM, RandomForestRegressor, SGDRegressor		
- в качестве предсказания CatBoost показала себя лучшим образом  с лидирующей метрикой RMSE.
- по времени обучения лидирует LightGBM
- по скорости предсказания лучшей оказалась SGDRegressor 
Рекомендуемой заказчику моделью признаётся CatBoost: RMSE 1590.41, r2_score 0.88.


Stack: Python, Pandas, Scikit-learn, CatBoost,LightGBM, RandomForestRegressor, RandomizedSearchCV, numpy, matplotlib, 

KeyWords: градиентный бустинг
