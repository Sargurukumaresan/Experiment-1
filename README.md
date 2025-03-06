# Experiment-1
## Name : SARGURU K
## REG NO : 212222230134
##  Write a C programs  to demonstrate the working of following constructs with possible test cases:
a) do…while b) while…do c) if …else d) switch e) for
## a) Aim
To demonstrate the working of the do...while loop, which ensures the loop body is executed at least once, even if the condition is false initially.

## Algorithm
1.	Initialize the loop variable.
2.	Execute the statements inside the loop body.
3.	After executing the loop body, check the condition.
4.	If the condition is true, repeat the loop; otherwise, exit the loop.

## Program
```
#include <stdio.h>
int main() {
    int i = 0;
    do {
        printf("Number: %d\n", i);
        i++;
    } while(i < 5);
    return 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/7970abc7-8979-4025-beaa-38cc9499120c)

## Result
To demonstrate the working of following constructs with possible test cases was executed Successfully.
## b) Aim
To demonstrate the working of the while...do loop, where the loop will execute the body of the loop as long as the condition is true.

## Algorithm
1.	Initialize the loop variable.
2.	Check the condition before executing the loop body.
3.	If the condition is true, execute the statements inside the loop.
4.	Repeat steps 2 and 3 until the condition becomes false.

## Program
```
#include <stdio.h>

int main() {
    int i = 0;
    while(i < 5) {
        printf("Number: %d\n", i);
        i++;
    }
    return 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/495923a4-4da3-4672-a56f-508c59eac5f2)

## Result
To demonstrate the working of the while...do loop was executed successfully.
## c) Aim
To demonstrate the working of the if...else conditional statement, which allows for decision-making based on a condition.

## Algorithm
1.	Evaluate the condition.
2.	If the condition is true, execute the block of code inside the if statement.
3.	If the condition is false, execute the block of code inside the else statement.

## Program
```
#include <stdio.h>

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    if(num % 2 == 0) {
        printf("The number %d is even.\n", num);
    } else {
        printf("The number %d is odd.\n", num);
    }
    return 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/d65c6b9f-ce03-4067-848e-7bfe964a3500)

## Result
To demonstrate the working of the while loop was Executed successfully.
## d) Aim
To demonstrate the working of the switch statement, which is used to select one of many code blocks to be executed.

## Algorithm
1.	Evaluate the expression in the switch statement.
2.	Compare the expression's value with each case value.
3.	If a match is found, execute the associated block of code.
4.	If no match is found, execute the default case (if defined).

## Program
```
#include <stdio.h>
int main() {
    int choice;
    printf("Enter a number between 1 and 3: ");
    scanf("%d", &choice);
    switch(choice) {
        case 1:
            printf("You selected option 1\n");
            break;
        case 2:
            printf("You selected option 2\n");
            break;
        case 3:
            printf("You selected option 3\n");
            break;
        default:
            printf("Invalid option selected!\n");
    }
    return 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/6a89b83a-2b86-4bf8-b526-979b052d147e)

## Result
To demonstrate the working of the switch statement was executed successfully.


# e) Aim
To demonstrate the working of the for loop, which is used to iterate a fixed number of times.

## Algorithm
1.	Initialize the loop variable.
2.	Set the loop condition.
3.	Execute the loop body.
4.	After each iteration, increment/decrement the loop variable and repeat until the condition becomes false.

## Program
```
#include <stdio.h>
int main() {
    int i;
    for(i = 0; i < 5; i++) {
        printf("Number: %d\n", i);
    }
    return 0;
}
```
## Output
![image](https://github.com/user-attachments/assets/e6aea20a-206a-44b6-a02b-2220b74e2fa5)

## Result
To demonstrate the working of the for loop was executed successfully.
