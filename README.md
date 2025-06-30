# Matrix Display Using Pointers

This C program takes 9 integer inputs to form a 3x3 matrix and prints the matrix using pointer arithmetic instead of standard indexing.

## 💻 Language

C


## 📋 Description
- Declares a 3x3 matrix `a[3][3]`
- Uses a pointer `p` to point to the first element of the array
- Accepts 9 integer inputs from the user
- Accesses and prints matrix elements using pointer arithmetic:
*(p + i * 3 + j)

## 🧪 Sample Output
Enter any 9 numbers.

1 2 3 4 5 6 7 8 9

The 9 numbers are:

1 2 3

4 5 6

7 8 9

## 🛠️ How to Run

```bash
gcc matrix_pointer.c -o matrix
./matrix

🌱 What I Learned

How to use pointers to navigate a 2D array

Difference between array indexing and pointer arithmetic

Efficient matrix printing techniques using memory addresses
