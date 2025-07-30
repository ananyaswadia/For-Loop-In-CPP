# For-Loop-In-CPP
## Aim
To study and implement loops in C++.
## Tools
Visual Studio Code 

## Theory 
In C++, for loop is an entry-controlled loop that is used to execute a block of code repeatedly for the given number of times. It is generally preferred over while and do-while loops in case the number of iterations is known beforehand.

### Syntax 
Initialization: Initialize the loop variable to some initial value.
Test Condition: This specifies the test condition. If the condition evaluates to true, then body of the loop is executed, and loop variable is updated according to update expression. If evaluated false, loop is terminated.
Update Expression: After executing the loop body, this expression increments/decrements the loop variable by some value.

### Working of a for Loop in C++
The working of for loop is as shown below:

Initialization: Control enters the loop, and initialization is done.
Condition Check: The condition is tested.
If true, the flow enters the loop body.
If false, the loop terminates, and control exits the loop.
Execution of Body: The statements inside the body of the loop are executed.
Update: The loop variable is updated.
Repeat: The flow returns to Step 2 (Condition Check) for the next iteration.
Exit: Once the condition becomes false, the loop terminates, and control exits the loop.

<img width="653" height="500" alt="image" src="https://github.com/user-attachments/assets/499ff8ec-7ca2-4a03-86d7-d3f5df7f3da2" />

## Algorithms
### Reversing A String
1. Start

2. Prompt the user to enter a PRN

3. We ead the PRN as a string

4. If the length of PRN is not 10:

5. Display error message and end program

6. Else: we first print the statemnt - “Reversed PRN:”

7. Use loop- For each character from end to start:

8. Print the character

9. End
### Floyd's Series
1. Start

2. Set n = 4 and num = 1

3. For i from 1 to n: and For j from 1 to i: we Print num

4.Increment num by 1

5. Print a newline

6. End
### Hourglass Pattern
1. Start

2. Set h = 10 (height of the pattern)

3. For upper half (inverted pyramid):

4. Use loop- For i from 0 to (h + 1)/2 - 1: , and Print i spaces

5. Print h - 2*i stars

6. Print newline

7. Lower half (upright pyramid):

8. Use loop- For i from (h - 1)/2 - 1 down to 0:, and Print i spaces

9. Print h - 2*i stars

10. Print newline

11. End
### Password Authentication
1. Start

2. Initialize Cap, Num, and Special as 0.

3. Define strings: cap,num , spchara

4. Repeat until a valid password is set (i.e., Cap == 1, Num == 1, Special == 1):

5. Prompt the user to enter a password

6. Prompt the user to enter the password again

7. Compare it with the set password: If it matches: Display “System Unlocked” else: Display “Incorrect Password”

8. End

## Conclusion
We learnt to implement the 'FOR' loop using different star patterns, and programs like password setting to gain a clear understanding.
