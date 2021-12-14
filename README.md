package java;
import java.util.Scanner;

public class game {
	
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter age : ");
		int age = sc.nextInt();
		
		if(age<=5) {
			System.out.println("baby");
		}
		else if(age<=10) {
			System.out.println("toddler");
		}
		else if(age<=18) {
			System.out.println("teenaged");
		}
		else if(age<=25) {
			System.out.println("adult");
		}
		else {
			System.out.println("old");
		}
	}

}
