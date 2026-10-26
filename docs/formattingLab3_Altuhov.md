## Примеры всех типов форматирования:
* **Жирный текст**
* *Курсив*
* ***Жирный курсив***
* ~~Зачёркнутый текст~~

```csharp
using System;

class FormatDemo
{
    static void Main()
    {
        Console.Write("Введите первое число: ");
        double num1 = Convert.ToDouble(Console.ReadLine());

        Console.Write("Введите второе число: ");
        double num2 = Convert.ToDouble(Console.ReadLine());

        double sum = num1 + num2;
        Console.WriteLine(\$"***Результаты операций: {sum}***");
    }
}
