import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner sc = new Scanner(System.in);

        float principal = sc.nextFloat();
        float rate = sc.nextFloat();
        float time = sc.nextFloat();

        float interest = (principal * rate * time) / 100;
        float totalAmount = principal + interest;
        float discount = (2 * interest) / 100;
        float finalAmount = totalAmount - discount;

        System.out.printf("%.2f\n%.2f\n%.2f\n%.2f\n", interest, totalAmount, discount, finalAmount);
    }
}
