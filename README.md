# Question-4
import java.util.Scanner;

public class MaxNumber {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        int maxNum;
        switch (num1 > num2 ? 1 : (num1 < num2 ? 2 : 0)) {
            case 1:
                max = num1;
                break;
            case 2:
                max = num2;
                break;
            default:
                System.out.println("Both numbers are equal.");
                return;
        }

        System.out.println("The maximum number is: " + maxNumber);
    }
}
