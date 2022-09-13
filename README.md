# Exercicio-precifica-o
Esse exercicio pede para que crie um algoritmo que receba o preço venda e custo e mostre o lucro/prejuizo de venda do produto

import java.util.Scanner;
public class principal { public static void main (String[] args) {

    String nomeProduto;
    float precoCusto;
    float precoVenda;

    float totalCusto = 0.0f;
    float totalVenda = 0.0f;

    Scanner leitor = new Scanner (System.in);

    int i = 0; // essa variavel ficou fora da estrutura for poque ela sera usada dentro do main para a conclusão do
    //codigo//
    for (; i < 3; i ++);

    System.out.println("Digite o nomeo do produto");
    nomeProduto = leitor.next();

    System.out.println("Digite o preço de custo do produto");
    precoCusto = leitor.nextFloat();

    System.out.println("Digite o preço de venda do produto");
    precoVenda = leitor.nextFloat();

    totalCusto = totalCusto + precoCusto;
    totalVenda = totalVenda + precoVenda;

    if ( precoCusto == precoVenda) {
        System.out.println(" Houve empate entre preço custo e preço venda");
    } else{
        if (precoCusto > precoVenda) {
            System.out.println("Houve prejuizo");
        } else{
            System.out.println("lucro");
        }

    }   System.out.println(nomeProduto + " preço de custo = " + precoCusto + " preço de venda = " + precoVenda);
        System.out.println("A media do prço de venda é de: " + totalVenda);



}

}
