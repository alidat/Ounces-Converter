# Ounces-Converter
Converts ounces to millilitres
//******************************************************************
// OunceConverter.java     Alida Thomas
// 
// This appication prompts the user to input a numerical amount of 
// ounces and then calculates and diplays the equivalent amount of 
// millilitres.
//******************************************************************

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
