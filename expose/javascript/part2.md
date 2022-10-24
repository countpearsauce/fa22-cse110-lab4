Question 1: Prints '3' since i is still able to be accessed outside of the for loop since it is of type var and it is still being referenced in the same function.

Question 2: Prints '150' since this is the last value that discountedPrice was declared as (300 * 0.5 = 150), and since it is of type var it can still be accessed outside of the for loop.

Question 3: Prints '150' since this is the last value that finalPrice was set to.

Question 4: The function returns a list of the discounted prices of the original prices list. This is since for each item in the original list, it calculates the discounted price and pushes the new price to the discounted list which it ultimately returns.

Question 5: The code causes an error because the variable i is of type let, which means it can't be accessed outside of its bracket scope (the for loop), and so it causes an error upon trying to print it outside of the loop.

Question 6: The code causes an error because the variable discountedPrice is of type let, so it can't be accessed outside of the loop it is created in.

Question 7: Prints '150' since this is the last value that finalPrice was set to, and there is not scope issues with finalPrice being type let since the print is still in the same bracket scope (in this case the whole function).

Question 8: The function correctly returns the list of discounted prices since all variable accesses are ok and make sense for what is happening.

Question 9: The code causes an error because the variable i is of type let and can't be accessed outside of the for loop.

Question 10: Prints '3' since the list of prices has length 3, and we set this to length. Even though it is of const type, we don't try to change it so its ok.

Question 11: The function correctly returns the list of discounted prices. The tricky part is that although the list discounted is of const type and we push discountedPrices to it, this is not actually violating the const attribute of not being able to be reassigned.

Question 12:
- Part A: student.name
- Part B: student['Grad Year']
- Part C: student.greeting();
- Part D: student['Favorite Teacher'].name
- Part E: student.courseLoad[0]

Question 13: 
- Part A: 32, adding 2 to the string '3' simply converts the 2 into a string and appends them, and '3' + '2' = '32'
- Part B: 1, trying to subtract 2 from the string '3' converts the string into an integer and then does 3 - 2 = 1
- Part C: 3, trying to add null simply adds 0 and keeps the integer 3 as is
- Part D: 3null, since '3' is a string it simply appends null as a string as well 
- Part E: 4, true is type shifted to 1 since it is being added to an integer
- Part F: 0, False has a value of 0 and null as well, 0 + 0 = 0
- Part G: 3undefined, converts undefined into a string and appends it
- Part H: NaN, its trying to subtract a string which doesn't work

Question 14: 
- Part A: True, compares '2' and 1 as integers
- Part B: True, compares '2' and '12' as integers
- Part C: True, compares '2' and 2 as integers
- Part D: False, === is a strict comparison, so since '2' and 2 have different types it is false
- Part E: False, true is converted to 1 as an integer, and 1 is not equal to 2
- Part F: True, Boolean(2) converts 2 into a boolean, and since 2 is not 0 this returns a value of true, and is of type boolean. since the value and type match (since === is used), the statement is true.

Question 15: The == operator checks if two values are equal and allows for automatic type casting. Meanwhile the === operator checks both the value and that the original values have the same variable type.

Question 17: The call will multiply each element of the array by 2. The modifyArray function takes in two parameters, an array and a function. It then creates a new array, and populates it with the original array's elements except they are run through the parameter function first. Since the function given simply returns twice the input value, this ultimately means the array returns twice the values of the original array.

Question 19: The console prints out the numbers in the order of 1,4,3,2
