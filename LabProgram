/*
*  Justin Blacksher
*  Created for class midterm
*  
*/


import java.util.Scanner;

public class LabProgram {
   public static void main(String[] args) {
      
      double mensTotal;          // The final total will be stored here
      double womensTotal;        // The final total will be stored here
      
      Scanner calCalc = new Scanner(System.in);       // Create a scanner 
      /*
      * Scanner Prompts
      */
      
      String subjectAge;                     // Text to use in prompt
      String subjectWeight;                  
      String subjectHeartRate;
      String subjectTime;        
      
      subjectAge = "Enter the age in years: ";
      subjectWeight = "Enter the weight in pounds: ";
      subjectHeartRate = "Enter the Heart Rate in beats per minute  (BPM): ";
      subjectTime = "Enter the lenght of time in minutes: ";
      
      /* Create the variables for the user input */
      
      int age;                // Age of the subject
      int weight;             // Weight of subject
      int heartRate;          // Heart Rate during activity
      int timeLapsed;         // The duration of the activity
      
      
      
      /* Create constants for the women
      *
      * Will contain the Calories constants, Weight constants, Heart Rate constants, Time divisor
      * These will be used in an array later
      */
      
      final double wAGE;                  // Hold the age constant
      final double wWEIGHT;               // Hold the weight constant
      final double wHEART;                // Hold the heart constant
      final double wTIME;                 // Hold the time divisor
      final double wSUBTRACT;             // Hold the subtraction constant
      
      
      /* Create constants for the men
      *
      * Will contain the Calories constants, Weight constants, Heart Rate constants, Time divisor
      * These will be used in an array later
      *
      */
      
      final double mAGE;                  // Hold the age constant
      final double mWEIGHT;               // Hold the weight constant
      final double mHEART;                // Hold the heart constant
      final double mTIME;                 // Hold the time divisor
      final double mSUBTRACT;             // Hold the subtraction constant
      
      /* Give the constants a value to use
      *  Women: AGE 0.074, Weight 0.05741, Heart Rate 0.4472, Const 20.4022, Time Divisor 4.184
      *  Men: AGE 0.2017, Weight 0.09036, Heart Rate 0.6309, Const 55.0969, Time Divisor 4.184
      */
      
      // Women
      wAGE = 0.074;
      wWEIGHT = 0.05741;
      wHEART = 0.4472;
      wSUBTRACT = 20.4022;
      wTIME = 4.184;
      
      // Men:
      mAGE = 0.2017;
      mWEIGHT = 0.09036;
      mHEART = 0.6309;
      mSUBTRACT = 55.0969;
      mTIME = 4.184;
      
      // Use the scanner to get input from the user
      // System.out.println(subjectAge);
      
      age = calCalc.nextInt();
      
      // System.out.println("Age: " + age);
      // System.out.println(subjectWeight);
      
      weight = calCalc.nextInt();
      
      // System.out.println("Age: " + age + " " + "Weight: " + weight);
      // System.out.println(subjectHeartRate);
      
      heartRate = calCalc.nextInt();
      
      // System.out.println("Age: " + age + " " + "Weight: " + weight + " " + "Heart Rate: " + heartRate);
      // System.out.println(subjectTime);
      
      timeLapsed = calCalc.nextInt();
      // System.out.println("Age: " + age + " " + "Weight: " + weight + " " + "Heart Rate: " + heartRate + " " + "Time Lapsed: " + timeLapsed);
      
      /* Make our calculations
      *
      */
      
      mensTotal = ((age * mAGE) + (weight * mWEIGHT) + (heartRate * mHEART) - mSUBTRACT) * timeLapsed / mTIME;
      womensTotal = ((age * wAGE) - (weight * wWEIGHT) + (heartRate * wHEART) - wSUBTRACT) * timeLapsed / wTIME;
      
      // Output the totals
      System.out.print("Women: ");
      System.out.printf("%.2f", womensTotal);
      System.out.print(" Calories");
      System.out.println();
      System.out.print("Men: ");
      System.out.printf("%.2f", mensTotal);
      System.out.print(" Calories");
   }
} 
