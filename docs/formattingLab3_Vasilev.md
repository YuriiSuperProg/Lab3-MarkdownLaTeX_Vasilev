<!-- **Жирный текст**
*Курсив*
***Жирный курсив***
~~Зачеркнутый~~
`Console.WriteLine("Hello")`

```csharp
string name;
name = Console.ReadLine();
Console.WriteLine(name);
``` -->

# Задание: Комментированная программа на C#
Создайте консольное приложение на C#, которое демонстрирует все форматы
Markdown в комментариях к коду.
## Требования к программе:
1.**Имя файла:** `FormatDemo.cs`
2.**Логика:**
* Запрашивает у пользователя два числа;
* Выполняет их сложение;
* Выводит результаты в форматированном виде.
### Пример реализации:
```csharp
Console.Write("Введите первое число: ");
double num1 = double.Parse(Console.ReadLine());
Console.Write("Введите второе число: ");
double num2 = double.Parse(Console.ReadLine());
double sum = num1 + num2;
Console.WriteLine($"Итог суммы: {sum}");
```

