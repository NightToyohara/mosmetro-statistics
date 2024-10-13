# mosmetro-statistics
Небольшое исследование статистики по Московскому метрополитену с помощью Python для курса [«Python для анализа данных»](https://github.com/teimy/geohse-python-2024-aut) (ФГГТ ВШЭ).
### Alarm! Единственный требующий открытия файл это _visualization.ipynb_

## Датасет
Для работы были использованы датасеты с Портала открытых данных правительства Москвы (находятся в репозитории) 
1. Информация о количестве станций, вагонов и протяженности линий: https://data.mos.ru/opendata/62741?isDynamic=false
2. Точность выполнения расписания: https://data.mos.ru/opendata/62745?isDynamic=false

## Задачи работы
Работу можно было разделить на два основных этапа:
1. Преобразование оригинальных json файлов в более удобный для анализа формат
2. Непосредственно извлечение из полученных данных полезной информации

## Результаты
Был написан скрипт, принимающий два json файла и возвращающий их с некоторыми дополнениями и в более удобном формате. Он приложен в виде отдельного .py файла (довести его до полноценного модуля не хватило времени). Этот код применяется в основном файле проекта.

Был написан скрипт, позволяющий визуализировать % сбоев в расписании для каждой линии метро. Вот пример его работы для Таганско-Краснопресненской
![image](https://github.com/user-attachments/assets/b2734ba6-45e0-4cf7-a88c-62c215f4c0a6)

Результаты анализа позволили получить несколько статистических показателей:
1. Средняя длинна линии в Московском метро составляет 30,67 киллометров
2. Средняя длинна одного перегона в Московском метро составляет 1,81 киллометра


Визуализация длинн всех линий метрополитена 
![image](https://github.com/user-attachments/assets/4e9d9c4f-5ad0-4d79-90e7-f81bbe721a8f)








