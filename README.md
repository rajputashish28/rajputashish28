import java.util.Scanner;
class Main{
    public static void main (String[]args){
        Scanner sc= new Scanner (System.in);
        System.out.print("Enter the First number:");
        int a =sc.nextInt();
        System.out.print("Enter the Second number:");
        int b =sc.nextInt();
        
        add(a,b);
        sub(a,b);
        mul(a,b);
        div(a,b);
    }
    
    public static void add(int a,int b) {
        int c=a+b; 
        System.out.println("add: " +c);
    }
    
    public static void sub(int a,int b){
        int c=a-b;
        System.out.println("Sub:" +c);
    }
    public static void mul(int a,int b){
        int c=a*b;
        System.out.println("mul:" + c);
    }
    public static void div(int a,int b){
        int c=a/b;
        System.out.println("div:"  +c);
    }
}
