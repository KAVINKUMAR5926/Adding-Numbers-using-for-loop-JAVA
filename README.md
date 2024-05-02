# Adding-Numbers-using-for-loop-JAVA
import java.util.Scanner;
public class Main
{
    public static void main(String arg[]){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int sum=0;
        for(; n>0; sum+=n%10, n/=10);
        System.out.println(sum);
        
    }
}
