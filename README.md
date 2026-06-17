dsa
array
linkedlist
stack
queue
tress
graph
sorting techinques
seraching tequchines
algorithms

17/6
code: 
import java.util.Scanner;

class day3 {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int num = sc.nextInt();
        int nums = 1;

        for (int col = 0; col < num; col++) {
            for (int row = 0; row < num; row++) {
                System.out.print(nums + " ");
                nums++;
            }
            System.out.println();

            
        }
    }
}
