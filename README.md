# Zaky-soleh-wirawan
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        double Nilai1;
        double Nilai2;
        double hasil;

        Scanner keyboard = new Scanner(System.in);

        System.out.print("Input angka-1: ");
        Nilai1 = keyboard.nextDouble();
        System.out.print("Input angka-2: ");
        Nilai2 = keyboard.nextDouble();

        // penjumlahan
        hasil = Nilai1 + Nilai2;
        System.out.println("Hasil Penjumlahan = " + hasil);

        System.out.print("Input angka-1: ");
        Nilai1 = keyboard.nextDouble();
        System.out.print("Input angka-2: ");
        Nilai2 = keyboard.nextDouble();

        // pengurangan
        hasil = Nilai1 - Nilai2;
        System.out.println("Hasil Pengurangan = " + hasil);

        System.out.print("Input angka-1: ");
        Nilai1 = keyboard.nextDouble();
        System.out.print("Input angka-2: ");
        Nilai2 = keyboard.nextDouble();

        // perkalian
        hasil = Nilai1 * Nilai2;
        System.out.println("Hasil Perkalian = " + hasil);

        System.out.print("Input angka-1: ");
        Nilai1 = keyboard.nextDouble();
        System.out.print("Input angka-2: ");
        Nilai2 = keyboard.nextDouble();

        // Pembagian
        hasil = Nilai1 / Nilai2;
        System.out.println("Hasil Pembagian = " + hasil);

        System.out.print("Input angka-1: ");
        Nilai1 = keyboard.nextDouble();
        System.out.print("Input angka-2: ");
        Nilai2 = keyboard.nextDouble();

        // Sisa Bagi
        hasil = Nilai1 % Nilai2;
        System.out.println("Hasil Sisa Bagi = " + hasil);
        
        keyboard.close(); // optional, for closing the Scanner
    }
}
