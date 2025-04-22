# Shape Calculator Program

This C program allows users to calculate the area and perimeter/circumference of basic shapes such as Circle, Rectangle, and Triangle. The program uses functions for each calculation and provides a menu-driven interface for user interaction.

## Features

- Calculate area and circumference of a Circle
- Calculate area and perimeter of a Rectangle
- Calculate area and perimeter of a Triangle
- Input validation for positive numeric values
- User-friendly menu for shape selection

## Files

- `ACE_PROJECT_AYUSHBANSAL.c`: The main C program file containing the implementation.

## Compilation

To compile the program, use the following command in your terminal or command prompt:

```bash
gcc -o shape_calculator ACE_PROJECT_AYUSHBANSAL.c -lm
```

The `-lm` flag links the math library, which is required for mathematical functions.

## Running the Program

After compilation, run the executable:

```bash
./shape_calculator
```

On Windows, you may run:

```bash
shape_calculator.exe
```

Follow the on-screen prompts to select a shape and enter its dimensions. The program will display the calculated area and perimeter/circumference.

## Notes

- Ensure to enter positive numeric values for dimensions.
- The triangle sides must satisfy the triangle inequality to form a valid triangle.

