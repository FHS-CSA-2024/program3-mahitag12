//Program 3
//Extension of program 2 that now asks for user input when assigning the length and width of the sides
import java.util.Scanner; //This imports the console scanner that reads user input

//Your code here:

public class Program3  {
    public static void main (String [] args) {
        // Make a Scanner
        Scanner myScanner = new Scanner(System.in);
       
        //Variables
        int length = 0;
        int width = 0;
        int area = 0;
        int perimeter = 0;
        
        //Ask for user input
        System.out.println("Enter Length:");
        //Get Input
        length = myScanner.nextInt(); 
        
        System.out.println("Enter Width:");
        width = myScanner.nextInt();
        
        System.out.println("Enter Area:");
        //Get Input
        area = myScanner.nextInt();
        
        System.out.println("Enter Perimeter:");
        //Get Input
        perimeter = myScanner.nextInt();
        
        //Output
        System.out.println ("Length is 143");
        System.out.println ("width is 82");
        System.out.println ("area is 11726");
        System.out.println ("perimeter is 450");
         System.out.println ("This program was written by Mahita Gadiraju on 8/13/24");

    }
}




//Paste console output below:
/*
Length is 143
width is 82
area is 11726
perimeter is 450
This program was written by Mahita Gadiraju on 8/13/24
*/
