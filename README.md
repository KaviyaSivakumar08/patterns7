# patterns7
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        for (int row=a;row>=1;row--,System.out.println())
            for(int col=row;col>=1;col--){
                System.out.print(col);
            }
    }
}
