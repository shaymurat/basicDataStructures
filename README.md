Практическое задание по уроку "Базовые структуры данных"

Цель: применить и закрепить базовые знания о структурах данных, решив набор задач.

Задача 1 (просто) "Арифметика":

    Напишите в начале программы однострочный комментарий: "1st program".
    Выведите на экран(в консоль) результат: возведение числа 9 в степень 0.5, после умножение на 5.
    Предполагаемый результат: 15.0


Задача 2 (просто) "Сравнение, or, and":

    Напишите в начале программы однострочный комментарий: "2nd program".
    Убедитесь в том что 9.99 больше 9.98 и 1000 не равно 1000.1 одновременно, выведете результат на экран(в консоль)
     Предполагаемый результат: True


Задача 3 (средне) "Сложная арифметика":

    Напишите в начале программы однострочный комментарий: "3rd program".
    Дано два целых четырёхзначных числа: 1234 и 5678.
    Выведите на экран(в консоль) сумму серединных чисел исходных данных (23 и 67).
    Предполагаемый результат: 90

ПОДСКАЗКА. Для взятия определённых частей числа понадобятся следующие арифметические действия: целочисленное деление //, остаточное деление %, а так же "круглые" числа: 10, 100 и т.д.
Например:
123 % 100 -> 23;
23 // 10 - > 2;
Так мы получили цифру 2 из числа 123.

Задача 4 (сложно) "Всё, везде и сразу":

    Напишите в начале программы однострочный комментарий: "4th program".
    Дано два дробных числа: 13.42 и 42.13.
    Необходимо убедиться в том, что целая часть хотя бы одного из чисел равна дробной части другого. Например: 13 == 13 (13.42, 42.13) или 42 == 42 (13.42, 42.13).
    Предполагаемые результат: True

УТОЧНЕНИЕ. 54.39 и 37.54 в результате дают True, т.к. один из вариантов был верным (54 == 54).
ПОДСКАЗКА. Многие фишки можно взять из предыдущей задачи. Не забывайте про преобразование типов, or и and.
НАПОМИНАНИЕ. Не достаточно просто написать сравнение этих двух чисел - print(13 == 13), нужно написать выражение, которое изначально работает с этими дробными числами.