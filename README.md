# project18
import java.io.*;
import java.util.*;
public class Amstrong
{
  public static void main(String args[])
  {
    Scanner sc=new Scanner(System.in);
    int n,a,temp,b=0;
    n=sc.nextInt();
    temp=n;
    while(n>0)
    {
      a=n%10;
      n=n/10;
      b=b+(a*a*a);
    }
    if(temp==b)
    {
      System.out.println("AmstrongNumber");
    }
    else
    {
      System.out.println("Not an Amstrong number");
    }
  }
}
