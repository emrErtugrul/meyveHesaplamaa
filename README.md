# meyveHesaplamaa

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        double a,e,d,m,p,toplam,A,E,D,M,P;
        
        double armut =2.14 ,elma = 3.67 , domates =1.11, muz=0.95 , patlican = 5.00 ;

        Scanner inu = new Scanner(System.in);

        System.out.print("Armut Kaç Kilo ? : ");
        a = inu.nextDouble();
        A=a*armut;

        System.out.print("Elma Kaç Kilo ? : ");
        e = inu.nextDouble();
        E=e*elma;

        System.out.print("Domates Kaç Kilo ? : ");
        d = inu.nextDouble();
        D=d*domates;

        System.out.print("Muz Kaç Kilo ? : ");
        m = inu.nextDouble();
        M=m*muz;

        System.out.print("Patlıcan Kaç Kilo ? : ");
        p = inu.nextDouble();
        P=p*patlican;

        toplam=A+E+D+M+P;
        System.out.print("Toplam Tutar: "+toplam);
        System.out.print(" Tl ");

    }

}
