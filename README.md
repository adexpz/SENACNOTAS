string nome;
decimal nota1, nota2, nota3, nota4, media;

Console.WriteLine("digite seu nome:");
nome = Console.ReadLine();

Console.WriteLine("digite a nota 1");
nota1 = Convert.ToDecimal(Console.ReadLine());

Console.WriteLine("digite a nota 2:");
nota2 = Convert.ToDecimal(Console.ReadLine());

Console.WriteLine("digite a nota 3");
    nota3 = Convert.ToDecimal(Console.ReadLine());

Console.WriteLine("digite a nota 4");
nota4 = Convert.ToDecimal(Console.ReadLine());





media = (nota1 + nota2 + nota3 + nota4) / 4;

if (media >= 60)
{
    Console.WriteLine("parabens " + nome + ", voce nao fez mais que a obrigação");

}

else
{
    decimal notadarecuperação;

    Console.WriteLine("digite a nota da recuperação:");
    notadarecuperação = Convert.ToDecimal(Console.ReadLine());

    if (notadarecuperação >= 80)
    {
        Console.WriteLine("parabens, " + nome + ", voce foi aprovado");
    }

    else
    {
        Console.WriteLine("voce foi reprovado");

    }
}
