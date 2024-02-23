# Day4-with-java

Today is 4th day. Every day i am learning new concept. Likewise today I learned how to write a program for printing tables in java. We can write this program in two ways. They are 
 without using methods and using methods.

 Here is the program to print tables by using method:
 
import java.util.Scanner;
public class Day4 {
    static void printTables(int n)
    {
        for(int i=1 ; i<=10 ; i++) {
            System.out.println(n + "x" + i + "=" + n*i);
            
        }
    }
    
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        printTables(n);
    }
}

sample input: 3

output: 
3x1=3
3x2=6
3x3=9
3x4=12
3x5=15
3x6=18
3x7=21
3x8=24
3x9=27
3x10=30


 
