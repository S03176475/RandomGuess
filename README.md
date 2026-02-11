# RandomGuess
public class RandomGuess {
    public static void main(String[] args) {
        
        // First message
        System.out.println("Think of a number between 1 and 10.");
        
        // Generate random number from 1 to 10
        int randomNumber = 1 + (int)(Math.random() * 10);
        
        // Second message
        System.out.println("The random number is " + randomNumber);
        
    }
}
