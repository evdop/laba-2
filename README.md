Лабораторная работа №2. Вариант 1. Необходимо развернуть строку в обратном направлении.

Оценка сложности алгоритма: Цикл выполняется N раз, таким образом, вычислительная сложность этого алгоритма равна O(N). Это линейная зависимость.

Цикл работает следующим образом: 
Здесь первая часть объявления цикла - int i = s.Length - 1 - создает i и приравнивает ее к индексу строке, то есть i равна длине строке, уменьшенной на 1 потому, что длина строки всегда на 1 больше, чем индекс последнего ее элемента. 
Вторая часть - условие i >= 0. То есть пока переменная i больше или равна 0, будет выполняться цикл.
И третья часть - действия, выполняемые после завершения действий из блока цикла - уменьшение переменной i на единицу.
В результате цикл развернет строку в обратном направлении.

Как пользоваться алгоритом:
1. Ввести строку, которою хотите развернуть в обратном направлении.
2. Дождаться результата.
