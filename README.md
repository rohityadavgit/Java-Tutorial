# Java-Tutorial
package JavaBasics;

public class LearnJava {

	public static void main(String[] args) {

		System.out.println("Hello World!");
		
		String s = "Java for Beginners";
		System.out.println(s);
		
		float f = 98.72f;
		System.out.println(f);
		
		double d = 75.345678d;
		System.out.println(d);
		
		char grade = 'A';
		System.out.println(grade);
		
		int num1 = 40, num2 = 80;
		System.out.println(num1 + num2);
		System.out.println("The value of num1 - num2 is");
		System.out.println(num1 - num2);
		System.out.println(num1 * num2);
		System.out.println(num1 % num2);
		System.out.println(num1 / num2);
		System.out.println(num1++);
		System.out.println(++num1);
		System.out.println(num1--);
		System.out.println(--num1);
		System.out.println(num1 == num2);
		System.out.println(num1 != num2);
		System.out.println(num1 > num2);
		
		String firstName = "Rohit";
		String lastName = "Yadav";
		System.out.println(firstName + lastName);
		System.out.println(firstName.length());
		System.out.println(lastName.contains("ad"));
		System.out.println(firstName.endsWith("it"));
		
		int x = 16, y = 9;
		System.out.println(Math.max(x, y));
		System.out.println(Math.min(x, y));
		System.out.println(Math.sqrt(x));
		System.out.println(Math.sqrt(y));
		
		int i = 0;
		while(i<100)
		{
			System.out.println(i);
			i = i+1;	
		}
		
	}
}
