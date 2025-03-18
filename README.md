using System;

internal class Program
{
    private static void Main()
    {
        // Solicita que o usuário insira um número
        Console.WriteLine("Informe um número inteiro:");
        int numero = int.Parse(Console.ReadLine());

        // Exibe a tabuada do número informado, de 1 até 10
        Console.WriteLine($"Tabuada do {numero}:");

        // Laço de repetição for para calcular e exibir a tabuada
        for (int i = 1; i <= 10; i++)
        {
            int resultado = numero * i;
            Console.WriteLine($"{numero} x {i} = {resultado}");
        }

    }
}
