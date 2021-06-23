# Lab3 - Java Collections Framework: ArrayList

## Q1:

- Create an ArrayList of Integers
- Fill each of the 10 slots with a random value from 1-50. 
- Display those values on the screen, and then prompt the user for an integer. 
- Search through the ArrayList, and if the item is present, print a message that the number is in the list. 
- If the value is not in the ArrayList, print a message that the number is not in the list

```
import java.util.ArrayList;
import java.util.Random;
import java.util.Scanner;

public class Lab3Q1 {

        public static void main(String[] args) {
            List<Integer> ArrayQ1 = new ArrayList<>();
            ArrayQ1.add(30);
            ArrayQ1.add(7);
            ArrayQ1.add(12);
            ArrayQ1.add(34);
            ArrayQ1.add(8);
            ArrayQ1.add(20);
            ArrayQ1.add(1);
            ArrayQ1.add(45);
            ArrayQ1.add(32);
            ArrayQ1.add(18);

            System.out.println(ArrayQ1); //[30, 7, 12, 34, 8, 20, 1, 45, 32, 18]

            boolean ans = ArrayQ1.contains(4);

            if (ans){
                System.out.println("the number is in the list");
            } else {
                System.out.println("the number is not in the list");
            }
        }

}
```

Console:
```
[30, 7, 12, 34, 8, 20, 1, 45, 32, 18]
the number is not in the list
```

## Q2:

- Create an ArrayList of Integers
- Fill the ArrayList with ten random numbers (1-50)
- Copy each value from the ArrayList into another ArrayList of the same capacity
- Change the last value in the first (original) ArrayList to a -5
- Display the contents of both ArrayLists

```
import java.util.ArrayList;
import java.util.Random

public class Lab3Q2 {

	public static void main(String[] args) {
        List<Integer> ArrayQ2 = new ArrayList<>();
        ArrayQ2.add(30);
        ArrayQ2.add(7);
        ArrayQ2.add(12);
        ArrayQ2.add(34);
        ArrayQ2.add(8);
        ArrayQ2.add(20);
        ArrayQ2.add(1);
        ArrayQ2.add(45);
        ArrayQ2.add(32);
        ArrayQ2.add(18);
        System.out.println("Original ArrayQ2: " + ArrayQ2);

        List<Integer> CopiedArray = new ArrayList<>();
        for (int number: ArrayQ2
             ) {
            CopiedArray.add(number);
        }

        ArrayQ2.set(0,-5);

        System.out.println("ArrayQ2: " + ArrayQ2);
        System.out.println("CopiedArray: " + CopiedArray);


    }

}
```
Console:
```
Original ArrayQ2: [30, 7, 12, 34, 8, 20, 1, 45, 32, 18]
ArrayQ2: [-5, 7, 12, 34, 8, 20, 1, 45, 32, 18]
CopiedArray: [30, 7, 12, 34, 8, 20, 1, 45, 32, 18]
```

## Q3:

- Make a record to store information about a car. It should contain fields for:
        - make (String)
        - model (String)
        - year (int)
- Create an ArrayList of Car objects.
- Sort the ArrayList of cars by year (Ascending) and print them out.

```
import java.util.ArrayList;
import java.util.List;

public class Lab3Q3 {

    public static void main(String[] args){
        
    }

}
```
