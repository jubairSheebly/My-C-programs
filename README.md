# My-C-programs
Lab Assessment-07
#include<stdio.h>

int main()
{
    int i,sum=0,n;
    char str[100];

    puts("Input the character : ");
    gets(str);

    printf("input the character : ");
    scanf("%s", &n);

    for(i=0; str[i]!='\0'; i++)
    {
        if(str[i]==n)
        {
            sum=sum+1;
        }
    }
    printf("the number of occurences of the letter is : %d\n",sum);


    for(i=0; str[i]!='\0'; i++)
    {
        if(str[i]==n)
        {
             str[i]='*';
        }
    }
    printf("The new string is: %s", str);




    return 0;
}

