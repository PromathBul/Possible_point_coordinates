# Задача
Напишите программу, которая по заданному номеру четверти, показывает диапазон возможных координат точек в этой четверти (x и y).
# Решение
В программу внесен набор условий:
- если номер четверти - 1, тогда x > 0 & y > 0
- если номер четверти - 2, тогда x < 0 & y > 0
- если номер четверти - 3, тогда x < 0 & y < 0
- если номер четверти - 4, тогда x > 0 & y < 0
- если значение четверти не входит в диапазон [1, 4], тогда вернуть сообщение об ошибке.