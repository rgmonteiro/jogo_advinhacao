import java.util.Random;
import java.util.Scanner;

public class JogoAdivinhacao {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Random random = new Random();
        int numeroAleatorio = random.nextInt(100) + 1; // Número entre 1 e 100
        int tentativa;
        int tentativas = 0;

        System.out.println("Bem-vindo ao Jogo de Adivinhação!");
        System.out.println("Tente adivinhar o número entre 1 e 100.");

        do {
            System.out.print("Digite seu palpite: ");
            tentativa = scanner.nextInt();
            tentativas++;

            if (tentativa < numeroAleatorio) {
                System.out.println("Muito baixo! Tente novamente.");
            } else if (tentativa > numeroAleatorio) {
                System.out.println("Muito alto! Tente novamente.");
            } else {
                System.out.println("Parabéns! Você acertou em " + tentativas + " tentativas.");
            }
        } while (tentativa != numeroAleatorio);

        scanner.close();
    }
}
