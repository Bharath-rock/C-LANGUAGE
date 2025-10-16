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


