# addition-subtraction-multiplication-divison-using-funcation
addition,subtraction,multiplication,divison using funcation

#include<stdio.h>
    void addition();
    void substraction();
    void multipication();
    void divison();

void addition()
{
    int a,b,c;
    
    printf("\n Enter the first number ::");
    scanf("%d",&a);
    
    printf("\n Enter the second number ::");
    scanf("%d",&b);
    
    c=a+b;
    
    printf("\n Addition of the number::%d",c);
}
void substraction()
{
    int a,b,c;
    
    printf("\n Enter the first number ::");
    scanf("%d",&a);
    
    printf("\n Enter the second number ::");
    scanf("%d",&b);
    
    c=a-b;
    
    printf("\n substraction of the number::%d",c);
}
void multipication()
{
    int a,b,c;
    
    printf("\n Enter the first number ::");
    scanf("%d",&a);
    
    printf("\n Enter the second number ::");
    scanf("%d",&b);
    
    c=a*b;
    
    printf("\n multipication of the number::%d",c);
}
void divison()
{
   int a,b,c;
    
    printf("\n Enter the first number ::");
    scanf("%d",&a);
    
    printf("\n Enter the second number ::");
    scanf("%d",&b);
    
    c=a/b;
    
    printf("\n divison of the number::%d",c); 
}
int main()
{   
    int choice;
    while(1)
 {
    printf("\n Menu::");
    printf("\n-----Addition-----");
    printf("\n-----Subtrection--");
    printf("\n--multiplication--");
    printf("\n ----divison------");
    printf("\n Enter your choice::");
    scanf("%d",&choice);
    
    switch(choice)
    {
       case 1: addition();
               break;
        case 2:substraction();
               break;
        case 3:multipication();
               break;
        case 4:divison();
              break;
        default:
              printf("\n invalid choice::");
       
    }
 }    
}
