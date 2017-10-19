package okan6;
import java.util.Scanner;
public class okan66 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int toplam =0, girdi;
		int sistemyarat;
		sistemyarat = (int)(Math.random() * 101);
		Scanner input = new Scanner(System.in);
		System.out.println(sistemyarat + "toplamak istediğiniz sayıyı girin");
		girdi = input.nextInt();
		while (girdi  >0){
			toplam = girdi + toplam + sistemyarat;
			sistemyarat = (int)(Math.random() * 101);
			System.out.println(sistemyarat+ "toplamak istediğiniz sayıyı girin");
			girdi = input.nextInt();
		}
		System.out.println("toplam sayi" + toplam);

	}

}
