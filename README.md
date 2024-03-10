import java.util.Scanner;
import java.util.Random;

public class DDCharacterCreator {

    public DDCharacterCreator() {
        Scanner input = new Scanner(System.in);
        System.out.print("Enter character name: ");
        String name = input.nextLine();
        random = new Random();
    }

    // Method 1.a: Roll an n-sided die
       int n = (math.random()*1)+1000;
      }

    public int randBetween(int start, int end) {
        return random.nextInt(end - start + 1) + start;
    }

    // Method 2: Find the sum of three numbers
    public int sumOfThree(int a, int b, int c) {
        return a + b + c;
    }

    // Method 3: Sort an array of integers in descending order
    public int[] sort(int[] arr) {
        for (int x = 0; x < arr.length; x++) {
            for (int y = x + 1; y < arr.length; y++) {
                if (arr[x] < arr[y]) {
                    int temp = arr[x];
                    arr[x] = arr[y];
                    arr[y] = temp;
                }
            }
        }
        return arr;
    }

    public static void main(String[] args) {
        new DDCharacterCreator();
    }
}
