# Project Name
This where my project description will go

## Code

```java
package additiongame1;
import java.util.Scanner;
public class additiongame1 {
	public static void main(String[] args) {
		
		 System.out.println("Hello Class!");
		
		// This is my master branch.
		// Outline for addition problem.
		
		int score = 0;
		int hardnessOfQuestion = 10;
		
		// Round 1
		//	Generate 2 random numbers
		int number1 = (int)(Math.random() * hardnessOfQuestion);
		 System.out.println("Number1 is :" + number1 );
		 
		
		int number2 = (int)(Math.random() * hardnessOfQuestion);
		
		 System.out.println("Number2 is :" + number2 );
		 
		
		// to keep track of the correct answer.
		int correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println
		("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please answer in integers only.");
		
		//  Read in their response
		Scanner input = new Scanner(System.in);
		int studentAnswer = input.nextInt();
		//  Check if the answer was correct
		//		IF correct
		if (studentAnswer == correctAnswer){
			//			Tell them it was correct
			System.out.println("Answer was correct");
			//			Give them points
			score += hardnessOfQuestion;
			System.out.println("Score is: " + score);
			//			Make the next question harder
			hardnessOfQuestion *= 10;	
			System.out.println("hardness is: " + hardnessOfQuestion);
		}
		//		IF not correct
		else{
			//			Tell them it was wrong
			System.out.println("Answer was not correct");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if(hardnessOfQuestion>10){
				hardnessOfQuestion /= 10;	
			
			}
		}
		System.out.println("End of round 1");
		// end of round 1
		
		// Round 2 (note: additional comments in round 1)
		//	Generate 2 random numbers
		number1 = (int)(Math.random() * hardnessOfQuestion);
		number2 = (int)(Math.random() * hardnessOfQuestion);

		
		// to keep track of the correct answer.
		correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println
		("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please answer in integers only.");
		
		//  Read in their response
		//Scanner input = new Scanner(System.in);
		studentAnswer = input.nextInt();
		//  Check if the answer was correct
		//		IF correct
		if (studentAnswer == correctAnswer){
			//			Tell them it was correct
			System.out.println("Answer was correct");
			//			Give them points
			score += hardnessOfQuestion;
			System.out.println("Score is: " + score);
			//			Make the next question harder
			hardnessOfQuestion *= 10;	
			System.out.println("hardness is: " + hardnessOfQuestion);
		}
		//		IF not correct
		else{
			//			Tell them it was wrong
			System.out.println("Answer was not correct");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if(hardnessOfQuestion>10){
				hardnessOfQuestion /= 10;	
			}
		}
		// end of round 2
		System.out.println("End of round 2");
		// Round 3 (note: additional comments in round 1)
		//	Generate 2 random numbers
		number1 = (int)(Math.random() * hardnessOfQuestion);
		number2 = (int)(Math.random() * hardnessOfQuestion);

		
		// to keep track of the correct answer.
		correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println
		("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please answer in integers only.");
		
		//  Read in their response
		//Scanner input = new Scanner(System.in);
		studentAnswer = input.nextInt();
		//  Check if the answer was correct
		//		IF correct
		if (studentAnswer == correctAnswer){
			//			Tell them it was correct
			System.out.println("Answer was correct");
			//			Give them points
			score += hardnessOfQuestion;
			System.out.println("Score is: " + score);
			//			Make the next question harder
			hardnessOfQuestion *= 10;	
			System.out.println("hardness is: " + hardnessOfQuestion);
		}
		//		IF not correct
		else{
			//			Tell them it was wrong
			System.out.println("Answer was not correct");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if(hardnessOfQuestion>10){
				hardnessOfQuestion /= 10;	
			}
		}
		// end of round 3
		System.out.println("End of round 3");
		// Round 4 (note: additional comments in round 1)
		//	Generate 2 random numbers
		number1 = (int)(Math.random() * hardnessOfQuestion);
		number2 = (int)(Math.random() * hardnessOfQuestion);

		
		// to keep track of the correct answer.
		correctAnswer = number1 + number2;
		
		//  Ask the user to add these two numbers together
		System.out.println
		("What integer is " + number1 + " + " + number2 + "?");
		System.out.println("Please answer in integers only.");
		
		//  Read in their response
		//Scanner input = new Scanner(System.in);
		studentAnswer = input.nextInt();
		//  Check if the answer was correct
		//		IF correct
		if (studentAnswer == correctAnswer){
			//			Tell them it was correct
			System.out.println("Answer was correct");
			//			Give them points
			score += hardnessOfQuestion;
			System.out.println("Score is: " + score);
			//			Make the next question harder
			hardnessOfQuestion *= 10;	
			System.out.println("hardness is: " + hardnessOfQuestion);
		}
		//		IF not correct
		else{
			//			Tell them it was wrong
			System.out.println("Answer was not correct");
			// 			Tell them the correct answer
			System.out.println("The correct answer was: " + correctAnswer);
			//			Do not give them points
			score += 0;
			//			Make the next question easier
			if(hardnessOfQuestion>10){
				hardnessOfQuestion /= 10;	
			}
		}
		// end of round 4
		System.out.println("End of round 4 and the end of the game");
	}
}
```

## Console Output

```
Hello Class!
Number1 is :8
Number2 is :5
What integer is 8 + 5?
Please answer in integers only.
13
Answer was correct
Score is: 10
hardness is: 100
End of round 1
What integer is 85 + 2?
Please answer in integers only.
```
## Summary
For this assignment, i learned that i could question and give points for correct answers
