1.Program to check even or odd.
```
#include<stdio.h>
int main(){
int num;
printf("Enter the number: ");
scanf("%d",&num);
if(num%2==0)
printf("Even");
else
printf("odd");
return 0;
}

```
2.Program to check the given number is positive or negative.
```
#include<stdio.h>
int main(){
int num;
printf("Enter a number: ");
scanf("%d",&num);
if(num>0){
printf("Positive");
}else {
printf("negative");
}
return 0;
}
```
3.Check weather a given year is leap year or not.
```
#include<stdio.h>
int main(){
int year;
printf("Enter the year: ")
scanf("%d",&year);
if((year%4==0||year%100!=0)||(year%400==0)){
printf("%d is a leap year.\n", year);
    } else {
        printf("%d is not a leap year.\n", year);
    }

    return 0;
}
```
4. PROGRAM TO FIND THE LARGEST OF THREE NUMBERS.
```
#include <stdio.h>

int main() {
    int num1, num2, num3;
    printf("Enter three numbers: ");
    scanf("%d %d %d", &num1, &num2, &num3);
    if (num1 >= num2 && num1 >= num3) {
        printf("%d is the largest number.\n", num1);
    }
    else if (num2 >= num1 && num2 >= num3) {
        printf("%d is the largest number.\n", num2);
    }
    else {
        printf("%d is the largest number.\n", num3);
    }

    return 0;
}
```
5. C PROGRAM TO CHECK WHETHER A CHARACTER IS AN ALPHABET OR NOT.
```
#include <stdio.h>

int main() {
    char ch;

    
    printf("Enter a character: ");
    scanf("%c", &ch);

      if ((ch >= 'A' && ch <= 'Z') || (ch >= 'a' && ch <= 'z')) {
        printf("%c is an alphabet.\n", ch);
    } else {
        printf("%c is not an alphabet.\n", ch);
    }

    return 0;
}
```
6.C PROGRAM TO ENTER WEEK NUMBER AND PRINT DAY OF WEEK.
```
#include <stdio.h>

int main() {
    int week;

    
    printf("Enter week number (1-7): ");
    scanf("%d", &week);

    
    switch (week) {
        case 1:
            printf("Monday\n");
            break;
        case 2:
            printf("Tuesday\n");
            break;
        case 3:
            printf("Wednesday\n");
            break;
        case 4:
            printf("Thursday\n");
            break;
        case 5:
            printf("Friday\n");
            break;
        case 6:
            printf("Saturday\n");
            break;
        case 7:
            printf("Sunday\n");
            break;
        default:
            printf("Invalid input! Please enter a number between 1 and 7.\n");
    }

    return 0;
}
```
7.C PROGRAM TO CHECK WHETHER A CHARACTER IS UPPERCASE OR LOWERCASE.
```
#include <stdio.h>

int main() {
    char ch;
    printf("Enter a charecter: ");
    scanf("%c",&ch);
    if(ch >= 'A'&& ch <='Z'){
        printf("%c is an upper case letter.\n",ch);
    }else if(ch >= 'a' && ch<='z'){
        printf("%c is an lower case letter.\n",ch);
    }else{
        printf("%c is invalid.\n",ch);
    }

    return 0;
}
```
8.C PROGRAM TO FIND MAXIMUM BETWEEN TWO NUMBERS USING SWITCH CASE.
```
#include <stdio.h>

int main() {
    int num1, num2;
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    switch (num1 > num2) {
        case 1:
            printf("%d is maximum.\n", num1);
            break;
        case 0:
            switch (num1 < num2) {
                case 1:
                    printf("%d is maximum.\n", num2);
                    break;
                case 0:
                    printf("Both numbers are equal.\n");
                    break;
            }
            break;
    }

    return 0;
}
```
9.C PROGRAM TO PRINT EVEN NUMBERS BETWEEN 1 TO 20 USING A FOR LOOP.
```
#include <stdio.h>

int main() {
    int i;
    printf("Even numbers between 1 and 20 are:\n");
    for (i = 1; i <= 20; i++) {
        if (i % 2 == 0) {   
            printf("%d ", i);
        }
    }

    return 0;
}
```
10.C PROGRAM TO CALCULATE THE SUM OF NUMBERS FROM 1 TO 100 USING A WHILE LOOP.
```
#include<stdio.h>
    int main(){
        int i=1,sum=0;
        while(i<=100){
            sum=sum+i;
            i++;
    }
    printf("%d",sum);
    return 0;
    }
```
11



