import java.util.Scanner;

public class codingexercise {

	public static void main(String[] args) {
		
		 Scanner sc = new Scanner(System.in);
	      System.out.println("Enter a number :");
	   
	      int n = sc.nextInt();
	      
		    if (n % 3 == 0) {
		      if (n % 5 == 0) { 
		    	  System.out.print(n +"FizzBuzz");
		      }
		      else{
		    	  System.out.print(n +"Fizz"); 
		      }
		    }
		      else if(n % 5 == 0) {
		    	  System.out.print(n +"Buzz"); 
		      }
		    
		    else {
		    	System.out.print(n +"invalid item");
		    }
		 
	}

}
