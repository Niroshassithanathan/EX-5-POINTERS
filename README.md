# EX-5-POINTERS
## AIM :
Write a C program to convert a 23.65 into 25 using pointer.
## ALGORITHAM :
1.Start

2.Declare a float variable value and initialize it to value.

3.Declare a pointer to a float (e.g., float *ptr).

4.Set the pointer ptr to point to the address of the value variable.

7.Print the updated value.

6.End.
## PROGARM :
```
# include<stdio.h>
int main()
{
float a,*b=&a;
scanf("%f",&a);
int ans,*val=&ans;
*val=(int)*b;
printf("the integer equivalent of %.2f =%d",a,*val);
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-5-POINTERS/assets/121418437/c77f314d-1c1d-41e8-8120-4fa12364183b)

## RESULT :
Thus , The C program has been executed successfully.

# EX-5-B-FUNCTIONS AND STORAGE CLASS
## AIM :
Write a C program to calculate the Product of first 12 natural numbers using Recursion.
## ALGORITHAM :
1.Start
2.Declare a function 

3.Inside the calculateProduct function:

4.In the main function:

5.End.
## PROGARM :
```
#include <stdio.h>
int Product(int n){
if (n == 1)
return 1;
else
return n * Product(n - 1);
}
int
main(){ int
n = 12;
int product = Product(n);
printf("Product is = %d\n", product);
return 0;
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-5-POINTERS/assets/121418437/abac7a4b-859e-4d50-9ce9-8054e21a04df)

## RESULT :
Thus , The C program has been executed successfully.

# EX-5-C-ARRAYS AND ITS OPERATIONS
## AIM :
C Program to find Sum of each row of a Matrix

## ALGORITHAM :
1.Start

2.Declare variables to represent the matrix dimensions, such as rows and cols.

3.Declare a 2D array to store the matrix.

4.Initialize the matrix with the given values.

5.Use nested loops to iterate through each row of the matrix:

6.Repeat steps 5 for each row in the matrix.

7.End.
## PROGARM :
```
#include<stdio.h>
int main()
{
int a,b,sum1=0,sum2=0,sum3=0;
scanf("%d %d",&a,&b);
int arr[a][b];
for(int i=0;i<a;i++)
{
for(int j=0;j<b;j++)
{
scanf("%d",&arr[i][j]);
}
}
for(int i=0;i<a;i++)
{
for(int j=0;j<b;j++)
Name: JAYA BHARATHI | Register212222100013
{
if(i==0)
sum1+=arr[i][j]
else if(i==1)
sum2+=arr[i][j]
else
sum3+=arr[i][j]
}
}
printf("The Sum of Elements of a Rows in a Matrix: %d\n",sum1);
printf("The Sum of Elements of a Rows in a Matrix: %d\n",sum2);
printf("The Sum of Elements of a Rows in a Matrix: %d\n",sum3);
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-5-POINTERS/assets/121418437/2571b643-e661-4def-a35c-33d5227ab287)

## RESULT :
Thus , The C program has been executed successfully.

# EX-5-D-STRINGS
## AIM :
Write C program for the below pyramid string pattern.
Enter a string: PROGRAM
Enter number of rows: 5
     p
    R O
   G R A
  M P R O
 G R A M P
R O G R A M
## ALGORITHAM :
1.Start

2.Define the height of the pyramid (the number of rows).

3.Use nested loops to create the pattern:

a. Outer loop (i) controls the rows from 1 to the height.

b. Inner loop (j) controls the spaces before the current row.

c. Inner loop (k) controls the printing of the string characters in the current row.

d. The string characters are derived based on the row and column indices.

e. Print the string characters and a space after each character.

4.End
## PROGARM :
```
#include<stdio.h>
int main()
{
char str[20];
int n,a=0;
scanf("%[^\n]"
,str);
scanf("%d"
,&n);
for(int i=0;i<=n;i++)
{
for(int j=0;j<=n-i;j++)
{
printf(" ");
}
for(int k=0;k<=i;k++)
{
printf("%2c"
,str[a++]);
if(str[a]==
'\0')
a=0;
}
printf("\n");
}
return 0;
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-5-POINTERS/assets/121418437/1a09e218-ba97-4d22-8111-b0109d3db20f)

## RESULT :
Thus , The C program has been executed successfully.
