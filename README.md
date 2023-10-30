# THE BASIC PROGRAMME ON C FUNCTION PART 3
 The basic programme on C function {without arguments and with return value}
#include<stdio.h>
int sum(int a, int b);
void printstar(int n)
{
    for (int i = 0; i < n; i++)
    {
        printf("%c", '*');

    }
    
}


    int takenumber()

{
    int i;
    printf("Enter the value\n");
    scanf("%d",&i);
    return i;

}
int main()
{
    int a,b,c;
    a = 9;
    b = 87;

   // c = sum(a,b);

    //printstar(7);

    c = takenumber();

    printf("The Entered number is  %d\n",c);


    return 0;

}
int sum(int a, int b)
{
    return a+b;
    
}