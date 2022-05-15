Sayıları küçükten büyüğe doğru sıralama:

```java
import java.util.Scanner;

public class siralama {
    public static void main(String[] args) {
        int x, y, z;
        Scanner input = new Scanner(System.in);

        System.out.print("1.Sayı(x) :");
        x = input.nextInt();
        System.out.print("2.Sayı(y) :");
        y = input.nextInt();
        System.out.print("3.Sayı(z) :");
        z = input.nextInt();

        if (x < y && y < z && x < z) {
            System.out.println("x<y<z");
        }
        if (z < x && z < y && x < y) {
            System.out.println("z<x<y");
        }
        if (x < z && x < y && z < y) {
            System.out.println("x<z<y");
        }
        if (y < x && x < z && y < z) {
            System.out.println("y<x<z");
        }
        if (z < y && y < x && z < x) {
            System.out.println("z<y<x");
        }
        if (y < z && z < x && y < x) {
            System.out.println("y<z<x");
        }

    }

}

```

