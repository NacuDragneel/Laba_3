# Laba_3
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _17_09_2016
{
    class Program
    {
        static void Main(string[] args)
        {
            //int k;
            //int sum = 0;

            //Console.WriteLine("Введите число");
            //k = int.Parse(Console.ReadLine());

            //for (int i = 1; i <= k; i++)
            //{
            //    sum += i;

            //}

            //Console.WriteLine(sum);


            //=======================================zadanie 2==============================

            //for (int i = 35; i <= 87; i++)
            //{
            //    if ((i % 7 == 1) || (i % 7 == 2) || (i % 7 == 5))
            //    {
            //        Console.WriteLine(i);
            //    }
            //}


            //===============================zadanie 3================================
            //int kol;
            //int max;
            //int min;
            //int sum = 0;
            //float SrZn;

            //Console.Write("Введите кол-во посетителей: ");
            //kol = int.Parse(Console.ReadLine());

            //int[] mass = new int[kol];

            //for (int i = 0; i < kol; i++)
            //{
            //    Console.Write("Введите возраст" + i + "-го пользователя: ");
            //    mass[i] = int.Parse(Console.ReadLine());
            //}

            //max = mass[0];

            //for (int i = 1; i < kol; i++)
            //{
            //    if (max < mass[i])
            //    {
            //        max = mass[i];
            //    }
            //}

            //min = mass[0];

            //for (int i = 1; i < kol; i++)
            //{
            //    if (min > mass[i])
            //    {
            //        min = mass[i];
            //    }
            //}

            //for (int i = 0; i < kol; i++)
            //{
            //    sum += mass[i];
            //}

            //SrZn = sum/kol;

            //Console.WriteLine("Возраст старшего: "+ max);
            //Console.WriteLine("Возраст младшего: "+min);
            //Console.WriteLine("Средний возраст = "+SrZn);


            //=============================ZADANIE 4=========================

            //int box = 15;
            //int auto;
            //int kol;

            //Console.Write("Кол-во машин: ");
            //auto = int.Parse(Console.ReadLine());

            //for (int i = 0; i < auto; i++)
            //{
            //    Console.Write("Сколько ящиков положить в " + (i + 1) + " машину?  -  ");
            //    kol = int.Parse(Console.ReadLine());

            //    if (kol <= box)
            //    {
            //        box -= kol;
            //        Console.WriteLine("На складе ещё " + box + " коробок");
            //    }
            //    else
            //    {
            //        Console.WriteLine("Ты всё портишь, гадёныш! >:C");
            //        continue;
            //    }
            //}

            //===========================ZADANIE 5=================================


            for (int i = 0; i < 4; i++)
            {
                for (int j = 0; j < 5; j++)
                {
                    Console.Write("3 ");
                }
                Console.WriteLine();
            }

            Console.WriteLine();




            //============ вторая таблица ==========

            int k = 1;

            for (int i = 0; i < 5; i++)
            {
                for (int j = 0; j < k; j++)
                {
                    Console.Write("* ");
                }

                if (k == 5)
                { break; }
                k++;
                Console.WriteLine();
            }
            Console.WriteLine();
            Console.WriteLine();



            //=============== третья таблица =======

            int z = 0;
            for (int i = 0; i < 4; i++)
            {
                for (int j = 0; j < 4; j++)
                {
                    Console.Write((++z) + " ");
                }
                Console.WriteLine();
            }
            Console.WriteLine();



            //=============== последняя таблица =======

            int[] mass = new int[25];
            for (int i = 0; i < 25; i++)
            {
                mass[i] = 0;
            }

            mass[0] = 1;
            mass[4] = 1;
            mass[6] = 1;
            mass[8] = 1;
            mass[12] = 1;
            mass[16] = 1;
            mass[18] = 1;
            mass[20] = 1;
            mass[24] = 1;

            for (int i = 0; i < 25; i++)
            {
                if ((i==5) || (i==10) || (i==15) || (i==20)) Console.WriteLine();
                Console.Write(mass[i]);
            }
            Console.ReadKey();
        }
    }
}

