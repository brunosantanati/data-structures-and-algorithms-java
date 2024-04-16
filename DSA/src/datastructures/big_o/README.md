## <> Big O: O(n)
Write a method called printItems in Java.

The purpose of this method is to print out a series of integer numbers, starting from 0 up to (but not including) a specified number.

Code that is provided:

The method is defined as public and static, meaning it can be accessed from any class without needing to create an instance of the class it belongs to.

The method  returns void, meaning it will not return any value.

The method accepts a single parameter, an integer n. The method will use this value to determine the number of items to be printed.



Code that you are tasked with writing:

The method should include a for loop. The loop should start with a counter i initialized at 0, continue as long as i is less than n, and increment i by 1 with each iteration.

Inside the loop, the method should print the current value of i to the console followed by a new line.



The final result of this task should be a method that, when called with an argument n, prints the integer numbers from 0 to n-1 (inclusive) on separate lines.

For instance, if called with n = 10, the output should be:

0
1
2
3
4
5
6
7
8
9

## Tips

Pseudo Code:

printItems Method

Purpose: This method is designed to print integer values from 0 to n-1 (inclusive) on separate lines.

printItems Method Signature

It is a public method, so it can be accessed from any other class.

It is a static method, meaning it belongs to the class it is defined in rather than an instance of that class.

The method has a void return type, indicating that it does not return any value.

The method accepts a single parameter, n, of type int.

Method Body

The method uses a for loop to iterate through a series of numbers, starting from 0 and ending at n - 1.

Loop Structure

Initialization: int i = 0 initializes the loop counter i to 0.

Condition: i < n is the loop's termination condition. The loop will continue iterating as long as i is less than n.

Post Iteration Operation: i++ increments i by 1 after each loop iteration.

Loop Body

System.out.println(i) is executed for each iteration of the loop. It prints the current value of i to the console followed by a new line.

In a nutshell, this method prints a sequence of integers from 0 to n-1 (inclusive) to the console, each on a new line.

## Explanation

    public static void printItems(int n) {
        for (int i = 0; i < n; i++) {
            System.out.println(i);
        }
    }




public static void printItems(int n): This is the declaration of a method named printItems which is public (meaning that it can be accessed from anywhere), static (meaning that it belongs to the class itself, not to an instance of the class), and void (meaning that it doesn't return any value). This method takes one parameter, an integer n.

for (int i = 0; i < n; i++): This is a for loop. The for loop is a control flow statement for specifying iteration, which allows code to be repeatedly executed. In this loop:

int i = 0; is the initialization. It's executed once at the beginning of the loop. Here, a variable i is declared and initialized to 0.

i < n; is the condition. Before every iteration of the loop, this condition is checked. If the condition is true, the loop executes. If the condition is false, the loop ends and the program continues with the code that follows the loop. Here, the condition is that i must be less than n.

i++ is the iteration expression. It's executed after every iteration. Here, i++ increments the value of i by 1 after each iteration.

System.out.println(i);: This line of code is the body of the for loop, which is executed on each iteration as long as the condition i < n is true. System.out.println(i) prints the value of i followed by a new line.

So overall, the printItems method prints the numbers from 0 to n-1 (inclusive) to the console, each on a new line. The number of lines printed is determined by the input n.





Code with inline comments:



public static void printItems(int n) {
// We are defining a static method, printItems. Static
// means this method belongs to the class, not an instance.
// It takes one integer parameter, n.

    for (int i = 0; i < n; i++) {
        // This is a for loop. It initializes an integer i to 0.
        // It continues looping as long as i is less than n.
        // After each iteration, it increments i by 1 (i++).
 
        System.out.println(i);
        // Inside the loop, we print the current value of i.
        // This is done for each iteration of the loop,
        // hence printing numbers from 0 to n-1 inclusive.
    }
}