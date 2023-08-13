# cl-and-git
Проектная работа по спринту "Командная строка и Git"
### Описание проекта
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Постройте модель с предельно большим значением *F1*-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте *F1*-меру на тестовой выборке самостоятельно.

В ходе работы над проектом, данные были предобработаны, кодированы, масштабированы.
После этого начался подбор моделей. В результате измерения метрик разных моделей, а именно решающего дерева, случайного леса и логистической регрессии, выбор пал на случайный лес.
