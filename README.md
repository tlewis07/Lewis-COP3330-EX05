# Lewis-COP3330-EX05
/*
 *  UCF COP3330 Summer 2021 Assignment 1 Solution
 *  Copyright 2021 TRISTAN LEWIS
 */
 
package com.example;

public class Main {

    public static void main(String[] args) {

        int Firstnumber = 10;
        int Secondnumber = 5;

        System.out.println("What is the first number? " + Firstnumber);
        System.out.println("What is the second number? " + Secondnumber);

        int sum = Firstnumber + Secondnumber;
        int difference = Firstnumber - Secondnumber;
        int multiplication = Firstnumber * Secondnumber;
        int quotient = Firstnumber / Secondnumber;


        System.out.println(Firstnumber + " + " + Secondnumber + " = " + sum);
        System.out.println(Firstnumber + " - " + Secondnumber + " = " + difference);
        System.out.println(Firstnumber + " * " + Secondnumber + " = " + multiplication);
        System.out.println(Firstnumber + " / " + Secondnumber + " = " + quotient);
    }
}
