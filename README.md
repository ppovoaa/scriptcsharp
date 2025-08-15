using System;
using System.Collections.Generic;
using System.Diagnostics.Eventing.Reader;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using static System.Console;

namespace Aulac_3
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int a = 3;
            if (a > 0)
            {
                WriteLine($"O número {a} é positivo!");
            }
            else
            {
                WriteLine($"O número {a} é positivo!");
            }
            ReadLine();
        }

            }
        }

{
    internal class Program
    {
        static void Main(string[] args)
        {
            int a = -2;
            if (a < 0)
            {
                WriteLine($"O número {a} é negativo!");
            }
            else
            {
                if (a == 0)
                {
                    WriteLine($"O número {a} é igual a zero!");
                }
                else
                {
                    WriteLine($"O número {a} é pisitivo!");
                }
                ReadKey();

            }

        }
    }
}
{
        static void Main(string[] args)
        {
            string nome = "";
            float nota1, nota2, media;

        inicio:
            WriteLine("Digite o nome do aluno: ");
            nome = ReadLine();
            WriteLine("Digite a primeira nota do aluno: ");
            nota1 = float.Parse(ReadLine());
            WriteLine("Digite a segunda nota do aluno: ");
            nota2 = float.Parse(ReadLine());
            media = (nota1 + nota2) / 2;
            WriteLine("A média do aluno" + nome + " é: " + media);
            WriteLine("Deseja realizar outro cálculo? (S/N)");
            string resposta = ReadLine();
            if (resposta == "S" || resposta == "s")
            {
                goto inicio;
            }
            else
            {
            }

               




        }
    }
}

                ReadLine();
