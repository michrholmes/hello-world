# hello-world
First Repository

// Hello World! My name is Michelle. I am a computer science student that is working on honing my 
// coding skills.
// Currently I am coding in Java but have some C++ basics as well. 
/
// The following program was made to introduce myself. 
//***********************************************************************************************

import java.util.Scanner;

public class Me
{
public static void main (String[] args)
	{
		String me, name;
  
		Scanner scan = new Scanner(System.in);
  
		System.out.println("What is your name? ");
		name = scan.nextLine();
  
		me = "Michelle";
		System.out.println("Hello " + name + " my name is " + me + " and I am new to GitHub.");
  
		System.out.println("I look forward to working on some projects with you " + name + ".");
	}

}
