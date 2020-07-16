# Ounces-Converter
Converts ounces to millilitres

import java.util.Scanner;

public class OunceCoverter
{
	
	public static void main(String[] args)
	{
		double ounces;

		Scanner scan = new Scanner(System.in);

		System.out.print("Welcome to the ounce to millilitre converter!");

		//prompt the user and accept input of ounces.
		System.out.println("Please enter number of ounces: ");
		ounces = scan.nextDouble();

		//calculate millilitre equivalent of ounces.
		double mill = ounce * 29.5735;

		//display results.
		System.out.println("Millilitres: ");



	}
}
