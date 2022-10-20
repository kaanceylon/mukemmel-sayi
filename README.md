# mukemmel-sayi

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        int number, toplam =0;

        System.out.print("bir sayı giriniz :");
        number = input.nextInt();

        for (int i = 1; i < number; i++){
            if ( number % i == 0){
                toplam+=i;

            }

        }
        if (number == toplam){
            System.out.print( number +  "Mükemmel bir sayıdır.");

        }else{
            System.out.print( number +  " mükemmel bir sayı değildir :");

        }


    }
}
































