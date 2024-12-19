# FizzBuzz Program

This repository contains a simple implementation of the classic **FizzBuzz** problem in Java.

## Description

The FizzBuzz program iterates through the numbers from 1 to 100 and prints:

- "Fizz" for numbers divisible by 3.
- "Buzz" for numbers divisible by 5.
- "FizzBuzz" for numbers divisible by both 3 and 5.
- The number itself if it is not divisible by 3 or 5.

## Code

Here is the Java implementation:

```java
public class FizzBuzz {
    public static void main(String[] args) {
        for (int i = 1; i <= 100; i++) {
            if (i % 3 == 0 && i % 5 == 0) {
                System.out.println("FizzBuzz");
            } else if (i % 3 == 0) {
                System.out.println("Fizz");
            } else if (i % 5 == 0) {
                System.out.println("Buzz");
            } else {
                System.out.println(i);
            }
        }
    }
}
```
