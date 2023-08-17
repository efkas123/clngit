### **Примечание для ревьюера v2**:
Спасибо за оперативное ревью! Извиняюсь, что затянул с ответом, и не изменил репозиторий по некоторым рекоммендациям. Просто сейчас проходит мастерская, и времени просто ноль. 
Внёс дополнительный коммит, теперь на английском, и изменил диапазон искомых гиперпараметров в цикле RFC.

### Примечание для ревьюера: пытался загрузить все файлы в изначальную ветку main, но получал ошибку error: src refspec main does not match any, поэтому по примеру из теории сделал push в master, и в таком варианте push сработал.
# cl-and-git
Проектная работа по спринту "Командная строка и Git"
### Описание проекта
Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 

Постройте модель с предельно большим значением *F1*-меры. Чтобы сдать проект успешно, нужно довести метрику до 0.59. Проверьте *F1*-меру на тестовой выборке самостоятельно.

В ходе работы над проектом, данные были предобработаны, кодированы, масштабированы.
После этого начался подбор моделей. В результате измерения метрик разных моделей, а именно решающего дерева, случайного леса и логистической регрессии, выбор пал на случайный лес.
