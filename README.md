public class test{
    public static void main(String[] args)
    {
        int i=1;
        j=1;
        muti=0;
        for(i=1;i<10;i++)
        {
            for(j=1;j<=i;j++)
            {
                muti=i*j;
                System.out.print("j"+"*"+"i"+"="+"muti");
            }
            System.out.print("\n");
        }
        
    }
}
public class test{
    public static void main(String[] args)
    {
        int i=1;
        double temp=0;
       double sum=0;
        for(i=1;i<100;i++)
        {
           temp=double(1/i)*((-1)^(i+1));
           sum+=temp;
            System.out.print("%f",sum);
        }
        
    }
}
public class test{
    public static void main(String[] args)
    {
        int i=1;
        int count=0;
        for(i=1;i<100;i++)
        {
            if(i%10==9)
            {
                count++;
            }
            if(i/10==9)
            {
                count++;
            }
            System.out.print("%d",count);
        }
        
    }
}
public class test{
    public static void main(String[] args)
    {
        int i=1,a,b,c;
        for(i=0;i<=999;i++)
        {
           a=i%10;
           b=i/10%10;
           c=i/100;
           if(pow(a,3)+pow(b,3)+pow(c,3)==i)
           {
              System.out.println(i);
           }
          
        }
        
    }
}


