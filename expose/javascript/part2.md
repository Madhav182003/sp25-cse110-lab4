1. outputs 3 because var makes i function-scoped and it was incremented until i = 3

2. outputs 150 because var makes discountedPrice function-scoped, and its last value was 150.

3. outputs 150 because finalPrice is function-scoped and its final value after the loop is 150.

4. The function returns [50, 100, 150]. The function iterates over the prices array and returns an array of discounted prices.

5. This code will result in an error because let is block-scoped and i does not exist outside the loop.

6. This code will result in an error because let is block-scoped and discountedPrice does not exist outside the loop.

7. outputs 150 because finalPrice is block-scoped and it was defined at the top of the function so its scope is the entire function. Its final value after the loop is 150, so the output would be 150.

8. The function returns [50, 100, 150]. The function iterates over the prices array and returns an array of discounted prices. The scope of discounted would work the same way as finalPrice in q7.

9. This code will result in an error because let is block-scoped and i does not exist outside the loop.

10. outputs 3 because length is block-scoped and it was defined at the top of the function so its scope is the entire function and equals the number of elements in prices.

11. The function returns [50, 100, 150]. The function iterates over the prices array and returns an array of discounted prices. discounted is declarded as a const array, but we can still modify the contents of the array, thus no error.

12. a. student.name
    b. student["Grad Year"]
    c. student.greeting()
    d. student["Favorite Teacher"].name
    e. student.courseLoad[0]

13. a. '32'
    b. 1
    c. 3
    d. '3null'
    e. 4
    f. 0
    g. '3undefined'
    h. NaN

14. a. true
    b. false
    c. true
    d. false
    e. false
    f. true

15. '==' operator checks only for the value and the '===' operator checks for the value and the type.

17. When modifyArray([1, 2, 3], doSomething) is called, it doubles each element of the array by applying the doSomething function, which multiplies a number by 2. The resulting values [2, 4, 6] are pushed into a new array and returned. Thus, the final result is [2, 4, 6].

19. When printNums() is called, 1 is printed immediately. Then setTimeout with 0 delay schedules console.log(3) to happen after the current call stack is cleared, so 4 is printed next. After about 0 milliseconds, 3 is printed, and finally after 1 second, 2 is printed. Therefore, the output will be: 1, 4, 3, and then 2.
    