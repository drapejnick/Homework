#  Задача :

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами. 

## Описание алгоритма :

Задается два массива, оба одинаковой такой длины. Описывается метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да, то элемент первого массива заносится в count элемент второго массива. Переменная count нужна для поочередно переноса из первого массива во второй и для того, чтобы не было пробелов. После присвоения переменная count увеличивается на 1 и возвращается к циклу for, в котором i увеличивается на 1. Итак проверяется до конца.

### Блок схема алгоритма : 

Блок схема алгоритма представлена по ссылке: [Блок-схема](/block_diagram.png)