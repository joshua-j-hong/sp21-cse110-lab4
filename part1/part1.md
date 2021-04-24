## Part 1a
1. values added: 20
2. final result: 20
3. values added: 20
4. The line returns an error as result is only locally defined within the if statement
5. The code returns an error as it tries to reassign the constant 'result' on line 7
6. The code returns an error as it tries to reassign the constant 'result' on line 7
## Part 1b
1. Line 12 will print 3 as the var 'i' is incremented until it is no longer less than the array length of prices. As 'i' is declared with var, it is accessible outside the for loop.
2. Line 13 will print 150 as 'discountedPrice' is equal to the last time it was reassigned within the for loop, which is for the last element in 'prices'. As it is declared with var, it is able to be accessed outside the for loop.
3. Line 14 will print 150 as the variable 'finalPrice' is reassigned for every element of 'prices in the for loop. 'finalPrice' is declared as var in the function, so it is able to be accessed within the for-loop
4. This function will return an array with the original elements of the 'prices' array with the discount applied. It will also round the discount price to the second decimal place. This is apparent as the discountPrice is calculated for each element within the for-loop and pushed onto the return array.
5. This will return an error as the variable 'i' is only defined within the for-loop. As line 12 is outside the for-loop and there is no additional declaration for 'i', the variable 'i' doesn't exist and cannot be accessed.
6. This will return an error as the variable 'discountedPrice' is only defined within the for-loop (due to being declared with 'let'). As line 13 is outside the for-loop and there is no additional declaration for 'discountedPrice', the variable 'discountedPrice' doesn't exist and cannot be accessed.
7. Line 14 will print 150 as the variable 'finalPrice' is declared within the same code block with 'let'. Therefore, it can be access and reassigned by lines within for-loop as well as line 14.
8. This function will return an array with the original elements of the 'prices' array with the discount applied. It will also round the discount price to the second decimal place. This is apparent as the discountPrice is calculated for each element within the for-loop and pushed onto the return array.
9. This will return an error as the variable 'i' is only defined within the for-loop (due to being declared with 'let'). As line 11 is outside the for-loop and there is no additional declaration for 'i', the variable 'i' doesn't exist and cannot be accessed.
10. Line 12 will print 3 as the constant 'length' is declared earlier to be the array length of prices. 
11. This function will return an array with the original elements of the 'prices' array with the discount applied. This is apparent as the discountPrice is calculated for each element within the for-loop and pushed onto the return array. We observe that pushing an element onto 'discounted' is allowed, as we are not reassigning 'discounted' and only manipulating it. 
12. 
    1. student.name
    2. student['Grad Year']
    3. student.greeting()
    4. student['Favorite Teacher'].name
    5. student.courseLoad[0]
13. 
    1.  '32', as the 2 is converted to a string and then concatenated
    2.  1, as the '3' is converted to a number and then 2 is subtracted
    3.  3, as null is converted to the number 0 and then added to 3
    4.  '3null', as null is converted to a string and then concatenated
    5.  4, as true is converted to the number 1 and then added to 3
    6.  0, as false and null are both converted to the number 0 and added together
    7.  '3undefined', as undefined is converted to a string and concatenated
    8.  NaN, as undefined is not a valid number and causes the behavior of the subtract operation to be undefined
14. 
    1.  true, as '2' is converted to a number
    2.  false, as '2' has a higher kexicographical order than '12'
    3.  true, as '2' is converted to a number
    4.  false, as 2 and '2' are different types
    5.  false, as true is converted to the number 1
    6.  true, as Boolean(2) evaluates to true
15. While == checks for equality after type conversions, === (strict equality) checks for equality without converting types. Therefore, === requires both to be the same type to evaluate to true, while == does not.
16. See separate file
17. The result will be [2,4,6] because the function modifyArray takes in an array as well as function. Within modifyArray, it loops through every element and applies the function to it. In this example, doSomething doubles the numbers passed into the function, so calling modifyArray on [1,2,3] with doSomething will double the individual elements of the array.
18. See separate file
19. Each number is printed on a separate line: 1 4 3 2
