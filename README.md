# daire alanı ve çevresi hesaplama

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        double r, alan, cevre, a;
        double pi = 3.14;
        Scanner input = new Scanner(System.in);
        System.out.println("Dairenin yarıçapını giriniz: ");
        r = input.nextDouble();
        System.out.println("Merkez açı ölçüsünü giriniz: ");
        a =input.nextDouble();
        alan = (pi*(r*r)*a)/360;
        cevre = 2*pi*r;
        System.out.println("Dairenin alanı: " +alan);
        System.out.println("Dairenin çevresi " +cevre);

    }
}
