1. Line 9 prints 20
2. Line 13 prints 20
3. You should not use var because it has function scope, so it can be accessed 
   outside of its initial block and cause issues with the scope and naming of variables.
4. Line 9 prints 20
5. Line 13 returns an error because declaring result using let gives the variable
   block scope instead of function scope, so it is no longer valid after the code
   block in which it is declared.
6. Line 9 prints 0
7. Line 13 returns an error because declaring result using const also gives the variable
   block scope instead of function scope, so it is no longer valid after the code
   block in which it is declared.
