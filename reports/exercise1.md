# Bug reports for exercise1.py

Line: 3
Problem: The function is_even should return True for even numbers, but the condition `n % 2 == 1` checks if the number is odd, as any number modulo 2 equal to 1 is odd. For even numbers, `n % 2` should be 0.
Example: is_even(4) returns False, expected True.
Fix: return n % 2 == 0

Line: 8
Problem: The function rectangle_area should return the area of a rectangle, which is width multiplied by height, but it currently returns the sum of width and height.
Example: rectangle_area(3, 4) returns 7, expected 12.
Fix: return width * height

Line: 13
Problem: The function double should return twice the number n, but it currently adds 2 to n, which is incorrect.
Example: double(5) returns 7, expected 10.
Fix: return n * 2
