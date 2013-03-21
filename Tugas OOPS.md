Tugas-OOPS
==========
Exercise 1
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

class Geometrical_Shapes
{
  double No_of_coordinates;
	double Area;
	string Color;

	public void Create()
	{
	Console.WriteLine("Enter Number of coordinates: ");
	No_of_coordinates=Convert.ToDouble(Console.ReadLine());
	Console.WriteLine("Enter the Area: ");
	Area=Convert.ToDouble(Console.ReadLine());
	Console.WriteLine("Enter the Color: ");
	Color=Console.ReadLine();
	
	}
	public void Display()
	{
	Console.WriteLine("THIS IS WHAT YOU ENTERED: \n");
	Console.Write("Number of coordinates: ");
	Console.WriteLine(No_of_coordinates);
	Console.Write("Area: ");
	Console.WriteLine(Area);
	Console.Write("Color: ");
	Console.WriteLine(Color);
	}
}
class classy
{
	static void Main(string[] args)
	{
	Geometrical_Shapes Small_rectangle= new Geometrical_Shapes();
	Small_rectangle.Create();
	Small_rectangle.Display();
	Console.ReadLine();

	}
}

Exercise 2
using System;
class GameDetails
	{
		string Fname;
		string Lname;
		int NoOfPlayers;
		int Level;
		
			public void Accept_game_details()
			 {
			
			Console.WriteLine("Enter your first name:");
			Fname=Console.ReadLine();
			Console.WriteLine("Enter your last name:");
			Lname=Console.ReadLine();
			Console.WriteLine("Enter number of players:");
			NoOfPlayers= Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("Enter complexity level number:");
			Level=Convert.ToInt32(Console.ReadLine());
		}
		public void Display_game_details()
		{
			Console.WriteLine("\nThe details entered are as follows:");
			   Console.Write("First name: ");
			Console.WriteLine(Fname);
			   Console.Write("Last name: ");
			Console.WriteLine(Lname);
			   Console.Write("Number of players:");
			Console.WriteLine(NoOfPlayers);
			   Console.Write("Level:");
			Console.WriteLine(Level);
		}
}
class My
{
			static void Main(string[] args)
			{
			GameDetails Bingo= new GameDetails();
			Bingo.Accept_game_details();
			Bingo.Display_game_details();
			}
}
