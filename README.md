Aim: To print Hello World and design a Claculator to add,subtract,multiply and divide two user input number.

Tools: VS Code

Theory: The program begins with #include, allowing the program to use cin and cout for input/output. Without this #include statement, the compiler is unable to process cin or cout. Using using namespace std; allows us to refer to cin and cout directly in our code.

The program begins execution in int main(). The statement std::cout << "Welcome to C++ Programming!" << std::endl; prints the welcome message. Likewise, cout << "Hello World" << std::endl; prints "Hello World".

After the greetings, int a; declares a variable of type int; then we have cout << "Enter a number: "; and cin >> a;. This line prompts the user for input, then stores the result of that input in the variable we declared above.

After storing a we execute cout << "You entered: " << a << std::endl; and lastly cout << "Thank you for your input.";. Finally we end our program with return 0; which indicates to the operating system that the program completed successfully.

Algorithm:

Start the program. Display a welcome message: Output: Welcome to C++ Programming! Output: Hello World Prompt the user to enter an integer: -Output: Enter a number: -Input: User enters an integer value and it is stored in variable x -Output: You entered: x

Calculator functionality: Prompt the user to input two numbers:

Output: Enter number 1: → Input stored in variable a Output: Enter number 2: → Input stored in variable b Perform operations: sum = a + b sub = a - b mul = a * b div = a / b

Display results:

Output: Sum: sum Output: Subtraction: sub Output: Multiplication: mul Output: Division: div End the program. The program then prints each of the calculations in the format of "Sum:" followed by std::endl to print the result of the calculation on a new line. We conclude with return 0; which indicates successful execution of our program.

Conclusion: This Program will help in understaing of basic input and output, diffrent arithmetic operation in C++.
