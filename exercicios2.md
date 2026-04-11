Exercicio 1 (Entrada de Dados)
import java.util.Scanner;
public class ExerciciosEntrasSaidaDeDados {
    public static void main(String [] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite seu nome:");
        String nome = scanner.nextLine();

        System.out.println("Olá, " + nome);

    }
} 


Exercicio 2
import java.util.Scanner;
public class ExerciciosEntrasSaidaDeDados {
    public static void main(String [] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite sua idade:");
        int idade = scanner.nextInt();

        System.out.println("Você tem " + idade + " anos");

    }
}


Exercicio 3
import java.util.Scanner;
public class ExerciciosEntrasSaidaDeDados {
    public static void main(String [] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite seu nome:");
        String nome = scanner.nextLine();

        System.out.println("Digite sua idade:");
        int idade = scanner.nextInt();

        System.out.println(nome + " tem " + idade +" anos");

    }
}


Exercicio 4
import java.util.Scanner;
public class ExerciciosEntrasSaidaDeDados {
    public static void main(String [] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite seu ano de nascimento:");
        int anoNascimento = scanner.nextInt();

        System.out.println("Digite o ano atual:");
        int anoAtual = scanner.nextInt();

        int idade = anoAtual - anoNascimento;

        System.out.println("Você tem " + idade + " anos");

    }
}


Exercicio 5
import java.util.Scanner;

public class ExerciciosEntrasSaidaDeDados {
    public static void main(String [] args) {

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite seu nome:");
        String nome = scanner.nextLine();

        System.out.println("Digite sua idade:");
        int idade = scanner.nextInt();

        System.out.println("Digite sua altura:");
        double altura = scanner.nextDouble();

        boolean maiorDeIdade = idade >= 18;

        System.out.println("Nome: " + nome);
        System.out.println("Idade: " + idade);
        System.out.println("Altura: " + altura);
        System.out.println("Maior de idade: " + maiorDeIdade);

    }
}
