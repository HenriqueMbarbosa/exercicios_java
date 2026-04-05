# exercicios_java
Exercicios básicos em java que estou fazendo para pratiacar/Basic Java exercises I'm doing to practice.

## 🧮 Exercício 1 - Variáveis básicas

Crie um programa que armazene seu nome e idade e exiba na tela.

```java
public class Ex1 {
    public static void main(String[] args) {
        String nome = "Henrique";
        int idade = 20;

        System.out.println(nome + " tem " + idade + " anos");
    }
}
```

💡 Aprendi:

* Declaração de variáveis
* Uso de String e int
* Saída com System.out.println

---

## 🔢 Exercício 2 - Soma

Crie um programa que some dois números inteiros.

```java
int a = 10;
int b = 5;

System.out.println(a + b);
```

💡 Aprendi:

* Operações aritméticas

---

## 🔁 Exercício 3 - Pode dirigir

Verifique se uma pessoa pode dirigir com base na idade.

```java
int idade = 18;

if (idade >= 18) {
    System.out.println("Pode dirigir");
} else {
    System.out.println("Não pode dirigir");
}
```

💡 Aprendi:

* Estrutura condicional (if/else)

---

## 🔍 Exercício 4 - Número par ou ímpar

Verifique se um número é par ou ímpar.

```java
int numero = 7;

if (numero % 2 == 0) {
    System.out.println("Par");
} else {
    System.out.println("Ímpar");
}
```

💡 Aprendi:

* Operador módulo (%)

---

## 🧾 Exercício 5 - Média simples

Calcule a média de duas notas.

```java
double nota1 = 7.5;
double nota2 = 8.0;

double media = (nota1 + nota2) / 2;

System.out.println("Média: " + media);
```

💡 Aprendi:

* Uso de double
* Cálculo de média

---

## 🚦 Exercício 6 - Aprovado ou reprovado

Mostre se um aluno foi aprovado (média >= 7).

```java
double media = 6.5;

if (media >= 7) {
    System.out.println("Aprovado");
} else {
    System.out.println("Reprovado");
}
```

💡 Aprendi:

* Comparações lógicas

---

## 🔄 Exercício 7 - Contagem com loop

Mostre números de 1 a 5.

```java
for (int i = 1; i <= 5; i++) {
    System.out.println(i);
}
```

💡 Aprendi:

* Estrutura de repetição (for)

---

## 🔢 Exercício 8 - Tabuada

Mostre a tabuada de um número.

```java
int numero = 5;

for (int i = 1; i <= 10; i++) {
    System.out.println(numero + " x " + i + " = " + (numero * i));
}
```

💡 Aprendi:

* Loop com cálculo

---

## 🎯 Exercício 9 - Maior número

Descubra qual número é maior entre dois.

```java
int a = 10;
int b = 20;

if (a > b) {
    System.out.println("A é maior");
} else {
    System.out.println("B é maior");
}
```

💡 Aprendi:

* Comparação entre valores

---

## 🔐 Exercício 10 - Login simples

Simule um login básico.

```java
String usuario = "admin";
String senha = "1234";

if (usuario.equals("admin") && senha.equals("1234")) {
    System.out.println("Login correto");
} else {
    System.out.println("Login inválido");
}
```

💡 Aprendi:

* Comparação de String (.equals)
* Operador lógico AND (&&)
