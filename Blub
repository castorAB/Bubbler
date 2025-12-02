// Bubbler class
//Copyright 2025
import java.util.Scanner;
import java.util.Random;

public class Bubbler {

  private double maxWidth = 100; //width of console page

  // activateBlow method
  public void activateBlow(double howManyBlows) {

    for (double b = howManyBlows; b > 0; b--) {
      Random r = new Random();
      double bub = 0;

      // Bubbles get more spread out the higher up they are
      if (b > maxWidth / 1.5) {
        bub = r.nextDouble((maxWidth));
      } else if (b > maxWidth / 2) {
        bub = r.nextDouble((maxWidth / 2));
      } else if (b > maxWidth / 4) {
        bub = r.nextDouble((maxWidth / 4));
      } else if (b > maxWidth / 6) {
        bub = r.nextDouble((maxWidth / 6));
      } else if (b > maxWidth / 8) {
        bub = r.nextDouble((maxWidth / 8));
      } else if (b > maxWidth / 10) {
        bub = r.nextDouble((maxWidth / 10));
      } else {
        bub = r.nextDouble((maxWidth / 15));
      }

      for (int i = 0; i < bub; i++) {
        System.out.print(' ');
      }
      System.out.print("o\n");
    }
    System.out.print("        o            ****    \n                 *****   *** \n        o       **         **\n          .     *  .     .  *\n    .           *           *\n      .         **    O    **\n     *           ***     ***\n  ┌─┐               ******* \n  └─┘                 **\n┌└┘──────────┐    *******  \n│            │ ****   ***\n│         O  │        * * \n│ │ H2O │    │      **  *    \n│            │     **   *    \n│            │  ****    *    \n│            │          *    \n│            │          **   \n│            │         ***   \n│            │        ** *   \n│            │        *  **  \n│            │        *   *  \n│            │       **   *  \n└────────────┘       **  **  \n                     *   * \n");

    System.out.println("Would you like to blow again? (y or n)");
    Scanner scnr = new Scanner(System.in);
    char blowChoice = scnr.next().charAt(0);
    if (blowChoice == 'y') {
      System.out.println("How many times would you like to blow?");
      howManyBlows = scnr.nextDouble();
      activateBlow(howManyBlows);
    }
    else
      System.out.println("You decide to walk away from the bubbler.");
  }

  public void speak() {

  }
}
