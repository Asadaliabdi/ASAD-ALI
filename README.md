import java.util.Random;

public class JavaRandom {
    public static void main(String[] args) {
        Random rand = new Random();


        int randomInt = rand.nextInt(100);
        System.out.println("Random integer: " + randomInt);

        double randomDouble = rand.nextDouble();
        System.out.println("Random double: " + randomDouble);

        boolean randomBoolean = rand.nextBoolean();
        System.out.println("Random boolean: " + randomBoolean);
}
}
