1. At line 12, the final value of i is printed which is 3 because i is declared as a var, hence it can be accessed anywhere in the function including outside of the loop. So i is equal to prices.length after the loop finishes which is 3.
2. At line 13, the final value of discountedPrice is printed which is 150 since it is declared as a var so the variable is accessible outside of the loop in the function. discountedPrice is equal to the last iteration of the for loop which would be 300 * (1 - 0.5) = 150.
3. At line 14, the final value of finalPrice is printed which is 150 since it is declared as a var it the variable is accessible anywhere in the function. finalPrice is is reassigned in the loop, so the value of finalPrice is the last iteration of the loop which is 150.
4. This function will return the discounted with discounted prices because the function iterates through the prices array, then pushes each price as a discounted price into the discounted array.
5. At line 12, there will be an error since it is trying to access i which is a let variable, trying to access outside of the block it is declared in so it is not defined. Hence, i only exists in the for loop it is declared in.
6. At line 13, there will be an error since it is trying to access discountedPrice which is a let variable, trying to access outside of the block it is declared in so it is not defined. Hence, discountedPrice only exists in the for loop it is declared in.
7. At line 14, it will print the last discounted price of the prices which is 150 because finalprice is declared as a let variable in the main function block, hence it is accessible. The reason why it is the last discounted price of the list is because the for loop iterates through the list of prices from the beginning to calculate and store the final price. Hence, when the loop ends, the value of the last discounted price is stored.
8. This function will return the array discounted which contains the discounted prices computed in the function since it is declared in the beginning of the function as an empty array, then the loop iterates through the initial list then adds each discounted price to the discounted array.
9. At line 11, the code will cause an error because i is declared as a let variable inside the for loop, hence it is not accessible outside of the block it is declared in. At line 11 which is outside the block i is declared in, the code tries to print i, but it is not defined in the outside of the block.
10. At line 12, 3 will be printed since it is the value of const length which is the length of prices. It is defined in the function scope and not inside any blocks, hence it is accessible at line 12.
11. This function will return the array discounted containing the discounted prices of prices. The function iterates through the prices array then computes a discounted price for each price and adds to the disconted array.
12. a. student.name\
    b. student["Grad Year"]\
    c. student.greeting()\
    d. student["Favorite Teacher"].name\
    e. student.courseLoad[0]
13. a. '3' + 2 = '32' since the + with a string and number turns the output into a string\
    b. '3' - 2 = 1 since the - converts operands to numbers hence '3' becomes a number\
    c. 3 + null = 3 since null becomes 0 after numeric conversion\
    d. '3' + null = '3null' since the + converts operands to a string hence null becomes a string\
    e. true + 3 = 4 since + converts true to 1, hence 1 + 3 = 4\
    f. false + null = 0 since false converts to 0 and null converts to 0, hence 0 + 0 = 0\
    g. '3' + undefined = '3undefined' since + converts undefined to a string since '3' is a string operand, hence '3' + 'undefined' = '3undefined'\
    h. '3' - undefined = Nan since both variables are converted to numbers, but 3 + Nan = Nan
14. a. '2' > 1 = true since '2' becomes a number, hence 2 > 1 is true\
    b. '2' < '12' = false since the first char of '12' is less than '2'\
    c. 2 == '2' = true since they equal each other only\
    d. 2 === '2' = false since they are different types\
    e. true == 2 = false since boolean true becomes 1 which is not equal to 2\
    f. true === Boolean(2) = true since Boolean(2) converts to true since any non-zero number is true
15. The difference between the == and === operators are that == essentially nonstrictly checks if two values equal each other after converting to a common type and === stritly checks if two values equal each other including a type check.
