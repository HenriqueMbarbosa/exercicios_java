Exercicio 1
import java.util.Scanner;
public class ExerciciosBasicos {
    public static void main(String[] args) {
        // O programa recebe como entrada um nome e uma idade e na saída informa se pode ou não dirigir. 

        Scanner sc = new Scanner(System.in);

        System.out.println("Digite seu nome: ");
        String nome = sc.nextLine();

        System.out.println("Digite sua idade: ");
        int idade = sc.nextInt();

        boolean maiorDeIdade = idade >= 18;

        System.out.println("Nome: " + nome);
        System.out.println("Idade: " + idade);

        if(maiorDeIdade) {
            System.out.println("Pode dirigir");
        }else{
            System.out.println("Não pode dirigir");
        }

    }
}


Exercicio 2
import java.util.Scanner;
public class ExerciciosBasicos {
    public static void main(String[] args) {
        // O programa recebe como entrada um número e na saída informa se é par ou ímpar.

        Scanner sc = new Scanner(System.in);

        System.out.println("Digite um número: ");
        int numero = sc.nextInt();

        if (numero % 2 == 0) {
            System.out.println("Par");
        }else{
            System.out.println("Ímpar");
        }
    }
}


Exercicio 3
public class ExerciciosBasicos {
    public static void main(String[] args) {
        // Use for para mostrar os números de 1 até 10; Mas só imprima os pares.

        for(int i = 1; i <= 10; i++){
            if(i % 2 == 0){
                System.out.println(i);
            }

        }
    }
}


Exercicio 4
import java.util.Scanner;
public class ExerciciosBasicos {
    public static void main(String[] args) {
        // Peça um número; Use for para mostrar a tabuada desse número (1 até 10).

        Scanner sc = new Scanner(System.in);

        System.out.println("Digite um número:");
        int numero = sc.nextInt();

        for (int i = 1; i <= 10; i++) {
            int resultado = numero * i;
            System.out.println(numero + " x " + i + " = " + resultado);
        }

    }
}


Exercicio 5
import java.util.Scanner;
public class ExerciciosBasicos {
    public static void main(String[] args) {
        // Peça um número; Use while para contar de 1 até esse número.

        int contador = 1;

        Scanner sc = new Scanner(System.in);

        System.out.println("Digite um número:");
        int numero = sc.nextInt();

        while(contador <= numero){
            System.out.println(contador);
            contador++;

        }
    }
}


Exercicio 6
import java.util.Scanner;
public class ExerciciosBasicos {
    public static void main(String[] args) {
        // Peça um número; Use while para somar de 1 até esse número.
        int i = 1;
        int soma = 0;

        Scanner sc = new Scanner(System.in);

        System.out.println("Digite um número:");
        int numero = sc.nextInt();

        while (i <= numero) {
            soma += i;
            i++;
        }

        System.out.println("Soma: " + soma);
    }
}


Exercicio 7
public class ExerciciosBasicos {
    public static void main(String[] args) {
    //Use for de 1 até 10; Para cada número: se for par mostre "par" e se for ímpar mostre "Ímpar".

        for (int i = 1; i <= 10; i++) {
            if (i % 2 == 0) {
                System.out.println(i + " - Par");
            } else {
                System.out.println(i + " - Ímpar");
            }
        }

    }
}
