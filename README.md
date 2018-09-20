# NumberstoWords-between-0-10
NumberstoWords between 0-10
import java.util.Scanner;

public class NumberToWords {
   public static void main(String[] args) {
	 
	    Scanner scan = new Scanner(System.in);
	    System.out.println("Enter please any number from 0 to 10");
	    int inputNumber = scan.nextInt();
	        
	    switch(inputNumber) {
	    case 0:
	    	System.out.println("zero");
	    	break;
	    case 1:
	    	System.out.println("one");
	    	break;
	    case 2:
	    	System.out.println("two");
	    	break;
	    case 3:
	    	System.out.println("three");
	    	break;
	    case 4:
	    	System.out.println("four");
	    	break;
	    case 5:
	    	System.out.println("five");
	    	break;
	    case 6:
	    	System.out.println("six");
	    	break;
	    case 7:
	    	System.out.println("seven");
	    	break;
	    case 8:
	    	System.out.println("eight");
	    	break;
	    case 9:
	    	System.out.println("nine");
	    	break;
	    case 10:
	    	System.out.println("ten");
	    	break;
	    	default :
	    		System.out.println("Invalid number");
		    	System.out.println("Input number should be from 0 to 10");
	    }
	    scan.close();
}
}
