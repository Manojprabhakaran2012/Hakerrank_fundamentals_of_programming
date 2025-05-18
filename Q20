import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner sc = new Scanner(System.in);

        int units = sc.nextInt();
        double amount = 0;
        if (units <= 200) {
            amount = units * 0.5;
        } else if (units <= 400) {
            amount = units * 0.65 + 100;
        } else if (units <= 600) {
            amount = units * 0.80 + 200;
        } else {
            amount = units * 1.25 + 425;
        }
        System.out.println("Rs." + (int)amount);
    }
}
