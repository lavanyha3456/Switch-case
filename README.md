# Switch-case
package pkgswitch.pkgcase;
import java.util.Scanner;
public class SWITCHCASE {

   static void main(String[] args) {
        Scanner ac=new Scanner(System.in);
        int number;
        System.out.println("enter a number");
        number=ac.nextInt();
        switch (number){
            case 29:
                System.out.println("the size is small");
                break;
            case 42:
                System.out.println("the size is medium");
                break;
            case 44:
                System.out.println("the size is large");
                break;
            case 48:
                System.out.println("the size is extra large");
                break;
            default:
                System.out.println("the size is unknown");
                break;
        }
    }
    
}



run:
odd and even numbers from 1 to 10:
1is odd
2is even
3is odd
4is even
5is odd
6is even
7is odd
8is even
9is odd
10is even
BUILD SUCCESSFUL (total time: 0 seconds)
