package porcentagem;

import java.text.DecimalFormat;
import java.util.Scanner;

public class CalculodaPorcentagem {

	public static void main(String[] args) {
		double x, y, valor;
		Scanner teclado = new Scanner(System.in);
		DecimalFormat formatador = new DecimalFormat("#0.00");
		System.out.println("Regra de 3");
		System.out.println("x% de y = valor");
		System.out.print("Digite o valor de x: ");
		x = teclado.nextDouble();
		System.out.print("Digite o valor de y: ");
		y = teclado.nextDouble();
		valor = (x * y) / 100;
		System.out.println(x + "% de " + y + " = " + formatador.format(valor));

		teclado.close();

	}

}
