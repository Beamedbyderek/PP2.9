# PP2.9

/* 

10/2/2022

 Derek Durand

Converts time to seconds

*/ 
import java.util.Scanner;

public class PP29 {

   
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.print("Input seconds: ");
        
        int seconds = in.nextInt();
        
        int S = seconds % 60;
        int H = seconds / 60;
        int M = H % 60;
        H = H / 60;
        
        System.out.print(H + ":" + M + ":" + S);
        System.out.print("\n");
    }
    
}
