# 2DChallenge

import java.util.Scanner;

public class Try2DChallenge {
    public static void main(String[] args) {
        int numbers[][] = new int[4][3];
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter values for the 2D array:");

        for (int i = 0; i < 4; i++) {
            for (int j = 0; j < 3; j++) {
                System.out.print("Enter value for numbers[" + i + "][" + j + "]: ");
                numbers[i][j] = scanner.nextInt();
            }
        }

        System.out.println("You entered the following values:");

        for (int i = 0; i < 4; i++) {
            for (int j = 0; j < 3; j++) {
                System.out.print(numbers[i][j] + " ");
            }
            System.out.println();
        }
    }
}
