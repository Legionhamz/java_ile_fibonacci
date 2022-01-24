# java_ile_fibonacci

package fibonaccii;

import java.util.Scanner;

public class fibonaacci {

	public static void main(String[] args) {
		/* fibonacci yapımı */
		
		Scanner girdi = new Scanner(System.in);
		System.out.println("Kaç sayı yazdirsin: ");
		int sayac = girdi.nextInt();
		
		
		int a = 0;
		int b = 1;
		int toplam;
		toplam = a + b;
		
		System.out.println(a);
		System.out.println(b);
		System.out.println(toplam);
		
		for(int i = 1; i < sayac-2; i++) {
			
			a = b;
			b = toplam;
			toplam = a + b;
			
			System.out.println(toplam);			
		}
		

	}

}
