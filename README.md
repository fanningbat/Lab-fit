# Simple Calculator
The working of a basic calculator.
Including a header file and then starting with the main function straight ahead.
Now we can declare the variables, choice as char and the two input numbers as double.
A series of printf statements where you tell the user what to press for the function they want the calculator to perform. Then using scanf we take user’s input and store it the variable choice.
Then using scanf again, we take two numbers from the user and store it in the variables num1 and num2 respectively. 
After the printf and scanf statements, we can move onto the working of the code. We use a switch statement and make cases based on the user choice. In each case, we perform basic calculator functions (add, subtract, multiply, divide). 
In the last case, which is divide, we used an if-else statement to make sure that num1 is not divided by zero and it generates an error instead. Similarly, we ended the code by the default case, where the user is told that they entered the wrong choice.

The git commands used on Vs code.
We started by initializing git by git init.
Then we moved on to creating a .c file named calculator.c in our opened folder named Simplecalculator.
We added and then committed the file by easy commands: git add and git commit –m”” but before committing, we had to make our identity known. So we entered our user.name and then email.
git config --global user.name "xxx"
git config --global user.email "xx@gmail.com"
Next up, we created a readme file for the document and repeated the steps of adding and then committing it. Now we create two branches. One for code and one for the document using “git branch code” “git branch document”
To check if our branches were created, we entered “git branch” which displayed our branch and on which one we are currently at.
Now using, “git checkout code” we entered in the branch code where we wrote our calculator code in the .c file we created in the started. I saved it in the vs code itself before adding and committing again. Next, we navigate to the “git checkout document” and add the document using either notepad. We saved the changes and then added and committed them.
Now, after saving and committing, we navigate to master and then merge the two branches by “git merge code” “git merge document”.

