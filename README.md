# FinalTest
Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

1.Создаем метод, который разделяет строки введенные в консоли в массив через знак «,»
2.Созаем метод, который сортирует  символы из массива.
3. Создаем метод,к оторый выdодит элементы из массива.
4.Выводим строку в консоли  # Введите набор символов через , -
5.Введенные символы от пользователя 
string inStringSymbol = Console.ReadLine();
string[] arraySymbol = GetArrayStringConsole(inStringSymbol);
6.Выводим на консоль введенные символы и символы длиной <= 3

