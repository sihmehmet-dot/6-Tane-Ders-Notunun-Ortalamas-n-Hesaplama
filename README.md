# 6-Tane-Ders-Notunun-Ortalamas-n-Hesaplama
Ortalama Hesaplama
import java.util.Scanner;
public class dersOrtalmaHesablama {
    static void main() {
     int fizik,mat,kimya,muzik,tarih,turkce;

        Scanner input = new Scanner(System.in);
         System.out.print("Matematik notunuzu girin: ");
         mat = input.nextInt();
         System.out.print("Kimya notunuzu girin: ");
         kimya = input.nextInt();
         System.out.print("Fizik notunuuzu girin: ");
         fizik = input.nextInt();
         System.out.print("Müzüik notunuzu girin: ");
        muzik = input.nextInt();
        System.out.print("Türkçe notunuzu girin: ");
        turkce = input.nextInt();
        System.out.print("Tarih notunuuzu girin: ");
        tarih= input.nextInt();
        int toplam =(mat+kimya+fizik+muzik+tarih+turkce);
        double Ortalama=(toplam/6);
        System.out.println("Ortalamanız :"+Ortalama);
        boolean kosul= Ortalama>=50;
        String str = kosul ? " Geçtin" : "Kaldın ";
        System.out.println(str);


    }
}
