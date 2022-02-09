package test;
import java.util.Scanner;
public class HIAHMED {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.println("what is yourname?");
		String name = input.next();

		
		System.out.println("Could you please enter the first number?");
		int num1 = input.nextInt();
		
		System.out.println("please enter the Second number?");
		int num2 = input.nextInt();
		
		System.out.println("please enter the Third number?");
		int num3 = input.nextInt();

		System.out.println("please enter the fourth number?");
		int num4 = input.nextInt();
		
		System.out.println("please enter the fifth number?");
		int num5 = input.nextInt();
		
		int sum = ((num1 + num2 + num3 + num4 + num5)/5);
		System.out.println("Hi "+ name + " Average of all number is " + sum );

	}

}
