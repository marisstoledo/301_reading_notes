1. What are loops used for in programming?
* loops offer an easy way to do something repeatedly. They can run the same code over and over again but getting different results

2. What are the 5 different types of loops we work with in JavaScript?
* for loop: loops through a block of code x amout of times
while loop: loops through a block of code if a condition is true
do..while: same as while loops
for in: loops through properties of an object
for..of: loops through the vaules of an iterate object

3. What is the definition of a for loop?
* for statements creates a loop that consists of 3 expressions, inside parenthesees and seperated by ; followed by a statement ( usually block) to be executed in the loop

4. What is the syntax and pseudocode of a for loop?
* for(i=0; conditionalExpression; iteratorExpression) {code block to run at evry iteration;}
5. What does the initial expression do?
* let i= 0, ran at the beginning and initializes the varible 

6. Why is it important to use `let` when declaring the `i` variable in a loop?
* let is used ti declare the i variable in a loop, i will only have scope within the loop

7. What does the conditional expression do?
* use i is <, > to the number of times you want to run the array

8. What does the iterator expression do?
* increments/ decrements the vaule of the intial varible and moves the loop to the iteration (i-- or i++)

9. When a for loop executes, the following occurs:
* -intial expression is executed once and make a loop counter 
- the conditional expression is evaluated, if it's true the loop will work, if it's false the loop will end
- the statement inside the code block execute 
- the iterator expression is executed and either increments or decrements the loop to the next 
- last you go back to #2 and the for loop continues to run until the condition returns false

10. What is a callback function?
* a function passed as an arguement to another function. allows a function to call another function. a call back can run after another function has finished

11. When do we use a callback function?
* where we will use the callbacl function is w JS built in methods.
