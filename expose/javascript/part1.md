1. No, the code doesn't return an error and prints the object result, which is the sum of objects num1 and num2 (in some way whether they are actually numbers or not)
2. Yes, the code can return an error on line 13, if the condition for add isn't met, object result can't be logged or printed if it was never initialized because it is only initialized within the if statement
3. var is not recommended because it acts like a global variable and isn't limited by code blocks. If the function was executed, the object can still be called upon for use outside the code block.
4. No, the code behaves as if we had result be a var object, where it returns the sum.
5. Yes, the remains to return an error like var, where it is only initialized in the if statement and cannot be used outside the code-block
6. Yes, the code returns an error because in line 7, the object is initialized as a const with the value 0 and cannot be changed, thus trying to change the value of result would constitute in an error
7. Yes, the object is still limited by the code block
