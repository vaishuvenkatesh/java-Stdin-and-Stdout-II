/*java-Stdin-and-Stdout-II
Sample Input:
42
3.1415
Welcome to HackerRank's Java tutorials!
Sample Output:
String: Welcome to HackerRank's Java tutorials!
Double: 3.1415
Int: 42
*/

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
       
        int myNum = scan.nextInt();
        double myDouble =scan.nextDouble();
        scan.nextLine(); 
        String txt=scan.nextLine();
        
        System.out.println("String: " + txt);
        System.out.println("Double: " + myDouble);
        System.out.println("Int: " + myNum);
        scan.close();
    }
}

//output:
Input (stdin)
42
3.1415
Welcome to HackerRank's Java tutorials!
Your Output (stdout)
String: Welcome to HackerRank's Java tutorials!
Double: 3.1415
Int: 42
Expected Output
String: Welcome to HackerRank's Java tutorials!
Double: 3.1415
Int: 42
