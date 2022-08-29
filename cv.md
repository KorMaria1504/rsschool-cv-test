# Korchevnyuk Maria
> I see the goal and I see no obstacles
> 
**Contacts:** kormaria2002@gmail.com

## About Me
Self development has always been my main priority, that is why I have a great will to study. 
After finishing C# course at university, I decided to continue studying software development. 
I found out that programming suits my personal qualities, such as great analytical skill, structural logic, accuracy, and persistance. 
I am also a great leader, that is why I would love to be a manager or a boss. 
All in all, programming is our future, and I hope, my future career.

## Professional Skills:
* 1 year of C# at University.
*Code Example:* 
```C#
class Program
    {
        static void Line(char ch, int length)
        {
            int i;
            for (i = 0; i < length; i++)
            {
                Console.Write(ch);
            }
        }

        static double CELtoFAHR(double cel)
        {
            double fahr;
            fahr = 1.8*cel + 32;
            return fahr;
        }

        static double CELtoKEL(double cel)
        {
            double kel;
            kel = cel + 273;
            return kel;
        }

        static void Main(string[] args)
        {
            double cel1, cel2; // начальная и конечная границы диапазона температур
            double step; // шаг приращения
            double kel; // температура в Кельвинах
            double fahr; // температура в градусах Фаренгейта
            double cel; // температура в градусах Цельсия
            string st;

            Console.Write("Начальная температура в градусах Цельсия -> ");
            st = Console.ReadLine();
            cel1 = Convert.ToDouble(st);

            Console.Write("Конечная температура в градусах Цельсия -> ");
            st = Console.ReadLine();
            cel2 = Convert.ToDouble(st);

            Console.Write("Шаг приращения в градусах Цельсия -> ");
            st = Console.ReadLine();
            step = Convert.ToDouble(st);

            Console.WriteLine();

            Console.WriteLine("  Цельсий      Фаренгейт      Кельвин");
          
            Line('_', 40);
            Console.WriteLine();

            cel = cel1;
            while (cel <= cel2)
            {
                fahr = CELtoFAHR(cel);
                kel = CELtoKEL(cel);
                Console.WriteLine("{0,8:f2}{1,14:f2}{2,14:f2}", cel, fahr, kel);
                cel = cel + step;
            }
            
            Line('_', 40);

            int c = Console.Read();
        }
    }
```
* 1 year of DataBase building at University
* Visual Studio, VS Code, GitHub

## Education
* 2020: Graduation from Saint Petersburg Academic Gymnasium 56
* 2022-nowadays: Saint Petersburg State Polytechnical University of Peter the Great, Institute of Computer Sciences, Innovation management

## English Level:
**Advanced** (between C1 Advanced and C2 Proficient) according to EF SET Quick Check.


