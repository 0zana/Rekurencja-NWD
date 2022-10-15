package rekurencja;

import java.util.Scanner;

public class NWD {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Podaj a = ");
		int a = sc.nextInt();
		System.out.println("Podaj b = ");
		int b = sc.nextInt();
		System.out.println("Zwykle NWD");
		System.out.println("Największy wspólny dzielnik "+ a+ " i "+ b + " to " + NWD(a,b));
			
		}
	public static int NWD(int a, int b) {
		if(a==0 || b==0) {
			if (a==0) {
				return b;
			}else {
				return a;
			}
		}else {
			return NWD(b, a%b);
		}
	}
	}

