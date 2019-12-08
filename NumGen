/*
-So basically im creating a text file
that has numbers of how many fox squirrels is spotted
-Have a random number generator that stops at 10,
Where 10 is a fox squirrel
-This code will run 1,000
times for 1,000 trials,
-count how many times 10 is seen on the program */


import java.util.Random;
import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
  
//declaring variables
    int userInput = 0;
    Random randomNumber = new Random();
    int animalSeen = 0;
    int length = 0;
    //int squirrelSeen = 0;
//prompt user input
		Scanner in = new Scanner (System.in);
		System.out.println("#1-9 represents animals seen");
		System.out.println("#10 represents fox squirrels");
    System.out.println("Please insert how many trials you need (min :11, max: 1000)");
    userInput = in.nextInt();
//if statements and while statement
    for (int i = 1; i <= userInput; i++) {
       animalSeen = randomNumber.nextInt(11); //1-10
       while (userInput <= 10 && userInput <= 1000){
          animalSeen = randomNumber.nextInt(5);
          //squirrelSeen++;
}
System.out.println(animalSeen);
    if (animalSeen == 10) {
      System.out.println("Squirrel");
    }
    }
  }
