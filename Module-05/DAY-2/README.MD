# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define `Cylinder` class:
-	a) Private variables `radius` and `height`
-	b) `setRadius(int r)` and `setHeight(int h)` methods to set values
-	c) `getVolume()` method:
- i) Calculate and print `volume = pi * radius * radius * height`
3.	In `Main` class `main` method:
-	a) Use `Scanner` to read `radius` and `height`
-	b) Create `Cylinder` object, set values, and call `getVolume()`
4.	End









## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: M.Suryakumar
RegisterNumber:  212224040340
*/
```

## Sourcecode.java:

```
import java.util.Scanner;

class StringReverser {
    private String text;

    public void setText(String text) {
        this.text = text;
    }

    public String getReversedText() {
        StringBuilder sb = new StringBuilder(text);
        return sb.reverse().toString();
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        StringReverser sr = new StringReverser();

        String input = scanner.nextLine();
        sr.setText(input);

        System.out.println(sr.getReversedText());
        scanner.close();
    }
}
```





## OUTPUT:
```
Input     Expected    Got

pot       top         top

lap       pal         pal

```


## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.




