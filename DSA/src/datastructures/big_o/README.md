<> Big O: O(n)
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