# java-test-0003-final-15325-sushant
Final Project Assignment - This repository contains the complete final project code and documentation.
public class Main {
    public static void main(String[] args) {
        for (int i = 1; i <= 6; i++) {
            for (int j = 1; j <= i; j++) {
                int value = (i + j) % 2;

                System.out.print(value);
                if (j < i) {
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
    }
}
