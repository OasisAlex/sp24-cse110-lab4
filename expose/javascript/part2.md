# part2

1. 3, because var is inside a function, it has a function scoope, which will be the length of prices that's given
2. 150, it will be the discountedprice from the last price. because var has the function scoope and it can change value untill the  last one.
3. 150, it's the same logic that finalprice is a var variable with in the function scoope that can be change and after for loop, last time it got assigned is the number of 150.

4. it will return an array of discounted prices. it won't show on the cmp because there is not alert.
5. error, because i is let variable which can't be access after for scope.
6. error, because discountedPrice is scoped to the for loop
7. 150,  it can be print out just fine because let finalPrice is in the scope of function.
8. discounted prices from the function, it's a let variable
9. error, becuause i is scoped inside the for loop
10. 3, it will correctly log the length of the prices that been send in. which is three, because its in scope of function.
11. it will return a const variable of discounted prices that's not changeable

12. 
    A. console.log(student.name);

    B. console.log(student['Grad Year']); 

    C. student.greeting();

    D. console.log(student['Favorite Teacher']['name']);

    E. console.log(student.courseLoad[0]);

13. 
    A. '32' because 2 maps to string '2' and concanate

    B. 1 because '3' can maps to integer 3 and perform arigmetic

    C. 3 because null can map to integer zero, which perfom addition zero

    D. '3null' because null maps to string 'null'

    E. 4, because true maps to 1

    F. 0 because false and null both maps to integer 0

    G. '3undefined' because undefined maps to string ' undefined'

    H. NaN, because both - means alrimatic , but undefined can't maps to integer.

14. 
    A. true, 2 can maps to integer 2 which is larger than 1

    B. false, In lexicographical order, '2' is greater than '1', hence '2' is considered larger than '12'.

    C. true, '2' can convert to integer 2

    D.false,  === check without conversion, string not equal to number

    E.false, true convert to number 1, which is not equal

    F. true, Boolean(2) is true, and since both operands are Boolean and identical, the comparison is true.

15. ==(Equality Operator) check for equality after performing type-conversion. ===(strict equality operator) check without performing type conversion.

17. The result will be a newarray of [2, 4, 6] being return. The function and three number array send to modifyArray as parameter, and then create a loop to iterate the array, send each item in array to the function that's beeing pass as parameter, that function double the number and return it back. Then function modifyArray push the new num to NewArr.
    
19. 1432 , because the function will still keep calling, but the delay come after
    