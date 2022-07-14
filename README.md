# Harmonik_sayi.java
www.patika.dev Harmonik sayi



        import java.util.Scanner;

        public class harmonik {
        public static void main(String[] args) {
        int sayi;
        double n,sum=0;
        System.out.println("Lutfen sayi giriniz");
        Scanner input = new Scanner(System.in);
        sayi = input.nextInt();
        for (n = 1; n <= sayi; n++) {
            sum +=1 / n;
        }
        System.out.println("toplam: " + sum);
    }
}
