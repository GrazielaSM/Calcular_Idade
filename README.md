using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Aula1
{
    class Program
    {
        static void Main(string[] args)
        {
            //Declarar variaveis:
            String nome = "Graziela";
            string sobrenome = "Martins";
            bool isValid = true;


            //Converter dados:
            string valor1 = "1";
            int v1 = Convert.ToInt32(valor1);
            int v2 = int.Parse(valor1);


            //Concatenar variáveis:
            string nomeCompleto = nome + " " + sobrenome;

            //Imprimir variável:
            Console.WriteLine(nomeCompleto);

            //Caracter Scape:
            Console.WriteLine("olá Mundo!");
            Console.WriteLine("Mundo da tecnologia...");
            Console.ReadKey();
        }
    }
}

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Aula1_B
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Nome: ");
            string nome = Console.ReadLine();
            Console.WriteLine("\nIdade");
            int idade = int.Parse(Console.ReadLine());

            if (idade < 18)
                Console.WriteLine("Menor idade");
            else
                Console.WriteLine("Maior de Idade");

            Console.WriteLine("O seu nome é:" + nome);
            //Aguarda uma tecla a ser precionada
            Console.ReadKey();


        }
    }
}

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Aula1_C
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Entre com o valor de A: ");
            int a = int.Parse(Console.ReadLine());

            Console.Write("\nEntre com o valor de B: ");
            int b = int.Parse(Console.ReadLine());

            Console.Write("\nOperação (+ - * /)>: ");
            string operacao = Console.ReadLine();

            int resultado = 0;
            
            switch (operacao)
            {
                case "+" :
                    resultado = a + b;
                    break;

                case "-":
                    resultado = a - b;
                    break;

                case "*":
                    resultado = a * b;
                    break;

                case "/":
                    resultado = a / b;
                    break;

                default:
                    Console.WriteLine("Operação inválida!");
                    break;

            }

            Console.WriteLine("Resultado: " + resultado);
            Console.ReadKey();
               

        }
    }
}
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {

            //while:

            int i = 0;

            while (i <= 10) 
            {
                Console.WriteLine(i);
                i++;
            }
            for ( int z = 0; z < 10; z++)
            {
                Console.WriteLine(z);
            }
        }
    }
}
