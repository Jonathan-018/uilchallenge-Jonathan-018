/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package uilchallenge;

import java.io.File;
import java.io.FileNotFoundException;
import static java.lang.System.in;
import java.math.BigInteger;
import java.util.Scanner;

/**
 *
 * @author Poncejon9
 */
public class UilChallenge {

    /**
     * @param args the command line arguments
     * @throws java.io.FileNotFoundException
     */
    public static void main(String[] args) throws FileNotFoundException {
        int x;
        int y;
        int z;
        System.out.println("Enter two integers to calculate their sum, positive "
                + "difference, product, and quotient");
        Scanner in = new Scanner(new File("Input.txt"));
        x = in.nextInt();
        y = in.nextInt();
        z = x + y;
        System.out.println("Sum of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        BigInteger first;
        z = x - y;
        System.out.println("Difference of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x * y;
        System.out.println("Product of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x / y;
        System.out.println("Quotient of the integers = " + z);
  
        //new integers
        System.out.println("\nEnter two integers to calculate their sum, positive "
                + "difference, product, and quotient");
        x = in.nextInt();
        y = in.nextInt();
        z = x + y;
        System.out.println("Sum of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x - y;
        System.out.println("Difference of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x * y;
        System.out.println("Product of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x / y;
        System.out.println("Quotient of the integers = " + z);
        //new integers
        System.out.println("\nEnter two integers to calculate their sum, positive "
                + "difference, product, and quotient");
        x = in.nextInt();
        y = in.nextInt();
        z = x + y;
        System.out.println("Sum of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x - y;
        System.out.println("Difference of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x * y;
        System.out.println("Product of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x / y;
        System.out.println("Quotient of the integers = " + z);
        //new integers
        System.out.println("\nEnter two integers to calculate their sum, positive "
                + "difference, product, and quotient");
        x = in.nextInt();
        y = in.nextInt();
        z = x + y;
        System.out.println("Sum of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x - y;
        System.out.println("Difference of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x * y;
        System.out.println("Product of the integers = " + z);
        
        x = in.nextInt();
        y = in.nextInt();
        z = x / y;
        System.out.println("Quotient of the integers = " + z);

    }
    
    
}
