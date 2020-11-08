import java.util.Scanner;
class quadraticequation
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        double a,b,c,r1,r2,d;
        System.out.println("Enter the values of a,b,c");
        a=sc.nextDouble();
        b=sc.nextDouble();
        c=sc.nextDouble();
        d=(b*b)-(4*a*c);
        if(d<0)
            System.out.println("No real roots for the given quadratic equation");
        else if(d>=0)
        {
            r1=(-b+(Math.sqrt(d)))/(2*a);
            r2=(-b-(Math.sqrt(d)))/(2*a);
            if(d==0)
            {
                System.out.println("Roots are real and equal");
                System.out.printf("The roots are: %.2f and %.2f",r1,r2);
            }
            else
            {
                System.out.println("Roots are real and unequal");
                System.out.printf("The roots are: %.2f and %.2f",r1,r2);
            }
        }
    }
}
