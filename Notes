To solve the given patterns, we can represent them as matrices. Each pattern can be seen as a 2D grid of characters or numbers, and we can construct the patterns by filling in the appropriate values in the matrix. Here's an explanation of how we can approach each pattern:



/* Pattern 1
*****
*****
*****
*****
*****
We can represent this pattern as a matrix of 5 rows and 5 columns, where each cell contains an asterisk (*). We can iterate through the rows and columns of the matrix and print an asterisk for each cell.
*/
console.log("Pattern 1:");
for (let i = 0; i < 5; i++) {
  let row = "";
  for (let j = 0; j < 5; j++) {
    row += "*";
  }
  console.log(row);
}


// Pattern 2
*
**
***
****
*****
This pattern can be represented as a matrix with 5 rows and 5 columns. To construct the pattern, we can iterate through the rows and columns of the matrix. If the row number is less than or equal to the column number, we print an asterisk; otherwise, we print a space.

console.log("\nPattern 2:");
for (let i = 0; i < 5; i++) {
  let row = "";
  for (let j = 0; j <= i; j++) {
    row += "*";
  }
  console.log(row);
}

// Pattern 3
*****
****
***
**
*
This pattern can also be represented as a matrix with 5 rows and 5 columns. To construct the pattern, we can iterate through the rows and columns of the matrix. If the column number is less than or equal to the row number, we print an asterisk; otherwise, we print a space.

console.log("\nPattern 3:");
for (let i = 0; i < 5; i++) {
  let row = "";
  for (let j = 0; j < 5 - i; j++) {
    row += "*";
  }
  console.log(row);
}

// Pattern 4
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
This pattern can be represented as a matrix with 5 rows and 5 columns. Each cell contains a number, where the value in each row increases by 1. We can iterate through the rows and columns of the matrix and print the corresponding number for each cell.

console.log("\nPattern 4:");
for (let i = 1; i <= 5; i++) {
  let row = "";
  for (let j = 1; j <= i; j++) {
    row += j + " ";
  }
  console.log(row);
}

// Pattern 5
*
**
***
****
*****
****
***
**
*
This pattern can be represented as a matrix with 9 rows and 5 columns. To construct the pattern, we can iterate through the rows and columns of the matrix. If the row number is less than or equal to the column number, we print an asterisk; otherwise, we print a space. After reaching the middle row, we start decrementing the number of asterisks.

console.log("\nPattern 5:");
for (let i = 1; i <= 5; i++) {
  let row = "";
  for (let j = 1; j <= i; j++) {
    row += "*";
  }
  console.log(row);
}
for (let i = 4; i >= 1; i--) {
  let row = "";
  for (let j = 1; j <= i; j++) {
    row += "*";
  }
  console.log(row);
}

// Pattern 6
    *
   **
  ***
 ****
*****
This pattern can be represented as a matrix with 5 rows and 5 columns. To construct the pattern, we can iterate through the rows and columns of the matrix. If the column number is greater than or equal to the difference between the total number of rows and the row number minus 1, we print an asterisk; otherwise, we print a space.

console.log("\nPattern 6:");
for (let i = 0; i < 5; i++) {
  let row = "";
  for (let j = 0; j < 5; j++) {
    if (j >= 5 - i - 1) {
      row += "*";
    } else {
      row += " ";
    }
  }
  console.log(row);
}

// Pattern 7
*****
****
***
**
*
This pattern can be represented as a matrix with 5 rows and 5 columns. To construct the pattern, we can iterate through the rows and columns of the matrix. If the column number is greater than or equal to the row number, we print an asterisk; otherwise, we print a space.
console.log("\nPattern 7:");
for (let i = 0; i < 5; i++) {
  let row = "";
  for (let j = 0; j < 5; j++) {
    if (j >= i) {
      row += "*";
    } else {
      row += " ";
    }
  }
  console.log(row);
}

// Pattern 8
     *
    ***
   *****
  *******
 *********
This pattern can be represented as a matrix with 5 rows and 9 columns. To construct the pattern, we can iterate through the rows and columns of the matrix. If the column number is within a specific range determined by the row number, we print an asterisk; otherwise, we print a space.

console.log("\nPattern 8:");
for (let i = 0; i < 5; i++) {
  let row = "";
  for (let j = 0; j < 9; j++) {
    if (j >= 5 - i - 1 && j <= 5 + i - 1) {
      row += "*";
    } else {
      row += " ";
    }
  }
  console.log(row);
}

// Pattern 9
*********
 *******
  *****
   ***
    *
This pattern can be represented as a matrix with 5 rows and 9 columns. To construct the pattern, we can iterate through the rows and columns of the matrix. If the column number is within a specific range determined by the row number, we print

console.log("\nPattern 9:");
for (let i = 0; i < 5; i++) {
  let row = "";
  for (let j = 0; j < 9; j++) {
    if (j >= i && j < 9 - i) {
      row += "*";
    } else {
      row += " ";
    }
  }
  console.log(row);
}

