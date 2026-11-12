//Arthemetic-problem

#include<stdio.h>
int main()
{
    int a,b;
    printf("Enter your values:\n");
    scanf("%d%d",&a,&b);
    printf("1 Addition\n");
    printf("2 Subtraction\n");
    printf("3 Multiplication\n");
    printf("4 Division\n");
    printf("5 Modulus division\n");
    int ch;
    printf("Enter your choice:\n");
    scanf("%d",&ch);

    if(ch==1)
    {
        printf("Addition is:%d\n",a+b);
    }    
    else if(ch==2)
    {
        printf("Subtraction is:%d\n",a-b);
    }
    else if(ch==3)
    {
        printf("Multiplication is:%d\n",a*b);
    }
    else if(ch==4)
    {
        printf("Division is:%d\n",a/b);
    }
    else if(ch==5)
    {
        printf("Modulus division is:%d\n",a%b);
    }    
    else {
        printf("Invalid choice");
    }
}
