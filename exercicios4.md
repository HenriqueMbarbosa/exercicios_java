Exercicio 1 (Maior que)
public class ExpressoesComparativas {
    public static void main(String[] args) {

        int numero = 10;
        boolean resultado = numero > 5;

        System.out.println("Resultado: " + resultado);


    }
}


Exercicio 2 (Igual a)
public class ExpressoesComparativas {
    public static void main(String[] args) {

        int numero = 10;
        boolean resultado = numero == 10;

        System.out.println("Resultado: " + resultado);


    }
}


Exercicio 3 ( Operador &&)
public class ExpressoesComparativas {
    public static void main(String[] args) {

        int idade = 20;
        boolean resultado = idade >= 18 && idade < 60 ;

        System.out.println("Resultado: " + resultado);


    }
}


Exercicio 4 (Operador ||)
public class ExpressoesComparativas {
    public static void main(String[] args) {

        int idade = 16;
        boolean resultado = idade < 18 || idade > 60;

        System.out.println("Resultado: " + resultado);

    }
}


Exercicio 5 (Operador !)
public class ExpressoesComparativas {
    public static void main(String[] args) {

        boolean estudando = true;


        System.out.println("Resultado: " + !estudando);


    }
}


Exercicio 6 (If, operador ! e Scanner)
import java.util.Scanner;
public class NegacaoExemplo {
    public static void main(String[] args) {

        Scanner scanner = new Scanner (System.in);


        System.out.println("Digite sua idade: ");
        int idade = scanner.nextInt();

        boolean isAutorizadoComprarBebidaAlcolica = idade >= 18;

        if (isAutorizadoComprarBebidaAlcolica) {
            System.out.println("Autorizado a comprar bebida alcolica.");
        }

        if (!isAutorizadoComprarBebidaAlcolica){
            System.out.println("Não autorizado a comprar bebida alcolica.");
        }
    }
}


Exercicio 7  (If-else e Scanner)
import java.util.Scanner;
public class IfElse {
    public static void main(String[]args) {

                Scanner scanner = new Scanner (System.in);


                System.out.println("Digite sua idade: ");
                int idade = scanner.nextInt();

                boolean isAutorizadoComprarBebidaAlcolica = idade >= 18;

                if (isAutorizadoComprarBebidaAlcolica) {
                    System.out.println("Autorizado a comprar bebida alcolica.");
                }

                else {
                    System.out.println("Não autorizado a comprar bebida alcolica.");
                }
            }
        }


Exercicio 8 (If, else if e else)
public class IfElse {
    static void main(String[] args) {
        //idade < 15 anos categoria infantil
        //idade >= 15 anos && < 18 anos categoria juvenil
        //idade > 18 anos categoria adulto

        int idade = 17;

        if(idade < 15) {
            System.out.println("Categoria infantil");

        } else if(idade >= 15 && idade < 18) {
            System.out.println("Categoria juvenil");

        } else {
                    System.out.println("Categoria adulto");
                }
            }
        }

Exercicio 9 (Operador ternario)
public class IfElse {
    static void main(String[] args) {
        //Comprar um celular novo se tiver 5000 reais guardados

        int dinheiroGuardado = 2800;
        String comprarCelularNovo = "Posso comprar um celular novo";
        String naoComprarCelularNovo = "Não posso comprar um celular novo";

        String mensagem = dinheiroGuardado >= 5000 ?comprarCelularNovo : naoComprarCelularNovo;

        System.out.println(mensagem);

    }
}
