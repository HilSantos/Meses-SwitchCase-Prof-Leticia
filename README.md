# Meses-SwitchCase-Prof-Leticia
Escreva um programa que solicite um numero de 1 a 12 do usuario e exiba o nome do dia do mês correspondente (1=Janeiro, 2=Fevereiro,...12=Dezembro), usando o comando switch case.
Entregar até 18/10/24
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace MesesSwitchCase
{
    public class Program
    {
        static void Main(string[] args)
        {
            int Mês, numero;

            Console.WriteLine("Informe um numero de 1 a 12: ");
            Mês = Convert.ToInt32(Console.ReadLine());
            switch (Mês)
            {
                case 1:
                    Console.WriteLine("Janeiro");
                    break;
                case 2:
                    Console.WriteLine("Fevereiro");
                    break;
                case 3:
                    Console.WriteLine("Março");
                    break;
                case 4:
                    Console.WriteLine("Abril");
                    break;
                case 5:
                    Console.WriteLine("Maio");
                    break;
                case 6:
                    Console.WriteLine("Junho");
                    break;
                case 7:
                    Console.WriteLine("Julho");
                    break;
                case 8:
                    Console.WriteLine("Agosto");
                    break;
                case 9:
                    Console.WriteLine("Setembro");
                    break;
                case 10:
                    Console.WriteLine("Outubro");
                    break;
                case 11:
                    Console.WriteLine("Novembro");
                    break;
                case 12:
                    Console.WriteLine("Dezembro");
                    break;
                default:
                    Console.WriteLine("Opção Incorreta!");
                    break;
            }
            //verificar os numeros referentes aos meses

            Console.ReadKey();
        }
    }
}
