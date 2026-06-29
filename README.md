import java.util.*;
public class main{
    public static void main(String args[]){
        Scanner in=new Scanner(System.in);
        int n=in.nextInt();
        int k=in.nextInt();
        int a[]=new int[n];
        for(int i=0;i<n;i++){
            a[i]=in.nextInt();
        }
        int c=0;
        int x=a[k-1];
        for(int i=0;i<n;i++){
            if(a[i]>=x && a[i]>0){
                c++;
            }
        }
        System.out.println(c);
    }
}