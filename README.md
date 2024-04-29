# mess


import java.util.Scanner;

public class mess {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int X = scanner.nextInt();
        int Y = scanner.nextInt();

        int totalCost = 0;
        for (int i = 0; i < 7; i++) {
            if (i == 6) {
                totalCost += Y;
            } else {
                totalCost += X;
            }
        }

        System.out.println(totalCost);
    }
}
