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
# Questao 4
```java
package desafio8;

import java.util.Scanner;

public class Desafio8 {

    public static void main(String[] args) {
        double n1, n2, n3;
        Scanner ler = new Scanner(System.in);

        System.out.println("Digite a primeira nota");
        n1 = ler.nextDouble();
        System.out.println("Digite a segunda nota");
        n2 = ler.nextDouble();
        System.out.println("Digite a terceiro nota");
        n3 = ler.nextDouble();
        System.out.println("Sua media e de:" + calcularMedia(n1, n2, n3));
    }

    public static double calcularMedia(double nota1, double nota2, double nota3) {
        double media = (nota1 + nota2 + nota3) / 3;
        return media;
    }
}
    
```
# Questao 5
```java
package desafio8;

import java.util.Scanner;
public class Desafio8 {

    public static void main(String[] args) {

        String palavra;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite uma palavra:");
        palavra = ler.nextLine();
        System.out.println("Original:" + palavra);
        System.out.println("Inverso:" + inverterTexto(palavra));

    }

    public static String inverterTexto(String p) {
        String inverte = " ";
        for (int i = p.length() - 1; i >= 0; i--) {
            inverte += p.charAt(i);
        }
        return inverte;
    }
}
````
# Questao 6
```java
package desafio8;

import java.util.Scanner;
public class Desafio8 {

    public static void main(String[] args) {

        double n;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite um numero:");
        n = ler.nextDouble();
        System.out.println("De metros para Km é:" + conversorKM(n) + "Km");

    }

    public static double conversorKM(double x) {
        double calculo = x / 1000;
        return calculo;
    }
}
```
# Questao 7
```java
package desafio8;

import java.util.Scanner;


public class Desafio8 {

    public static void main(String[] args) {

        double r;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite um numero:");
        r = ler.nextDouble();
        System.out.println("O volume da esfera é:" + (calcularVolume(r)) + "cm³");

    }

    public static double calcularVolume(double x) {
        double calculo = (4.0 / 3.0) * Math.PI * (Math.pow(x, 3));
        return calculo;
    }
}
```

