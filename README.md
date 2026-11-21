# data-structure-2b
first repository
import java.util.Stack;

public class SimpleStack {
    public static void main(String[] args) {

        Stack<String> names = new Stack<>();

        names.push("Alice");
        names.push("Bob");
        names.push("Charlie");

        System.out.println("Stack after push:");

        for (String name : names) {
            System.out.println(name);
        }

        names.pop();

        System.out.println("Top item: " + names.peek());

        System.out.println("Stack values:");

        for (String name : names) {
            System.out.println(name);
        }
    }
}
