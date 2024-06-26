# Выполнила Бондарева Алина Кирилловна
## Описание
Этот проект посвящен анализу биоинформатического датасета, сосредоточенного на изучении пространственной транскриптомики клеток, вовлеченных в плоскоклеточный рак. Мы изучаем клеточные микроокружения, объединяя клетки по типам взаимодействия, с целью выявить различия в организации микроокружения у пациентов различных возрастных групп.

## Данные
Датасет `community_dataset.zip` включает следующие ключевые параметры для анализа:

* `distance_to_vasculature`: Расстояние до ближайших сосудов.
* `distance_to_largest_cell`: Расстояние до ближайшей крупной клетки.
* `immune_marker_1` и `immune_marker_2`: Экспрессия иммунных маркеров.
* `cell_type`: Тип клетки.
* `area_of_cell`: Размер клетки.
* `cell_interaction`: Вид взаимодействия клеток, формирующих микроокружение.
* `age_group`: Возрастная группа пациента.
* `case_id`: Уникальный идентификатор пациента.

## Задачи
1. Анализ статистической значимости между типом клетки и различными физиологическими и морфологическими параметрами.
2. Определение количественного превалирования типов клеток в различных клеточных микроокружениях.
3. Исследование разницы в долях микроокружений между возрастными группами.
3. Проверка гипотез о близости иммунных клеток к сосудам и крупным клеткам с использованием методов бутстрапа и пермутационных тестов.
