# Aula02_03

Escreva um programa em JAVA que solicite ao usuário 2 números inteiros (um de cada vez), armazene os valores em variáveis e depois mostre a soma dos dois em uma mensagem.

~~~
import javax.swing.JOptionPane;

public class Aula02_03
{
    public static void main(String[] args)
    {
        String A = JOptionPane.showInputDialog("Digite um número: ");
        int B = Integer.parseInt(A);
        int C = Integer.parseInt(JOptionPane.showInputDialog("Digite outro número: "));

        int D = B + C;

        JOptionPane.showMessageDialog(null, D, "A soma é: ", 0);
    }
}
~~~
