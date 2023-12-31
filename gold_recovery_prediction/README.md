# Прогноз восстановления золота из руды

Компании необходимо оптимизировать процесс очистки золота для эффективной работы промышленных предприятий.

## Данные

Исходные данные состоят из трёх датасетов:
- полный и обучающий, содержащие информацию о каждом этапе очистки, параметрах сырья, продукта, расчётных характеристиках;
- тестовый, содержащий информацию только об этапах очистки и параметрах сырья.

## Цель

Обучить две ML-модели, предсказывающих коэффициент восстановления золота чернового и финального концентратов.

## Задачи

- изучить исходные данные, провести предобработку данных и их подготовку к обучению;
- проанализировать концентрацию металлов на разных этапах очистки, сравнить распределения гранул сырья на обучающей и тестовой выборках;
- создать функцию, рассчитывающую метрику качества для на каждом этапе очистки руды, а также функцию, вычисляющую финальную метрику качества.

## Используемые библиотеки

*sklearn, pandas, matplotlib*