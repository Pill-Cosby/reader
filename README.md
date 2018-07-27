# reader
import java.util.Scanner;
public class JavaApplication17 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        System.out.println("Hey, what's your name?");
        String name = reader.nextLine();
        System.out.println("Welcome to my world, " + name);
