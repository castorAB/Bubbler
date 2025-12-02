// import static org.junit.jupiter.api.Assertions.assertEquals;

// import org.junit.jupiter.api.Test;

// @Test
// void addition() {
// assertEquals(2, 1 + 1);
// }

// Bubbler class
// Copyright 2025
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scnr = new Scanner(System.in);
        Bubbler bubbler = new Bubbler();
        char choice = 'a';

        System.out.println(
            "You've just happened upon a bubbler in the strange woods. How would you like to spend your time together?\n\n\nPerhaps you can tug the water spout rope and watch how the bubbler stirs a rise?\nMaybe take a sip of the miracle liquid that is interesting water (new substance)?\nMaybe a word shared in a word twice as valuable in a bush?\n\nEnter:\nt - To tug\nl - To lap it up\ns - To orate\n");

        while (choice != 'q') {
            choice = scnr.next().charAt(0);
            switch (choice) {
                case 't':
                    System.out.println("\nHow many times would you stretch the twine? Feeling strong?");
                    double numBlows = scnr.nextDouble();
                    bubbler.activateBlow(numBlows);
                    break;
                case 'l':
                    System.out.println("\nHow much would you like to lap up?");
                    break;
                case 's':
                    System.out.println("\nHow many words would you like to share?");
                    break;
                case 'q':
                    System.out.println(
                            "\nAs you walk away, you know that you are taking the chance you may never see this entity again. But you are okay with that. The possibility of return will not be zero. You will never be the same as you are this one moment.\n");
                    break;
                default:
                    System.out.println(
                            "\nThe machinated technology simply does not understand. Second attempts are allowed.");
            }
            if (choice != 'q') {
                System.out.println("You have been gifted the freedom of choice, what will you di with it?\n\nEnter:\nt - To tug\nl - To lap it up\ns - To orate\n");
            }
        }
    }
}
// can you see this????? yes
