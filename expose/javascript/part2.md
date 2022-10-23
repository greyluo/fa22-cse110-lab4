1. output 3, because i is defined as *var* and thus can be modified and accessed anywhere in the function. Since i would stop incrementing after reaching the length of *prices*, it would stop at 3.
2. output 150, because *discountedPrice* is defined as *var* and thus can be modified and accessed anywhere in the function. Since the last element in *prices* is 300, *discountedPrice* would be replace by 300 * 0.5, which is 150. 
3. output 150, because *finalPrice* is defined as *var* and thus can be modified and accessed anywhere in the function. It would store the rounded value of the last *discountedPrice*, which is also 150.
4. [50, 100, 150], because all the *finalPrice* are pushed into the returned list *discounted*.
5. output an error, because i is defined as *let* so it cannot be accessed outside the block it's defined.
6. output an error, because *discountedPrice* is defined as *let* so it cannot be accessed outside the block it's defined.
7. output 150, because *finalPrice* is defined as *let* and in the same scope as the line 14. It would store the rounded value of the last *discountedPrice*, which is also 150.
8. [50, 100, 150], because all the *finalPrice* are pushed into the returned list *discounted*.
9.  error, because i is defined as *let* so it cannot be accessed outside the block it's defined.
10. output 3, because const length is the size of *prices* and not modified after assigned.
11. [50, 100, 150], because all the *discountedPrice* are pushed into the returned list *discounted*. *dscountedPrice* is not reassigned and still keeps the same array.
12. 
    A. student.name 
    B. student["Grad Year"] 
    C. student.greeting() 
    D. student["Favorite Teacher"].name 
    E. student.courseLoad[0]
13. 
    A. '32', because integers map to their exact string representation
    B. 1, because '3' maps to to 3, and 3 - 2 = 1 
    C. 3, because null maps to to 0, and 3 + 0 = 3
    D. '3null', because null maps to to 'null', a string
    E. 4, because true maps to to 1, and 1 + 3 = 4
    F. 0, because both map to to 0, and 0 + 0 = 0
    G. '3undefined', because undefined maps to its exact string representation 
    H. NaN, because '3' maps to 3 and undefined maps to NaN
14. 
    A. true, because '2' maps to 2, and 2 > 1
    B. false, because string are compared letter by letter and '1' is greater than '2' in lexicographical order
    C. true, because '2' maps to 2, an  integer, and 2 == 2
    D. false, because === checks the equality without type conversion
    E. false, because true maps to 1, and 1 < 2
    F. true, because Boolean(2) returns true, and true === true
15. == checks the equality after type conversion while === checks the equality without type conversion, meaning that for ===, variables with different types would immediately be returned false.
17. The result would be [2,4,6], because in each loop, *doSomething* would be called, multiply the value of each element in the array by 2, and return it to the new array. 
19. The output would be 1 4 3 2 (vertically).
    