# Java-Day-13-Divisible-by-5
# Java Day 13 - Divisible by 5

This program checks whether a number entered by the user is divisible by 5.

## Example

Input:

```text
25
```

Output:

```text
25 is divisible by 5.
```

## Concepts Used

* Scanner
* User input
* `if-else`
* Modulus operator `%`
* Comparison operator `==`

## How It Works

1. The program creates a `Scanner` object.
2. The user enters a number.
3. The program uses the modulus operator `%`.
4. If the remainder after dividing the number by 5 is `0`, the number is divisible by 5.
5. Otherwise, the number is not divisible by 5.
6. The result is displayed on the screen.

## Java Code

```java
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = sc.nextInt();

        if (number % 5 == 0)
        {
            System.out.println(number + " is divisible by 5.");
        }
        else
        {
            System.out.println(number + " is not divisible by 5.");
        }

        sc.close();
    }
}
```

## Output

```text
Enter a number: 25
25 is divisible by 5.
```

## Goal

The goal of this project is to understand the modulus operator and use `if-else` to check whether a number is divisible by 5.
