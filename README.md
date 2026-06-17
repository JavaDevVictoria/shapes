# Shapes

A Java OOP exercise demonstrating inheritance and polymorphism through a shape management system.

## Class Hierarchy

- **Shape** — superclass with `name`, `color`, `area()`, and `perimeter()`
- **Circle** — extends Shape; requires `radius`
- **Rectangle** — extends Shape; requires `length` and `width`
- **Triangle** — extends Shape; requires `side1`, `side2`, and `side3`

## Running the Program

Compile all files:

```bash
javac *.java
```

Run the interactive demo:

```bash
java ShapeDemo
```

The program presents a menu to add up to 5 shapes (circle, rectangle, or triangle) and display their area and perimeter.

## Formulas Used

| Shape | Area | Perimeter |
|---|---|---|
| Circle | π × r² | 2 × π × r |
| Rectangle | length × width | 2 × (length + width) |
| Triangle | Heron's formula: √(s(s-a)(s-b)(s-c)) | a + b + c |
