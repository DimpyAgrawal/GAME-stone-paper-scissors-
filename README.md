// GAME-stone-paper-scissors-
//Making a game called stone paper scissors using java.

import java.util.Random;                                       // 0 for Stone 
import java.util.Scanner;                                      // 1 for paper 
public class Main                                              // 2 or scissors
{
	public static void main(String[] args) {
	System.out.println("Enter Number between 0 to 3, 0 for Stone, 1 for paper, 2 or scissors");
	Scanner sc=new Scanner(System.in);
	int a= sc.nextInt();
	System.out.println(a);
	Random rand= new Random();
	int b=(rand.nextInt(3));
	System.out.println(b);
	if(a>2)
	    System.out.println("Invalid Number.");
	    if(a==0 && b==0)
	        System.out.println("Draw");
	    else if(a==0 && b==1)
	        System.out.println("You Losses");
	    else if(a==0 && b==2)
	        System.out.println("You Win");
	    else if(a==1 && b==1)
	        System.out.println("Draw");
	   else if(a==1 && b==0)
	        System.out.println("You Win");
	   else if(a==1 && b==2)
	        System.out.println("You Losses");
	   if(a==2 && b==2)
	        System.out.println("Draw");
	   else if(a==2 && b==0)
	        System.out.println("You Losses");
	   else if(a==2 && b==1)
	        System.out.println("You Win");
	    }
}
