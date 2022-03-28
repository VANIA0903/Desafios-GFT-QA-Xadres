# Desafios-GFT-QA-
import java.util.Scanner;
public class Chess {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		int line = sc.nextInt();
		int column = sc.nextInt();
		
		int color = ((line+column)%2==0) ? 1 : 0;
		
		System.out.println(color);

		sc.close();
	}
}
