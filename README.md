# FIBONACCI-SERIES-IN-JAVA
import java.util.Scanner;
public class Main
{
	public static void main(String[] args)
	{
	    Scanner sc=new Scanner(System.in);
	    int a=0,b=1,i,c=0;
		
		System.out.println("FIBONACCI SERIES");
	    System.out.print(a+" "+b+" ");
	    for(i=1;i<=10;i++)
	    {
	        c=a+b;
	        System.out.print(c+" ");
	        a=b;
	        b=c;
	    }
	    
	    
	}
}
