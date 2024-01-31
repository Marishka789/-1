using System;

class Program
{
    static void Main()
    {
        // Пример массива
        int[] array = { 1, 2, 3, 4, 5 };

        // Вызываем рекурсивную функцию для вывода элементов массива
        PrintArrayReverse(array, array.Length - 1);
    }

    static void PrintArrayReverse(int[] arr, int index)
    {
        if (index >= 0)
        {
            // Выводим элемент массива
            Console.WriteLine(arr[index]);

            // Рекурсивно вызываем функцию для следующего элемента
            PrintArrayReverse(arr, index - 1);
        }
    }
}
