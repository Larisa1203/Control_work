## Задача
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Примеры
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”] 

[“1234”, “1567”, “-2”, “computer science”] → [“-2”] 

[“Russia”, “Denmark”, “Kazan”] → []

## Решение
Запрос размера массива строк у пользователя

Ввод данных пользователем и сохранение в массиве

Подсчет подходящих строк (длина не более 3 символов)

Выделение памяти под новый массив с подходящими строками

Заполнение нового массива подходящими строками

Вывод результатов [Новый массив с подходящими строками (длина <= 3 символов)]