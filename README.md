//# patterns
import java.util.*;
class Main
{
    public static void main(String []args)
    {
        Scanner s=new Scanner(System.in);
        int n=s.nextInt();
        if(n<0)
        n=-n;
        if(n>0)
        {
        for(int i=n;i>=1;i--)
        {
            for(int j=n;j>=1;j--)
            {
               if(i>=j)
               System.out.print(i);
               else
               System.out.print(j);
            }
            System.out.println();
        }
        }
        else
        System.out.println("InvaliD Input");
    }
}
