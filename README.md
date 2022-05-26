# UsluSayiHesaplama

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        int n,k;
        int sonuc=1;

        Scanner input = new Scanner(System.in);
        System.out.println("Üssü alınacak sayıyı giriniz: ");
        n = input.nextInt();
        System.out.println("Üs olacak sayıyı  giriniz: ");
        k = input.nextInt();

        for (int i = 1;i<=k;i++){
            sonuc=sonuc*n;
            }
        System.out.println(sonuc);

    }
}
