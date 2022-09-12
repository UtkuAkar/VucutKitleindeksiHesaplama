# VucutKitleindeksiHesaplama
VucutKitleindeksiHesaplama

import java.util.Scanner;

public class daire {
    public static void main(String[] args) {

        double kilo,boy,index;


        Scanner input=new Scanner(System.in);

        System.out.println("Lutfen boyunuz (metre cinsinde) giriniz: ");
        boy =input.nextInt();

        System.out.println("Kilonuzu girin: ");
        kilo =input.nextInt();


        index=kilo/(boy*boy);
        System.out.println("Vucut İndixi : " +index);


    }
}
