import java.util.Scanner;


public class example3 {

	public static void main(String[] args) {
		
		int Number;
		
		Scanner myObj = new Scanner(System.in);
		
		System.out.println("Enter number");
		
		 Number= myObj.nextInt();
		
		if (Number > 0) {
			System.out.println (Number + "is positive");
			
		}else {
			System.out.println (Number + "is negative");
