# else-if-ladder
Else if ladder program  in java
import java.util.*;
class Main 
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner (System.in);
        System.out.print("Enter n1 value:");
        int n1 = sc.nextInt();
        System.out.print("Enter n2 value:");
        int n2 = sc.nextInt();
        if(n1%10 > n2%10)
        {
            System.out.printf("%d %d",n2,n1);
        }
        else if (n2%10 > n1%10)
        {
            System.out.printf("%d %d",n1,n2);
        }
        else if (n1%10 == n2%10)
        {
            System.out.printf("%d %d",Math.max(n1,n2),Math.min(n1,n2));
        }
    }
}
