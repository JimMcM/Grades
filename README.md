
import java.util.Scanner; 	
public class Grades {

	public static void main(String[]args)

		{

		String Student1;
		String Student2;
		
		Scanner input = new Scanner(System.in);
		System.out.print("Student 1 Name: ");
		Student1 = input.nextLine();
		
		System.out.print("Student 2 Name: ");
		Student2 = input.next();

		calcGrade(Student1, Student2 , input);

		}

		public static void calcGrade(String Student1 , String Student2, Scanner input)

		{
	
		int eGrade;
		int Test1;
		int Test2;
		int Test3;
		int Test4;
		
		;
		System.out.print("Please enter your first exam grade " + Student1);
		Test1 = input.nextInt();

		System.out.print("Please enter your second exam grade " + Student1);
		Test2 = input.nextInt();
		
		System.out.print("Please enter your first exam grade " + Student2);

		Test3 = input.nextInt();

		System.out.print("Please enter your second exam grade " + Student2);
		Test4 = input.nextInt();

		
		double eScore = 0;

		int i= 1;
		
		System.out.println();
		System.out.println("Name:" + Student1  +"  Test1: " + Test1  + " Test2: " +  Test2 );
		System.out.println();
		System.out.println("Name:" + Student2  +"  Test1: " + Test3  + " Test2: " +  Test4 );
		
		}
		}
