# Desafio-8
```java
package desafio8;

import java.util.Scanner;

public class Desafio8 {

    public static void main(String[] args) {
        int num1, num2, num3;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite o primeiro numero");
        num1 = ler.nextInt();
        System.out.println("Digite o segundo numero");
        num2 = ler.nextInt();
        System.out.println("Digite o terceiro numero");
        num3 = ler.nextInt();
        mostrarMaior(num1,num2,num3);
    }

    public static void mostrarMaior(int a, int b, int c) {
        int maior;
        if (a > b && a > c) {
            System.out.println(" Primeiro numero e maior "+a);
        } else if (b > a && b > c) {
            System.out.println(" O segundo numero e maior "+b);
        } else if (c > a && c > b) {
            System.out.println(" O terceiro numero e maior "+c);
        } else {
            System.out.println("TODOS SAO IGUAIS");
    }
}
}
```
# Questao 2
```java
package desafio8;

import java.util.Scanner;

public class Desafio8 {

    public static void main(String[] args) {
        String letras;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite a palavra");
        letras = ler.nextLine();
        converterMaiusculaEConta(letras);
    }
    public static void converterMaiusculaEConta(String pa){
        Scanner ler = new Scanner(System.in);
        System.out.println(pa.toUpperCase());
        System.out.println(pa.length()+" caracteres");
        
    }
}
```
# Questao 3
```java
package desafio8;

import java.util.Scanner;


public class Desafio8 {

    public static void main(String[] args) {

        int n;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite um número:");
        n = ler.nextInt();
        somaLista(n);
    }

    public static void somaLista(int x) {
        int i = 0;
        int soma = 0;
        while (i < x) {
            i++;
            soma += i;

        }
        System.out.println("A soma da lista de número é:" + soma);

    }
}
```
