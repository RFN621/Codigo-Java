# Codigo-Java
Aqui está alguns códigos que eu desenvolvi ao longo do tempo. Estou aprendendo ainda então acaba sendo codigos de aprendizado basicos.
Nesse codigo abaixo o usuario teria que colocar um valor inteiro para saber o estado do dia se é Dia, Tarde ou Noite.


import java.util.Scanner;

public class Main {
	public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	int hora;
	
	System.out.println("Quantas hora?");
	hora=sc.nextInt();
	
	if (hora<12){
		System.out.println("Bom dia");
	}
	else if (hora<18){
		System.out.println("Boa tarde");
	}
	else {
		System.out.println("boa noite");
	}
	sc.close();
	
	}
}


Fazer um programa para ler um número inteiro, e depois dizer se este número é negativo ou não.


import java.util.Scanner;

public class Main {
	public static void main(String[] args) {
		 Scanner sc= new Scanner(System.in);
		 int x;
		 
		 x = sc.nextInt();
		 
		if (x < 0) {
		System.out.println("negativo");
		}
			else {
			System.out.println("positivo");
		}
		sc.close();
	}
	
	}


 Fazer um programa para ler um número inteiro e dizer se este número é par ou ímpar.

 
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);

		int N = sc.nextInt();
	    
		if (N % 2 == 0) {
			System.out.println("PAR");
		}
		else {
			System.out.println("IMPAR");
		}

		sc.close();
	}
}










































