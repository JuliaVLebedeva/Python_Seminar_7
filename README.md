# 1. ЗАДАЧА 
Создать калькулятор для работы с рациональными и комплексными числами, 

организовать меню, добавив в неё систему логирования.

Архитектура:

interface.py - модуль старт/запуск, далее запускаются следующие модули (digit, in_num, log)

in_num.py - модуль ввод выражения и вывод результата

digit.py - модуль арифметические расчеты; из in_num извлекается + переводится в формат для вычисления (основной калькулятор расчетов)

log.py - модуль журнал решений (прошлые записи); собираются записи (пример и результат), далее записываются в текстовый файл

main.py - возврат к старту или остановке; возвращается модуль interface

file.txt - блокнот для записей, сохраняются итоговые результаты.