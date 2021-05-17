# StarPatternJavaProgramme
import java.util.Scanner;
public class Star
{
     public static void main(String[] args)
        {
            Scanner sc = new Scanner(System.in);
 
            System.out.println("Enter the number of rows: ");
 
            int n = sc.nextInt();
             
            for (int i=1; i<= n; i++)
            {
                for (int j = i; j < n; j++) {
                    System.out.print(" ");
                }   
                for (int k = 1; k <= (2*i -1) ;k++) {
                    if( k==1 || i == n || k==(2*i-1)) {
                        System.out.print("*");
                    }
                    else {
                        System.out.print(" ");
                    }
                }
                System.out.println("");
            }
            sc.close();
        }
    }
