Exercicio 1
package aprendendo.programar.introducao;
//Crie um array com:{10, 20, 30, 40, 50}; Mostre o primeiro valor.
public class Arrays {
    public static void main(String[] args) {

        int[] numeros = {10, 20, 30, 40, 50};

        System.out.println(numeros[0]);
    }
}


Exercicio 2
package aprendendo.programar.introducao;
// Use o mesmo array:{10, 20, 30, 40, 50}; Mostre o último valor.
public class Arrays {
    public static void main(String[] args) {

        int[] numeros = {10, 20, 30, 40, 50};

        System.out.println(numeros[numeros.length - 1]);
    }
}


Exercicio 3
package aprendendo.programar.introducao;
//Crie um array:{10, 20, 30}; Mude o valor 20 → 99; Mostre o array completo.
public class Arrays {
    public static void main(String[] args) {

        int[] numeros = {10, 20, 30};
        numeros[1] = 99;

        for (int i = 0; i < numeros.length; i++) {
            System.out.println(numeros[i]);
        }
    }
}


Exercicio 4
package aprendendo.programar.introducao;
//Crie um array:{5, 10, 15, 20}; Use for para somar todos os valores.
public class Arrays {
    public static void main(String[] args) {

        int[] numeros = {5, 10, 15, 20};
        int soma = 0;

        for (int i = 0; i < numeros.length; i++) {
            soma += numeros[i];
        }
        System.out.println("Soma: " + soma);
    }
}


Exercicio 5
package aprendendo.programar.introducao;
//Crie um array:{3, 8, 15, 20, 7}; Mostre apenas os números maiores que 10.
public class Arrays {
    public static void main(String[] args) {

        int[] numeros = {3, 8, 15, 20, 7};

        for (int i = 0; i < numeros.length; i++) {
            if(numeros[i] > 10){
                System.out.println(numeros[i]);
            }
        }
    }
}


Exercicio 6
package aprendendo.programar.introducao;
//Crie uma matriz:
//{
//    {2, 4},
//    {6, 8}
//}
//Mostre apenas os valores pares maiores que 4.
public class ArraysMultidimensionais {
    public static void main(String[] args) {
        int[][] arrayInt = new int[2][2];

        arrayInt[0] = new int[]{2, 4};
        arrayInt[1] = new int[]{6, 8};

        for(int[] arrayBase: arrayInt){
            for(int num: arrayBase){
                if(num % 2 == 0 && num > 4){
                    System.out.println(num);
                }
            }
        }
    }
}
