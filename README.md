# ALX Interview Challenges

This repo contains all interview challenges from ALX Software Enginerring Program.

## Projects

## 0x00 Pascal Triangle

### Tasks :heavy_check_mark:

+ [x] 0. **Pascal's Triangle**<br/>[0-pascal_triangle.py](0-pascal_triangle.py) contains a function `def pascal_triangle(n):` that returns a list of lists of integers representing the Pascal's triangle of `n`:
  + Returns an empty list if `n <= 0`.
  + You can assume `n` will be always an integer.

### Explanation

This function takes an integer n as input and returns a list of lists representing the first n rows of Pascal's triangle. The function first initializes an empty list triangle which will be used to store the rows of the triangle. It then checks if n is a positive integer, and if it's not, it returns the empty list. Otherwise, it iterates over the range 0 to n - 1 and generates each row of the triangle.

For each row, it initializes an empty list line which will be used to store the values in the row. It then iterates over the range 0 to i, where i is the current row number, and calculates the value for each element in the row. If the element is the first or last element in the row, it is set to 1. Otherwise, it is calculated by adding the value of the element in the previous row at the same position and the element in the previous row at the position before that. The completed row is then appended to the triangle list.

Finally, the triangle list is returned as the result of the function.

![](pascal_image.jpg)

## 0x03 Minimum Operations :neckbeard:

> Technical interview challenges

### Tasks :heavy_check_mark:

In a text file, there is a single character H. Your text editor can execute only two operations in this file: Copy All and Paste. Given a number n, write a method that calculates the fewest number of operations needed to result in exactly n H characters in the file.

Prototype: def minOperations(n)
Returns an integer
If n is impossible to achieve, return 0
Example:

n = 9

H => Copy All => Paste => HH => Paste =>HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH

Number of operations: 6

### Results :chart_with_upwards_trend:

| Filename |
| ------ |
| [0-minoperations.py](https://github.com/Ahercode/alx-interview/blob/master/0x03-minimum_operations/0-minoperations.py)|


### Try It On Your Machine :computer:
```bash
git clone https://github.com/Ahercode/alx-interview
cd 0x03-minimum_operations
./main_files/0-main
```
