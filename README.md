import java.util.*;

public class Main{
    private static void printBinaryNumber(int number){
        if(number == 0) return;
        else{
            printBinaryNumber(number/2);
            System.out.print(number%2);
        }
    }
    public static void main(String[] args){
        for(int i = 1; i < 20; i ++){
            printBinaryNumber(i);            System.out.println();
        }
    }
}
