# Module-1-Assignment-for-IARP
PROGRAMS
a)Write a C program to find the ASCII value of given character.
```
#include <stdio.h>

int main()
{
   char word;
   printf("Enter the charcter to find its ascii value :");
   scanf("%c",&word);
   printf("\nAscii value of %c is %d",word,(int)word);
}
```
OUTPUT
<img width="515" height="209" alt="Screenshot 2025-10-19 144912" src="https://github.com/user-attachments/assets/9bc6dc35-caef-41be-9769-2e6566fac542" />
2)Write a C program to read a value and check whether that number is less than 100 or not. using  if-else
```
#include <stdio.h>

int main()
{
   int num;
   printf("Enter the number: ");
   scanf("%d",&num);
   if(num>100)
   printf("\n The entered number is greater than 100");
   else if(num==100)
   printf("The entered number is 100");
   else
   printf("\nThe entered number is less than 100");
}
```
OUTPUT
<img width="413" height="177" alt="Screenshot 2025-10-19 145506" src="https://github.com/user-attachments/assets/46c09810-34a5-4778-a675-3ace1a526f60" />

3)Write a C program to find simple interest. 
```
#include <stdio.h>

int main()
{
   float principal,year,rate;
   printf("Enter principal amount,year and rate of interst :");
   scanf("%f %f %f",&principal,&year,&rate);
   printf("\nSimple Interst = %.2f",(principal*year*rate)/100);
}
```
OUTPUT
<img width="413" height="177" alt="Screenshot 2025-10-19 145506" src="https://github.com/user-attachments/assets/54d98292-a4b4-458d-9e71-6960b6f1e5e9" />

4)Write a C Program for analysis of people of certain age groups who are eligible for getting a suitable college admission if their condition and norms get satisfied using nested if statement. Assume eligible age is 18 - 25. Total marks >=180.
```
#include <stdio.h>

int main()
{
  int age,mark;
  printf("Enter Student age :");
  scanf("%d",&age);
  if(age>=18 && age<=25){
  printf("\n Enter the Student's total mark");
  scanf("%d",&mark);
    if(mark>=180)
    printf("\nHe/She is eligible for college admission");
    else
    {
        printf("\nhis/her total marks is less than 180 not eligible");
    }
  }
  else
  printf("\nNot eligible for college admission");
}
```
OUTPUT
<img width="414" height="170" alt="Screenshot 2025-10-19 151438" src="https://github.com/user-attachments/assets/5884f9e5-2cac-47d9-af68-78ff37efaba1" />
<img width="449" height="199" alt="Screenshot 2025-10-19 151504" src="https://github.com/user-attachments/assets/966d2348-6a4a-43b8-b4f0-1c1091bce89b" />
<img width="560" height="211" alt="Screenshot 2025-10-19 151525" src="https://github.com/user-attachments/assets/28e1b379-3d02-4745-901a-3efdadee40bf" />

5)Write a program to convert centimeter into meter and kilometer
```
#include <stdio.h>

int main()
{
  float cm,m,km;
  printf("Enter the number in ");
  scanf("%f",&cm);
  m=cm/100;
  km=cm/100000;
  printf("\n The value in meter : %.2fm in km : %.2fkm",m,km);
}
```
OUTPUT
<img width="525" height="184" alt="Screenshot 2025-10-19 152143" src="https://github.com/user-attachments/assets/3454533b-121f-4653-9ac4-bd3541b94ccb" />










