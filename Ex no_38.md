# # Task

# # Given a positive integer denoting , do the following:

# If  41<=n <=49 print the lowercase English word corresponding to the number (e.g., forty one for 41 , forty two for 42 etc.).
If n>49 print Greater than 49.
## Input Format

The first line contains a single integer, .

## Constraints

## Output Format

If  41<=n <=49 print the lowercase English word corresponding to the number (e.g., forty one for 4 , forty two for 42 etc.).
If n>49 print Greater than 49.
## Sample Input

41
## Sample Output

forty one


## Program

```
#include <stdio.h>

int main() {
    int n;
    scanf("%d", &n);

    if (n >= 41 && n <= 49)
  {
        printf("forty ");
        switch(n)
       {
            case 41: printf("one\n"); break;
            case 42: printf("two\n"); break;
            case 43: printf("three\n"); break;
            case 44: printf("four\n"); break;
            case 45: printf("five\n"); break;
            case 46: printf("six\n"); break;
            case 47: printf("seven\n"); break;
            case 48: printf("eight\n"); break;
            case 49: printf("nine\n"); break;
        }
    }
    else if (n > 49)
    {
        printf("Greater than 49\n");
    }
    return 0;
}


```
## Output

<img width="592" height="301" alt="image" src="https://github.com/user-attachments/assets/f5c0cce3-4858-4a6a-963f-d900962a333f" />

## RESULT:
Thus, the program is executed and verified successfully.
