1. it prints 3 because since i is declared with var, its scope is function-wide and wont disappear after the for loop ends. prices.length is 3, so i increments by 1 from 0 to 3.
2. prints 150 because that is the last value that discountedPrice was assigned
3. prints 150 because that is the last value that finalPrice was assigned
4. [50, 100, 150] because that is what was pushed into the array. going through the loop...
discountedPrice = 100 * (1-.5) = 50
then we round the value (still 50) and push it to discounted. same process for 100 and 150.
5. error because i is a block-scoped variable declared in the for loop which is erased when the loop ends
6. error because discountedPrice is a block-scoped variable declared in the for loop which is erased when the loop ends 
7. prints 150 because it was declared before the for loop, so it belongs to the entire function. 
8. [50, 100, 150], same as question 4. the logic is the same, and values were pushed to the array properly in the for loop.
9. error because i is a block-scoped variable declared in the for loop which is erased when the loop ends
10. 3 because it was declared before the for loop, so it belongs to the entire function.
11. [50, 100, 150]. same reason as question 8.
12. 
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]
13.
A. '32'. 2 is convertied to a string, so is concatenated to '3'
B. 1. '3' becomes 3 because of the minus sign, so 3-2=1
C. 3. null becomes 0
D. '3null'. null is concatenated
E. 4. true is 1 when treated as a number. 1+3=4
F. 0. false is 0 when treated as a number. null also becomes 0
G. '3undefined'. undefined is concatenated
H. NaN. '3' becomes number 3, and undefined becomes NaN. any arithmetic with NaN becomes NaN
14.
A. true. '2' becomes 2 because of > sign. 2>1, which is true
B. false. both strings are compared lexicographically, so 2<1 is false
C. true. '2' becomes 2, 2 is equal to 2
D. false. === checks the type of the values because it is the "strict equality" operator. 2 is a number, '2' is a string, so they are not strictly equal
E. false. true becomes 1, and 1 is not equal to 2
F. true. Boolean(2) becomes true because Boolean(any non-zero number) is true.
15. == is the loose equality operator, which only checks for value equality. javascript will try to convert one or both values to a common type before making the comparison.
=== is the strict equality operator. it checks for both value and type equality, and no type conversion happens. 

17. [2, 4, 6]. pass the original array [1,2,3] and doSomething which multiplies a number by 2. modifyArray has a const array. the for loop will iterate through the original array. starting at array[0], 1 is passed to callback, which is just another name for doSomething. 1*2=2, which is then pushed to newArr. same logic for the remaining values, 2*2=4, push it, 3*2 = 6, push it, and newArr is returned.

19. 1 4 3 2

