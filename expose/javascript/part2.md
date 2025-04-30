1. Line 12 will output 3 because i is declared as a var, so it is available outside of the block.
2. Line 13 will output 150 because it is the last loop that determines the discounted price of 300, and is declared as a var.
3. Line 14 will output 150 because the final rounded price is the same as the discounted price, declared as a var.
4. The function will return [50, 100, 150] because the discounted array is pushed all of the values.
5. Line 12 will output an error because let is used to declare i in the for loop, so it is not accessible outside of it.
6. Line 13 will output an error because let is used to declare discountedPrice in the for loop, so it is not accessible outside of it.
7. Line 14 will output 150 because the finalPrice is set to 150 and is available in the function.
8. The function will return [50, 100, 150] because the discounted array is pushed all of the values and is available in the function.
9. Line 11 will cause an error because let is used to declare i in the for loop, so it is not accessible outside of it.
10. Line 12 will output 3 because the length is set to 3 using const.
11. The function will return [50, 100, 150] because the discounted array can still be pushed values as a const.
12.  
    - A.   student.name 
    - B.   student['Grad Year']
    - C.   student.greeting()
    - D.   student['Favorite Teacher'].name
    - E.   student.courseLoad[0]
13. 
    - A.   32 because the + operator is string concatenation rather than addition.
    - B.   1 because - can only be for arithmetic, so it converts to integers and subtracts.
    - C.   3 because null becomes 0.
    - D.   '3null' because + will do string concatenation, 
    - E.   4 because true has the value 1. 
    - F.   0 because false is 0 and null is 0.
    - G.   '3undefined' because + does string concatenation
    - H.    NaN because - should be for aritmetic, but undefined cannot be converted to a number.
14. 
    - A.   True because the string becomes converted to the number 2, which is >1.
    - B.   False because comparing strings is in lexographic order, where 2 is after 1.
    - C.   True because == does string conversion, where 2 is equal to 2. 
    - D.   False because === doesn't convert, and the number 2 and string 2 are different
    - E.   False because true is converted to the number 1, which is not equal to 2. 
    - F.   True because Boolean(2) is true, and true = true. 
15. == is loose equality, which converts the values to correct types and compares them. However, === is strict and does not conver the values before comparing, so the operands have to have the same type and the same value. 
17. The result will be [2, 4, 6]. This is because for each element in the array, the modifyArray function pushes the value returned by doSomething, which mulitiplies the parameter by 2. This returns a new array, where each element of the original is multiplied by 2. 
19. The code outputs 1 4 3 2. 