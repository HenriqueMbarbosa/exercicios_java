Exercicio 1 (Casting automatico)
public class ConversaoDeTipos {
    public static void main (String[] args){

        int numero = 10;
        double valor = numero;

        System.out.println("Valor: " + valor);

    }
}


Exercicio 2 (Casting manual) 
public class ConversaoDeTipos {
    public static void main (String[] args){

        double numero = 10.7;
        int valor = (int) numero;

        System.out.println("Valor: " + valor);

    }
}


Exercicio 3 (Casting + Scanner)
import java.util.Scanner;
public class ConversaoDeTipos {
    public static void main (String[] args){

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite um número decimal:");
        double numeroDecimal = scanner.nextDouble();

        int valor = (int) numeroDecimal;

        System.out.println("Valor inteiro: " + valor);

    }
}


Exercicio 4 (Inteiro para String)
public class ConversaoDeTipos {
    public static void main (String[] args){

        int idade = 20;
        String idadeTexto = String.valueOf(idade);

        System.out.println("Idade: " + idadeTexto);

    }
}


Exercicio 5 (Double para String e Inteiro)
import java.util.Scanner;
public class ConversaoDeTipos {
    public static void main (String[] args){

        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite um número decimal:");
        double numeroDecimal = scanner.nextDouble();

        int numeroInteiro = (int) numeroDecimal;
        String numeroTexto = String.valueOf(numeroDecimal);

        System.out.println("Número decimal: " + numeroDecimal);
        System.out.println("Número inteiro: " + numeroInteiro);
        System.out.println("Número texto: " + numeroTexto);

    }
}
