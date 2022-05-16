# Tabuada
Tabuada de qualquer número.
package olamundo;

import java.util.Scanner;

public class Forlooping {

	public static void main(String[] args) {

		Scanner scan = new Scanner (System.in);
		
		System.out.println("Digite o numero da tabuada:");
		int num = scan.nextInt();
		
		for (int i = 1; i <= 10; i++) {
			System.out.println(num+"x"+i+"="+(num*i));
		}
	}

}
