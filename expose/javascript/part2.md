
1. It would print the index of elements in the list prices at line 12, this case i=2.
2. There would be no error in the code and line 12 would print the most recent discounted price calculated since the variable is a global variable from 300 * .5 = 150.
3. finalPrice is a global variable visually not limited by any code blocks and is clearly in the scope of the function, thus no error at line 14, 150.
4. The function either returns an empty list or a list of discounted prices because it is a var object which is more global and can be used in the context of this function.
5. There would be an error in the code, let is code blocked and the resource mentioned that even though its visually not in the inner code block, it still isn't available outside the loop, so there is an error
6. There would be an error in the code, let is limited in the for loop so it cannot be used outside the code block
7. Final price would not result in an error and in line 14 would output either 0 or the most recent modification from the for loop.
8. The function returns correctly, either an empty list or a list of discounted prices
9. There would be an error in the code, let is code blocked and the resource mentioned that even though its visually not in the inner code block, it still isn't available outside the loop, so there is an error
10. The code will output the variable length, no error since its not modified nor is limited by any code block.
11. The function should successfully return either an empty array or an array of discounted prices. We are still following within the confines of the array so the array being a const shouldn't be affected, unless we were to reassign another array onto it.
#### 12
12a. student.name
12b. student['Grad Year']
12c. student.greeting();
12d. student['Favorite Teacher'].name
12e. student.courseLoad[0]
#### 13
13a. '32' due to string concatenation not addition
13b. 1 due to - being solely arithmetic thus theres numeric coercion
13c. 3 due to null having the arithmetic value 0
13d. '3null' due to string concatenation properties
13e. 4 due to true having the arithmetic value 1
13f. 0 due to false and null are coerced to 0
13g. '3undefined' due to + being in a string concatenation
13h. NaN due to undefined being NaN in arithmetic
#### 14
14a. True, in comparisons strings get converted to numbers so 2 is greater than 1
14b. false, because its now only comparing strings by character, so '2' > '1' and thus '2' is not < '12'
14c. true, coercion to numbers so '2' => 2 so 2 == 2.
14d. false, === considers types and doesn't involve type conversions, so different types return a false
14e. false, true is converted into 1 and thus 1 != 2
14f. true, any nonzero number is true when converted in Boolean so 2 = true and true = true, also === doesn't affect the output because the type conversion has already been performed
#### 15
15. As briefly explained in 14d == is different from === because == performs type conversions and === does not, thus making for largely different comaprisons.
#### 17
17. The result is an array [2,4,6] because the function iterates through each number of the list and refers to another function that multiplies that number by 2 and pushes it onto a new array which the function returns that new array.
#### 19
19. The code would output 1 and 4, then 3, then 2. This is due to how 2 and 3 have a timeout (scheduling and executing), therefore 1 and 4 are basically instantenous while 3 with the timeout function set after and 1 second with 2.
