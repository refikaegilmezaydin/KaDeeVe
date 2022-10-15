# KaDeeVe
18% KDV hesaplayan kod
package Deneme;
 import java.util.Scanner;
public class Kadeeve {
    public static void main(String[] args) {
        System.out.println("Fatura tutarını giriniz:");
        Scanner kdv= new Scanner(System.in);
        double a,b,c;
        a = kdv.nextDouble();
        System.out.println("Fatura matrahı:" +a );
        b = (a*18)/100;
        System.out.println("Matrahı girilen faturanın KDV tutarı:" + b);
        c = a+b;
        System.out.println("KDV dahil toplam fatura tutarı:" + c);
        }
        www.patika.dev
