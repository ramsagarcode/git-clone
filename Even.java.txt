package org.com;

import java.util.Scanner;

public class EvenNumber {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the number");
		int n = sc.nextInt();
		int sum = 0;
		int i = 2;

		while (i <= n) {
			if (i % 2 == 0) 
				sum = sum + i;
			i++;
		}
		System.out.println("Sum of all even number : " + sum);

	}
}
