# ACD_JAVAB_Session_7_Assignment_1_Main
ACD_JAVAB_Session_7_Assignment_1_Main


package exceptionHandling;

public class ArrayIndexOutOfBoundsExceptionClass {

	public static void main(String[] args) {
		int a[]=new int[5];
		a[1]=10;
		System.out.println("first step completed : ");
		try{
			a[9]=50;
			System.out.println("second step completed : ");
		}
		catch(ArrayIndexOutOfBoundsException e)
		{System.out.println("ArrayIndexOutOfBounds Exception Handled: "+e);}  
	}

}
