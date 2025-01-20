# Моделирование динамики полового и возрастного состава населения России за последние 50 лет

### Пользователь в python ноутбуке указывает:
- путь к файлу с первоначальным возрастным составом населения
- путь к файлу с таблицей смертности
- год начала моделирования (по умолчанию - 1970);
- год окончания моделирования (по умолчанию - 2021);
- начальная общая численность населения (по умолчанию - 130 млн. чел.).

После чего python ноутбук запускает программу самого имитационного моделирования, написанную на C#, которая и начинает процесс моделирования с заданными параметрами. По окончании процесса, программа должна выдавать файлы с результатами. 

### После этого - при помощи python ноутбука данные визуализируются. А именно
- график изменения общего населения по годам в виде spline chart;
- график изменения населения мужского пола по годам в виде spline chart;
- график изменения населения женского пола по годам в виде spline chart;
- возрастной состав населения мужского пола на конец моделирования для возрастных категорий 0-18, 19-45, 45-65 и 65-100 лет в виде bar chart;
- возрастной состав населения женского пола на конец моделирования для возрастных категорий 0-18, 19-44, 45-65 и 66-100 лет в виде bar chart.
