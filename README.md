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
# Product Card Challenge

This project demonstrates the creation of visually appealing, responsive product cards for sneakers using HTML and CSS.

## Features

### 1. Design
- Two product cards are displayed side by side on larger screens and stack vertically on smaller screens.
- Each card contains:
  - An image of the product.
  - Product title.
  - Short description.
  - Price.
  - "Buy Now" button.
  - Favorite (star) icon.

### 2. Hover Effects
- The "Buy Now" button changes color when hovered over.
- The favorite icon fills with color when hovered over to indicate selection.

### 3. Responsiveness
- Cards are fully responsive and adapt well to different screen sizes.
- For smaller screens, the cards stack vertically for better usability.

### 4. Styling
- Cards feature rounded corners and subtle box shadows for a clean user interface.
- Contrasting background colors for the cards make them visually distinct.

## Technologies Used
- **HTML**: For structuring the content.
- **CSS**: For styling and responsiveness.

## How to Run
1. Copy the HTML and CSS code provided in the `index.html` file.
2. Open the file in any web browser.

## Future Improvements
- Add animations to the hover effects.
- Integrate with a JavaScript backend for real product data.
- Include additional card details like ratings or reviews.
