1. 3 is printed to the console. i is declared as a var, so its value will still be accessible outside of the loop. The loop terminates when i equals the length of the array. Since the input array is of length 3, i = 3 when the loop terminates. After, i is printed to the console, so its value, 3, will be printed.
2. 150 is printed to the console. discountedPrice is declared as a var, making it accessible outside the loop. The last value of discountedPrice before the loop terminates is prices[2] * 1 - discount = 300 * 0.5 = 150. Thus, 150 will be printed from the console log.
3. 150 is printed to the console. finalPrice is declared as a var, making it accessible globally. The last value of finalPrice before the loop terminates is Math.round(150 * 100) / 100 = 150. Thus, 150 will be printed from the console log.
4. [50, 100, 150] will be returned by the function. discounted is an initially empty array that is to be returned at the end of the function. Each rounded discounted price (finalPrice) is to be pushed on to the array. As the input array is [100, 200, 300] with a discount value of 0.5, the final array will be [50, 100, 150].
5. Error; i is locally defined in the loop, and the code tries to print i to the console outside the loop where it is not defined.
6. Error; discountedPrice is locally defined in the loop, and the code tries to print discountedPrice to the console outside the loop where it is not defined.
7. 150 will print to console. Since finalPrice is declared outside of the loop, there won't be an error when it is printed.
8. [50, 100, 150] will be returned. discounted is declared outside the loop so there is not scoping error when it is returned.
9. Error; i is still locally defined with let.
10. 3 will print to console. length is a constant describing the length of the input array. As the input array is [100, 200, 300], the length printed will be 3.
11. [50, 100, 150] will be printed. Even though discounted is a const, that only means that a constant reference to the array is defined, not the array itself. As such, elements can be reassigned, which is why there is no error.
12. 
    A. student.name
    B. student.['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. 
    A. 32, int 2 maps to string 3
    B. 1, strings cannot be subtracted so 3 converts to int 3, -2 = 1
    C. 3, null converts to 0
    D. 3null, null converts to string "null"
    E. 4, true maps to 1
    F. 0, false maps to 0, null maps to 0
    G. 3undefined, undefined maps to string
    H. NaN, 3 maps to int 3 due to "-", undefined has no int version
14. 
    A. true, int version of "2" is greater than 1
    B. false, 2 < 12
    C. true, 2 == int version of "2"
    D. false, === considers if types are different
    E. true, Boolean(2) is true, so true === true
15. == does the type conversion before comparison, === compares values AND operands
17. [2, 4, 6] will be the result. For each element in the array, doSomething will be called on that number, which doubles it. These values will be pushed to a new array. Thus, the final array will be doubled the values of each element, or [2, 4, 6].
19.
    1
    4
    3
    2