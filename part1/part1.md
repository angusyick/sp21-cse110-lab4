Part 1 answers:

1a)
  1) values added: 20
  2) final result: 20
  3) values added: 20
  4) Error because result is outside of the block scope due to the "let" declaration.
  5) Error because const cannot be changed like in line 5
  6) Error because const cannot be changed and it is out of block scope

1b) 
  1) Outputs "3". i was declared using "var" so it is within scope.
  2) Outputs "150". discountedPrice was declared using "var" so it is within scope.
  3) Outputs "150". finalPrice was declared using "var" so it is within scope.
  4) An array that contains the values of finalPrice from each iteration of the for loop is returned: (50, 100, 150). None of the variables were out of scope since they were all defined using the "var" keyword.
  5) i was defined using let and is outside of line 12's scope so it results in an error.
  6) discountedPrice was defined using let and is outside of line 13's scope so it results in an error.
  7) Outputs "150". Although finalPrice was defined using the let keywords, everything that accesses it is within its scope so it does not result in an error.
  8) Output the same as question 4. Although "discounted" was defined using let, everything that accesses it is within its scope including the return statement so it does not result in an error.
  9) This has the same error as in number 5. i was defined using let and is outside of line 12's scope.
  10) Outputs "3". Although length is a const variable, it is never changed and is always within scope so there is no error.
  11) Outputs the same array values as in question 4 and 9. The variables defined using const keyword are never changed after declaration and none of the variables are out of scope of anything that accesses it. So, no errors. 
  12) 
