import java.util.Scanner;

public class Boom {
	public static void main(String args[]) {
		
		Scanner prim = new Scanner(System.in);
		Scanner seg = new Scanner(System.in);
		Scanner pos = new Scanner(System.in);
		System.out.println("Primer Plato:");
		System.out.println("-Ensalada");
		System.out.println("-Croquetas");
		System.out.println("-Arroz");
		
		System.out.println("¿Qué quieres de primer plato?");
		String plat1 = prim.nextLine();

		System.out.println("Segundo Plato:");
		System.out.println("-Merluza");
		System.out.println("-Chuleta");
		System.out.println("-Albóndigas");
		
		System.out.println("¿Qué quieres de segundo plato?");
		String plat2 = seg.nextLine();
		
		System.out.println("Postre:");
		System.out.println("-Mousse de chocolate");
		System.out.println("-Helado");
		System.out.println("-Flán");
		
		System.out.println("¿Qué quieres de postre?");
		String plat3 = pos.nextLine();
		System.out.print("Entonces quieres ");
		System.out.print(plat1 + " , " + plat2 + " y " + plat3);
				
				
	}
	
}
