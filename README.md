# Programacao-de-Solucoes-Computacionais-Ex05-Lista05
Faça um programa com uma função chamada somaImposto. A função possui dois parâmetros formais: taxaImposto, que é a quantia de imposto sobre vendas expressa em porcentagem e custo, que é o custo de um item antes do imposto. A função “altera” o valor de custo para incluir o imposto sobre vendas.
import java.util.Scanner;

public class Ex05 {
    public static void main(String[] args) throws Exception {
        Scanner sc = new Scanner(System.in);
        System.out.println("Informe o valor do produto: ");
        double valorProd = sc.nextDouble();
        System.out.println("Informe o valor do imposto do produto declarado: ");
        double valorImp = sc.nextDouble();
        sc.close();
        double valorTotal = somaTotal(valorProd, valorImp);
        System.out.println("O valor total do produto é: " + valorTotal);
    }

    public static double somaTotal(double valorProd, double valorImp) {

        return valorProd + valorImp;
    }
}
