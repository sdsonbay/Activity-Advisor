# Activity-Advisor

import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int heat;

        Scanner scanner = new Scanner(System.in);

        System.out.println("Sıcaklık giriniz: ");
        heat = scanner.nextInt();

        if(heat > 25){
            System.out.println("Yüzme");
        }
        else if(heat > 15){
            System.out.println("Piknik");
        }
        else if(heat > 5){
            System.out.println("Sinema");
        }
        else{
            System.out.println("Kayak");
        }

    }
}
