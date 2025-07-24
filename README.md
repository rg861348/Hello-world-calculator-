Aim: To print Hello World and design a Claculator to add,subtract,multiply and divide two user input number.

Tools: VS Code

Theory: The program begins with #include, allowing the program to use cin and cout for input/output. Without this #include statement, the compiler is unable to process cin or cout. Using using namespace std; allows us to refer to cin and cout directly in our code.

The program begins execution in int main(). The statement std::cout << "Welcome to C++ Programming!" << std::endl; prints the welcome message. Likewise, cout << "Hello World" << std::endl; prints "Hello World".

After the greetings, int a; declares a variable of type int; then we have cout << "Enter a number: "; and cin >> a;. This line prompts the user for input, then stores the result of that input in the variable we declared above.

After storing a we execute cout << "You entered: " << a << std::endl; and lastly cout << "Thank you for your input.";. Finally we end our program with return 0; which indicates to the operating system that the program completed successfully.

Algorithm:

Step-wise Algorithm

Part 1: Print Hello World and Take User Input

1. Start the program.


2. Display a welcome message.
→ Output: Welcome to C++ Programming!


3. Print "Hello World".
→ Output: Hello World


4. Declare an integer variable x.


5. Prompt the user to enter a number.
→ Output: Enter a number:


6. Read user input into variable x.
→ Input: User enters a number


7. Display the entered number.
→ Output: You entered: x


8. Print a thank you message.
→ Output: Thank you for your input.




---

Part 2: Calculator Functionality

9. Declare two integer variables a and b.


10. Prompt the user to enter the first number.
→ Output: Enter number 1:


11. Read user input into variable a.
→ Input: User enters a number


12. Prompt the user to enter the second number.
→ Output: Enter number 2:


13. Read user input into variable b.
→ Input: User enters a number


14. Perform addition and store result in sum.
→ sum = a + b


15. Perform subtraction and store result in sub.
→ sub = a - b


16. Perform multiplication and store result in mul.
→ mul = a * b


17. Perform division and store result in div.
→ div = a / b (ensure b != 0)


18. Display the results:
→ Output: Sum: sum
→ Output: Subtraction: sub
→ Output: Multiplication: mul
→ Output: Division: div


19. End the program.
→ Return 0



Conclusion: This Program will help in understaing of basic input and output, diffrent arithmetic operation in C++.
