# Numbers
EasyWay
import java.util.Scanner;
public class Arrays {
    public static void main(String[] args) {
        int[] arr = new int[105];
        System.out.println("add text");
        for (int i = 0; i < arr.length; i++) {
            Scanner sc = new Scanner(System.in);
            System.out.println(i + ".write text:");
            arr[i] = sc.nextInt();
        }

        System.out.println("print the numbers:");
        for (int i = 0; i < arr.length; i++) {
            System.out.println(i + "." + arr[i]);
        }
    }
}
