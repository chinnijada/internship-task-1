import java.util.*;
class task1 {
    public static void main(String[] args) {
        Scanner sc = new Scanner (System.in);
        
        System.out.println("Enter the two integers:");
        int a = sc.nextInt();
        int b = sc.nextInt();
        System.out.println("Enter the floating point number:");
        float c = sc.nextFloat();
        System.out.println("Enter a single character:");
        char ch=sc.next().charAt(0);
        System.out.println("Single char:"+ch);
        System.out.println("Enter the boolean value:");
        boolean d = sc.nextBoolean();
        System.out.println("Enter the name :");
        String s = sc.next();
        System.out.println("Enter the integers:");
        int x = sc.nextInt();
        int y = sc.nextInt();
        int sum = x+y;
        int sub = x-y;
        int mul = x*y;
        System.out.println("Sum of X and Y is: "+sum);
        System.out.println("Sub of X and Y is: "+sub);
        System.out.println("Mul of X and Y is: "+mul);
      //  System.out.println("multiplying the floating point number by 2:");
        float f1 = c*2;
        System.out.println("floating point number multiplied by 2 is:"+f1);
        char ch1 = (char) (ch+1);
        System.out.println("Next character in the ASCII sequence after the entered character is:"+ch1);
        boolean orginalValue = (true);
        boolean oppositeValue = !orginalValue;
        System.out.println("Opposite value is:"+oppositeValue);
        System.out.println("Hello," + s);
    }
}
