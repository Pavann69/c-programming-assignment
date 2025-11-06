// Question-1
#include <stdio.h>
int main() {
int i;
char ;
for (i=0; i<=10; i++)
printf("Hello sir.\n");
return 0;
}
// Output
Hello sir.
.
.
z
.10
// Question-2
#include <stdio.h>
int main() {
int i, j, rows;
printf("Enter the rows:");
scanf("%d", &rows);
for(i = 0; i <= rows; i++ )
{
for(j = 1; j <= rows - i; j ++)
    printf("   ");
for(j = 1; j <= (2*i - 1); j ++)
    printf(" * ");
printf(" \n ");
}
return 0;
}
// output
                   *
               *  *  *
            *  *  *  *  *
         *  *  *  *  *  *  *
      *  *  *  *  *  *  *  *  * 
   *  *  *  *  *  *  *  *  *  *  *
*  *  *  *  *  *  *  *  *  *  *  *  *
// Question-3

#include <stdio.h>
int main() {
int i,n;
printf("Enter number :");
scanf("%d,&n);
for(i=0; i<=; i++)
{
printf("%d\n",i);
}
return 0;
}
// Output
1
2
3
.
.
.100
// Question-4

#include <stdio.h>
int main() { 
int a,b;
printf("Enter the value of a: ");
scanf("%d",&a);
printf("Enter the value of b: ");
scanf("%d",&b);
a=a+b
b=a-b
a=a-b
printf("Swap =a%d\nSwap =b%d\n" a,b)
return 0;
}
// Output 
Enter the value of a: 20
Enter the value of b: 30
Swap a = 30
Swap b = 20
// Question 5
#include <stdio.h>
int main() {
int a, b , c;
printf("Enter the value of a:");
scanf("%d,&a);
printf("Enter the value of b:");
scanf("%d",&b);
printf("Enter the value of c:");
scanf("%d",&c);
if(a >= b && a >= c) 
{
printf("Greatest =%d\n",a);
}
else if(b >= a && b >= c)
{
printf("Greatest =%d\n",b);
}
else
printf("Greatest =%d\n",c);
return 0;
}
// output 
Enter the value of a:15
Enter the value of b:78
Enter the value of c:65
Greatest = 78













            




