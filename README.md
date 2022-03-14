# Lab-06
package com.example.lab06;

import java.util.Scanner;

public class AddNum {
    public static void main(String[] args) {
        Scanner scnr = new Scanner(System.in);

        System.out.println("first number:");
        int firstNum = scnr.nextInt();
        System.out.println("second number:");
        int secondNum = scnr.nextInt();

        System.out.println(firstNum - secondNum);
    }
}
