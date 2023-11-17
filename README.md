# TurtleFlow Programming Language

## Introduction

TurtleFlow is an educational programming language inspired by Turtle Graphics, enhanced with control flow and variable handling capabilities. It's designed to provide a user-friendly platform for beginners to learn programming fundamentals, logical thinking, and basic data handling, all while creating engaging visual outputs.

## Features

- **Intuitive Syntax:** Easy-to-understand commands for movement, drawing, and control flows.
- **Variable Support:** Variables for dynamic programming and more complex algorithms.
- **Control Flow Constructs:** Includes `if-else` statements, `for` and `while` loops for advanced control.
- **Interactive Drawing:** Visual feedback through turtle graphics for immediate understanding of code effects.
- **Cross-Platform:** Developed in Python, making it accessible on multiple operating systems.

## Usage

### Basic Commands

- `move <distance>`: Move the turtle forward by the specified distance.
- `turn <angle>`: Turn the turtle by a given angle (in degrees).
- `pen up` / `pen down`: Lift or lower the pen to stop/start drawing.
- `color <color>`: Change the pen color (e.g., red, blue, green).

### Control Structures

- `if`, `else`: Conditional execution of code blocks.
- `for <variable> in <range>`: Loop a certain number of times.
- `while <condition>`: Repeat as long as a condition is true.

### Working with Variables

- Declare a variable: `var <name> = <value>`

### Example Program

```
begin
pen down
color green
var distance = 100
var angle = 90
for i in 1 to 4
move distance
if i is odd
turn angle
else
turn angle / 2
end
pen up
end
```

## Contributing

We welcome contributions to TurtleFlow! If you have suggestions or improvements, please submit an issue or pull request on our [GitHub repository].
