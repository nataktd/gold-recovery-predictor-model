# gold-recovery-predictor-model
# Описание проекта
В нашем распоряжении сырые данные (их просто выгрузили из хранилища) с параметрами добычи и очистки золотосодержащей руды.
Необходимо подготовить прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.

# Цель:
Нам нужно смоделировать процесс восстановления золота из золотосодержащей руды.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды.
Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

# План работы

1  Изучение данных и подготовка к работе

1.1  Переменные константы, функции и формулы для расчетов

1.2  Общая информация о датасетах и данных

1.3  Проверка правильности расчета эффективность обогащения.

1.4  Предобработка данных

2  Анализ данных

2.1  Анализ изменения концентрация металлов (Au, Ag, Pb) на различных этапах очистки

2.2  Анализ распределения размеров гранул исходного сырья на обучающей и тестовой выборках.

2.3  Суммарная концентрация металлов на разных стадиях: в сырье, в черновом концентрате, в концентрате после первой очистки и в финальном концентрате.

3  Построение модели

3.1  Подготовка данных

3.2  Метрики

3.3  Обучение моделей и оценка их качества кросс-валидацией

3.4  Проверка модели на тестовой выборке

4  Итоги и выводы по проекту

#  Итоги
Итогом обучения является признание лучшей модели по составленным метрикам - Случайный лес очищенная от выбросов. Итоговое sMAPE этой модели -7.552.
Можно сделать вывод: ошибка модели Случайный Лес на тестовой выборке приемлемая (7.362), так как она меньше чем у константной модели (8.27).
