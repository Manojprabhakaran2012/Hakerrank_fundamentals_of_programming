import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner sc = new Scanner(System.in);

        int total = sc.nextInt();
        int benPercent = sc.nextInt();
        int blackbeardPercent = sc.nextInt();

        int benShare = (total * benPercent) / 100;
        int remaining = total - benShare;
        int blackbeardShare = (remaining * blackbeardPercent) / 100;
        remaining -= blackbeardShare;

        int eachPirateShare = remaining / 3;
        
        System.out.println(benShare);
        System.out.println(blackbeardShare);
        System.out.println(eachPirateShare);
    }
}
