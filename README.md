Проект по дисциплине "Введение в анализ данных"

Выполнили:
Киселев Глеб
Дорохович Вероника
Киберева Алла
Захарчук Александр
Нестеров Анатолий


В данной работы мы используем линейные модели для решения задачи регрессии, а именно одномерную линейную регрессию на датасете boston. Этот датасет, набор данных конца 70-х годов прошлого века, используется нами для для предсказания цен на недвижимости в Бостоне.
Для реализации использовался фреймворк PyTorch, предназначенный для работы с нейронными сетями. 

В дополнение, мы усложнили модель, добавивляя слои нейронов и сравнили с исходной моделью. Так, для двухслойной модели MSE уменьшилось, но не намного, то есть точность двухслойной модели слабо отличается от точности однослойной в данном случае. Добавим ещё одного слоя активации и линейного слоя так же не улучшило MSE по сравнению с предыдущим результатом. Это позволяет сделать вывод, что для реализации данного примера достаточно однослойной модели, то есть просто линейной регрессии.


